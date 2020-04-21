---
title: HcmJobTemplateResponsibilityEntity - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/21/2020
ms.author: nebanfic
---

# HcmJobTemplateResponsibilityEntity

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/HumanResources/HRM/HcmJobTemplateResponsibilityEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[JobTemplate](#JobTemplate)||<a href="HcmJobTemplateResponsibilityEntity.md" target="_blank">HRM/HcmJobTemplateResponsibilityEntity</a>|
|[Note](#Note)||<a href="HcmJobTemplateResponsibilityEntity.md" target="_blank">HRM/HcmJobTemplateResponsibilityEntity</a>|
|[AreaOfResponsibility](#AreaOfResponsibility)||<a href="HcmJobTemplateResponsibilityEntity.md" target="_blank">HRM/HcmJobTemplateResponsibilityEntity</a>|
|[JobTemplateId](#JobTemplateId)||<a href="HcmJobTemplateResponsibilityEntity.md" target="_blank">HRM/HcmJobTemplateResponsibilityEntity</a>|
|[AreaOfResponsibilityId](#AreaOfResponsibilityId)||<a href="HcmJobTemplateResponsibilityEntity.md" target="_blank">HRM/HcmJobTemplateResponsibilityEntity</a>|
|[Relationship_ResponsibilityRelationshipId](#Relationship_ResponsibilityRelationshipId)||<a href="HcmJobTemplateResponsibilityEntity.md" target="_blank">HRM/HcmJobTemplateResponsibilityEntity</a>|
|[Relationship_JobTemplateRelationshipId](#Relationship_JobTemplateRelationshipId)||<a href="HcmJobTemplateResponsibilityEntity.md" target="_blank">HRM/HcmJobTemplateResponsibilityEntity</a>|

### <a href=#JobTemplate name="JobTemplate">JobTemplate</a>

First included in: HRM/HcmJobTemplateResponsibilityEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the JobTemplate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Note name="Note">Note</a>

First included in: HRM/HcmJobTemplateResponsibilityEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Note attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AreaOfResponsibility name="AreaOfResponsibility">AreaOfResponsibility</a>

First included in: HRM/HcmJobTemplateResponsibilityEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AreaOfResponsibility attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#JobTemplateId name="JobTemplateId">JobTemplateId</a>

First included in: HRM/HcmJobTemplateResponsibilityEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the JobTemplateId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AreaOfResponsibilityId name="AreaOfResponsibilityId">AreaOfResponsibilityId</a>

First included in: HRM/HcmJobTemplateResponsibilityEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AreaOfResponsibilityId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_ResponsibilityRelationshipId name="Relationship_ResponsibilityRelationshipId">Relationship_ResponsibilityRelationshipId</a>

First included in: HRM/HcmJobTemplateResponsibilityEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_ResponsibilityRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_JobTemplateRelationshipId name="Relationship_JobTemplateRelationshipId">Relationship_JobTemplateRelationshipId</a>

First included in: HRM/HcmJobTemplateResponsibilityEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_JobTemplateRelationshipId attribute are listed below.</summary>

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
