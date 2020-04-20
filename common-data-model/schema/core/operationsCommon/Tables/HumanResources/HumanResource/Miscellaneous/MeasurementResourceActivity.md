---
title: MeasurementResourceActivity - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/20/2020
ms.author: nebanfic
---

# MeasurementResourceActivity

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Tables/HumanResources/HumanResource/Miscellaneous/MeasurementResourceActivity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[MeasurementResourceActivity/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="MeasurementResourceActivity.md" target="_blank">Miscellaneous/MeasurementResourceActivity</a>|
|[Resource](#Resource)||<a href="MeasurementResourceActivity.md" target="_blank">Miscellaneous/MeasurementResourceActivity</a>|
|[Activity](#Activity)||<a href="MeasurementResourceActivity.md" target="_blank">Miscellaneous/MeasurementResourceActivity</a>|
|[SourceSystem](#SourceSystem)||<a href="MeasurementResourceActivity.md" target="_blank">Miscellaneous/MeasurementResourceActivity</a>|
|[ValidTo](#ValidTo)||<a href="MeasurementResourceActivity.md" target="_blank">Miscellaneous/MeasurementResourceActivity</a>|
|[ValidFrom](#ValidFrom)||<a href="MeasurementResourceActivity.md" target="_blank">Miscellaneous/MeasurementResourceActivity</a>|
|[Relationship_MeasurementActivityRelationshipId](#Relationship_MeasurementActivityRelationshipId)||<a href="MeasurementResourceActivity.md" target="_blank">Miscellaneous/MeasurementResourceActivity</a>|
|[Relationship_MeasurementResourceRelationshipId](#Relationship_MeasurementResourceRelationshipId)||<a href="MeasurementResourceActivity.md" target="_blank">Miscellaneous/MeasurementResourceActivity</a>|
|[Relationship_MeasurementSourceSystemRelationshipId](#Relationship_MeasurementSourceSystemRelationshipId)||<a href="MeasurementResourceActivity.md" target="_blank">Miscellaneous/MeasurementResourceActivity</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: Miscellaneous/MeasurementResourceActivity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[MeasurementResourceActivity/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#Resource name="Resource">Resource</a>

First included in: Miscellaneous/MeasurementResourceActivity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Resource attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#Activity name="Activity">Activity</a>

First included in: Miscellaneous/MeasurementResourceActivity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Activity attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#SourceSystem name="SourceSystem">SourceSystem</a>

First included in: Miscellaneous/MeasurementResourceActivity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SourceSystem attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#ValidTo name="ValidTo">ValidTo</a>

First included in: Miscellaneous/MeasurementResourceActivity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ValidTo attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.dataFormat.date**  
</details>

### <a href=#ValidFrom name="ValidFrom">ValidFrom</a>

First included in: Miscellaneous/MeasurementResourceActivity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ValidFrom attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.dataFormat.date**  
</details>

### <a href=#Relationship_MeasurementActivityRelationshipId name="Relationship_MeasurementActivityRelationshipId">Relationship_MeasurementActivityRelationshipId</a>

First included in: Miscellaneous/MeasurementResourceActivity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_MeasurementActivityRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="MeasurementActivity.md" target="_blank">/core/operationsCommon/Tables/HumanResources/HumanResource/Miscellaneous/MeasurementActivity.cdm.json/MeasurementActivity</a></td><td><a href="MeasurementActivity.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_MeasurementResourceRelationshipId name="Relationship_MeasurementResourceRelationshipId">Relationship_MeasurementResourceRelationshipId</a>

First included in: Miscellaneous/MeasurementResourceActivity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_MeasurementResourceRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="MeasurementResource.md" target="_blank">/core/operationsCommon/Tables/HumanResources/HumanResource/Miscellaneous/MeasurementResource.cdm.json/MeasurementResource</a></td><td><a href="MeasurementResource.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_MeasurementSourceSystemRelationshipId name="Relationship_MeasurementSourceSystemRelationshipId">Relationship_MeasurementSourceSystemRelationshipId</a>

First included in: Miscellaneous/MeasurementResourceActivity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_MeasurementSourceSystemRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="MeasurementSourceSystem.md" target="_blank">/core/operationsCommon/Tables/HumanResources/HumanResource/Miscellaneous/MeasurementSourceSystem.cdm.json/MeasurementSourceSystem</a></td><td><a href="MeasurementSourceSystem.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>
