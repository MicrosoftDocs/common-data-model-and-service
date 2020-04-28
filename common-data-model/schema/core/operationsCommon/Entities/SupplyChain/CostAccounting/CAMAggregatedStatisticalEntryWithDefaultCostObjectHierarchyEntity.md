---
title: CAMAggregatedStatisticalEntryWithDefaultCostObjectHierarchyEntity - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/28/2020
ms.author: nebanfic
---

# Aggregated statistical entries with statistical dimension hierarchies and default cost object dimension hierarchies

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/SupplyChain/CostAccounting/CAMAggregatedStatisticalEntryWithDefaultCostObjectHierarchyEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Aggregated statistical entries with statistical dimension hierarchies and default cost object dimension hierarchies</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[Magnitude](#Magnitude)||<a href="CAMAggregatedStatisticalEntryWithDefaultCostObjectHierarchyEntity.md" target="_blank">CostAccounting/CAMAggregatedStatisticalEntryWithDefaultCostObjectHierarchyEntity</a>|
|[CostObjectDimensionHierarchyLevel1](#CostObjectDimensionHierarchyLevel1)||<a href="CAMAggregatedStatisticalEntryWithDefaultCostObjectHierarchyEntity.md" target="_blank">CostAccounting/CAMAggregatedStatisticalEntryWithDefaultCostObjectHierarchyEntity</a>|
|[CostObjectDimensionHierarchyLevel2](#CostObjectDimensionHierarchyLevel2)||<a href="CAMAggregatedStatisticalEntryWithDefaultCostObjectHierarchyEntity.md" target="_blank">CostAccounting/CAMAggregatedStatisticalEntryWithDefaultCostObjectHierarchyEntity</a>|
|[CostObjectDimensionHierarchyLevel3](#CostObjectDimensionHierarchyLevel3)||<a href="CAMAggregatedStatisticalEntryWithDefaultCostObjectHierarchyEntity.md" target="_blank">CostAccounting/CAMAggregatedStatisticalEntryWithDefaultCostObjectHierarchyEntity</a>|
|[CostObjectDimensionHierarchyLevel4](#CostObjectDimensionHierarchyLevel4)||<a href="CAMAggregatedStatisticalEntryWithDefaultCostObjectHierarchyEntity.md" target="_blank">CostAccounting/CAMAggregatedStatisticalEntryWithDefaultCostObjectHierarchyEntity</a>|
|[CostObjectDimensionHierarchyLevel5](#CostObjectDimensionHierarchyLevel5)||<a href="CAMAggregatedStatisticalEntryWithDefaultCostObjectHierarchyEntity.md" target="_blank">CostAccounting/CAMAggregatedStatisticalEntryWithDefaultCostObjectHierarchyEntity</a>|
|[CostObjectDimensionHierarchyLevel6](#CostObjectDimensionHierarchyLevel6)||<a href="CAMAggregatedStatisticalEntryWithDefaultCostObjectHierarchyEntity.md" target="_blank">CostAccounting/CAMAggregatedStatisticalEntryWithDefaultCostObjectHierarchyEntity</a>|
|[CostObjectDimensionHierarchyLevel7](#CostObjectDimensionHierarchyLevel7)||<a href="CAMAggregatedStatisticalEntryWithDefaultCostObjectHierarchyEntity.md" target="_blank">CostAccounting/CAMAggregatedStatisticalEntryWithDefaultCostObjectHierarchyEntity</a>|
|[CostObjectDimensionHierarchyLevel8](#CostObjectDimensionHierarchyLevel8)||<a href="CAMAggregatedStatisticalEntryWithDefaultCostObjectHierarchyEntity.md" target="_blank">CostAccounting/CAMAggregatedStatisticalEntryWithDefaultCostObjectHierarchyEntity</a>|
|[CostObjectDimensionHierarchyLevel9](#CostObjectDimensionHierarchyLevel9)||<a href="CAMAggregatedStatisticalEntryWithDefaultCostObjectHierarchyEntity.md" target="_blank">CostAccounting/CAMAggregatedStatisticalEntryWithDefaultCostObjectHierarchyEntity</a>|
|[CostObjectDimensionHierarchyLevel10](#CostObjectDimensionHierarchyLevel10)||<a href="CAMAggregatedStatisticalEntryWithDefaultCostObjectHierarchyEntity.md" target="_blank">CostAccounting/CAMAggregatedStatisticalEntryWithDefaultCostObjectHierarchyEntity</a>|
|[CostObjectDimensionHierarchyLevel11](#CostObjectDimensionHierarchyLevel11)||<a href="CAMAggregatedStatisticalEntryWithDefaultCostObjectHierarchyEntity.md" target="_blank">CostAccounting/CAMAggregatedStatisticalEntryWithDefaultCostObjectHierarchyEntity</a>|
|[CostObjectDimensionHierarchyLevel12](#CostObjectDimensionHierarchyLevel12)||<a href="CAMAggregatedStatisticalEntryWithDefaultCostObjectHierarchyEntity.md" target="_blank">CostAccounting/CAMAggregatedStatisticalEntryWithDefaultCostObjectHierarchyEntity</a>|
|[CostObjectDimensionHierarchyLevel13](#CostObjectDimensionHierarchyLevel13)||<a href="CAMAggregatedStatisticalEntryWithDefaultCostObjectHierarchyEntity.md" target="_blank">CostAccounting/CAMAggregatedStatisticalEntryWithDefaultCostObjectHierarchyEntity</a>|
|[CostObjectDimensionHierarchyLevel14](#CostObjectDimensionHierarchyLevel14)||<a href="CAMAggregatedStatisticalEntryWithDefaultCostObjectHierarchyEntity.md" target="_blank">CostAccounting/CAMAggregatedStatisticalEntryWithDefaultCostObjectHierarchyEntity</a>|
|[CostObjectDimensionHierarchyLevel15](#CostObjectDimensionHierarchyLevel15)||<a href="CAMAggregatedStatisticalEntryWithDefaultCostObjectHierarchyEntity.md" target="_blank">CostAccounting/CAMAggregatedStatisticalEntryWithDefaultCostObjectHierarchyEntity</a>|
|[CostAccountingDate](#CostAccountingDate)||<a href="CAMAggregatedStatisticalEntryWithDefaultCostObjectHierarchyEntity.md" target="_blank">CostAccounting/CAMAggregatedStatisticalEntryWithDefaultCostObjectHierarchyEntity</a>|
|[CostAccountingLedgerName](#CostAccountingLedgerName)||<a href="CAMAggregatedStatisticalEntryWithDefaultCostObjectHierarchyEntity.md" target="_blank">CostAccounting/CAMAggregatedStatisticalEntryWithDefaultCostObjectHierarchyEntity</a>|
|[CostControlUnitName](#CostControlUnitName)||<a href="CAMAggregatedStatisticalEntryWithDefaultCostObjectHierarchyEntity.md" target="_blank">CostAccounting/CAMAggregatedStatisticalEntryWithDefaultCostObjectHierarchyEntity</a>|
|[StatisticalDimensionHierarchyLevel1](#StatisticalDimensionHierarchyLevel1)||<a href="CAMAggregatedStatisticalEntryWithDefaultCostObjectHierarchyEntity.md" target="_blank">CostAccounting/CAMAggregatedStatisticalEntryWithDefaultCostObjectHierarchyEntity</a>|
|[StatisticalDimensionHierarchyLevel2](#StatisticalDimensionHierarchyLevel2)||<a href="CAMAggregatedStatisticalEntryWithDefaultCostObjectHierarchyEntity.md" target="_blank">CostAccounting/CAMAggregatedStatisticalEntryWithDefaultCostObjectHierarchyEntity</a>|
|[StatisticalDimensionHierarchyLevel3](#StatisticalDimensionHierarchyLevel3)||<a href="CAMAggregatedStatisticalEntryWithDefaultCostObjectHierarchyEntity.md" target="_blank">CostAccounting/CAMAggregatedStatisticalEntryWithDefaultCostObjectHierarchyEntity</a>|
|[StatisticalDimensionHierarchyLevel4](#StatisticalDimensionHierarchyLevel4)||<a href="CAMAggregatedStatisticalEntryWithDefaultCostObjectHierarchyEntity.md" target="_blank">CostAccounting/CAMAggregatedStatisticalEntryWithDefaultCostObjectHierarchyEntity</a>|
|[StatisticalDimensionHierarchyLevel5](#StatisticalDimensionHierarchyLevel5)||<a href="CAMAggregatedStatisticalEntryWithDefaultCostObjectHierarchyEntity.md" target="_blank">CostAccounting/CAMAggregatedStatisticalEntryWithDefaultCostObjectHierarchyEntity</a>|
|[StatisticalDimensionHierarchyLevel6](#StatisticalDimensionHierarchyLevel6)||<a href="CAMAggregatedStatisticalEntryWithDefaultCostObjectHierarchyEntity.md" target="_blank">CostAccounting/CAMAggregatedStatisticalEntryWithDefaultCostObjectHierarchyEntity</a>|
|[StatisticalDimensionHierarchyLevel7](#StatisticalDimensionHierarchyLevel7)||<a href="CAMAggregatedStatisticalEntryWithDefaultCostObjectHierarchyEntity.md" target="_blank">CostAccounting/CAMAggregatedStatisticalEntryWithDefaultCostObjectHierarchyEntity</a>|
|[StatisticalDimensionHierarchyLevel8](#StatisticalDimensionHierarchyLevel8)||<a href="CAMAggregatedStatisticalEntryWithDefaultCostObjectHierarchyEntity.md" target="_blank">CostAccounting/CAMAggregatedStatisticalEntryWithDefaultCostObjectHierarchyEntity</a>|
|[StatisticalDimensionHierarchyLevel9](#StatisticalDimensionHierarchyLevel9)||<a href="CAMAggregatedStatisticalEntryWithDefaultCostObjectHierarchyEntity.md" target="_blank">CostAccounting/CAMAggregatedStatisticalEntryWithDefaultCostObjectHierarchyEntity</a>|
|[StatisticalDimensionHierarchyLevel10](#StatisticalDimensionHierarchyLevel10)||<a href="CAMAggregatedStatisticalEntryWithDefaultCostObjectHierarchyEntity.md" target="_blank">CostAccounting/CAMAggregatedStatisticalEntryWithDefaultCostObjectHierarchyEntity</a>|
|[StatisticalDimensionHierarchyLevel11](#StatisticalDimensionHierarchyLevel11)||<a href="CAMAggregatedStatisticalEntryWithDefaultCostObjectHierarchyEntity.md" target="_blank">CostAccounting/CAMAggregatedStatisticalEntryWithDefaultCostObjectHierarchyEntity</a>|
|[StatisticalDimensionHierarchyLevel12](#StatisticalDimensionHierarchyLevel12)||<a href="CAMAggregatedStatisticalEntryWithDefaultCostObjectHierarchyEntity.md" target="_blank">CostAccounting/CAMAggregatedStatisticalEntryWithDefaultCostObjectHierarchyEntity</a>|
|[StatisticalDimensionHierarchyLevel13](#StatisticalDimensionHierarchyLevel13)||<a href="CAMAggregatedStatisticalEntryWithDefaultCostObjectHierarchyEntity.md" target="_blank">CostAccounting/CAMAggregatedStatisticalEntryWithDefaultCostObjectHierarchyEntity</a>|
|[StatisticalDimensionHierarchyLevel14](#StatisticalDimensionHierarchyLevel14)||<a href="CAMAggregatedStatisticalEntryWithDefaultCostObjectHierarchyEntity.md" target="_blank">CostAccounting/CAMAggregatedStatisticalEntryWithDefaultCostObjectHierarchyEntity</a>|
|[StatisticalDimensionHierarchyLevel15](#StatisticalDimensionHierarchyLevel15)||<a href="CAMAggregatedStatisticalEntryWithDefaultCostObjectHierarchyEntity.md" target="_blank">CostAccounting/CAMAggregatedStatisticalEntryWithDefaultCostObjectHierarchyEntity</a>|
|[VersionIdentificationName](#VersionIdentificationName)||<a href="CAMAggregatedStatisticalEntryWithDefaultCostObjectHierarchyEntity.md" target="_blank">CostAccounting/CAMAggregatedStatisticalEntryWithDefaultCostObjectHierarchyEntity</a>|
|[SourceVersionIdentificationName](#SourceVersionIdentificationName)||<a href="CAMAggregatedStatisticalEntryWithDefaultCostObjectHierarchyEntity.md" target="_blank">CostAccounting/CAMAggregatedStatisticalEntryWithDefaultCostObjectHierarchyEntity</a>|
|[VersionType](#VersionType)||<a href="CAMAggregatedStatisticalEntryWithDefaultCostObjectHierarchyEntity.md" target="_blank">CostAccounting/CAMAggregatedStatisticalEntryWithDefaultCostObjectHierarchyEntity</a>|
|[YearName](#YearName)||<a href="CAMAggregatedStatisticalEntryWithDefaultCostObjectHierarchyEntity.md" target="_blank">CostAccounting/CAMAggregatedStatisticalEntryWithDefaultCostObjectHierarchyEntity</a>|
|[CalendarId](#CalendarId)||<a href="CAMAggregatedStatisticalEntryWithDefaultCostObjectHierarchyEntity.md" target="_blank">CostAccounting/CAMAggregatedStatisticalEntryWithDefaultCostObjectHierarchyEntity</a>|
|[Month](#Month)||<a href="CAMAggregatedStatisticalEntryWithDefaultCostObjectHierarchyEntity.md" target="_blank">CostAccounting/CAMAggregatedStatisticalEntryWithDefaultCostObjectHierarchyEntity</a>|
|[PeriodName](#PeriodName)||<a href="CAMAggregatedStatisticalEntryWithDefaultCostObjectHierarchyEntity.md" target="_blank">CostAccounting/CAMAggregatedStatisticalEntryWithDefaultCostObjectHierarchyEntity</a>|
|[PeriodOffset](#PeriodOffset)||<a href="CAMAggregatedStatisticalEntryWithDefaultCostObjectHierarchyEntity.md" target="_blank">CostAccounting/CAMAggregatedStatisticalEntryWithDefaultCostObjectHierarchyEntity</a>|
|[Quarter](#Quarter)||<a href="CAMAggregatedStatisticalEntryWithDefaultCostObjectHierarchyEntity.md" target="_blank">CostAccounting/CAMAggregatedStatisticalEntryWithDefaultCostObjectHierarchyEntity</a>|
|[QuarterOffset](#QuarterOffset)||<a href="CAMAggregatedStatisticalEntryWithDefaultCostObjectHierarchyEntity.md" target="_blank">CostAccounting/CAMAggregatedStatisticalEntryWithDefaultCostObjectHierarchyEntity</a>|
|[YearOffset](#YearOffset)||<a href="CAMAggregatedStatisticalEntryWithDefaultCostObjectHierarchyEntity.md" target="_blank">CostAccounting/CAMAggregatedStatisticalEntryWithDefaultCostObjectHierarchyEntity</a>|
|[CostObjectDimensionMemberDescription](#CostObjectDimensionMemberDescription)||<a href="CAMAggregatedStatisticalEntryWithDefaultCostObjectHierarchyEntity.md" target="_blank">CostAccounting/CAMAggregatedStatisticalEntryWithDefaultCostObjectHierarchyEntity</a>|
|[CostObjectDimensionMemberName](#CostObjectDimensionMemberName)||<a href="CAMAggregatedStatisticalEntryWithDefaultCostObjectHierarchyEntity.md" target="_blank">CostAccounting/CAMAggregatedStatisticalEntryWithDefaultCostObjectHierarchyEntity</a>|
|[StatisticalDimensionMemberDescription](#StatisticalDimensionMemberDescription)||<a href="CAMAggregatedStatisticalEntryWithDefaultCostObjectHierarchyEntity.md" target="_blank">CostAccounting/CAMAggregatedStatisticalEntryWithDefaultCostObjectHierarchyEntity</a>|
|[StatisticalDimensionHierarchyName](#StatisticalDimensionHierarchyName)||<a href="CAMAggregatedStatisticalEntryWithDefaultCostObjectHierarchyEntity.md" target="_blank">CostAccounting/CAMAggregatedStatisticalEntryWithDefaultCostObjectHierarchyEntity</a>|
|[StatisticalDimensionMemberName](#StatisticalDimensionMemberName)||<a href="CAMAggregatedStatisticalEntryWithDefaultCostObjectHierarchyEntity.md" target="_blank">CostAccounting/CAMAggregatedStatisticalEntryWithDefaultCostObjectHierarchyEntity</a>|

### <a href=#Magnitude name="Magnitude">Magnitude</a>

First included in: CostAccounting/CAMAggregatedStatisticalEntryWithDefaultCostObjectHierarchyEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Magnitude attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CostObjectDimensionHierarchyLevel1 name="CostObjectDimensionHierarchyLevel1">CostObjectDimensionHierarchyLevel1</a>

First included in: CostAccounting/CAMAggregatedStatisticalEntryWithDefaultCostObjectHierarchyEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CostObjectDimensionHierarchyLevel1 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CostObjectDimensionHierarchyLevel2 name="CostObjectDimensionHierarchyLevel2">CostObjectDimensionHierarchyLevel2</a>

First included in: CostAccounting/CAMAggregatedStatisticalEntryWithDefaultCostObjectHierarchyEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CostObjectDimensionHierarchyLevel2 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CostObjectDimensionHierarchyLevel3 name="CostObjectDimensionHierarchyLevel3">CostObjectDimensionHierarchyLevel3</a>

First included in: CostAccounting/CAMAggregatedStatisticalEntryWithDefaultCostObjectHierarchyEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CostObjectDimensionHierarchyLevel3 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CostObjectDimensionHierarchyLevel4 name="CostObjectDimensionHierarchyLevel4">CostObjectDimensionHierarchyLevel4</a>

First included in: CostAccounting/CAMAggregatedStatisticalEntryWithDefaultCostObjectHierarchyEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CostObjectDimensionHierarchyLevel4 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CostObjectDimensionHierarchyLevel5 name="CostObjectDimensionHierarchyLevel5">CostObjectDimensionHierarchyLevel5</a>

First included in: CostAccounting/CAMAggregatedStatisticalEntryWithDefaultCostObjectHierarchyEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CostObjectDimensionHierarchyLevel5 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CostObjectDimensionHierarchyLevel6 name="CostObjectDimensionHierarchyLevel6">CostObjectDimensionHierarchyLevel6</a>

First included in: CostAccounting/CAMAggregatedStatisticalEntryWithDefaultCostObjectHierarchyEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CostObjectDimensionHierarchyLevel6 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CostObjectDimensionHierarchyLevel7 name="CostObjectDimensionHierarchyLevel7">CostObjectDimensionHierarchyLevel7</a>

First included in: CostAccounting/CAMAggregatedStatisticalEntryWithDefaultCostObjectHierarchyEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CostObjectDimensionHierarchyLevel7 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CostObjectDimensionHierarchyLevel8 name="CostObjectDimensionHierarchyLevel8">CostObjectDimensionHierarchyLevel8</a>

First included in: CostAccounting/CAMAggregatedStatisticalEntryWithDefaultCostObjectHierarchyEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CostObjectDimensionHierarchyLevel8 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CostObjectDimensionHierarchyLevel9 name="CostObjectDimensionHierarchyLevel9">CostObjectDimensionHierarchyLevel9</a>

First included in: CostAccounting/CAMAggregatedStatisticalEntryWithDefaultCostObjectHierarchyEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CostObjectDimensionHierarchyLevel9 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CostObjectDimensionHierarchyLevel10 name="CostObjectDimensionHierarchyLevel10">CostObjectDimensionHierarchyLevel10</a>

First included in: CostAccounting/CAMAggregatedStatisticalEntryWithDefaultCostObjectHierarchyEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CostObjectDimensionHierarchyLevel10 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CostObjectDimensionHierarchyLevel11 name="CostObjectDimensionHierarchyLevel11">CostObjectDimensionHierarchyLevel11</a>

First included in: CostAccounting/CAMAggregatedStatisticalEntryWithDefaultCostObjectHierarchyEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CostObjectDimensionHierarchyLevel11 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CostObjectDimensionHierarchyLevel12 name="CostObjectDimensionHierarchyLevel12">CostObjectDimensionHierarchyLevel12</a>

First included in: CostAccounting/CAMAggregatedStatisticalEntryWithDefaultCostObjectHierarchyEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CostObjectDimensionHierarchyLevel12 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CostObjectDimensionHierarchyLevel13 name="CostObjectDimensionHierarchyLevel13">CostObjectDimensionHierarchyLevel13</a>

First included in: CostAccounting/CAMAggregatedStatisticalEntryWithDefaultCostObjectHierarchyEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CostObjectDimensionHierarchyLevel13 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CostObjectDimensionHierarchyLevel14 name="CostObjectDimensionHierarchyLevel14">CostObjectDimensionHierarchyLevel14</a>

First included in: CostAccounting/CAMAggregatedStatisticalEntryWithDefaultCostObjectHierarchyEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CostObjectDimensionHierarchyLevel14 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CostObjectDimensionHierarchyLevel15 name="CostObjectDimensionHierarchyLevel15">CostObjectDimensionHierarchyLevel15</a>

First included in: CostAccounting/CAMAggregatedStatisticalEntryWithDefaultCostObjectHierarchyEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CostObjectDimensionHierarchyLevel15 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CostAccountingDate name="CostAccountingDate">CostAccountingDate</a>

First included in: CostAccounting/CAMAggregatedStatisticalEntryWithDefaultCostObjectHierarchyEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CostAccountingDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CostAccountingLedgerName name="CostAccountingLedgerName">CostAccountingLedgerName</a>

First included in: CostAccounting/CAMAggregatedStatisticalEntryWithDefaultCostObjectHierarchyEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CostAccountingLedgerName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CostControlUnitName name="CostControlUnitName">CostControlUnitName</a>

First included in: CostAccounting/CAMAggregatedStatisticalEntryWithDefaultCostObjectHierarchyEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CostControlUnitName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#StatisticalDimensionHierarchyLevel1 name="StatisticalDimensionHierarchyLevel1">StatisticalDimensionHierarchyLevel1</a>

First included in: CostAccounting/CAMAggregatedStatisticalEntryWithDefaultCostObjectHierarchyEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the StatisticalDimensionHierarchyLevel1 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#StatisticalDimensionHierarchyLevel2 name="StatisticalDimensionHierarchyLevel2">StatisticalDimensionHierarchyLevel2</a>

First included in: CostAccounting/CAMAggregatedStatisticalEntryWithDefaultCostObjectHierarchyEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the StatisticalDimensionHierarchyLevel2 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#StatisticalDimensionHierarchyLevel3 name="StatisticalDimensionHierarchyLevel3">StatisticalDimensionHierarchyLevel3</a>

First included in: CostAccounting/CAMAggregatedStatisticalEntryWithDefaultCostObjectHierarchyEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the StatisticalDimensionHierarchyLevel3 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#StatisticalDimensionHierarchyLevel4 name="StatisticalDimensionHierarchyLevel4">StatisticalDimensionHierarchyLevel4</a>

First included in: CostAccounting/CAMAggregatedStatisticalEntryWithDefaultCostObjectHierarchyEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the StatisticalDimensionHierarchyLevel4 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#StatisticalDimensionHierarchyLevel5 name="StatisticalDimensionHierarchyLevel5">StatisticalDimensionHierarchyLevel5</a>

First included in: CostAccounting/CAMAggregatedStatisticalEntryWithDefaultCostObjectHierarchyEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the StatisticalDimensionHierarchyLevel5 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#StatisticalDimensionHierarchyLevel6 name="StatisticalDimensionHierarchyLevel6">StatisticalDimensionHierarchyLevel6</a>

First included in: CostAccounting/CAMAggregatedStatisticalEntryWithDefaultCostObjectHierarchyEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the StatisticalDimensionHierarchyLevel6 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#StatisticalDimensionHierarchyLevel7 name="StatisticalDimensionHierarchyLevel7">StatisticalDimensionHierarchyLevel7</a>

First included in: CostAccounting/CAMAggregatedStatisticalEntryWithDefaultCostObjectHierarchyEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the StatisticalDimensionHierarchyLevel7 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#StatisticalDimensionHierarchyLevel8 name="StatisticalDimensionHierarchyLevel8">StatisticalDimensionHierarchyLevel8</a>

First included in: CostAccounting/CAMAggregatedStatisticalEntryWithDefaultCostObjectHierarchyEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the StatisticalDimensionHierarchyLevel8 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#StatisticalDimensionHierarchyLevel9 name="StatisticalDimensionHierarchyLevel9">StatisticalDimensionHierarchyLevel9</a>

First included in: CostAccounting/CAMAggregatedStatisticalEntryWithDefaultCostObjectHierarchyEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the StatisticalDimensionHierarchyLevel9 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#StatisticalDimensionHierarchyLevel10 name="StatisticalDimensionHierarchyLevel10">StatisticalDimensionHierarchyLevel10</a>

First included in: CostAccounting/CAMAggregatedStatisticalEntryWithDefaultCostObjectHierarchyEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the StatisticalDimensionHierarchyLevel10 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#StatisticalDimensionHierarchyLevel11 name="StatisticalDimensionHierarchyLevel11">StatisticalDimensionHierarchyLevel11</a>

First included in: CostAccounting/CAMAggregatedStatisticalEntryWithDefaultCostObjectHierarchyEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the StatisticalDimensionHierarchyLevel11 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#StatisticalDimensionHierarchyLevel12 name="StatisticalDimensionHierarchyLevel12">StatisticalDimensionHierarchyLevel12</a>

First included in: CostAccounting/CAMAggregatedStatisticalEntryWithDefaultCostObjectHierarchyEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the StatisticalDimensionHierarchyLevel12 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#StatisticalDimensionHierarchyLevel13 name="StatisticalDimensionHierarchyLevel13">StatisticalDimensionHierarchyLevel13</a>

First included in: CostAccounting/CAMAggregatedStatisticalEntryWithDefaultCostObjectHierarchyEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the StatisticalDimensionHierarchyLevel13 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#StatisticalDimensionHierarchyLevel14 name="StatisticalDimensionHierarchyLevel14">StatisticalDimensionHierarchyLevel14</a>

First included in: CostAccounting/CAMAggregatedStatisticalEntryWithDefaultCostObjectHierarchyEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the StatisticalDimensionHierarchyLevel14 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#StatisticalDimensionHierarchyLevel15 name="StatisticalDimensionHierarchyLevel15">StatisticalDimensionHierarchyLevel15</a>

First included in: CostAccounting/CAMAggregatedStatisticalEntryWithDefaultCostObjectHierarchyEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the StatisticalDimensionHierarchyLevel15 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#VersionIdentificationName name="VersionIdentificationName">VersionIdentificationName</a>

First included in: CostAccounting/CAMAggregatedStatisticalEntryWithDefaultCostObjectHierarchyEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Version</td></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VersionIdentificationName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Version</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SourceVersionIdentificationName name="SourceVersionIdentificationName">SourceVersionIdentificationName</a>

First included in: CostAccounting/CAMAggregatedStatisticalEntryWithDefaultCostObjectHierarchyEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Source version</td></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SourceVersionIdentificationName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Source version</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#VersionType name="VersionType">VersionType</a>

First included in: CostAccounting/CAMAggregatedStatisticalEntryWithDefaultCostObjectHierarchyEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Version type</td></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VersionType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Version type</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#YearName name="YearName">YearName</a>

First included in: CostAccounting/CAMAggregatedStatisticalEntryWithDefaultCostObjectHierarchyEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the YearName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CalendarId name="CalendarId">CalendarId</a>

First included in: CostAccounting/CAMAggregatedStatisticalEntryWithDefaultCostObjectHierarchyEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CalendarId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Month name="Month">Month</a>

First included in: CostAccounting/CAMAggregatedStatisticalEntryWithDefaultCostObjectHierarchyEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Month attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PeriodName name="PeriodName">PeriodName</a>

First included in: CostAccounting/CAMAggregatedStatisticalEntryWithDefaultCostObjectHierarchyEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PeriodName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PeriodOffset name="PeriodOffset">PeriodOffset</a>

First included in: CostAccounting/CAMAggregatedStatisticalEntryWithDefaultCostObjectHierarchyEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PeriodOffset attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Quarter name="Quarter">Quarter</a>

First included in: CostAccounting/CAMAggregatedStatisticalEntryWithDefaultCostObjectHierarchyEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Quarter attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#QuarterOffset name="QuarterOffset">QuarterOffset</a>

First included in: CostAccounting/CAMAggregatedStatisticalEntryWithDefaultCostObjectHierarchyEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the QuarterOffset attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#YearOffset name="YearOffset">YearOffset</a>

First included in: CostAccounting/CAMAggregatedStatisticalEntryWithDefaultCostObjectHierarchyEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the YearOffset attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CostObjectDimensionMemberDescription name="CostObjectDimensionMemberDescription">CostObjectDimensionMemberDescription</a>

First included in: CostAccounting/CAMAggregatedStatisticalEntryWithDefaultCostObjectHierarchyEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CostObjectDimensionMemberDescription attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CostObjectDimensionMemberName name="CostObjectDimensionMemberName">CostObjectDimensionMemberName</a>

First included in: CostAccounting/CAMAggregatedStatisticalEntryWithDefaultCostObjectHierarchyEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Cost object dimension member name</td></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CostObjectDimensionMemberName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Cost object dimension member name</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#StatisticalDimensionMemberDescription name="StatisticalDimensionMemberDescription">StatisticalDimensionMemberDescription</a>

First included in: CostAccounting/CAMAggregatedStatisticalEntryWithDefaultCostObjectHierarchyEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the StatisticalDimensionMemberDescription attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#StatisticalDimensionHierarchyName name="StatisticalDimensionHierarchyName">StatisticalDimensionHierarchyName</a>

First included in: CostAccounting/CAMAggregatedStatisticalEntryWithDefaultCostObjectHierarchyEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the StatisticalDimensionHierarchyName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#StatisticalDimensionMemberName name="StatisticalDimensionMemberName">StatisticalDimensionMemberName</a>

First included in: CostAccounting/CAMAggregatedStatisticalEntryWithDefaultCostObjectHierarchyEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Statistical dimension member name</td></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the StatisticalDimensionMemberName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Statistical dimension member name</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>
