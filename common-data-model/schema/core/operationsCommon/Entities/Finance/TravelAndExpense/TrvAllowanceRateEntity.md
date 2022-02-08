---
title: TrvAllowanceRateEntity in TravelAndExpense - Common Data Model | Microsoft Docs
description: undefined
author: llawwaii
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: reference
ms.date: 8/7/2020
ms.author: weiluo
---

# Allowance rate in TravelAndExpense(TrvAllowanceRateEntity)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/Finance/TravelAndExpense/TrvAllowanceRateEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.1"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Allowance rate</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[ReductionInPercentageForBreakfast](#ReductionInPercentageForBreakfast)||<a href="TrvAllowanceRateEntity.md" target="_blank">TravelAndExpense/TrvAllowanceRateEntity</a>|
|[ReductionInPercentageForDinner](#ReductionInPercentageForDinner)||<a href="TrvAllowanceRateEntity.md" target="_blank">TravelAndExpense/TrvAllowanceRateEntity</a>|
|[ReductionInPercentageForLunch](#ReductionInPercentageForLunch)||<a href="TrvAllowanceRateEntity.md" target="_blank">TravelAndExpense/TrvAllowanceRateEntity</a>|
|[PercentageReductionFor1Meal](#PercentageReductionFor1Meal)||<a href="TrvAllowanceRateEntity.md" target="_blank">TravelAndExpense/TrvAllowanceRateEntity</a>|
|[PercentageReductionFor3OrMoreMeals](#PercentageReductionFor3OrMoreMeals)||<a href="TrvAllowanceRateEntity.md" target="_blank">TravelAndExpense/TrvAllowanceRateEntity</a>|
|[PercentageReductionFor2Meals](#PercentageReductionFor2Meals)||<a href="TrvAllowanceRateEntity.md" target="_blank">TravelAndExpense/TrvAllowanceRateEntity</a>|
|[MinimumHours](#MinimumHours)||<a href="TrvAllowanceRateEntity.md" target="_blank">TravelAndExpense/TrvAllowanceRateEntity</a>|
|[HotelPercent](#HotelPercent)||<a href="TrvAllowanceRateEntity.md" target="_blank">TravelAndExpense/TrvAllowanceRateEntity</a>|
|[MealPercent](#MealPercent)||<a href="TrvAllowanceRateEntity.md" target="_blank">TravelAndExpense/TrvAllowanceRateEntity</a>|
|[OtherPercent](#OtherPercent)||<a href="TrvAllowanceRateEntity.md" target="_blank">TravelAndExpense/TrvAllowanceRateEntity</a>|
|[Reference](#Reference)||<a href="TrvAllowanceRateEntity.md" target="_blank">TravelAndExpense/TrvAllowanceRateEntity</a>|
|[MaximumHours](#MaximumHours)||<a href="TrvAllowanceRateEntity.md" target="_blank">TravelAndExpense/TrvAllowanceRateEntity</a>|
|[ApplyTo](#ApplyTo)||<a href="TrvAllowanceRateEntity.md" target="_blank">TravelAndExpense/TrvAllowanceRateEntity</a>|
|[DateFrom](#DateFrom)||<a href="TrvAllowanceRateEntity.md" target="_blank">TravelAndExpense/TrvAllowanceRateEntity</a>|
|[DateTo](#DateTo)||<a href="TrvAllowanceRateEntity.md" target="_blank">TravelAndExpense/TrvAllowanceRateEntity</a>|
|[Location](#Location)||<a href="TrvAllowanceRateEntity.md" target="_blank">TravelAndExpense/TrvAllowanceRateEntity</a>|
|[StateId](#StateId)||<a href="TrvAllowanceRateEntity.md" target="_blank">TravelAndExpense/TrvAllowanceRateEntity</a>|
|[CountryRegionId](#CountryRegionId)||<a href="TrvAllowanceRateEntity.md" target="_blank">TravelAndExpense/TrvAllowanceRateEntity</a>|
|[BackingTable_TrvAllowanceRateRelationshipId](#BackingTable_TrvAllowanceRateRelationshipId)||<a href="TrvAllowanceRateEntity.md" target="_blank">TravelAndExpense/TrvAllowanceRateEntity</a>|
|[Relationship_PrimaryCompanyContextRelationshipId](#Relationship_PrimaryCompanyContextRelationshipId)||<a href="TrvAllowanceRateEntity.md" target="_blank">TravelAndExpense/TrvAllowanceRateEntity</a>|

### <a href=#ReductionInPercentageForBreakfast name="ReductionInPercentageForBreakfast">ReductionInPercentageForBreakfast</a>

First included in: TravelAndExpense/TrvAllowanceRateEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReductionInPercentageForBreakfast attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ReductionInPercentageForDinner name="ReductionInPercentageForDinner">ReductionInPercentageForDinner</a>

First included in: TravelAndExpense/TrvAllowanceRateEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReductionInPercentageForDinner attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ReductionInPercentageForLunch name="ReductionInPercentageForLunch">ReductionInPercentageForLunch</a>

First included in: TravelAndExpense/TrvAllowanceRateEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReductionInPercentageForLunch attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PercentageReductionFor1Meal name="PercentageReductionFor1Meal">PercentageReductionFor1Meal</a>

First included in: TravelAndExpense/TrvAllowanceRateEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PercentageReductionFor1Meal attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PercentageReductionFor3OrMoreMeals name="PercentageReductionFor3OrMoreMeals">PercentageReductionFor3OrMoreMeals</a>

First included in: TravelAndExpense/TrvAllowanceRateEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PercentageReductionFor3OrMoreMeals attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PercentageReductionFor2Meals name="PercentageReductionFor2Meals">PercentageReductionFor2Meals</a>

First included in: TravelAndExpense/TrvAllowanceRateEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PercentageReductionFor2Meals attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MinimumHours name="MinimumHours">MinimumHours</a>

First included in: TravelAndExpense/TrvAllowanceRateEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MinimumHours attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#HotelPercent name="HotelPercent">HotelPercent</a>

First included in: TravelAndExpense/TrvAllowanceRateEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the HotelPercent attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MealPercent name="MealPercent">MealPercent</a>

First included in: TravelAndExpense/TrvAllowanceRateEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MealPercent attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#OtherPercent name="OtherPercent">OtherPercent</a>

First included in: TravelAndExpense/TrvAllowanceRateEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OtherPercent attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Reference name="Reference">Reference</a>

First included in: TravelAndExpense/TrvAllowanceRateEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Reference attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MaximumHours name="MaximumHours">MaximumHours</a>

First included in: TravelAndExpense/TrvAllowanceRateEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MaximumHours attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ApplyTo name="ApplyTo">ApplyTo</a>

First included in: TravelAndExpense/TrvAllowanceRateEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ApplyTo attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DateFrom name="DateFrom">DateFrom</a>

First included in: TravelAndExpense/TrvAllowanceRateEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DateFrom attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DateTo name="DateTo">DateTo</a>

First included in: TravelAndExpense/TrvAllowanceRateEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DateTo attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Location name="Location">Location</a>

First included in: TravelAndExpense/TrvAllowanceRateEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Location attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#StateId name="StateId">StateId</a>

First included in: TravelAndExpense/TrvAllowanceRateEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the StateId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CountryRegionId name="CountryRegionId">CountryRegionId</a>

First included in: TravelAndExpense/TrvAllowanceRateEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CountryRegionId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BackingTable_TrvAllowanceRateRelationshipId name="BackingTable_TrvAllowanceRateRelationshipId">BackingTable_TrvAllowanceRateRelationshipId</a>

First included in: TravelAndExpense/TrvAllowanceRateEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_TrvAllowanceRateRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/Finance/Expense/Reference/TrvAllowanceRate.md" target="_blank">/core/operationsCommon/Tables/Finance/Expense/Reference/TrvAllowanceRate.cdm.json/TrvAllowanceRate</a></td><td><a href="../../../Tables/Finance/Expense/Reference/TrvAllowanceRate.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PrimaryCompanyContextRelationshipId name="Relationship_PrimaryCompanyContextRelationshipId">Relationship_PrimaryCompanyContextRelationshipId</a>

First included in: TravelAndExpense/TrvAllowanceRateEntity (this entity)  

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
