---
title: BIMeasurementPriorityAssignments in Miscellaneous - Common Data Model | Microsoft Docs
description: undefined
author: llawwaii
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: reference
ms.date: 8/7/2020
ms.author: weiluo
---

# BIMeasurementPriorityAssignments in Miscellaneous

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Tables/System/SystemAdministration/Miscellaneous/BIMeasurementPriorityAssignments.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[BIMeasurementPriorityAssignments/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.1"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="BIMeasurementPriorityAssignments.md" target="_blank">Miscellaneous/BIMeasurementPriorityAssignments</a>|
|[BIMeasurement](#BIMeasurement)||<a href="BIMeasurementPriorityAssignments.md" target="_blank">Miscellaneous/BIMeasurementPriorityAssignments</a>|
|[BIPriorityAgeLimit](#BIPriorityAgeLimit)||<a href="BIMeasurementPriorityAssignments.md" target="_blank">Miscellaneous/BIMeasurementPriorityAssignments</a>|
|[ProcessingType](#ProcessingType)||<a href="BIMeasurementPriorityAssignments.md" target="_blank">Miscellaneous/BIMeasurementPriorityAssignments</a>|
|[Relationship_BIMeasurementRelationshipId](#Relationship_BIMeasurementRelationshipId)||<a href="BIMeasurementPriorityAssignments.md" target="_blank">Miscellaneous/BIMeasurementPriorityAssignments</a>|
|[Relationship_BIMeasurementPriorityRelationshipId](#Relationship_BIMeasurementPriorityRelationshipId)||<a href="BIMeasurementPriorityAssignments.md" target="_blank">Miscellaneous/BIMeasurementPriorityAssignments</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: Miscellaneous/BIMeasurementPriorityAssignments (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[BIMeasurementPriorityAssignments/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#BIMeasurement name="BIMeasurement">BIMeasurement</a>

First included in: Miscellaneous/BIMeasurementPriorityAssignments (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BIMeasurement attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#BIPriorityAgeLimit name="BIPriorityAgeLimit">BIPriorityAgeLimit</a>

First included in: Miscellaneous/BIMeasurementPriorityAssignments (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BIPriorityAgeLimit attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#ProcessingType name="ProcessingType">ProcessingType</a>

First included in: Miscellaneous/BIMeasurementPriorityAssignments (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProcessingType attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#Relationship_BIMeasurementRelationshipId name="Relationship_BIMeasurementRelationshipId">Relationship_BIMeasurementRelationshipId</a>

First included in: Miscellaneous/BIMeasurementPriorityAssignments (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_BIMeasurementRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="BIMeasurement.md" target="_blank">/core/operationsCommon/Tables/System/SystemAdministration/Miscellaneous/BIMeasurement.cdm.json/BIMeasurement</a></td><td><a href="BIMeasurement.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_BIMeasurementPriorityRelationshipId name="Relationship_BIMeasurementPriorityRelationshipId">Relationship_BIMeasurementPriorityRelationshipId</a>

First included in: Miscellaneous/BIMeasurementPriorityAssignments (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_BIMeasurementPriorityRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="BIPriorityAgeLimits.md" target="_blank">/core/operationsCommon/Tables/System/SystemAdministration/Miscellaneous/BIPriorityAgeLimits.cdm.json/BIPriorityAgeLimits</a></td><td><a href="BIPriorityAgeLimits.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>
