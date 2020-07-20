---
title: RetailStoreHoursRange in Miscellaneous - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 7/20/2020
ms.author: nebanfic
---

# RetailStoreHoursRange in Miscellaneous

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Tables/Commerce/ChannelManagement/BrickAndMortarStore/Miscellaneous/RetailStoreHoursRange.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[RetailStoreHoursRange/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="RetailStoreHoursRange.md" target="_blank">Miscellaneous/RetailStoreHoursRange</a>|
|[Description](#Description)||<a href="RetailStoreHoursRange.md" target="_blank">Miscellaneous/RetailStoreHoursRange</a>|
|[StartDate](#StartDate)||<a href="RetailStoreHoursRange.md" target="_blank">Miscellaneous/RetailStoreHoursRange</a>|
|[EndDate](#EndDate)||<a href="RetailStoreHoursRange.md" target="_blank">Miscellaneous/RetailStoreHoursRange</a>|
|[StoreHoursTemplateId](#StoreHoursTemplateId)||<a href="RetailStoreHoursRange.md" target="_blank">Miscellaneous/RetailStoreHoursRange</a>|
|[LineNum](#LineNum)||<a href="RetailStoreHoursRange.md" target="_blank">Miscellaneous/RetailStoreHoursRange</a>|
|[MondayOpenTime](#MondayOpenTime)||<a href="RetailStoreHoursRange.md" target="_blank">Miscellaneous/RetailStoreHoursRange</a>|
|[MondayCloseTime](#MondayCloseTime)||<a href="RetailStoreHoursRange.md" target="_blank">Miscellaneous/RetailStoreHoursRange</a>|
|[TuesdayOpenTime](#TuesdayOpenTime)||<a href="RetailStoreHoursRange.md" target="_blank">Miscellaneous/RetailStoreHoursRange</a>|
|[TuesdayCloseTime](#TuesdayCloseTime)||<a href="RetailStoreHoursRange.md" target="_blank">Miscellaneous/RetailStoreHoursRange</a>|
|[WednesdayOpenTime](#WednesdayOpenTime)||<a href="RetailStoreHoursRange.md" target="_blank">Miscellaneous/RetailStoreHoursRange</a>|
|[WednesdayCloseTime](#WednesdayCloseTime)||<a href="RetailStoreHoursRange.md" target="_blank">Miscellaneous/RetailStoreHoursRange</a>|
|[ThursdayOpenTime](#ThursdayOpenTime)||<a href="RetailStoreHoursRange.md" target="_blank">Miscellaneous/RetailStoreHoursRange</a>|
|[ThursdayCloseTime](#ThursdayCloseTime)||<a href="RetailStoreHoursRange.md" target="_blank">Miscellaneous/RetailStoreHoursRange</a>|
|[FridayOpenTime](#FridayOpenTime)||<a href="RetailStoreHoursRange.md" target="_blank">Miscellaneous/RetailStoreHoursRange</a>|
|[FridayCloseTime](#FridayCloseTime)||<a href="RetailStoreHoursRange.md" target="_blank">Miscellaneous/RetailStoreHoursRange</a>|
|[SaturdayOpenTime](#SaturdayOpenTime)||<a href="RetailStoreHoursRange.md" target="_blank">Miscellaneous/RetailStoreHoursRange</a>|
|[SaturdayCloseTime](#SaturdayCloseTime)||<a href="RetailStoreHoursRange.md" target="_blank">Miscellaneous/RetailStoreHoursRange</a>|
|[SundayOpenTime](#SundayOpenTime)||<a href="RetailStoreHoursRange.md" target="_blank">Miscellaneous/RetailStoreHoursRange</a>|
|[SundayCloseTime](#SundayCloseTime)||<a href="RetailStoreHoursRange.md" target="_blank">Miscellaneous/RetailStoreHoursRange</a>|
|[ClosedOnMonday](#ClosedOnMonday)||<a href="RetailStoreHoursRange.md" target="_blank">Miscellaneous/RetailStoreHoursRange</a>|
|[ClosedOnTuesday](#ClosedOnTuesday)||<a href="RetailStoreHoursRange.md" target="_blank">Miscellaneous/RetailStoreHoursRange</a>|
|[ClosedOnWednesday](#ClosedOnWednesday)||<a href="RetailStoreHoursRange.md" target="_blank">Miscellaneous/RetailStoreHoursRange</a>|
|[ClosedOnThursday](#ClosedOnThursday)||<a href="RetailStoreHoursRange.md" target="_blank">Miscellaneous/RetailStoreHoursRange</a>|
|[ClosedOnFriday](#ClosedOnFriday)||<a href="RetailStoreHoursRange.md" target="_blank">Miscellaneous/RetailStoreHoursRange</a>|
|[ClosedOnSaturday](#ClosedOnSaturday)||<a href="RetailStoreHoursRange.md" target="_blank">Miscellaneous/RetailStoreHoursRange</a>|
|[ClosedOnSunday](#ClosedOnSunday)||<a href="RetailStoreHoursRange.md" target="_blank">Miscellaneous/RetailStoreHoursRange</a>|
|[DataAreaId](#DataAreaId)||<a href="RetailStoreHoursRange.md" target="_blank">Miscellaneous/RetailStoreHoursRange</a>|
|[Relationship_RetailStoreHoursTemplateRelationshipId](#Relationship_RetailStoreHoursTemplateRelationshipId)||<a href="RetailStoreHoursRange.md" target="_blank">Miscellaneous/RetailStoreHoursRange</a>|
|[Relationship_CompanyRelationshipId](#Relationship_CompanyRelationshipId)||<a href="RetailStoreHoursRange.md" target="_blank">Miscellaneous/RetailStoreHoursRange</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: Miscellaneous/RetailStoreHoursRange (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[RetailStoreHoursRange/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#Description name="Description">Description</a>

First included in: Miscellaneous/RetailStoreHoursRange (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Label</td></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Description attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Label</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#StartDate name="StartDate">StartDate</a>

First included in: Miscellaneous/RetailStoreHoursRange (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr></table>

#### Traits

<details>
<summary>List of traits for the StartDate attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.dataFormat.date**  
</details>

### <a href=#EndDate name="EndDate">EndDate</a>

First included in: Miscellaneous/RetailStoreHoursRange (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EndDate attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.date**  
</details>

### <a href=#StoreHoursTemplateId name="StoreHoursTemplateId">StoreHoursTemplateId</a>

First included in: Miscellaneous/RetailStoreHoursRange (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the StoreHoursTemplateId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LineNum name="LineNum">LineNum</a>

First included in: Miscellaneous/RetailStoreHoursRange (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LineNum attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#MondayOpenTime name="MondayOpenTime">MondayOpenTime</a>

First included in: Miscellaneous/RetailStoreHoursRange (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>time</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MondayOpenTime attribute are listed below.</summary>

**is.dataFormat.time**  
**means.measurement.time**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.time**  
</details>

### <a href=#MondayCloseTime name="MondayCloseTime">MondayCloseTime</a>

First included in: Miscellaneous/RetailStoreHoursRange (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>time</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MondayCloseTime attribute are listed below.</summary>

**is.dataFormat.time**  
**means.measurement.time**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.time**  
</details>

### <a href=#TuesdayOpenTime name="TuesdayOpenTime">TuesdayOpenTime</a>

First included in: Miscellaneous/RetailStoreHoursRange (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>time</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TuesdayOpenTime attribute are listed below.</summary>

**is.dataFormat.time**  
**means.measurement.time**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.time**  
</details>

### <a href=#TuesdayCloseTime name="TuesdayCloseTime">TuesdayCloseTime</a>

First included in: Miscellaneous/RetailStoreHoursRange (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>time</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TuesdayCloseTime attribute are listed below.</summary>

**is.dataFormat.time**  
**means.measurement.time**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.time**  
</details>

### <a href=#WednesdayOpenTime name="WednesdayOpenTime">WednesdayOpenTime</a>

First included in: Miscellaneous/RetailStoreHoursRange (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>time</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WednesdayOpenTime attribute are listed below.</summary>

**is.dataFormat.time**  
**means.measurement.time**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.time**  
</details>

### <a href=#WednesdayCloseTime name="WednesdayCloseTime">WednesdayCloseTime</a>

First included in: Miscellaneous/RetailStoreHoursRange (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>time</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WednesdayCloseTime attribute are listed below.</summary>

**is.dataFormat.time**  
**means.measurement.time**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.time**  
</details>

### <a href=#ThursdayOpenTime name="ThursdayOpenTime">ThursdayOpenTime</a>

First included in: Miscellaneous/RetailStoreHoursRange (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>time</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ThursdayOpenTime attribute are listed below.</summary>

**is.dataFormat.time**  
**means.measurement.time**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.time**  
</details>

### <a href=#ThursdayCloseTime name="ThursdayCloseTime">ThursdayCloseTime</a>

First included in: Miscellaneous/RetailStoreHoursRange (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>time</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ThursdayCloseTime attribute are listed below.</summary>

**is.dataFormat.time**  
**means.measurement.time**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.time**  
</details>

### <a href=#FridayOpenTime name="FridayOpenTime">FridayOpenTime</a>

First included in: Miscellaneous/RetailStoreHoursRange (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>time</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FridayOpenTime attribute are listed below.</summary>

**is.dataFormat.time**  
**means.measurement.time**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.time**  
</details>

### <a href=#FridayCloseTime name="FridayCloseTime">FridayCloseTime</a>

First included in: Miscellaneous/RetailStoreHoursRange (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>time</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FridayCloseTime attribute are listed below.</summary>

**is.dataFormat.time**  
**means.measurement.time**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.time**  
</details>

### <a href=#SaturdayOpenTime name="SaturdayOpenTime">SaturdayOpenTime</a>

First included in: Miscellaneous/RetailStoreHoursRange (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>time</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SaturdayOpenTime attribute are listed below.</summary>

**is.dataFormat.time**  
**means.measurement.time**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.time**  
</details>

### <a href=#SaturdayCloseTime name="SaturdayCloseTime">SaturdayCloseTime</a>

First included in: Miscellaneous/RetailStoreHoursRange (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>time</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SaturdayCloseTime attribute are listed below.</summary>

**is.dataFormat.time**  
**means.measurement.time**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.time**  
</details>

### <a href=#SundayOpenTime name="SundayOpenTime">SundayOpenTime</a>

First included in: Miscellaneous/RetailStoreHoursRange (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>time</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SundayOpenTime attribute are listed below.</summary>

**is.dataFormat.time**  
**means.measurement.time**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.time**  
</details>

### <a href=#SundayCloseTime name="SundayCloseTime">SundayCloseTime</a>

First included in: Miscellaneous/RetailStoreHoursRange (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>time</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SundayCloseTime attribute are listed below.</summary>

**is.dataFormat.time**  
**means.measurement.time**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.time**  
</details>

### <a href=#ClosedOnMonday name="ClosedOnMonday">ClosedOnMonday</a>

First included in: Miscellaneous/RetailStoreHoursRange (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ClosedOnMonday attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#ClosedOnTuesday name="ClosedOnTuesday">ClosedOnTuesday</a>

First included in: Miscellaneous/RetailStoreHoursRange (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ClosedOnTuesday attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#ClosedOnWednesday name="ClosedOnWednesday">ClosedOnWednesday</a>

First included in: Miscellaneous/RetailStoreHoursRange (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ClosedOnWednesday attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#ClosedOnThursday name="ClosedOnThursday">ClosedOnThursday</a>

First included in: Miscellaneous/RetailStoreHoursRange (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ClosedOnThursday attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#ClosedOnFriday name="ClosedOnFriday">ClosedOnFriday</a>

First included in: Miscellaneous/RetailStoreHoursRange (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ClosedOnFriday attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#ClosedOnSaturday name="ClosedOnSaturday">ClosedOnSaturday</a>

First included in: Miscellaneous/RetailStoreHoursRange (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ClosedOnSaturday attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#ClosedOnSunday name="ClosedOnSunday">ClosedOnSunday</a>

First included in: Miscellaneous/RetailStoreHoursRange (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ClosedOnSunday attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#DataAreaId name="DataAreaId">DataAreaId</a>

First included in: Miscellaneous/RetailStoreHoursRange (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DataAreaId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.readOnly**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_RetailStoreHoursTemplateRelationshipId name="Relationship_RetailStoreHoursTemplateRelationshipId">Relationship_RetailStoreHoursTemplateRelationshipId</a>

First included in: Miscellaneous/RetailStoreHoursRange (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_RetailStoreHoursTemplateRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="RetailStoreHoursTemplate.md" target="_blank">/core/operationsCommon/Tables/Commerce/ChannelManagement/BrickAndMortarStore/Miscellaneous/RetailStoreHoursTemplate.cdm.json/RetailStoreHoursTemplate</a></td><td><a href="RetailStoreHoursTemplate.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_CompanyRelationshipId name="Relationship_CompanyRelationshipId">Relationship_CompanyRelationshipId</a>

First included in: Miscellaneous/RetailStoreHoursRange (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_CompanyRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../../Finance/Ledger/Main/CompanyInfo.md" target="_blank">/core/operationsCommon/Tables/Finance/Ledger/Main/CompanyInfo.cdm.json/CompanyInfo</a></td><td><a href="../../../../Finance/Ledger/Main/CompanyInfo.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>
