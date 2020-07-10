---
title: BudgetCycleTimeSpanEntity in Budgeting - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 7/10/2020
ms.author: nebanfic
---

# Budget cycle time span in Budgeting(BudgetCycleTimeSpanEntity)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/Finance/Budgeting/BudgetCycleTimeSpanEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Budget cycle time span</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[Name](#Name)||<a href="BudgetCycleTimeSpanEntity.md" target="_blank">Budgeting/BudgetCycleTimeSpanEntity</a>|
|[FiscalCalendarId](#FiscalCalendarId)||<a href="BudgetCycleTimeSpanEntity.md" target="_blank">Budgeting/BudgetCycleTimeSpanEntity</a>|
|[FiscalCalendar](#FiscalCalendar)||<a href="BudgetCycleTimeSpanEntity.md" target="_blank">Budgeting/BudgetCycleTimeSpanEntity</a>|
|[BudgetCycleLengthOption](#BudgetCycleLengthOption)||<a href="BudgetCycleTimeSpanEntity.md" target="_blank">Budgeting/BudgetCycleTimeSpanEntity</a>|
|[DefaultNumberOfAccountingPeriods](#DefaultNumberOfAccountingPeriods)||<a href="BudgetCycleTimeSpanEntity.md" target="_blank">Budgeting/BudgetCycleTimeSpanEntity</a>|
|[BackingTable_BudgetCycleTimeSpanRelationshipId](#BackingTable_BudgetCycleTimeSpanRelationshipId)||<a href="BudgetCycleTimeSpanEntity.md" target="_blank">Budgeting/BudgetCycleTimeSpanEntity</a>|

### <a href=#Name name="Name">Name</a>

First included in: Budgeting/BudgetCycleTimeSpanEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Name attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FiscalCalendarId name="FiscalCalendarId">FiscalCalendarId</a>

First included in: Budgeting/BudgetCycleTimeSpanEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FiscalCalendarId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FiscalCalendar name="FiscalCalendar">FiscalCalendar</a>

First included in: Budgeting/BudgetCycleTimeSpanEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FiscalCalendar attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BudgetCycleLengthOption name="BudgetCycleLengthOption">BudgetCycleLengthOption</a>

First included in: Budgeting/BudgetCycleTimeSpanEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BudgetCycleLengthOption attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DefaultNumberOfAccountingPeriods name="DefaultNumberOfAccountingPeriods">DefaultNumberOfAccountingPeriods</a>

First included in: Budgeting/BudgetCycleTimeSpanEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultNumberOfAccountingPeriods attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BackingTable_BudgetCycleTimeSpanRelationshipId name="BackingTable_BudgetCycleTimeSpanRelationshipId">BackingTable_BudgetCycleTimeSpanRelationshipId</a>

First included in: Budgeting/BudgetCycleTimeSpanEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_BudgetCycleTimeSpanRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/Finance/Budget/Group/BudgetCycleTimeSpan.md" target="_blank">/core/operationsCommon/Tables/Finance/Budget/Group/BudgetCycleTimeSpan.cdm.json/BudgetCycleTimeSpan</a></td><td><a href="../../../Tables/Finance/Budget/Group/BudgetCycleTimeSpan.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>
