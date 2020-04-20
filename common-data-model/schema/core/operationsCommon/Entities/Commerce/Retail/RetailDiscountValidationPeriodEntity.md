---
title: RetailDiscountValidationPeriodEntity - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/20/2020
ms.author: nebanfic
---

# RetailDiscountValidationPeriodEntity

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/Commerce/Retail/RetailDiscountValidationPeriodEntity.cdm.json" target="_blank">GitHub</a>.  

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
|[endingTime](#endingTime)||<a href="RetailDiscountValidationPeriodEntity.md" target="_blank">Retail/RetailDiscountValidationPeriodEntity</a>|
|[endingTimeAfterMidnight](#endingTimeAfterMidnight)||<a href="RetailDiscountValidationPeriodEntity.md" target="_blank">Retail/RetailDiscountValidationPeriodEntity</a>|
|[fridayEndingTime](#fridayEndingTime)||<a href="RetailDiscountValidationPeriodEntity.md" target="_blank">Retail/RetailDiscountValidationPeriodEntity</a>|
|[fridayEndingTimeAfterMidnight](#fridayEndingTimeAfterMidnight)||<a href="RetailDiscountValidationPeriodEntity.md" target="_blank">Retail/RetailDiscountValidationPeriodEntity</a>|
|[fridayStartingTime](#fridayStartingTime)||<a href="RetailDiscountValidationPeriodEntity.md" target="_blank">Retail/RetailDiscountValidationPeriodEntity</a>|
|[fridayTimeWithinBounds](#fridayTimeWithinBounds)||<a href="RetailDiscountValidationPeriodEntity.md" target="_blank">Retail/RetailDiscountValidationPeriodEntity</a>|
|[mondayEndingTime](#mondayEndingTime)||<a href="RetailDiscountValidationPeriodEntity.md" target="_blank">Retail/RetailDiscountValidationPeriodEntity</a>|
|[mondayEndingTimeAfterMidnight](#mondayEndingTimeAfterMidnight)||<a href="RetailDiscountValidationPeriodEntity.md" target="_blank">Retail/RetailDiscountValidationPeriodEntity</a>|
|[mondayStartingTime](#mondayStartingTime)||<a href="RetailDiscountValidationPeriodEntity.md" target="_blank">Retail/RetailDiscountValidationPeriodEntity</a>|
|[mondayTimeWithinBounds](#mondayTimeWithinBounds)||<a href="RetailDiscountValidationPeriodEntity.md" target="_blank">Retail/RetailDiscountValidationPeriodEntity</a>|
|[name](#name)||<a href="RetailDiscountValidationPeriodEntity.md" target="_blank">Retail/RetailDiscountValidationPeriodEntity</a>|
|[PeriodId](#PeriodId)||<a href="RetailDiscountValidationPeriodEntity.md" target="_blank">Retail/RetailDiscountValidationPeriodEntity</a>|
|[saturdayEndingTime](#saturdayEndingTime)||<a href="RetailDiscountValidationPeriodEntity.md" target="_blank">Retail/RetailDiscountValidationPeriodEntity</a>|
|[saturdayEndingTimeAfterMidnight](#saturdayEndingTimeAfterMidnight)||<a href="RetailDiscountValidationPeriodEntity.md" target="_blank">Retail/RetailDiscountValidationPeriodEntity</a>|
|[saturdayStartingTime](#saturdayStartingTime)||<a href="RetailDiscountValidationPeriodEntity.md" target="_blank">Retail/RetailDiscountValidationPeriodEntity</a>|
|[saturdayTimeWithinBounds](#saturdayTimeWithinBounds)||<a href="RetailDiscountValidationPeriodEntity.md" target="_blank">Retail/RetailDiscountValidationPeriodEntity</a>|
|[startingTime](#startingTime)||<a href="RetailDiscountValidationPeriodEntity.md" target="_blank">Retail/RetailDiscountValidationPeriodEntity</a>|
|[sundayEndingTime](#sundayEndingTime)||<a href="RetailDiscountValidationPeriodEntity.md" target="_blank">Retail/RetailDiscountValidationPeriodEntity</a>|
|[sundayEndingTimeAfterMidnight](#sundayEndingTimeAfterMidnight)||<a href="RetailDiscountValidationPeriodEntity.md" target="_blank">Retail/RetailDiscountValidationPeriodEntity</a>|
|[sundayStartingTime](#sundayStartingTime)||<a href="RetailDiscountValidationPeriodEntity.md" target="_blank">Retail/RetailDiscountValidationPeriodEntity</a>|
|[sundayTimeWithinBounds](#sundayTimeWithinBounds)||<a href="RetailDiscountValidationPeriodEntity.md" target="_blank">Retail/RetailDiscountValidationPeriodEntity</a>|
|[tuesdayEndingTime](#tuesdayEndingTime)||<a href="RetailDiscountValidationPeriodEntity.md" target="_blank">Retail/RetailDiscountValidationPeriodEntity</a>|
|[tuesdayEndingTimeAfterMidnight](#tuesdayEndingTimeAfterMidnight)||<a href="RetailDiscountValidationPeriodEntity.md" target="_blank">Retail/RetailDiscountValidationPeriodEntity</a>|
|[tuesdayStartingTime](#tuesdayStartingTime)||<a href="RetailDiscountValidationPeriodEntity.md" target="_blank">Retail/RetailDiscountValidationPeriodEntity</a>|
|[tuesdayTimeWithinBounds](#tuesdayTimeWithinBounds)||<a href="RetailDiscountValidationPeriodEntity.md" target="_blank">Retail/RetailDiscountValidationPeriodEntity</a>|
|[thursdayEndingTime](#thursdayEndingTime)||<a href="RetailDiscountValidationPeriodEntity.md" target="_blank">Retail/RetailDiscountValidationPeriodEntity</a>|
|[thursdayEndingTimeAfterMidnight](#thursdayEndingTimeAfterMidnight)||<a href="RetailDiscountValidationPeriodEntity.md" target="_blank">Retail/RetailDiscountValidationPeriodEntity</a>|
|[thursdayStartingTime](#thursdayStartingTime)||<a href="RetailDiscountValidationPeriodEntity.md" target="_blank">Retail/RetailDiscountValidationPeriodEntity</a>|
|[thursdayTimeWithinBounds](#thursdayTimeWithinBounds)||<a href="RetailDiscountValidationPeriodEntity.md" target="_blank">Retail/RetailDiscountValidationPeriodEntity</a>|
|[timeWithinBounds](#timeWithinBounds)||<a href="RetailDiscountValidationPeriodEntity.md" target="_blank">Retail/RetailDiscountValidationPeriodEntity</a>|
|[validFrom](#validFrom)||<a href="RetailDiscountValidationPeriodEntity.md" target="_blank">Retail/RetailDiscountValidationPeriodEntity</a>|
|[validTo](#validTo)||<a href="RetailDiscountValidationPeriodEntity.md" target="_blank">Retail/RetailDiscountValidationPeriodEntity</a>|
|[wednesdayEndingTime](#wednesdayEndingTime)||<a href="RetailDiscountValidationPeriodEntity.md" target="_blank">Retail/RetailDiscountValidationPeriodEntity</a>|
|[wednesdayEndingTimeAfterMidnight](#wednesdayEndingTimeAfterMidnight)||<a href="RetailDiscountValidationPeriodEntity.md" target="_blank">Retail/RetailDiscountValidationPeriodEntity</a>|
|[wednesdayStartingTime](#wednesdayStartingTime)||<a href="RetailDiscountValidationPeriodEntity.md" target="_blank">Retail/RetailDiscountValidationPeriodEntity</a>|
|[wednesdayTimeWithinBounds](#wednesdayTimeWithinBounds)||<a href="RetailDiscountValidationPeriodEntity.md" target="_blank">Retail/RetailDiscountValidationPeriodEntity</a>|
|[BackingTable_RetailDiscountValidationPeriodRelationshipId](#BackingTable_RetailDiscountValidationPeriodRelationshipId)||<a href="RetailDiscountValidationPeriodEntity.md" target="_blank">Retail/RetailDiscountValidationPeriodEntity</a>|
|[Relationship_PrimaryCompanyContextRelationshipId](#Relationship_PrimaryCompanyContextRelationshipId)||<a href="RetailDiscountValidationPeriodEntity.md" target="_blank">Retail/RetailDiscountValidationPeriodEntity</a>|

### <a href=#endingTime name="endingTime">endingTime</a>

First included in: Retail/RetailDiscountValidationPeriodEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the endingTime attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#endingTimeAfterMidnight name="endingTimeAfterMidnight">endingTimeAfterMidnight</a>

First included in: Retail/RetailDiscountValidationPeriodEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the endingTimeAfterMidnight attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#fridayEndingTime name="fridayEndingTime">fridayEndingTime</a>

First included in: Retail/RetailDiscountValidationPeriodEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the fridayEndingTime attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#fridayEndingTimeAfterMidnight name="fridayEndingTimeAfterMidnight">fridayEndingTimeAfterMidnight</a>

First included in: Retail/RetailDiscountValidationPeriodEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the fridayEndingTimeAfterMidnight attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#fridayStartingTime name="fridayStartingTime">fridayStartingTime</a>

First included in: Retail/RetailDiscountValidationPeriodEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the fridayStartingTime attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#fridayTimeWithinBounds name="fridayTimeWithinBounds">fridayTimeWithinBounds</a>

First included in: Retail/RetailDiscountValidationPeriodEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the fridayTimeWithinBounds attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#mondayEndingTime name="mondayEndingTime">mondayEndingTime</a>

First included in: Retail/RetailDiscountValidationPeriodEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the mondayEndingTime attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#mondayEndingTimeAfterMidnight name="mondayEndingTimeAfterMidnight">mondayEndingTimeAfterMidnight</a>

First included in: Retail/RetailDiscountValidationPeriodEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the mondayEndingTimeAfterMidnight attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#mondayStartingTime name="mondayStartingTime">mondayStartingTime</a>

First included in: Retail/RetailDiscountValidationPeriodEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the mondayStartingTime attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#mondayTimeWithinBounds name="mondayTimeWithinBounds">mondayTimeWithinBounds</a>

First included in: Retail/RetailDiscountValidationPeriodEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the mondayTimeWithinBounds attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#name name="name">name</a>

First included in: Retail/RetailDiscountValidationPeriodEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the name attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PeriodId name="PeriodId">PeriodId</a>

First included in: Retail/RetailDiscountValidationPeriodEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PeriodId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#saturdayEndingTime name="saturdayEndingTime">saturdayEndingTime</a>

First included in: Retail/RetailDiscountValidationPeriodEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the saturdayEndingTime attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#saturdayEndingTimeAfterMidnight name="saturdayEndingTimeAfterMidnight">saturdayEndingTimeAfterMidnight</a>

First included in: Retail/RetailDiscountValidationPeriodEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the saturdayEndingTimeAfterMidnight attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#saturdayStartingTime name="saturdayStartingTime">saturdayStartingTime</a>

First included in: Retail/RetailDiscountValidationPeriodEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the saturdayStartingTime attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#saturdayTimeWithinBounds name="saturdayTimeWithinBounds">saturdayTimeWithinBounds</a>

First included in: Retail/RetailDiscountValidationPeriodEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the saturdayTimeWithinBounds attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#startingTime name="startingTime">startingTime</a>

First included in: Retail/RetailDiscountValidationPeriodEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the startingTime attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#sundayEndingTime name="sundayEndingTime">sundayEndingTime</a>

First included in: Retail/RetailDiscountValidationPeriodEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the sundayEndingTime attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#sundayEndingTimeAfterMidnight name="sundayEndingTimeAfterMidnight">sundayEndingTimeAfterMidnight</a>

First included in: Retail/RetailDiscountValidationPeriodEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the sundayEndingTimeAfterMidnight attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#sundayStartingTime name="sundayStartingTime">sundayStartingTime</a>

First included in: Retail/RetailDiscountValidationPeriodEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the sundayStartingTime attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#sundayTimeWithinBounds name="sundayTimeWithinBounds">sundayTimeWithinBounds</a>

First included in: Retail/RetailDiscountValidationPeriodEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the sundayTimeWithinBounds attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#tuesdayEndingTime name="tuesdayEndingTime">tuesdayEndingTime</a>

First included in: Retail/RetailDiscountValidationPeriodEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the tuesdayEndingTime attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#tuesdayEndingTimeAfterMidnight name="tuesdayEndingTimeAfterMidnight">tuesdayEndingTimeAfterMidnight</a>

First included in: Retail/RetailDiscountValidationPeriodEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the tuesdayEndingTimeAfterMidnight attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#tuesdayStartingTime name="tuesdayStartingTime">tuesdayStartingTime</a>

First included in: Retail/RetailDiscountValidationPeriodEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the tuesdayStartingTime attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#tuesdayTimeWithinBounds name="tuesdayTimeWithinBounds">tuesdayTimeWithinBounds</a>

First included in: Retail/RetailDiscountValidationPeriodEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the tuesdayTimeWithinBounds attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#thursdayEndingTime name="thursdayEndingTime">thursdayEndingTime</a>

First included in: Retail/RetailDiscountValidationPeriodEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the thursdayEndingTime attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#thursdayEndingTimeAfterMidnight name="thursdayEndingTimeAfterMidnight">thursdayEndingTimeAfterMidnight</a>

First included in: Retail/RetailDiscountValidationPeriodEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the thursdayEndingTimeAfterMidnight attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#thursdayStartingTime name="thursdayStartingTime">thursdayStartingTime</a>

First included in: Retail/RetailDiscountValidationPeriodEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the thursdayStartingTime attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#thursdayTimeWithinBounds name="thursdayTimeWithinBounds">thursdayTimeWithinBounds</a>

First included in: Retail/RetailDiscountValidationPeriodEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the thursdayTimeWithinBounds attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#timeWithinBounds name="timeWithinBounds">timeWithinBounds</a>

First included in: Retail/RetailDiscountValidationPeriodEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the timeWithinBounds attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#validFrom name="validFrom">validFrom</a>

First included in: Retail/RetailDiscountValidationPeriodEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the validFrom attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#validTo name="validTo">validTo</a>

First included in: Retail/RetailDiscountValidationPeriodEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the validTo attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#wednesdayEndingTime name="wednesdayEndingTime">wednesdayEndingTime</a>

First included in: Retail/RetailDiscountValidationPeriodEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the wednesdayEndingTime attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#wednesdayEndingTimeAfterMidnight name="wednesdayEndingTimeAfterMidnight">wednesdayEndingTimeAfterMidnight</a>

First included in: Retail/RetailDiscountValidationPeriodEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the wednesdayEndingTimeAfterMidnight attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#wednesdayStartingTime name="wednesdayStartingTime">wednesdayStartingTime</a>

First included in: Retail/RetailDiscountValidationPeriodEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the wednesdayStartingTime attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#wednesdayTimeWithinBounds name="wednesdayTimeWithinBounds">wednesdayTimeWithinBounds</a>

First included in: Retail/RetailDiscountValidationPeriodEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the wednesdayTimeWithinBounds attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BackingTable_RetailDiscountValidationPeriodRelationshipId name="BackingTable_RetailDiscountValidationPeriodRelationshipId">BackingTable_RetailDiscountValidationPeriodRelationshipId</a>

First included in: Retail/RetailDiscountValidationPeriodEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_RetailDiscountValidationPeriodRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/Commerce/Retail/Parameter/RetailDiscountValidationPeriod.md" target="_blank">/core/operationsCommon/Tables/Commerce/Retail/Parameter/RetailDiscountValidationPeriod.cdm.json/RetailDiscountValidationPeriod</a></td><td><a href="../../../Tables/Commerce/Retail/Parameter/RetailDiscountValidationPeriod.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PrimaryCompanyContextRelationshipId name="Relationship_PrimaryCompanyContextRelationshipId">Relationship_PrimaryCompanyContextRelationshipId</a>

First included in: Retail/RetailDiscountValidationPeriodEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_PrimaryCompanyContextRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/Finance/Ledger/Main/CompanyInfo.md" target="_blank">/core/operationsCommon/Tables/Finance/Ledger/Main/CompanyInfo.cdm.json/CompanyInfo</a></td><td><a href="../../../Tables/Finance/Ledger/Main/CompanyInfo.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>
