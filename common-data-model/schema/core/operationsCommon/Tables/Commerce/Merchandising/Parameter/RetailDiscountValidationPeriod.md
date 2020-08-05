---
title: RetailDiscountValidationPeriod in Parameter - Common Data Model | Microsoft Docs
description: undefined
author: llawwaii
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 8/5/2020
ms.author: weiluo
---

# Discount validation period in Parameter(RetailDiscountValidationPeriod)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Tables/Commerce/Merchandising/Parameter/RetailDiscountValidationPeriod.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[RetailDiscountValidationPeriod/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Discount validation period</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="RetailDiscountValidationPeriod.md" target="_blank">Parameter/RetailDiscountValidationPeriod</a>|
|[endingTime](#endingTime)||<a href="RetailDiscountValidationPeriod.md" target="_blank">Parameter/RetailDiscountValidationPeriod</a>|
|[endingTimeAfterMidnight](#endingTimeAfterMidnight)||<a href="RetailDiscountValidationPeriod.md" target="_blank">Parameter/RetailDiscountValidationPeriod</a>|
|[fridayEndingTime](#fridayEndingTime)||<a href="RetailDiscountValidationPeriod.md" target="_blank">Parameter/RetailDiscountValidationPeriod</a>|
|[fridayEndingTimeAfterMidnight](#fridayEndingTimeAfterMidnight)||<a href="RetailDiscountValidationPeriod.md" target="_blank">Parameter/RetailDiscountValidationPeriod</a>|
|[fridayStartingTime](#fridayStartingTime)||<a href="RetailDiscountValidationPeriod.md" target="_blank">Parameter/RetailDiscountValidationPeriod</a>|
|[fridayTimeWithinBounds](#fridayTimeWithinBounds)||<a href="RetailDiscountValidationPeriod.md" target="_blank">Parameter/RetailDiscountValidationPeriod</a>|
|[mondayEndingTime](#mondayEndingTime)||<a href="RetailDiscountValidationPeriod.md" target="_blank">Parameter/RetailDiscountValidationPeriod</a>|
|[mondayEndingTimeAfterMidnight](#mondayEndingTimeAfterMidnight)||<a href="RetailDiscountValidationPeriod.md" target="_blank">Parameter/RetailDiscountValidationPeriod</a>|
|[mondayStartingTime](#mondayStartingTime)||<a href="RetailDiscountValidationPeriod.md" target="_blank">Parameter/RetailDiscountValidationPeriod</a>|
|[mondayTimeWithinBounds](#mondayTimeWithinBounds)||<a href="RetailDiscountValidationPeriod.md" target="_blank">Parameter/RetailDiscountValidationPeriod</a>|
|[name](#name)||<a href="RetailDiscountValidationPeriod.md" target="_blank">Parameter/RetailDiscountValidationPeriod</a>|
|[periodId](#periodId)||<a href="RetailDiscountValidationPeriod.md" target="_blank">Parameter/RetailDiscountValidationPeriod</a>|
|[saturdayEndingTime](#saturdayEndingTime)||<a href="RetailDiscountValidationPeriod.md" target="_blank">Parameter/RetailDiscountValidationPeriod</a>|
|[saturdayEndingTimeAfterMidnight](#saturdayEndingTimeAfterMidnight)||<a href="RetailDiscountValidationPeriod.md" target="_blank">Parameter/RetailDiscountValidationPeriod</a>|
|[saturdayStartingTime](#saturdayStartingTime)||<a href="RetailDiscountValidationPeriod.md" target="_blank">Parameter/RetailDiscountValidationPeriod</a>|
|[saturdayTimeWithinBounds](#saturdayTimeWithinBounds)||<a href="RetailDiscountValidationPeriod.md" target="_blank">Parameter/RetailDiscountValidationPeriod</a>|
|[startingTime](#startingTime)||<a href="RetailDiscountValidationPeriod.md" target="_blank">Parameter/RetailDiscountValidationPeriod</a>|
|[sundayEndingTime](#sundayEndingTime)||<a href="RetailDiscountValidationPeriod.md" target="_blank">Parameter/RetailDiscountValidationPeriod</a>|
|[sundayEndingTimeAfterMidnight](#sundayEndingTimeAfterMidnight)||<a href="RetailDiscountValidationPeriod.md" target="_blank">Parameter/RetailDiscountValidationPeriod</a>|
|[sundayStartingTime](#sundayStartingTime)||<a href="RetailDiscountValidationPeriod.md" target="_blank">Parameter/RetailDiscountValidationPeriod</a>|
|[sundayTimeWithinBounds](#sundayTimeWithinBounds)||<a href="RetailDiscountValidationPeriod.md" target="_blank">Parameter/RetailDiscountValidationPeriod</a>|
|[thuesdayEndingTime](#thuesdayEndingTime)||<a href="RetailDiscountValidationPeriod.md" target="_blank">Parameter/RetailDiscountValidationPeriod</a>|
|[thuesdayEndingTimeAfterMidnight](#thuesdayEndingTimeAfterMidnight)||<a href="RetailDiscountValidationPeriod.md" target="_blank">Parameter/RetailDiscountValidationPeriod</a>|
|[thuesdayStartingTime](#thuesdayStartingTime)||<a href="RetailDiscountValidationPeriod.md" target="_blank">Parameter/RetailDiscountValidationPeriod</a>|
|[thuesdayTimeWithinBounds](#thuesdayTimeWithinBounds)||<a href="RetailDiscountValidationPeriod.md" target="_blank">Parameter/RetailDiscountValidationPeriod</a>|
|[thursdayEndingTime](#thursdayEndingTime)||<a href="RetailDiscountValidationPeriod.md" target="_blank">Parameter/RetailDiscountValidationPeriod</a>|
|[thursdayEndingTimeAfterMidnight](#thursdayEndingTimeAfterMidnight)||<a href="RetailDiscountValidationPeriod.md" target="_blank">Parameter/RetailDiscountValidationPeriod</a>|
|[thursdayStartingTime](#thursdayStartingTime)||<a href="RetailDiscountValidationPeriod.md" target="_blank">Parameter/RetailDiscountValidationPeriod</a>|
|[thursdayTimeWithinBounds](#thursdayTimeWithinBounds)||<a href="RetailDiscountValidationPeriod.md" target="_blank">Parameter/RetailDiscountValidationPeriod</a>|
|[timeWithinBounds](#timeWithinBounds)||<a href="RetailDiscountValidationPeriod.md" target="_blank">Parameter/RetailDiscountValidationPeriod</a>|
|[validFrom](#validFrom)||<a href="RetailDiscountValidationPeriod.md" target="_blank">Parameter/RetailDiscountValidationPeriod</a>|
|[validTo](#validTo)||<a href="RetailDiscountValidationPeriod.md" target="_blank">Parameter/RetailDiscountValidationPeriod</a>|
|[wednesdayEndingTime](#wednesdayEndingTime)||<a href="RetailDiscountValidationPeriod.md" target="_blank">Parameter/RetailDiscountValidationPeriod</a>|
|[wednesdayEndingTimeAfterMidnight](#wednesdayEndingTimeAfterMidnight)||<a href="RetailDiscountValidationPeriod.md" target="_blank">Parameter/RetailDiscountValidationPeriod</a>|
|[wednesdayStartingTime](#wednesdayStartingTime)||<a href="RetailDiscountValidationPeriod.md" target="_blank">Parameter/RetailDiscountValidationPeriod</a>|
|[wednesdayTimeWithinBounds](#wednesdayTimeWithinBounds)||<a href="RetailDiscountValidationPeriod.md" target="_blank">Parameter/RetailDiscountValidationPeriod</a>|
|[DataAreaId](#DataAreaId)||<a href="RetailDiscountValidationPeriod.md" target="_blank">Parameter/RetailDiscountValidationPeriod</a>|
|[Relationship_CompanyRelationshipId](#Relationship_CompanyRelationshipId)||<a href="RetailDiscountValidationPeriod.md" target="_blank">Parameter/RetailDiscountValidationPeriod</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: Parameter/RetailDiscountValidationPeriod (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[RetailDiscountValidationPeriod/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#endingTime name="endingTime">endingTime</a>

First included in: Parameter/RetailDiscountValidationPeriod (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>time</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the endingTime attribute are listed below.</summary>

**is.dataFormat.time**  
**means.measurement.time**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.time**  
</details>

### <a href=#endingTimeAfterMidnight name="endingTimeAfterMidnight">endingTimeAfterMidnight</a>

First included in: Parameter/RetailDiscountValidationPeriod (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the endingTimeAfterMidnight attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#fridayEndingTime name="fridayEndingTime">fridayEndingTime</a>

First included in: Parameter/RetailDiscountValidationPeriod (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>time</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the fridayEndingTime attribute are listed below.</summary>

**is.dataFormat.time**  
**means.measurement.time**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.time**  
</details>

### <a href=#fridayEndingTimeAfterMidnight name="fridayEndingTimeAfterMidnight">fridayEndingTimeAfterMidnight</a>

First included in: Parameter/RetailDiscountValidationPeriod (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the fridayEndingTimeAfterMidnight attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#fridayStartingTime name="fridayStartingTime">fridayStartingTime</a>

First included in: Parameter/RetailDiscountValidationPeriod (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>time</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the fridayStartingTime attribute are listed below.</summary>

**is.dataFormat.time**  
**means.measurement.time**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.time**  
</details>

### <a href=#fridayTimeWithinBounds name="fridayTimeWithinBounds">fridayTimeWithinBounds</a>

First included in: Parameter/RetailDiscountValidationPeriod (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the fridayTimeWithinBounds attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#mondayEndingTime name="mondayEndingTime">mondayEndingTime</a>

First included in: Parameter/RetailDiscountValidationPeriod (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>time</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the mondayEndingTime attribute are listed below.</summary>

**is.dataFormat.time**  
**means.measurement.time**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.time**  
</details>

### <a href=#mondayEndingTimeAfterMidnight name="mondayEndingTimeAfterMidnight">mondayEndingTimeAfterMidnight</a>

First included in: Parameter/RetailDiscountValidationPeriod (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the mondayEndingTimeAfterMidnight attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#mondayStartingTime name="mondayStartingTime">mondayStartingTime</a>

First included in: Parameter/RetailDiscountValidationPeriod (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>time</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the mondayStartingTime attribute are listed below.</summary>

**is.dataFormat.time**  
**means.measurement.time**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.time**  
</details>

### <a href=#mondayTimeWithinBounds name="mondayTimeWithinBounds">mondayTimeWithinBounds</a>

First included in: Parameter/RetailDiscountValidationPeriod (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the mondayTimeWithinBounds attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#name name="name">name</a>

First included in: Parameter/RetailDiscountValidationPeriod (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the name attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#periodId name="periodId">periodId</a>

First included in: Parameter/RetailDiscountValidationPeriod (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the periodId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#saturdayEndingTime name="saturdayEndingTime">saturdayEndingTime</a>

First included in: Parameter/RetailDiscountValidationPeriod (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>time</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the saturdayEndingTime attribute are listed below.</summary>

**is.dataFormat.time**  
**means.measurement.time**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.time**  
</details>

### <a href=#saturdayEndingTimeAfterMidnight name="saturdayEndingTimeAfterMidnight">saturdayEndingTimeAfterMidnight</a>

First included in: Parameter/RetailDiscountValidationPeriod (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the saturdayEndingTimeAfterMidnight attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#saturdayStartingTime name="saturdayStartingTime">saturdayStartingTime</a>

First included in: Parameter/RetailDiscountValidationPeriod (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>time</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the saturdayStartingTime attribute are listed below.</summary>

**is.dataFormat.time**  
**means.measurement.time**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.time**  
</details>

### <a href=#saturdayTimeWithinBounds name="saturdayTimeWithinBounds">saturdayTimeWithinBounds</a>

First included in: Parameter/RetailDiscountValidationPeriod (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the saturdayTimeWithinBounds attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#startingTime name="startingTime">startingTime</a>

First included in: Parameter/RetailDiscountValidationPeriod (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>time</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the startingTime attribute are listed below.</summary>

**is.dataFormat.time**  
**means.measurement.time**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.time**  
</details>

### <a href=#sundayEndingTime name="sundayEndingTime">sundayEndingTime</a>

First included in: Parameter/RetailDiscountValidationPeriod (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>time</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the sundayEndingTime attribute are listed below.</summary>

**is.dataFormat.time**  
**means.measurement.time**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.time**  
</details>

### <a href=#sundayEndingTimeAfterMidnight name="sundayEndingTimeAfterMidnight">sundayEndingTimeAfterMidnight</a>

First included in: Parameter/RetailDiscountValidationPeriod (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the sundayEndingTimeAfterMidnight attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#sundayStartingTime name="sundayStartingTime">sundayStartingTime</a>

First included in: Parameter/RetailDiscountValidationPeriod (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>time</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the sundayStartingTime attribute are listed below.</summary>

**is.dataFormat.time**  
**means.measurement.time**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.time**  
</details>

### <a href=#sundayTimeWithinBounds name="sundayTimeWithinBounds">sundayTimeWithinBounds</a>

First included in: Parameter/RetailDiscountValidationPeriod (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the sundayTimeWithinBounds attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#thuesdayEndingTime name="thuesdayEndingTime">thuesdayEndingTime</a>

First included in: Parameter/RetailDiscountValidationPeriod (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>time</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the thuesdayEndingTime attribute are listed below.</summary>

**is.dataFormat.time**  
**means.measurement.time**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.time**  
</details>

### <a href=#thuesdayEndingTimeAfterMidnight name="thuesdayEndingTimeAfterMidnight">thuesdayEndingTimeAfterMidnight</a>

First included in: Parameter/RetailDiscountValidationPeriod (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the thuesdayEndingTimeAfterMidnight attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#thuesdayStartingTime name="thuesdayStartingTime">thuesdayStartingTime</a>

First included in: Parameter/RetailDiscountValidationPeriod (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>time</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the thuesdayStartingTime attribute are listed below.</summary>

**is.dataFormat.time**  
**means.measurement.time**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.time**  
</details>

### <a href=#thuesdayTimeWithinBounds name="thuesdayTimeWithinBounds">thuesdayTimeWithinBounds</a>

First included in: Parameter/RetailDiscountValidationPeriod (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the thuesdayTimeWithinBounds attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#thursdayEndingTime name="thursdayEndingTime">thursdayEndingTime</a>

First included in: Parameter/RetailDiscountValidationPeriod (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>time</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the thursdayEndingTime attribute are listed below.</summary>

**is.dataFormat.time**  
**means.measurement.time**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.time**  
</details>

### <a href=#thursdayEndingTimeAfterMidnight name="thursdayEndingTimeAfterMidnight">thursdayEndingTimeAfterMidnight</a>

First included in: Parameter/RetailDiscountValidationPeriod (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the thursdayEndingTimeAfterMidnight attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#thursdayStartingTime name="thursdayStartingTime">thursdayStartingTime</a>

First included in: Parameter/RetailDiscountValidationPeriod (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>time</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the thursdayStartingTime attribute are listed below.</summary>

**is.dataFormat.time**  
**means.measurement.time**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.time**  
</details>

### <a href=#thursdayTimeWithinBounds name="thursdayTimeWithinBounds">thursdayTimeWithinBounds</a>

First included in: Parameter/RetailDiscountValidationPeriod (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the thursdayTimeWithinBounds attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#timeWithinBounds name="timeWithinBounds">timeWithinBounds</a>

First included in: Parameter/RetailDiscountValidationPeriod (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the timeWithinBounds attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#validFrom name="validFrom">validFrom</a>

First included in: Parameter/RetailDiscountValidationPeriod (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the validFrom attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.date**  
</details>

### <a href=#validTo name="validTo">validTo</a>

First included in: Parameter/RetailDiscountValidationPeriod (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the validTo attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.date**  
</details>

### <a href=#wednesdayEndingTime name="wednesdayEndingTime">wednesdayEndingTime</a>

First included in: Parameter/RetailDiscountValidationPeriod (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>time</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the wednesdayEndingTime attribute are listed below.</summary>

**is.dataFormat.time**  
**means.measurement.time**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.time**  
</details>

### <a href=#wednesdayEndingTimeAfterMidnight name="wednesdayEndingTimeAfterMidnight">wednesdayEndingTimeAfterMidnight</a>

First included in: Parameter/RetailDiscountValidationPeriod (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the wednesdayEndingTimeAfterMidnight attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#wednesdayStartingTime name="wednesdayStartingTime">wednesdayStartingTime</a>

First included in: Parameter/RetailDiscountValidationPeriod (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>time</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the wednesdayStartingTime attribute are listed below.</summary>

**is.dataFormat.time**  
**means.measurement.time**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.time**  
</details>

### <a href=#wednesdayTimeWithinBounds name="wednesdayTimeWithinBounds">wednesdayTimeWithinBounds</a>

First included in: Parameter/RetailDiscountValidationPeriod (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the wednesdayTimeWithinBounds attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#DataAreaId name="DataAreaId">DataAreaId</a>

First included in: Parameter/RetailDiscountValidationPeriod (this entity)  

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

### <a href=#Relationship_CompanyRelationshipId name="Relationship_CompanyRelationshipId">Relationship_CompanyRelationshipId</a>

First included in: Parameter/RetailDiscountValidationPeriod (this entity)  

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
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Finance/Ledger/Main/CompanyInfo.md" target="_blank">/core/operationsCommon/Tables/Finance/Ledger/Main/CompanyInfo.cdm.json/CompanyInfo</a></td><td><a href="../../../Finance/Ledger/Main/CompanyInfo.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>
