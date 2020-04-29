---
title: DataManagementTemplateSourceDependencyEntity - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/29/2020
ms.author: nebanfic
---

# Entities for a processing group

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/System/SystemAdministration/DataManagementTemplateSourceDependencyEntity.cdm.json" target="_blank">GitHub</a>.  

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
|[TemplateId](#TemplateId)||<a href="DataManagementTemplateSourceDependencyEntity.md" target="_blank">SystemAdministration/DataManagementTemplateSourceDependencyEntity</a>|
|[SourceEntity](#SourceEntity)||<a href="DataManagementTemplateSourceDependencyEntity.md" target="_blank">SystemAdministration/DataManagementTemplateSourceDependencyEntity</a>|
|[DependentOnEntity](#DependentOnEntity)||<a href="DataManagementTemplateSourceDependencyEntity.md" target="_blank">SystemAdministration/DataManagementTemplateSourceDependencyEntity</a>|
|[RelationName](#RelationName)||<a href="DataManagementTemplateSourceDependencyEntity.md" target="_blank">SystemAdministration/DataManagementTemplateSourceDependencyEntity</a>|
|[Description](#Description)||<a href="DataManagementTemplateSourceDependencyEntity.md" target="_blank">SystemAdministration/DataManagementTemplateSourceDependencyEntity</a>|
|[FriendlyName](#FriendlyName)||<a href="DataManagementTemplateSourceDependencyEntity.md" target="_blank">SystemAdministration/DataManagementTemplateSourceDependencyEntity</a>|
|[ValidationRequired](#ValidationRequired)||<a href="DataManagementTemplateSourceDependencyEntity.md" target="_blank">SystemAdministration/DataManagementTemplateSourceDependencyEntity</a>|
|[Relationship_DefinitionGroupTemplateSourceDependencyRelationshipId](#Relationship_DefinitionGroupTemplateSourceDependencyRelationshipId)||<a href="DataManagementTemplateSourceDependencyEntity.md" target="_blank">SystemAdministration/DataManagementTemplateSourceDependencyEntity</a>|

### <a href=#TemplateId name="TemplateId">TemplateId</a>

First included in: SystemAdministration/DataManagementTemplateSourceDependencyEntity (this entity)  

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

### <a href=#SourceEntity name="SourceEntity">SourceEntity</a>

First included in: SystemAdministration/DataManagementTemplateSourceDependencyEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SourceEntity attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DependentOnEntity name="DependentOnEntity">DependentOnEntity</a>

First included in: SystemAdministration/DataManagementTemplateSourceDependencyEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DependentOnEntity attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RelationName name="RelationName">RelationName</a>

First included in: SystemAdministration/DataManagementTemplateSourceDependencyEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RelationName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Description name="Description">Description</a>

First included in: SystemAdministration/DataManagementTemplateSourceDependencyEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Description attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FriendlyName name="FriendlyName">FriendlyName</a>

First included in: SystemAdministration/DataManagementTemplateSourceDependencyEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FriendlyName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ValidationRequired name="ValidationRequired">ValidationRequired</a>

First included in: SystemAdministration/DataManagementTemplateSourceDependencyEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ValidationRequired attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_DefinitionGroupTemplateSourceDependencyRelationshipId name="Relationship_DefinitionGroupTemplateSourceDependencyRelationshipId">Relationship_DefinitionGroupTemplateSourceDependencyRelationshipId</a>

First included in: SystemAdministration/DataManagementTemplateSourceDependencyEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_DefinitionGroupTemplateSourceDependencyRelationshipId attribute are listed below.</summary>

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
