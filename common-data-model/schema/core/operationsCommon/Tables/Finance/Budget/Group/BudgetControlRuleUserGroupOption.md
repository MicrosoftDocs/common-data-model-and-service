---
title: BudgetControlRuleUserGroupOption in Group - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 7/13/2020
ms.author: nebanfic
---

# Budget user group options in Group(BudgetControlRuleUserGroupOption)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Tables/Finance/Budget/Group/BudgetControlRuleUserGroupOption.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[BudgetControlRuleUserGroupOption/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Budget user group options</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="BudgetControlRuleUserGroupOption.md" target="_blank">Group/BudgetControlRuleUserGroupOption</a>|
|[BudgetControlRule](#BudgetControlRule)||<a href="BudgetControlRuleUserGroupOption.md" target="_blank">Group/BudgetControlRuleUserGroupOption</a>|
|[BudgetOverrideUserGroupOption](#BudgetOverrideUserGroupOption)||<a href="BudgetControlRuleUserGroupOption.md" target="_blank">Group/BudgetControlRuleUserGroupOption</a>|
|[OverbudgetBudgetGroupCheckOption](#OverbudgetBudgetGroupCheckOption)||<a href="BudgetControlRuleUserGroupOption.md" target="_blank">Group/BudgetControlRuleUserGroupOption</a>|
|[OverrideOverbudgetOption](#OverrideOverbudgetOption)||<a href="BudgetControlRuleUserGroupOption.md" target="_blank">Group/BudgetControlRuleUserGroupOption</a>|
|[Relationship_BudgetControlRuleRelationshipId](#Relationship_BudgetControlRuleRelationshipId)||<a href="BudgetControlRuleUserGroupOption.md" target="_blank">Group/BudgetControlRuleUserGroupOption</a>|
|[Relationship_BudgetOverrideUserGroupOptionRelationshipId](#Relationship_BudgetOverrideUserGroupOptionRelationshipId)||<a href="BudgetControlRuleUserGroupOption.md" target="_blank">Group/BudgetControlRuleUserGroupOption</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: Group/BudgetControlRuleUserGroupOption (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[BudgetControlRuleUserGroupOption/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#BudgetControlRule name="BudgetControlRule">BudgetControlRule</a>

First included in: Group/BudgetControlRuleUserGroupOption (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Budget control rules</td></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BudgetControlRule attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Budget control rules</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#BudgetOverrideUserGroupOption name="BudgetOverrideUserGroupOption">BudgetOverrideUserGroupOption</a>

First included in: Group/BudgetControlRuleUserGroupOption (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Over budget permissions</td></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BudgetOverrideUserGroupOption attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Over budget permissions</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#OverbudgetBudgetGroupCheckOption name="OverbudgetBudgetGroupCheckOption">OverbudgetBudgetGroupCheckOption</a>

First included in: Group/BudgetControlRuleUserGroupOption (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OverbudgetBudgetGroupCheckOption attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#OverrideOverbudgetOption name="OverrideOverbudgetOption">OverrideOverbudgetOption</a>

First included in: Group/BudgetControlRuleUserGroupOption (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OverrideOverbudgetOption attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#Relationship_BudgetControlRuleRelationshipId name="Relationship_BudgetControlRuleRelationshipId">Relationship_BudgetControlRuleRelationshipId</a>

First included in: Group/BudgetControlRuleUserGroupOption (this entity)  

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

### <a href=#Relationship_BudgetOverrideUserGroupOptionRelationshipId name="Relationship_BudgetOverrideUserGroupOptionRelationshipId">Relationship_BudgetOverrideUserGroupOptionRelationshipId</a>

First included in: Group/BudgetControlRuleUserGroupOption (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_BudgetOverrideUserGroupOptionRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="BudgetOverrideUserGroupOption.md" target="_blank">/core/operationsCommon/Tables/Finance/Budget/Group/BudgetOverrideUserGroupOption.cdm.json/BudgetOverrideUserGroupOption</a></td><td><a href="BudgetOverrideUserGroupOption.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>
