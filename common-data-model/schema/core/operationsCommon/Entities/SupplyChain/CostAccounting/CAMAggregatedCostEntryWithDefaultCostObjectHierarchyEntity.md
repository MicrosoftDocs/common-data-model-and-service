---
title: CAMAggregatedCostEntryWithDefaultCostObjectHierarchyEntity in CostAccounting - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 7/20/2020
ms.author: nebanfic
---

# Aggregated cost entries with cost element dimension hierarchies and default cost object dimension hierarchies in CostAccounting(CAMAggregatedCostEntryWithDefaultCostObjectHierarchyEntity)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/SupplyChain/CostAccounting/CAMAggregatedCostEntryWithDefaultCostObjectHierarchyEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Aggregated cost entries with cost element dimension hierarchies and default cost object dimension hierarchies</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[CostAccountingCurrencyAmount](#CostAccountingCurrencyAmount)||<a href="CAMAggregatedCostEntryWithDefaultCostObjectHierarchyEntity.md" target="_blank">CostAccounting/CAMAggregatedCostEntryWithDefaultCostObjectHierarchyEntity</a>|
|[CostAccountingDate](#CostAccountingDate)||<a href="CAMAggregatedCostEntryWithDefaultCostObjectHierarchyEntity.md" target="_blank">CostAccounting/CAMAggregatedCostEntryWithDefaultCostObjectHierarchyEntity</a>|
|[CostAccountingLedgerName](#CostAccountingLedgerName)||<a href="CAMAggregatedCostEntryWithDefaultCostObjectHierarchyEntity.md" target="_blank">CostAccounting/CAMAggregatedCostEntryWithDefaultCostObjectHierarchyEntity</a>|
|[CostControlUnitName](#CostControlUnitName)||<a href="CAMAggregatedCostEntryWithDefaultCostObjectHierarchyEntity.md" target="_blank">CostAccounting/CAMAggregatedCostEntryWithDefaultCostObjectHierarchyEntity</a>|
|[CostBehavior](#CostBehavior)||<a href="CAMAggregatedCostEntryWithDefaultCostObjectHierarchyEntity.md" target="_blank">CostAccounting/CAMAggregatedCostEntryWithDefaultCostObjectHierarchyEntity</a>|
|[CostElementDimensionHierarchyLevel1](#CostElementDimensionHierarchyLevel1)||<a href="CAMAggregatedCostEntryWithDefaultCostObjectHierarchyEntity.md" target="_blank">CostAccounting/CAMAggregatedCostEntryWithDefaultCostObjectHierarchyEntity</a>|
|[CostElementDimensionHierarchyLevel10](#CostElementDimensionHierarchyLevel10)||<a href="CAMAggregatedCostEntryWithDefaultCostObjectHierarchyEntity.md" target="_blank">CostAccounting/CAMAggregatedCostEntryWithDefaultCostObjectHierarchyEntity</a>|
|[CostElementDimensionHierarchyLevel11](#CostElementDimensionHierarchyLevel11)||<a href="CAMAggregatedCostEntryWithDefaultCostObjectHierarchyEntity.md" target="_blank">CostAccounting/CAMAggregatedCostEntryWithDefaultCostObjectHierarchyEntity</a>|
|[CostElementDimensionHierarchyLevel12](#CostElementDimensionHierarchyLevel12)||<a href="CAMAggregatedCostEntryWithDefaultCostObjectHierarchyEntity.md" target="_blank">CostAccounting/CAMAggregatedCostEntryWithDefaultCostObjectHierarchyEntity</a>|
|[CostElementDimensionHierarchyLevel13](#CostElementDimensionHierarchyLevel13)||<a href="CAMAggregatedCostEntryWithDefaultCostObjectHierarchyEntity.md" target="_blank">CostAccounting/CAMAggregatedCostEntryWithDefaultCostObjectHierarchyEntity</a>|
|[CostElementDimensionHierarchyLevel14](#CostElementDimensionHierarchyLevel14)||<a href="CAMAggregatedCostEntryWithDefaultCostObjectHierarchyEntity.md" target="_blank">CostAccounting/CAMAggregatedCostEntryWithDefaultCostObjectHierarchyEntity</a>|
|[CostElementDimensionHierarchyLevel15](#CostElementDimensionHierarchyLevel15)||<a href="CAMAggregatedCostEntryWithDefaultCostObjectHierarchyEntity.md" target="_blank">CostAccounting/CAMAggregatedCostEntryWithDefaultCostObjectHierarchyEntity</a>|
|[CostElementDimensionHierarchyLevel2](#CostElementDimensionHierarchyLevel2)||<a href="CAMAggregatedCostEntryWithDefaultCostObjectHierarchyEntity.md" target="_blank">CostAccounting/CAMAggregatedCostEntryWithDefaultCostObjectHierarchyEntity</a>|
|[CostElementDimensionHierarchyLevel3](#CostElementDimensionHierarchyLevel3)||<a href="CAMAggregatedCostEntryWithDefaultCostObjectHierarchyEntity.md" target="_blank">CostAccounting/CAMAggregatedCostEntryWithDefaultCostObjectHierarchyEntity</a>|
|[CostElementDimensionHierarchyLevel4](#CostElementDimensionHierarchyLevel4)||<a href="CAMAggregatedCostEntryWithDefaultCostObjectHierarchyEntity.md" target="_blank">CostAccounting/CAMAggregatedCostEntryWithDefaultCostObjectHierarchyEntity</a>|
|[CostElementDimensionHierarchyLevel5](#CostElementDimensionHierarchyLevel5)||<a href="CAMAggregatedCostEntryWithDefaultCostObjectHierarchyEntity.md" target="_blank">CostAccounting/CAMAggregatedCostEntryWithDefaultCostObjectHierarchyEntity</a>|
|[CostElementDimensionHierarchyLevel6](#CostElementDimensionHierarchyLevel6)||<a href="CAMAggregatedCostEntryWithDefaultCostObjectHierarchyEntity.md" target="_blank">CostAccounting/CAMAggregatedCostEntryWithDefaultCostObjectHierarchyEntity</a>|
|[CostElementDimensionHierarchyLevel7](#CostElementDimensionHierarchyLevel7)||<a href="CAMAggregatedCostEntryWithDefaultCostObjectHierarchyEntity.md" target="_blank">CostAccounting/CAMAggregatedCostEntryWithDefaultCostObjectHierarchyEntity</a>|
|[CostElementDimensionHierarchyLevel8](#CostElementDimensionHierarchyLevel8)||<a href="CAMAggregatedCostEntryWithDefaultCostObjectHierarchyEntity.md" target="_blank">CostAccounting/CAMAggregatedCostEntryWithDefaultCostObjectHierarchyEntity</a>|
|[CostElementDimensionHierarchyLevel9](#CostElementDimensionHierarchyLevel9)||<a href="CAMAggregatedCostEntryWithDefaultCostObjectHierarchyEntity.md" target="_blank">CostAccounting/CAMAggregatedCostEntryWithDefaultCostObjectHierarchyEntity</a>|
|[CostElementDimensionMemberName](#CostElementDimensionMemberName)||<a href="CAMAggregatedCostEntryWithDefaultCostObjectHierarchyEntity.md" target="_blank">CostAccounting/CAMAggregatedCostEntryWithDefaultCostObjectHierarchyEntity</a>|
|[CostElementDimensionMemberDescription](#CostElementDimensionMemberDescription)||<a href="CAMAggregatedCostEntryWithDefaultCostObjectHierarchyEntity.md" target="_blank">CostAccounting/CAMAggregatedCostEntryWithDefaultCostObjectHierarchyEntity</a>|
|[CostObjectDimensionHierarchyLevel1](#CostObjectDimensionHierarchyLevel1)||<a href="CAMAggregatedCostEntryWithDefaultCostObjectHierarchyEntity.md" target="_blank">CostAccounting/CAMAggregatedCostEntryWithDefaultCostObjectHierarchyEntity</a>|
|[CostObjectDimensionHierarchyLevel10](#CostObjectDimensionHierarchyLevel10)||<a href="CAMAggregatedCostEntryWithDefaultCostObjectHierarchyEntity.md" target="_blank">CostAccounting/CAMAggregatedCostEntryWithDefaultCostObjectHierarchyEntity</a>|
|[CostObjectDimensionHierarchyLevel11](#CostObjectDimensionHierarchyLevel11)||<a href="CAMAggregatedCostEntryWithDefaultCostObjectHierarchyEntity.md" target="_blank">CostAccounting/CAMAggregatedCostEntryWithDefaultCostObjectHierarchyEntity</a>|
|[CostObjectDimensionHierarchyLevel12](#CostObjectDimensionHierarchyLevel12)||<a href="CAMAggregatedCostEntryWithDefaultCostObjectHierarchyEntity.md" target="_blank">CostAccounting/CAMAggregatedCostEntryWithDefaultCostObjectHierarchyEntity</a>|
|[CostObjectDimensionHierarchyLevel13](#CostObjectDimensionHierarchyLevel13)||<a href="CAMAggregatedCostEntryWithDefaultCostObjectHierarchyEntity.md" target="_blank">CostAccounting/CAMAggregatedCostEntryWithDefaultCostObjectHierarchyEntity</a>|
|[CostObjectDimensionHierarchyLevel14](#CostObjectDimensionHierarchyLevel14)||<a href="CAMAggregatedCostEntryWithDefaultCostObjectHierarchyEntity.md" target="_blank">CostAccounting/CAMAggregatedCostEntryWithDefaultCostObjectHierarchyEntity</a>|
|[CostObjectDimensionHierarchyLevel15](#CostObjectDimensionHierarchyLevel15)||<a href="CAMAggregatedCostEntryWithDefaultCostObjectHierarchyEntity.md" target="_blank">CostAccounting/CAMAggregatedCostEntryWithDefaultCostObjectHierarchyEntity</a>|
|[CostObjectDimensionHierarchyLevel2](#CostObjectDimensionHierarchyLevel2)||<a href="CAMAggregatedCostEntryWithDefaultCostObjectHierarchyEntity.md" target="_blank">CostAccounting/CAMAggregatedCostEntryWithDefaultCostObjectHierarchyEntity</a>|
|[CostObjectDimensionHierarchyLevel3](#CostObjectDimensionHierarchyLevel3)||<a href="CAMAggregatedCostEntryWithDefaultCostObjectHierarchyEntity.md" target="_blank">CostAccounting/CAMAggregatedCostEntryWithDefaultCostObjectHierarchyEntity</a>|
|[CostObjectDimensionHierarchyLevel4](#CostObjectDimensionHierarchyLevel4)||<a href="CAMAggregatedCostEntryWithDefaultCostObjectHierarchyEntity.md" target="_blank">CostAccounting/CAMAggregatedCostEntryWithDefaultCostObjectHierarchyEntity</a>|
|[CostObjectDimensionHierarchyLevel5](#CostObjectDimensionHierarchyLevel5)||<a href="CAMAggregatedCostEntryWithDefaultCostObjectHierarchyEntity.md" target="_blank">CostAccounting/CAMAggregatedCostEntryWithDefaultCostObjectHierarchyEntity</a>|
|[CostObjectDimensionHierarchyLevel6](#CostObjectDimensionHierarchyLevel6)||<a href="CAMAggregatedCostEntryWithDefaultCostObjectHierarchyEntity.md" target="_blank">CostAccounting/CAMAggregatedCostEntryWithDefaultCostObjectHierarchyEntity</a>|
|[CostObjectDimensionHierarchyLevel7](#CostObjectDimensionHierarchyLevel7)||<a href="CAMAggregatedCostEntryWithDefaultCostObjectHierarchyEntity.md" target="_blank">CostAccounting/CAMAggregatedCostEntryWithDefaultCostObjectHierarchyEntity</a>|
|[CostObjectDimensionHierarchyLevel8](#CostObjectDimensionHierarchyLevel8)||<a href="CAMAggregatedCostEntryWithDefaultCostObjectHierarchyEntity.md" target="_blank">CostAccounting/CAMAggregatedCostEntryWithDefaultCostObjectHierarchyEntity</a>|
|[CostObjectDimensionHierarchyLevel9](#CostObjectDimensionHierarchyLevel9)||<a href="CAMAggregatedCostEntryWithDefaultCostObjectHierarchyEntity.md" target="_blank">CostAccounting/CAMAggregatedCostEntryWithDefaultCostObjectHierarchyEntity</a>|
|[CostObjectDimensionMemberName](#CostObjectDimensionMemberName)||<a href="CAMAggregatedCostEntryWithDefaultCostObjectHierarchyEntity.md" target="_blank">CostAccounting/CAMAggregatedCostEntryWithDefaultCostObjectHierarchyEntity</a>|
|[CostObjectDimensionMemberDescription](#CostObjectDimensionMemberDescription)||<a href="CAMAggregatedCostEntryWithDefaultCostObjectHierarchyEntity.md" target="_blank">CostAccounting/CAMAggregatedCostEntryWithDefaultCostObjectHierarchyEntity</a>|
|[CalendarId](#CalendarId)||<a href="CAMAggregatedCostEntryWithDefaultCostObjectHierarchyEntity.md" target="_blank">CostAccounting/CAMAggregatedCostEntryWithDefaultCostObjectHierarchyEntity</a>|
|[Month](#Month)||<a href="CAMAggregatedCostEntryWithDefaultCostObjectHierarchyEntity.md" target="_blank">CostAccounting/CAMAggregatedCostEntryWithDefaultCostObjectHierarchyEntity</a>|
|[PeriodName](#PeriodName)||<a href="CAMAggregatedCostEntryWithDefaultCostObjectHierarchyEntity.md" target="_blank">CostAccounting/CAMAggregatedCostEntryWithDefaultCostObjectHierarchyEntity</a>|
|[PeriodOffset](#PeriodOffset)||<a href="CAMAggregatedCostEntryWithDefaultCostObjectHierarchyEntity.md" target="_blank">CostAccounting/CAMAggregatedCostEntryWithDefaultCostObjectHierarchyEntity</a>|
|[Quarter](#Quarter)||<a href="CAMAggregatedCostEntryWithDefaultCostObjectHierarchyEntity.md" target="_blank">CostAccounting/CAMAggregatedCostEntryWithDefaultCostObjectHierarchyEntity</a>|
|[QuarterOffset](#QuarterOffset)||<a href="CAMAggregatedCostEntryWithDefaultCostObjectHierarchyEntity.md" target="_blank">CostAccounting/CAMAggregatedCostEntryWithDefaultCostObjectHierarchyEntity</a>|
|[YearOffset](#YearOffset)||<a href="CAMAggregatedCostEntryWithDefaultCostObjectHierarchyEntity.md" target="_blank">CostAccounting/CAMAggregatedCostEntryWithDefaultCostObjectHierarchyEntity</a>|
|[YearName](#YearName)||<a href="CAMAggregatedCostEntryWithDefaultCostObjectHierarchyEntity.md" target="_blank">CostAccounting/CAMAggregatedCostEntryWithDefaultCostObjectHierarchyEntity</a>|
|[CostElementDimensionHierarchyName](#CostElementDimensionHierarchyName)||<a href="CAMAggregatedCostEntryWithDefaultCostObjectHierarchyEntity.md" target="_blank">CostAccounting/CAMAggregatedCostEntryWithDefaultCostObjectHierarchyEntity</a>|
|[VersionIdentificationName](#VersionIdentificationName)||<a href="CAMAggregatedCostEntryWithDefaultCostObjectHierarchyEntity.md" target="_blank">CostAccounting/CAMAggregatedCostEntryWithDefaultCostObjectHierarchyEntity</a>|
|[SourceVersionIdentificationName](#SourceVersionIdentificationName)||<a href="CAMAggregatedCostEntryWithDefaultCostObjectHierarchyEntity.md" target="_blank">CostAccounting/CAMAggregatedCostEntryWithDefaultCostObjectHierarchyEntity</a>|
|[VersionType](#VersionType)||<a href="CAMAggregatedCostEntryWithDefaultCostObjectHierarchyEntity.md" target="_blank">CostAccounting/CAMAggregatedCostEntryWithDefaultCostObjectHierarchyEntity</a>|

### <a href=#CostAccountingCurrencyAmount name="CostAccountingCurrencyAmount">CostAccountingCurrencyAmount</a>

First included in: CostAccounting/CAMAggregatedCostEntryWithDefaultCostObjectHierarchyEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CostAccountingCurrencyAmount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CostAccountingDate name="CostAccountingDate">CostAccountingDate</a>

First included in: CostAccounting/CAMAggregatedCostEntryWithDefaultCostObjectHierarchyEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CostAccountingDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CostAccountingLedgerName name="CostAccountingLedgerName">CostAccountingLedgerName</a>

First included in: CostAccounting/CAMAggregatedCostEntryWithDefaultCostObjectHierarchyEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CostAccountingLedgerName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CostControlUnitName name="CostControlUnitName">CostControlUnitName</a>

First included in: CostAccounting/CAMAggregatedCostEntryWithDefaultCostObjectHierarchyEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CostControlUnitName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CostBehavior name="CostBehavior">CostBehavior</a>

First included in: CostAccounting/CAMAggregatedCostEntryWithDefaultCostObjectHierarchyEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CostBehavior attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CostElementDimensionHierarchyLevel1 name="CostElementDimensionHierarchyLevel1">CostElementDimensionHierarchyLevel1</a>

First included in: CostAccounting/CAMAggregatedCostEntryWithDefaultCostObjectHierarchyEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CostElementDimensionHierarchyLevel1 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CostElementDimensionHierarchyLevel10 name="CostElementDimensionHierarchyLevel10">CostElementDimensionHierarchyLevel10</a>

First included in: CostAccounting/CAMAggregatedCostEntryWithDefaultCostObjectHierarchyEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CostElementDimensionHierarchyLevel10 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CostElementDimensionHierarchyLevel11 name="CostElementDimensionHierarchyLevel11">CostElementDimensionHierarchyLevel11</a>

First included in: CostAccounting/CAMAggregatedCostEntryWithDefaultCostObjectHierarchyEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CostElementDimensionHierarchyLevel11 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CostElementDimensionHierarchyLevel12 name="CostElementDimensionHierarchyLevel12">CostElementDimensionHierarchyLevel12</a>

First included in: CostAccounting/CAMAggregatedCostEntryWithDefaultCostObjectHierarchyEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CostElementDimensionHierarchyLevel12 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CostElementDimensionHierarchyLevel13 name="CostElementDimensionHierarchyLevel13">CostElementDimensionHierarchyLevel13</a>

First included in: CostAccounting/CAMAggregatedCostEntryWithDefaultCostObjectHierarchyEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CostElementDimensionHierarchyLevel13 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CostElementDimensionHierarchyLevel14 name="CostElementDimensionHierarchyLevel14">CostElementDimensionHierarchyLevel14</a>

First included in: CostAccounting/CAMAggregatedCostEntryWithDefaultCostObjectHierarchyEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CostElementDimensionHierarchyLevel14 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CostElementDimensionHierarchyLevel15 name="CostElementDimensionHierarchyLevel15">CostElementDimensionHierarchyLevel15</a>

First included in: CostAccounting/CAMAggregatedCostEntryWithDefaultCostObjectHierarchyEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CostElementDimensionHierarchyLevel15 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CostElementDimensionHierarchyLevel2 name="CostElementDimensionHierarchyLevel2">CostElementDimensionHierarchyLevel2</a>

First included in: CostAccounting/CAMAggregatedCostEntryWithDefaultCostObjectHierarchyEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CostElementDimensionHierarchyLevel2 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CostElementDimensionHierarchyLevel3 name="CostElementDimensionHierarchyLevel3">CostElementDimensionHierarchyLevel3</a>

First included in: CostAccounting/CAMAggregatedCostEntryWithDefaultCostObjectHierarchyEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CostElementDimensionHierarchyLevel3 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CostElementDimensionHierarchyLevel4 name="CostElementDimensionHierarchyLevel4">CostElementDimensionHierarchyLevel4</a>

First included in: CostAccounting/CAMAggregatedCostEntryWithDefaultCostObjectHierarchyEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CostElementDimensionHierarchyLevel4 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CostElementDimensionHierarchyLevel5 name="CostElementDimensionHierarchyLevel5">CostElementDimensionHierarchyLevel5</a>

First included in: CostAccounting/CAMAggregatedCostEntryWithDefaultCostObjectHierarchyEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CostElementDimensionHierarchyLevel5 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CostElementDimensionHierarchyLevel6 name="CostElementDimensionHierarchyLevel6">CostElementDimensionHierarchyLevel6</a>

First included in: CostAccounting/CAMAggregatedCostEntryWithDefaultCostObjectHierarchyEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CostElementDimensionHierarchyLevel6 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CostElementDimensionHierarchyLevel7 name="CostElementDimensionHierarchyLevel7">CostElementDimensionHierarchyLevel7</a>

First included in: CostAccounting/CAMAggregatedCostEntryWithDefaultCostObjectHierarchyEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CostElementDimensionHierarchyLevel7 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CostElementDimensionHierarchyLevel8 name="CostElementDimensionHierarchyLevel8">CostElementDimensionHierarchyLevel8</a>

First included in: CostAccounting/CAMAggregatedCostEntryWithDefaultCostObjectHierarchyEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CostElementDimensionHierarchyLevel8 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CostElementDimensionHierarchyLevel9 name="CostElementDimensionHierarchyLevel9">CostElementDimensionHierarchyLevel9</a>

First included in: CostAccounting/CAMAggregatedCostEntryWithDefaultCostObjectHierarchyEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CostElementDimensionHierarchyLevel9 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CostElementDimensionMemberName name="CostElementDimensionMemberName">CostElementDimensionMemberName</a>

First included in: CostAccounting/CAMAggregatedCostEntryWithDefaultCostObjectHierarchyEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CostElementDimensionMemberName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CostElementDimensionMemberDescription name="CostElementDimensionMemberDescription">CostElementDimensionMemberDescription</a>

First included in: CostAccounting/CAMAggregatedCostEntryWithDefaultCostObjectHierarchyEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CostElementDimensionMemberDescription attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CostObjectDimensionHierarchyLevel1 name="CostObjectDimensionHierarchyLevel1">CostObjectDimensionHierarchyLevel1</a>

First included in: CostAccounting/CAMAggregatedCostEntryWithDefaultCostObjectHierarchyEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CostObjectDimensionHierarchyLevel1 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CostObjectDimensionHierarchyLevel10 name="CostObjectDimensionHierarchyLevel10">CostObjectDimensionHierarchyLevel10</a>

First included in: CostAccounting/CAMAggregatedCostEntryWithDefaultCostObjectHierarchyEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CostObjectDimensionHierarchyLevel10 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CostObjectDimensionHierarchyLevel11 name="CostObjectDimensionHierarchyLevel11">CostObjectDimensionHierarchyLevel11</a>

First included in: CostAccounting/CAMAggregatedCostEntryWithDefaultCostObjectHierarchyEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CostObjectDimensionHierarchyLevel11 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CostObjectDimensionHierarchyLevel12 name="CostObjectDimensionHierarchyLevel12">CostObjectDimensionHierarchyLevel12</a>

First included in: CostAccounting/CAMAggregatedCostEntryWithDefaultCostObjectHierarchyEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CostObjectDimensionHierarchyLevel12 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CostObjectDimensionHierarchyLevel13 name="CostObjectDimensionHierarchyLevel13">CostObjectDimensionHierarchyLevel13</a>

First included in: CostAccounting/CAMAggregatedCostEntryWithDefaultCostObjectHierarchyEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CostObjectDimensionHierarchyLevel13 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CostObjectDimensionHierarchyLevel14 name="CostObjectDimensionHierarchyLevel14">CostObjectDimensionHierarchyLevel14</a>

First included in: CostAccounting/CAMAggregatedCostEntryWithDefaultCostObjectHierarchyEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CostObjectDimensionHierarchyLevel14 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CostObjectDimensionHierarchyLevel15 name="CostObjectDimensionHierarchyLevel15">CostObjectDimensionHierarchyLevel15</a>

First included in: CostAccounting/CAMAggregatedCostEntryWithDefaultCostObjectHierarchyEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CostObjectDimensionHierarchyLevel15 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CostObjectDimensionHierarchyLevel2 name="CostObjectDimensionHierarchyLevel2">CostObjectDimensionHierarchyLevel2</a>

First included in: CostAccounting/CAMAggregatedCostEntryWithDefaultCostObjectHierarchyEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CostObjectDimensionHierarchyLevel2 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CostObjectDimensionHierarchyLevel3 name="CostObjectDimensionHierarchyLevel3">CostObjectDimensionHierarchyLevel3</a>

First included in: CostAccounting/CAMAggregatedCostEntryWithDefaultCostObjectHierarchyEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CostObjectDimensionHierarchyLevel3 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CostObjectDimensionHierarchyLevel4 name="CostObjectDimensionHierarchyLevel4">CostObjectDimensionHierarchyLevel4</a>

First included in: CostAccounting/CAMAggregatedCostEntryWithDefaultCostObjectHierarchyEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CostObjectDimensionHierarchyLevel4 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CostObjectDimensionHierarchyLevel5 name="CostObjectDimensionHierarchyLevel5">CostObjectDimensionHierarchyLevel5</a>

First included in: CostAccounting/CAMAggregatedCostEntryWithDefaultCostObjectHierarchyEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CostObjectDimensionHierarchyLevel5 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CostObjectDimensionHierarchyLevel6 name="CostObjectDimensionHierarchyLevel6">CostObjectDimensionHierarchyLevel6</a>

First included in: CostAccounting/CAMAggregatedCostEntryWithDefaultCostObjectHierarchyEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CostObjectDimensionHierarchyLevel6 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CostObjectDimensionHierarchyLevel7 name="CostObjectDimensionHierarchyLevel7">CostObjectDimensionHierarchyLevel7</a>

First included in: CostAccounting/CAMAggregatedCostEntryWithDefaultCostObjectHierarchyEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CostObjectDimensionHierarchyLevel7 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CostObjectDimensionHierarchyLevel8 name="CostObjectDimensionHierarchyLevel8">CostObjectDimensionHierarchyLevel8</a>

First included in: CostAccounting/CAMAggregatedCostEntryWithDefaultCostObjectHierarchyEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CostObjectDimensionHierarchyLevel8 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CostObjectDimensionHierarchyLevel9 name="CostObjectDimensionHierarchyLevel9">CostObjectDimensionHierarchyLevel9</a>

First included in: CostAccounting/CAMAggregatedCostEntryWithDefaultCostObjectHierarchyEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CostObjectDimensionHierarchyLevel9 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CostObjectDimensionMemberName name="CostObjectDimensionMemberName">CostObjectDimensionMemberName</a>

First included in: CostAccounting/CAMAggregatedCostEntryWithDefaultCostObjectHierarchyEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CostObjectDimensionMemberName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CostObjectDimensionMemberDescription name="CostObjectDimensionMemberDescription">CostObjectDimensionMemberDescription</a>

First included in: CostAccounting/CAMAggregatedCostEntryWithDefaultCostObjectHierarchyEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CostObjectDimensionMemberDescription attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CalendarId name="CalendarId">CalendarId</a>

First included in: CostAccounting/CAMAggregatedCostEntryWithDefaultCostObjectHierarchyEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CalendarId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Month name="Month">Month</a>

First included in: CostAccounting/CAMAggregatedCostEntryWithDefaultCostObjectHierarchyEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Month attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PeriodName name="PeriodName">PeriodName</a>

First included in: CostAccounting/CAMAggregatedCostEntryWithDefaultCostObjectHierarchyEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PeriodName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PeriodOffset name="PeriodOffset">PeriodOffset</a>

First included in: CostAccounting/CAMAggregatedCostEntryWithDefaultCostObjectHierarchyEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PeriodOffset attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Quarter name="Quarter">Quarter</a>

First included in: CostAccounting/CAMAggregatedCostEntryWithDefaultCostObjectHierarchyEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Quarter attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#QuarterOffset name="QuarterOffset">QuarterOffset</a>

First included in: CostAccounting/CAMAggregatedCostEntryWithDefaultCostObjectHierarchyEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the QuarterOffset attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#YearOffset name="YearOffset">YearOffset</a>

First included in: CostAccounting/CAMAggregatedCostEntryWithDefaultCostObjectHierarchyEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the YearOffset attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#YearName name="YearName">YearName</a>

First included in: CostAccounting/CAMAggregatedCostEntryWithDefaultCostObjectHierarchyEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the YearName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CostElementDimensionHierarchyName name="CostElementDimensionHierarchyName">CostElementDimensionHierarchyName</a>

First included in: CostAccounting/CAMAggregatedCostEntryWithDefaultCostObjectHierarchyEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CostElementDimensionHierarchyName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#VersionIdentificationName name="VersionIdentificationName">VersionIdentificationName</a>

First included in: CostAccounting/CAMAggregatedCostEntryWithDefaultCostObjectHierarchyEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Version</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VersionIdentificationName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Version</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SourceVersionIdentificationName name="SourceVersionIdentificationName">SourceVersionIdentificationName</a>

First included in: CostAccounting/CAMAggregatedCostEntryWithDefaultCostObjectHierarchyEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Source version</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SourceVersionIdentificationName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Source version</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#VersionType name="VersionType">VersionType</a>

First included in: CostAccounting/CAMAggregatedCostEntryWithDefaultCostObjectHierarchyEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Version type</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VersionType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Version type</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>
