---
title: DataManagementTemplateDetailEntity - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/28/2020
ms.author: nebanfic
---

# Entities for a processing group

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/System/SystemAdministration/DataManagementTemplateDetailEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Entities for a processing group</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[TemplateId](#TemplateId)||<a href="DataManagementTemplateDetailEntity.md" target="_blank">SystemAdministration/DataManagementTemplateDetailEntity</a>|
|[EntityName](#EntityName)||<a href="DataManagementTemplateDetailEntity.md" target="_blank">SystemAdministration/DataManagementTemplateDetailEntity</a>|
|[ValidationStatus](#ValidationStatus)||<a href="DataManagementTemplateDetailEntity.md" target="_blank">SystemAdministration/DataManagementTemplateDetailEntity</a>|
|[ExecutionUnit](#ExecutionUnit)||<a href="DataManagementTemplateDetailEntity.md" target="_blank">SystemAdministration/DataManagementTemplateDetailEntity</a>|
|[LevelInExecutionUnit](#LevelInExecutionUnit)||<a href="DataManagementTemplateDetailEntity.md" target="_blank">SystemAdministration/DataManagementTemplateDetailEntity</a>|
|[SequenceInLevel](#SequenceInLevel)||<a href="DataManagementTemplateDetailEntity.md" target="_blank">SystemAdministration/DataManagementTemplateDetailEntity</a>|
|[FailLevelOnError](#FailLevelOnError)||<a href="DataManagementTemplateDetailEntity.md" target="_blank">SystemAdministration/DataManagementTemplateDetailEntity</a>|
|[FailExecutionUnitOnError](#FailExecutionUnitOnError)||<a href="DataManagementTemplateDetailEntity.md" target="_blank">SystemAdministration/DataManagementTemplateDetailEntity</a>|
|[Relationship_DefinitionGroupTemplateDetailsRelationshipId](#Relationship_DefinitionGroupTemplateDetailsRelationshipId)||<a href="DataManagementTemplateDetailEntity.md" target="_blank">SystemAdministration/DataManagementTemplateDetailEntity</a>|

### <a href=#TemplateId name="TemplateId">TemplateId</a>

First included in: SystemAdministration/DataManagementTemplateDetailEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TemplateId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#EntityName name="EntityName">EntityName</a>

First included in: SystemAdministration/DataManagementTemplateDetailEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EntityName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ValidationStatus name="ValidationStatus">ValidationStatus</a>

First included in: SystemAdministration/DataManagementTemplateDetailEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ValidationStatus attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ExecutionUnit name="ExecutionUnit">ExecutionUnit</a>

First included in: SystemAdministration/DataManagementTemplateDetailEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ExecutionUnit attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LevelInExecutionUnit name="LevelInExecutionUnit">LevelInExecutionUnit</a>

First included in: SystemAdministration/DataManagementTemplateDetailEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LevelInExecutionUnit attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SequenceInLevel name="SequenceInLevel">SequenceInLevel</a>

First included in: SystemAdministration/DataManagementTemplateDetailEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SequenceInLevel attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FailLevelOnError name="FailLevelOnError">FailLevelOnError</a>

First included in: SystemAdministration/DataManagementTemplateDetailEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FailLevelOnError attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FailExecutionUnitOnError name="FailExecutionUnitOnError">FailExecutionUnitOnError</a>

First included in: SystemAdministration/DataManagementTemplateDetailEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FailExecutionUnitOnError attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_DefinitionGroupTemplateDetailsRelationshipId name="Relationship_DefinitionGroupTemplateDetailsRelationshipId">Relationship_DefinitionGroupTemplateDetailsRelationshipId</a>

First included in: SystemAdministration/DataManagementTemplateDetailEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_DefinitionGroupTemplateDetailsRelationshipId attribute are listed below.</summary>

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
