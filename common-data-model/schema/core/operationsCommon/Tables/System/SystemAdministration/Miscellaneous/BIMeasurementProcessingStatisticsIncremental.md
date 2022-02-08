---
title: BIMeasurementProcessingStatisticsIncremental in Miscellaneous - Common Data Model | Microsoft Docs
description: undefined
author: llawwaii
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: reference
ms.date: 8/7/2020
ms.author: weiluo
---

# BIMeasurementProcessingStatisticsIncremental in Miscellaneous

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Tables/System/SystemAdministration/Miscellaneous/BIMeasurementProcessingStatisticsIncremental.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[BIMeasurementProcessingStatisticsIncremental/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.1"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="BIMeasurementProcessingStatisticsIncremental.md" target="_blank">Miscellaneous/BIMeasurementProcessingStatisticsIncremental</a>|
|[BIMeasurement](#BIMeasurement)||<a href="BIMeasurementProcessingStatisticsIncremental.md" target="_blank">Miscellaneous/BIMeasurementProcessingStatisticsIncremental</a>|
|[Outcome](#Outcome)||<a href="BIMeasurementProcessingStatisticsIncremental.md" target="_blank">Miscellaneous/BIMeasurementProcessingStatisticsIncremental</a>|
|[LastProcessed](#LastProcessed)||<a href="BIMeasurementProcessingStatisticsIncremental.md" target="_blank">Miscellaneous/BIMeasurementProcessingStatisticsIncremental</a>|
|[MaximumDuration](#MaximumDuration)||<a href="BIMeasurementProcessingStatisticsIncremental.md" target="_blank">Miscellaneous/BIMeasurementProcessingStatisticsIncremental</a>|
|[LastDuration](#LastDuration)||<a href="BIMeasurementProcessingStatisticsIncremental.md" target="_blank">Miscellaneous/BIMeasurementProcessingStatisticsIncremental</a>|
|[Relationship_BIMeasurementRelationshipId](#Relationship_BIMeasurementRelationshipId)||<a href="BIMeasurementProcessingStatisticsIncremental.md" target="_blank">Miscellaneous/BIMeasurementProcessingStatisticsIncremental</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: Miscellaneous/BIMeasurementProcessingStatisticsIncremental (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[BIMeasurementProcessingStatisticsIncremental/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#BIMeasurement name="BIMeasurement">BIMeasurement</a>

First included in: Miscellaneous/BIMeasurementProcessingStatisticsIncremental (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Measurement</td></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BIMeasurement attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Measurement</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#Outcome name="Outcome">Outcome</a>

First included in: Miscellaneous/BIMeasurementProcessingStatisticsIncremental (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>@BIMeasurementProcessingStatisticsIncremental</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Outcome attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>@BIMeasurementProcessingStatisticsIncremental</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#LastProcessed name="LastProcessed">LastProcessed</a>

First included in: Miscellaneous/BIMeasurementProcessingStatisticsIncremental (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>@BIMeasurementProcessingStatisticsIncremental</td></tr><tr><td>dataFormat</td><td>date</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LastProcessed attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>@BIMeasurementProcessingStatisticsIncremental</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.date**  
</details>

### <a href=#MaximumDuration name="MaximumDuration">MaximumDuration</a>

First included in: Miscellaneous/BIMeasurementProcessingStatisticsIncremental (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MaximumDuration attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#LastDuration name="LastDuration">LastDuration</a>

First included in: Miscellaneous/BIMeasurementProcessingStatisticsIncremental (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LastDuration attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#Relationship_BIMeasurementRelationshipId name="Relationship_BIMeasurementRelationshipId">Relationship_BIMeasurementRelationshipId</a>

First included in: Miscellaneous/BIMeasurementProcessingStatisticsIncremental (this entity)  

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
