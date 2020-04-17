---
title: HcmJobTemplateEducationDisciplineEntity - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/17/2020
ms.author: nebanfic
---

# HcmJobTemplateEducationDisciplineEntity

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/erp/Entities/HumanResources/HRM/HcmJobTemplateEducationDisciplineEntity.cdm.json" target="_blank">GitHub</a>.  

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
|[Education](#Education)||<a href="HcmJobTemplateEducationDisciplineEntity.md" target="_blank">HRM/HcmJobTemplateEducationDisciplineEntity</a>|
|[Importance](#Importance)||<a href="HcmJobTemplateEducationDisciplineEntity.md" target="_blank">HRM/HcmJobTemplateEducationDisciplineEntity</a>|
|[JobTemplate](#JobTemplate)||<a href="HcmJobTemplateEducationDisciplineEntity.md" target="_blank">HRM/HcmJobTemplateEducationDisciplineEntity</a>|
|[EducationId](#EducationId)||<a href="HcmJobTemplateEducationDisciplineEntity.md" target="_blank">HRM/HcmJobTemplateEducationDisciplineEntity</a>|
|[JobTemplateId](#JobTemplateId)||<a href="HcmJobTemplateEducationDisciplineEntity.md" target="_blank">HRM/HcmJobTemplateEducationDisciplineEntity</a>|
|[Relationship_EducationDisciplineRelationshipId](#Relationship_EducationDisciplineRelationshipId)||<a href="HcmJobTemplateEducationDisciplineEntity.md" target="_blank">HRM/HcmJobTemplateEducationDisciplineEntity</a>|
|[Relationship_JobTemplateRelationshipId](#Relationship_JobTemplateRelationshipId)||<a href="HcmJobTemplateEducationDisciplineEntity.md" target="_blank">HRM/HcmJobTemplateEducationDisciplineEntity</a>|

### <a href=#Education name="Education">Education</a>

First included in: HRM/HcmJobTemplateEducationDisciplineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Education attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Importance name="Importance">Importance</a>

First included in: HRM/HcmJobTemplateEducationDisciplineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Importance attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#JobTemplate name="JobTemplate">JobTemplate</a>

First included in: HRM/HcmJobTemplateEducationDisciplineEntity (this entity)  

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

### <a href=#EducationId name="EducationId">EducationId</a>

First included in: HRM/HcmJobTemplateEducationDisciplineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EducationId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#JobTemplateId name="JobTemplateId">JobTemplateId</a>

First included in: HRM/HcmJobTemplateEducationDisciplineEntity (this entity)  

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

### <a href=#Relationship_EducationDisciplineRelationshipId name="Relationship_EducationDisciplineRelationshipId">Relationship_EducationDisciplineRelationshipId</a>

First included in: HRM/HcmJobTemplateEducationDisciplineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_EducationDisciplineRelationshipId attribute are listed below.</summary>

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

First included in: HRM/HcmJobTemplateEducationDisciplineEntity (this entity)  

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
