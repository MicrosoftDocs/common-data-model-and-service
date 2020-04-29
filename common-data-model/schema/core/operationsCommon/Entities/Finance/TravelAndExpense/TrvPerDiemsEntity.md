---
title: TrvPerDiemsEntity - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/29/2020
ms.author: nebanfic
---

# Per diems

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/Finance/TravelAndExpense/TrvPerDiemsEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Per diems</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[Currency](#Currency)||<a href="TrvPerDiemsEntity.md" target="_blank">TravelAndExpense/TrvPerDiemsEntity</a>|
|[DateFrom](#DateFrom)||<a href="TrvPerDiemsEntity.md" target="_blank">TravelAndExpense/TrvPerDiemsEntity</a>|
|[DateTo](#DateTo)||<a href="TrvPerDiemsEntity.md" target="_blank">TravelAndExpense/TrvPerDiemsEntity</a>|
|[HotelAllowance](#HotelAllowance)||<a href="TrvPerDiemsEntity.md" target="_blank">TravelAndExpense/TrvPerDiemsEntity</a>|
|[Location](#Location)||<a href="TrvPerDiemsEntity.md" target="_blank">TravelAndExpense/TrvPerDiemsEntity</a>|
|[StateId](#StateId)||<a href="TrvPerDiemsEntity.md" target="_blank">TravelAndExpense/TrvPerDiemsEntity</a>|
|[CountryRegionId](#CountryRegionId)||<a href="TrvPerDiemsEntity.md" target="_blank">TravelAndExpense/TrvPerDiemsEntity</a>|
|[MealAllowance](#MealAllowance)||<a href="TrvPerDiemsEntity.md" target="_blank">TravelAndExpense/TrvPerDiemsEntity</a>|
|[OtherAllowance](#OtherAllowance)||<a href="TrvPerDiemsEntity.md" target="_blank">TravelAndExpense/TrvPerDiemsEntity</a>|
|[DeductBreakf](#DeductBreakf)||<a href="TrvPerDiemsEntity.md" target="_blank">TravelAndExpense/TrvPerDiemsEntity</a>|
|[DeductDinner](#DeductDinner)||<a href="TrvPerDiemsEntity.md" target="_blank">TravelAndExpense/TrvPerDiemsEntity</a>|
|[DeductLunch](#DeductLunch)||<a href="TrvPerDiemsEntity.md" target="_blank">TravelAndExpense/TrvPerDiemsEntity</a>|
|[DeductOneMeal](#DeductOneMeal)||<a href="TrvPerDiemsEntity.md" target="_blank">TravelAndExpense/TrvPerDiemsEntity</a>|
|[DeductThreeOrMoreMeals](#DeductThreeOrMoreMeals)||<a href="TrvPerDiemsEntity.md" target="_blank">TravelAndExpense/TrvPerDiemsEntity</a>|
|[DeductTwoMeals](#DeductTwoMeals)||<a href="TrvPerDiemsEntity.md" target="_blank">TravelAndExpense/TrvPerDiemsEntity</a>|
|[BackingTable_TrvPerDiemsRelationshipId](#BackingTable_TrvPerDiemsRelationshipId)||<a href="TrvPerDiemsEntity.md" target="_blank">TravelAndExpense/TrvPerDiemsEntity</a>|
|[Relationship_PrimaryCompanyContextRelationshipId](#Relationship_PrimaryCompanyContextRelationshipId)||<a href="TrvPerDiemsEntity.md" target="_blank">TravelAndExpense/TrvPerDiemsEntity</a>|

### <a href=#Currency name="Currency">Currency</a>

First included in: TravelAndExpense/TrvPerDiemsEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Currency attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DateFrom name="DateFrom">DateFrom</a>

First included in: TravelAndExpense/TrvPerDiemsEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DateFrom attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DateTo name="DateTo">DateTo</a>

First included in: TravelAndExpense/TrvPerDiemsEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DateTo attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#HotelAllowance name="HotelAllowance">HotelAllowance</a>

First included in: TravelAndExpense/TrvPerDiemsEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the HotelAllowance attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Location name="Location">Location</a>

First included in: TravelAndExpense/TrvPerDiemsEntity (this entity)  

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

First included in: TravelAndExpense/TrvPerDiemsEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the StateId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CountryRegionId name="CountryRegionId">CountryRegionId</a>

First included in: TravelAndExpense/TrvPerDiemsEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CountryRegionId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MealAllowance name="MealAllowance">MealAllowance</a>

First included in: TravelAndExpense/TrvPerDiemsEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MealAllowance attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#OtherAllowance name="OtherAllowance">OtherAllowance</a>

First included in: TravelAndExpense/TrvPerDiemsEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OtherAllowance attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DeductBreakf name="DeductBreakf">DeductBreakf</a>

First included in: TravelAndExpense/TrvPerDiemsEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DeductBreakf attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DeductDinner name="DeductDinner">DeductDinner</a>

First included in: TravelAndExpense/TrvPerDiemsEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DeductDinner attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DeductLunch name="DeductLunch">DeductLunch</a>

First included in: TravelAndExpense/TrvPerDiemsEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DeductLunch attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DeductOneMeal name="DeductOneMeal">DeductOneMeal</a>

First included in: TravelAndExpense/TrvPerDiemsEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DeductOneMeal attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DeductThreeOrMoreMeals name="DeductThreeOrMoreMeals">DeductThreeOrMoreMeals</a>

First included in: TravelAndExpense/TrvPerDiemsEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DeductThreeOrMoreMeals attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DeductTwoMeals name="DeductTwoMeals">DeductTwoMeals</a>

First included in: TravelAndExpense/TrvPerDiemsEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DeductTwoMeals attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BackingTable_TrvPerDiemsRelationshipId name="BackingTable_TrvPerDiemsRelationshipId">BackingTable_TrvPerDiemsRelationshipId</a>

First included in: TravelAndExpense/TrvPerDiemsEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_TrvPerDiemsRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/Finance/Expense/Reference/TrvPerDiems.md" target="_blank">/core/operationsCommon/Tables/Finance/Expense/Reference/TrvPerDiems.cdm.json/TrvPerDiems</a></td><td><a href="../../../Tables/Finance/Expense/Reference/TrvPerDiems.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PrimaryCompanyContextRelationshipId name="Relationship_PrimaryCompanyContextRelationshipId">Relationship_PrimaryCompanyContextRelationshipId</a>

First included in: TravelAndExpense/TrvPerDiemsEntity (this entity)  

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
