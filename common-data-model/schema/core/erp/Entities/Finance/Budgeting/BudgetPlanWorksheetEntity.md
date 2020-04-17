---
title: BudgetPlanWorksheetEntity - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/17/2020
ms.author: nebanfic
---

# BudgetPlanWorksheetEntity

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/erp/Entities/Finance/Budgeting/BudgetPlanWorksheetEntity.cdm.json" target="_blank">GitHub</a>.  

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
|[BudgetPlanHeader](#BudgetPlanHeader)||<a href="BudgetPlanWorksheetEntity.md" target="_blank">Budgeting/BudgetPlanWorksheetEntity</a>|
|[BudgetClass](#BudgetClass)||<a href="BudgetPlanWorksheetEntity.md" target="_blank">Budgeting/BudgetPlanWorksheetEntity</a>|
|[Comment](#Comment)||<a href="BudgetPlanWorksheetEntity.md" target="_blank">Budgeting/BudgetPlanWorksheetEntity</a>|
|[IsNewRequest](#IsNewRequest)||<a href="BudgetPlanWorksheetEntity.md" target="_blank">Budgeting/BudgetPlanWorksheetEntity</a>|
|[IsRecurring](#IsRecurring)||<a href="BudgetPlanWorksheetEntity.md" target="_blank">Budgeting/BudgetPlanWorksheetEntity</a>|
|[AssetId](#AssetId)||<a href="BudgetPlanWorksheetEntity.md" target="_blank">Budgeting/BudgetPlanWorksheetEntity</a>|
|[ProjectId](#ProjectId)||<a href="BudgetPlanWorksheetEntity.md" target="_blank">Budgeting/BudgetPlanWorksheetEntity</a>|
|[SourceDataAreaId](#SourceDataAreaId)||<a href="BudgetPlanWorksheetEntity.md" target="_blank">Budgeting/BudgetPlanWorksheetEntity</a>|
|[ProposedAsset](#ProposedAsset)||<a href="BudgetPlanWorksheetEntity.md" target="_blank">Budgeting/BudgetPlanWorksheetEntity</a>|
|[ProposedProject](#ProposedProject)||<a href="BudgetPlanWorksheetEntity.md" target="_blank">Budgeting/BudgetPlanWorksheetEntity</a>|
|[Position](#Position)||<a href="BudgetPlanWorksheetEntity.md" target="_blank">Budgeting/BudgetPlanWorksheetEntity</a>|
|[LineNumber](#LineNumber)||<a href="BudgetPlanWorksheetEntity.md" target="_blank">Budgeting/BudgetPlanWorksheetEntity</a>|
|[DocumentNumber](#DocumentNumber)||<a href="BudgetPlanWorksheetEntity.md" target="_blank">Budgeting/BudgetPlanWorksheetEntity</a>|
|[ProposedAssetName](#ProposedAssetName)||<a href="BudgetPlanWorksheetEntity.md" target="_blank">Budgeting/BudgetPlanWorksheetEntity</a>|
|[ProposedAssetDescription](#ProposedAssetDescription)||<a href="BudgetPlanWorksheetEntity.md" target="_blank">Budgeting/BudgetPlanWorksheetEntity</a>|
|[ProposedProjectName](#ProposedProjectName)||<a href="BudgetPlanWorksheetEntity.md" target="_blank">Budgeting/BudgetPlanWorksheetEntity</a>|
|[ProposedProjectDescription](#ProposedProjectDescription)||<a href="BudgetPlanWorksheetEntity.md" target="_blank">Budgeting/BudgetPlanWorksheetEntity</a>|
|[ForecastPosition](#ForecastPosition)||<a href="BudgetPlanWorksheetEntity.md" target="_blank">Budgeting/BudgetPlanWorksheetEntity</a>|
|[PositionId](#PositionId)||<a href="BudgetPlanWorksheetEntity.md" target="_blank">Budgeting/BudgetPlanWorksheetEntity</a>|
|[TransactionCurrencyCode](#TransactionCurrencyCode)||<a href="BudgetPlanWorksheetEntity.md" target="_blank">Budgeting/BudgetPlanWorksheetEntity</a>|
|[DimensionValue1](#DimensionValue1)||<a href="BudgetPlanWorksheetEntity.md" target="_blank">Budgeting/BudgetPlanWorksheetEntity</a>|
|[DimensionName1](#DimensionName1)||<a href="BudgetPlanWorksheetEntity.md" target="_blank">Budgeting/BudgetPlanWorksheetEntity</a>|
|[DimensionValue2](#DimensionValue2)||<a href="BudgetPlanWorksheetEntity.md" target="_blank">Budgeting/BudgetPlanWorksheetEntity</a>|
|[DimensionName2](#DimensionName2)||<a href="BudgetPlanWorksheetEntity.md" target="_blank">Budgeting/BudgetPlanWorksheetEntity</a>|
|[DimensionValue3](#DimensionValue3)||<a href="BudgetPlanWorksheetEntity.md" target="_blank">Budgeting/BudgetPlanWorksheetEntity</a>|
|[DimensionName3](#DimensionName3)||<a href="BudgetPlanWorksheetEntity.md" target="_blank">Budgeting/BudgetPlanWorksheetEntity</a>|
|[DimensionValue4](#DimensionValue4)||<a href="BudgetPlanWorksheetEntity.md" target="_blank">Budgeting/BudgetPlanWorksheetEntity</a>|
|[DimensionName4](#DimensionName4)||<a href="BudgetPlanWorksheetEntity.md" target="_blank">Budgeting/BudgetPlanWorksheetEntity</a>|
|[DimensionValue5](#DimensionValue5)||<a href="BudgetPlanWorksheetEntity.md" target="_blank">Budgeting/BudgetPlanWorksheetEntity</a>|
|[DimensionName5](#DimensionName5)||<a href="BudgetPlanWorksheetEntity.md" target="_blank">Budgeting/BudgetPlanWorksheetEntity</a>|
|[DimensionValue6](#DimensionValue6)||<a href="BudgetPlanWorksheetEntity.md" target="_blank">Budgeting/BudgetPlanWorksheetEntity</a>|
|[DimensionName6](#DimensionName6)||<a href="BudgetPlanWorksheetEntity.md" target="_blank">Budgeting/BudgetPlanWorksheetEntity</a>|
|[DimensionValue7](#DimensionValue7)||<a href="BudgetPlanWorksheetEntity.md" target="_blank">Budgeting/BudgetPlanWorksheetEntity</a>|
|[DimensionName7](#DimensionName7)||<a href="BudgetPlanWorksheetEntity.md" target="_blank">Budgeting/BudgetPlanWorksheetEntity</a>|
|[DimensionValue8](#DimensionValue8)||<a href="BudgetPlanWorksheetEntity.md" target="_blank">Budgeting/BudgetPlanWorksheetEntity</a>|
|[DimensionName8](#DimensionName8)||<a href="BudgetPlanWorksheetEntity.md" target="_blank">Budgeting/BudgetPlanWorksheetEntity</a>|
|[DimensionValue9](#DimensionValue9)||<a href="BudgetPlanWorksheetEntity.md" target="_blank">Budgeting/BudgetPlanWorksheetEntity</a>|
|[DimensionName9](#DimensionName9)||<a href="BudgetPlanWorksheetEntity.md" target="_blank">Budgeting/BudgetPlanWorksheetEntity</a>|
|[DimensionValue10](#DimensionValue10)||<a href="BudgetPlanWorksheetEntity.md" target="_blank">Budgeting/BudgetPlanWorksheetEntity</a>|
|[DimensionName10](#DimensionName10)||<a href="BudgetPlanWorksheetEntity.md" target="_blank">Budgeting/BudgetPlanWorksheetEntity</a>|
|[DimensionValue11](#DimensionValue11)||<a href="BudgetPlanWorksheetEntity.md" target="_blank">Budgeting/BudgetPlanWorksheetEntity</a>|
|[DimensionName11](#DimensionName11)||<a href="BudgetPlanWorksheetEntity.md" target="_blank">Budgeting/BudgetPlanWorksheetEntity</a>|
|[TransactionCurrencyAmount1](#TransactionCurrencyAmount1)||<a href="BudgetPlanWorksheetEntity.md" target="_blank">Budgeting/BudgetPlanWorksheetEntity</a>|
|[TransactionCurrencyAmount2](#TransactionCurrencyAmount2)||<a href="BudgetPlanWorksheetEntity.md" target="_blank">Budgeting/BudgetPlanWorksheetEntity</a>|
|[TransactionCurrencyAmount3](#TransactionCurrencyAmount3)||<a href="BudgetPlanWorksheetEntity.md" target="_blank">Budgeting/BudgetPlanWorksheetEntity</a>|
|[TransactionCurrencyAmount4](#TransactionCurrencyAmount4)||<a href="BudgetPlanWorksheetEntity.md" target="_blank">Budgeting/BudgetPlanWorksheetEntity</a>|
|[TransactionCurrencyAmount5](#TransactionCurrencyAmount5)||<a href="BudgetPlanWorksheetEntity.md" target="_blank">Budgeting/BudgetPlanWorksheetEntity</a>|
|[TransactionCurrencyAmount6](#TransactionCurrencyAmount6)||<a href="BudgetPlanWorksheetEntity.md" target="_blank">Budgeting/BudgetPlanWorksheetEntity</a>|
|[TransactionCurrencyAmount7](#TransactionCurrencyAmount7)||<a href="BudgetPlanWorksheetEntity.md" target="_blank">Budgeting/BudgetPlanWorksheetEntity</a>|
|[TransactionCurrencyAmount8](#TransactionCurrencyAmount8)||<a href="BudgetPlanWorksheetEntity.md" target="_blank">Budgeting/BudgetPlanWorksheetEntity</a>|
|[TransactionCurrencyAmount9](#TransactionCurrencyAmount9)||<a href="BudgetPlanWorksheetEntity.md" target="_blank">Budgeting/BudgetPlanWorksheetEntity</a>|
|[TransactionCurrencyAmount10](#TransactionCurrencyAmount10)||<a href="BudgetPlanWorksheetEntity.md" target="_blank">Budgeting/BudgetPlanWorksheetEntity</a>|
|[TransactionCurrencyAmount11](#TransactionCurrencyAmount11)||<a href="BudgetPlanWorksheetEntity.md" target="_blank">Budgeting/BudgetPlanWorksheetEntity</a>|
|[TransactionCurrencyAmount12](#TransactionCurrencyAmount12)||<a href="BudgetPlanWorksheetEntity.md" target="_blank">Budgeting/BudgetPlanWorksheetEntity</a>|
|[TransactionCurrencyAmount13](#TransactionCurrencyAmount13)||<a href="BudgetPlanWorksheetEntity.md" target="_blank">Budgeting/BudgetPlanWorksheetEntity</a>|
|[TransactionCurrencyAmount14](#TransactionCurrencyAmount14)||<a href="BudgetPlanWorksheetEntity.md" target="_blank">Budgeting/BudgetPlanWorksheetEntity</a>|
|[TransactionCurrencyAmount15](#TransactionCurrencyAmount15)||<a href="BudgetPlanWorksheetEntity.md" target="_blank">Budgeting/BudgetPlanWorksheetEntity</a>|
|[TransactionCurrencyAmount16](#TransactionCurrencyAmount16)||<a href="BudgetPlanWorksheetEntity.md" target="_blank">Budgeting/BudgetPlanWorksheetEntity</a>|
|[TransactionCurrencyAmount17](#TransactionCurrencyAmount17)||<a href="BudgetPlanWorksheetEntity.md" target="_blank">Budgeting/BudgetPlanWorksheetEntity</a>|
|[TransactionCurrencyAmount18](#TransactionCurrencyAmount18)||<a href="BudgetPlanWorksheetEntity.md" target="_blank">Budgeting/BudgetPlanWorksheetEntity</a>|
|[TransactionCurrencyAmount19](#TransactionCurrencyAmount19)||<a href="BudgetPlanWorksheetEntity.md" target="_blank">Budgeting/BudgetPlanWorksheetEntity</a>|
|[TransactionCurrencyAmount20](#TransactionCurrencyAmount20)||<a href="BudgetPlanWorksheetEntity.md" target="_blank">Budgeting/BudgetPlanWorksheetEntity</a>|
|[TransactionCurrencyAmount21](#TransactionCurrencyAmount21)||<a href="BudgetPlanWorksheetEntity.md" target="_blank">Budgeting/BudgetPlanWorksheetEntity</a>|
|[TransactionCurrencyAmount22](#TransactionCurrencyAmount22)||<a href="BudgetPlanWorksheetEntity.md" target="_blank">Budgeting/BudgetPlanWorksheetEntity</a>|
|[TransactionCurrencyAmount23](#TransactionCurrencyAmount23)||<a href="BudgetPlanWorksheetEntity.md" target="_blank">Budgeting/BudgetPlanWorksheetEntity</a>|
|[TransactionCurrencyAmount24](#TransactionCurrencyAmount24)||<a href="BudgetPlanWorksheetEntity.md" target="_blank">Budgeting/BudgetPlanWorksheetEntity</a>|
|[TransactionCurrencyAmount25](#TransactionCurrencyAmount25)||<a href="BudgetPlanWorksheetEntity.md" target="_blank">Budgeting/BudgetPlanWorksheetEntity</a>|
|[TransactionCurrencyAmount26](#TransactionCurrencyAmount26)||<a href="BudgetPlanWorksheetEntity.md" target="_blank">Budgeting/BudgetPlanWorksheetEntity</a>|
|[TransactionCurrencyAmount27](#TransactionCurrencyAmount27)||<a href="BudgetPlanWorksheetEntity.md" target="_blank">Budgeting/BudgetPlanWorksheetEntity</a>|
|[TransactionCurrencyAmount28](#TransactionCurrencyAmount28)||<a href="BudgetPlanWorksheetEntity.md" target="_blank">Budgeting/BudgetPlanWorksheetEntity</a>|
|[TransactionCurrencyAmount29](#TransactionCurrencyAmount29)||<a href="BudgetPlanWorksheetEntity.md" target="_blank">Budgeting/BudgetPlanWorksheetEntity</a>|
|[TransactionCurrencyAmount30](#TransactionCurrencyAmount30)||<a href="BudgetPlanWorksheetEntity.md" target="_blank">Budgeting/BudgetPlanWorksheetEntity</a>|
|[TransactionCurrencyAmount31](#TransactionCurrencyAmount31)||<a href="BudgetPlanWorksheetEntity.md" target="_blank">Budgeting/BudgetPlanWorksheetEntity</a>|
|[TransactionCurrencyAmount32](#TransactionCurrencyAmount32)||<a href="BudgetPlanWorksheetEntity.md" target="_blank">Budgeting/BudgetPlanWorksheetEntity</a>|
|[TransactionCurrencyAmount33](#TransactionCurrencyAmount33)||<a href="BudgetPlanWorksheetEntity.md" target="_blank">Budgeting/BudgetPlanWorksheetEntity</a>|
|[TransactionCurrencyAmount34](#TransactionCurrencyAmount34)||<a href="BudgetPlanWorksheetEntity.md" target="_blank">Budgeting/BudgetPlanWorksheetEntity</a>|
|[TransactionCurrencyAmount35](#TransactionCurrencyAmount35)||<a href="BudgetPlanWorksheetEntity.md" target="_blank">Budgeting/BudgetPlanWorksheetEntity</a>|
|[TransactionCurrencyAmount36](#TransactionCurrencyAmount36)||<a href="BudgetPlanWorksheetEntity.md" target="_blank">Budgeting/BudgetPlanWorksheetEntity</a>|
|[Quantity1](#Quantity1)||<a href="BudgetPlanWorksheetEntity.md" target="_blank">Budgeting/BudgetPlanWorksheetEntity</a>|
|[Quantity2](#Quantity2)||<a href="BudgetPlanWorksheetEntity.md" target="_blank">Budgeting/BudgetPlanWorksheetEntity</a>|
|[Quantity3](#Quantity3)||<a href="BudgetPlanWorksheetEntity.md" target="_blank">Budgeting/BudgetPlanWorksheetEntity</a>|
|[Quantity4](#Quantity4)||<a href="BudgetPlanWorksheetEntity.md" target="_blank">Budgeting/BudgetPlanWorksheetEntity</a>|
|[Quantity5](#Quantity5)||<a href="BudgetPlanWorksheetEntity.md" target="_blank">Budgeting/BudgetPlanWorksheetEntity</a>|
|[Quantity6](#Quantity6)||<a href="BudgetPlanWorksheetEntity.md" target="_blank">Budgeting/BudgetPlanWorksheetEntity</a>|
|[Quantity7](#Quantity7)||<a href="BudgetPlanWorksheetEntity.md" target="_blank">Budgeting/BudgetPlanWorksheetEntity</a>|
|[Quantity8](#Quantity8)||<a href="BudgetPlanWorksheetEntity.md" target="_blank">Budgeting/BudgetPlanWorksheetEntity</a>|
|[Quantity9](#Quantity9)||<a href="BudgetPlanWorksheetEntity.md" target="_blank">Budgeting/BudgetPlanWorksheetEntity</a>|
|[Quantity10](#Quantity10)||<a href="BudgetPlanWorksheetEntity.md" target="_blank">Budgeting/BudgetPlanWorksheetEntity</a>|
|[Quantity11](#Quantity11)||<a href="BudgetPlanWorksheetEntity.md" target="_blank">Budgeting/BudgetPlanWorksheetEntity</a>|
|[Quantity12](#Quantity12)||<a href="BudgetPlanWorksheetEntity.md" target="_blank">Budgeting/BudgetPlanWorksheetEntity</a>|
|[Quantity13](#Quantity13)||<a href="BudgetPlanWorksheetEntity.md" target="_blank">Budgeting/BudgetPlanWorksheetEntity</a>|
|[Quantity14](#Quantity14)||<a href="BudgetPlanWorksheetEntity.md" target="_blank">Budgeting/BudgetPlanWorksheetEntity</a>|
|[Quantity15](#Quantity15)||<a href="BudgetPlanWorksheetEntity.md" target="_blank">Budgeting/BudgetPlanWorksheetEntity</a>|
|[Quantity16](#Quantity16)||<a href="BudgetPlanWorksheetEntity.md" target="_blank">Budgeting/BudgetPlanWorksheetEntity</a>|
|[Quantity17](#Quantity17)||<a href="BudgetPlanWorksheetEntity.md" target="_blank">Budgeting/BudgetPlanWorksheetEntity</a>|
|[Quantity18](#Quantity18)||<a href="BudgetPlanWorksheetEntity.md" target="_blank">Budgeting/BudgetPlanWorksheetEntity</a>|
|[Quantity19](#Quantity19)||<a href="BudgetPlanWorksheetEntity.md" target="_blank">Budgeting/BudgetPlanWorksheetEntity</a>|
|[Quantity20](#Quantity20)||<a href="BudgetPlanWorksheetEntity.md" target="_blank">Budgeting/BudgetPlanWorksheetEntity</a>|
|[Quantity21](#Quantity21)||<a href="BudgetPlanWorksheetEntity.md" target="_blank">Budgeting/BudgetPlanWorksheetEntity</a>|
|[Quantity22](#Quantity22)||<a href="BudgetPlanWorksheetEntity.md" target="_blank">Budgeting/BudgetPlanWorksheetEntity</a>|
|[Quantity23](#Quantity23)||<a href="BudgetPlanWorksheetEntity.md" target="_blank">Budgeting/BudgetPlanWorksheetEntity</a>|
|[Quantity24](#Quantity24)||<a href="BudgetPlanWorksheetEntity.md" target="_blank">Budgeting/BudgetPlanWorksheetEntity</a>|
|[Quantity25](#Quantity25)||<a href="BudgetPlanWorksheetEntity.md" target="_blank">Budgeting/BudgetPlanWorksheetEntity</a>|
|[Quantity26](#Quantity26)||<a href="BudgetPlanWorksheetEntity.md" target="_blank">Budgeting/BudgetPlanWorksheetEntity</a>|
|[Quantity27](#Quantity27)||<a href="BudgetPlanWorksheetEntity.md" target="_blank">Budgeting/BudgetPlanWorksheetEntity</a>|
|[Quantity28](#Quantity28)||<a href="BudgetPlanWorksheetEntity.md" target="_blank">Budgeting/BudgetPlanWorksheetEntity</a>|
|[Quantity29](#Quantity29)||<a href="BudgetPlanWorksheetEntity.md" target="_blank">Budgeting/BudgetPlanWorksheetEntity</a>|
|[Quantity30](#Quantity30)||<a href="BudgetPlanWorksheetEntity.md" target="_blank">Budgeting/BudgetPlanWorksheetEntity</a>|
|[Quantity31](#Quantity31)||<a href="BudgetPlanWorksheetEntity.md" target="_blank">Budgeting/BudgetPlanWorksheetEntity</a>|
|[Quantity32](#Quantity32)||<a href="BudgetPlanWorksheetEntity.md" target="_blank">Budgeting/BudgetPlanWorksheetEntity</a>|
|[Quantity33](#Quantity33)||<a href="BudgetPlanWorksheetEntity.md" target="_blank">Budgeting/BudgetPlanWorksheetEntity</a>|
|[Quantity34](#Quantity34)||<a href="BudgetPlanWorksheetEntity.md" target="_blank">Budgeting/BudgetPlanWorksheetEntity</a>|
|[Quantity35](#Quantity35)||<a href="BudgetPlanWorksheetEntity.md" target="_blank">Budgeting/BudgetPlanWorksheetEntity</a>|
|[Quantity36](#Quantity36)||<a href="BudgetPlanWorksheetEntity.md" target="_blank">Budgeting/BudgetPlanWorksheetEntity</a>|
|[BudgetPlanLayout](#BudgetPlanLayout)||<a href="BudgetPlanWorksheetEntity.md" target="_blank">Budgeting/BudgetPlanWorksheetEntity</a>|
|[Layout](#Layout)||<a href="BudgetPlanWorksheetEntity.md" target="_blank">Budgeting/BudgetPlanWorksheetEntity</a>|
|[AssetIdDescription](#AssetIdDescription)||<a href="BudgetPlanWorksheetEntity.md" target="_blank">Budgeting/BudgetPlanWorksheetEntity</a>|
|[ProjectIdDescription](#ProjectIdDescription)||<a href="BudgetPlanWorksheetEntity.md" target="_blank">Budgeting/BudgetPlanWorksheetEntity</a>|
|[PositionDescription](#PositionDescription)||<a href="BudgetPlanWorksheetEntity.md" target="_blank">Budgeting/BudgetPlanWorksheetEntity</a>|
|[PositionWorkerName](#PositionWorkerName)||<a href="BudgetPlanWorksheetEntity.md" target="_blank">Budgeting/BudgetPlanWorksheetEntity</a>|
|[BackingTable_BudgetPlanLineActiveViewRelationshipId](#BackingTable_BudgetPlanLineActiveViewRelationshipId)||<a href="BudgetPlanWorksheetEntity.md" target="_blank">Budgeting/BudgetPlanWorksheetEntity</a>|

### <a href=#BudgetPlanHeader name="BudgetPlanHeader">BudgetPlanHeader</a>

First included in: Budgeting/BudgetPlanWorksheetEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BudgetPlanHeader attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BudgetClass name="BudgetClass">BudgetClass</a>

First included in: Budgeting/BudgetPlanWorksheetEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BudgetClass attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Comment name="Comment">Comment</a>

First included in: Budgeting/BudgetPlanWorksheetEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Comment attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsNewRequest name="IsNewRequest">IsNewRequest</a>

First included in: Budgeting/BudgetPlanWorksheetEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsNewRequest attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsRecurring name="IsRecurring">IsRecurring</a>

First included in: Budgeting/BudgetPlanWorksheetEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsRecurring attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AssetId name="AssetId">AssetId</a>

First included in: Budgeting/BudgetPlanWorksheetEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AssetId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProjectId name="ProjectId">ProjectId</a>

First included in: Budgeting/BudgetPlanWorksheetEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProjectId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SourceDataAreaId name="SourceDataAreaId">SourceDataAreaId</a>

First included in: Budgeting/BudgetPlanWorksheetEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SourceDataAreaId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProposedAsset name="ProposedAsset">ProposedAsset</a>

First included in: Budgeting/BudgetPlanWorksheetEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProposedAsset attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProposedProject name="ProposedProject">ProposedProject</a>

First included in: Budgeting/BudgetPlanWorksheetEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProposedProject attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Position name="Position">Position</a>

First included in: Budgeting/BudgetPlanWorksheetEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Position attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LineNumber name="LineNumber">LineNumber</a>

First included in: Budgeting/BudgetPlanWorksheetEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LineNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DocumentNumber name="DocumentNumber">DocumentNumber</a>

First included in: Budgeting/BudgetPlanWorksheetEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DocumentNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProposedAssetName name="ProposedAssetName">ProposedAssetName</a>

First included in: Budgeting/BudgetPlanWorksheetEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProposedAssetName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProposedAssetDescription name="ProposedAssetDescription">ProposedAssetDescription</a>

First included in: Budgeting/BudgetPlanWorksheetEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProposedAssetDescription attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProposedProjectName name="ProposedProjectName">ProposedProjectName</a>

First included in: Budgeting/BudgetPlanWorksheetEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProposedProjectName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProposedProjectDescription name="ProposedProjectDescription">ProposedProjectDescription</a>

First included in: Budgeting/BudgetPlanWorksheetEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProposedProjectDescription attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ForecastPosition name="ForecastPosition">ForecastPosition</a>

First included in: Budgeting/BudgetPlanWorksheetEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ForecastPosition attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PositionId name="PositionId">PositionId</a>

First included in: Budgeting/BudgetPlanWorksheetEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PositionId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TransactionCurrencyCode name="TransactionCurrencyCode">TransactionCurrencyCode</a>

First included in: Budgeting/BudgetPlanWorksheetEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TransactionCurrencyCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DimensionValue1 name="DimensionValue1">DimensionValue1</a>

First included in: Budgeting/BudgetPlanWorksheetEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DimensionValue1 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DimensionName1 name="DimensionName1">DimensionName1</a>

First included in: Budgeting/BudgetPlanWorksheetEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DimensionName1 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DimensionValue2 name="DimensionValue2">DimensionValue2</a>

First included in: Budgeting/BudgetPlanWorksheetEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DimensionValue2 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DimensionName2 name="DimensionName2">DimensionName2</a>

First included in: Budgeting/BudgetPlanWorksheetEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DimensionName2 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DimensionValue3 name="DimensionValue3">DimensionValue3</a>

First included in: Budgeting/BudgetPlanWorksheetEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DimensionValue3 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DimensionName3 name="DimensionName3">DimensionName3</a>

First included in: Budgeting/BudgetPlanWorksheetEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DimensionName3 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DimensionValue4 name="DimensionValue4">DimensionValue4</a>

First included in: Budgeting/BudgetPlanWorksheetEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DimensionValue4 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DimensionName4 name="DimensionName4">DimensionName4</a>

First included in: Budgeting/BudgetPlanWorksheetEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DimensionName4 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DimensionValue5 name="DimensionValue5">DimensionValue5</a>

First included in: Budgeting/BudgetPlanWorksheetEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DimensionValue5 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DimensionName5 name="DimensionName5">DimensionName5</a>

First included in: Budgeting/BudgetPlanWorksheetEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DimensionName5 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DimensionValue6 name="DimensionValue6">DimensionValue6</a>

First included in: Budgeting/BudgetPlanWorksheetEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DimensionValue6 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DimensionName6 name="DimensionName6">DimensionName6</a>

First included in: Budgeting/BudgetPlanWorksheetEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DimensionName6 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DimensionValue7 name="DimensionValue7">DimensionValue7</a>

First included in: Budgeting/BudgetPlanWorksheetEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DimensionValue7 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DimensionName7 name="DimensionName7">DimensionName7</a>

First included in: Budgeting/BudgetPlanWorksheetEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DimensionName7 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DimensionValue8 name="DimensionValue8">DimensionValue8</a>

First included in: Budgeting/BudgetPlanWorksheetEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DimensionValue8 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DimensionName8 name="DimensionName8">DimensionName8</a>

First included in: Budgeting/BudgetPlanWorksheetEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DimensionName8 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DimensionValue9 name="DimensionValue9">DimensionValue9</a>

First included in: Budgeting/BudgetPlanWorksheetEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DimensionValue9 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DimensionName9 name="DimensionName9">DimensionName9</a>

First included in: Budgeting/BudgetPlanWorksheetEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DimensionName9 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DimensionValue10 name="DimensionValue10">DimensionValue10</a>

First included in: Budgeting/BudgetPlanWorksheetEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DimensionValue10 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DimensionName10 name="DimensionName10">DimensionName10</a>

First included in: Budgeting/BudgetPlanWorksheetEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DimensionName10 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DimensionValue11 name="DimensionValue11">DimensionValue11</a>

First included in: Budgeting/BudgetPlanWorksheetEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DimensionValue11 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DimensionName11 name="DimensionName11">DimensionName11</a>

First included in: Budgeting/BudgetPlanWorksheetEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DimensionName11 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TransactionCurrencyAmount1 name="TransactionCurrencyAmount1">TransactionCurrencyAmount1</a>

First included in: Budgeting/BudgetPlanWorksheetEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TransactionCurrencyAmount1 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TransactionCurrencyAmount2 name="TransactionCurrencyAmount2">TransactionCurrencyAmount2</a>

First included in: Budgeting/BudgetPlanWorksheetEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TransactionCurrencyAmount2 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TransactionCurrencyAmount3 name="TransactionCurrencyAmount3">TransactionCurrencyAmount3</a>

First included in: Budgeting/BudgetPlanWorksheetEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TransactionCurrencyAmount3 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TransactionCurrencyAmount4 name="TransactionCurrencyAmount4">TransactionCurrencyAmount4</a>

First included in: Budgeting/BudgetPlanWorksheetEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TransactionCurrencyAmount4 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TransactionCurrencyAmount5 name="TransactionCurrencyAmount5">TransactionCurrencyAmount5</a>

First included in: Budgeting/BudgetPlanWorksheetEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TransactionCurrencyAmount5 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TransactionCurrencyAmount6 name="TransactionCurrencyAmount6">TransactionCurrencyAmount6</a>

First included in: Budgeting/BudgetPlanWorksheetEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TransactionCurrencyAmount6 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TransactionCurrencyAmount7 name="TransactionCurrencyAmount7">TransactionCurrencyAmount7</a>

First included in: Budgeting/BudgetPlanWorksheetEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TransactionCurrencyAmount7 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TransactionCurrencyAmount8 name="TransactionCurrencyAmount8">TransactionCurrencyAmount8</a>

First included in: Budgeting/BudgetPlanWorksheetEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TransactionCurrencyAmount8 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TransactionCurrencyAmount9 name="TransactionCurrencyAmount9">TransactionCurrencyAmount9</a>

First included in: Budgeting/BudgetPlanWorksheetEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TransactionCurrencyAmount9 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TransactionCurrencyAmount10 name="TransactionCurrencyAmount10">TransactionCurrencyAmount10</a>

First included in: Budgeting/BudgetPlanWorksheetEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TransactionCurrencyAmount10 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TransactionCurrencyAmount11 name="TransactionCurrencyAmount11">TransactionCurrencyAmount11</a>

First included in: Budgeting/BudgetPlanWorksheetEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TransactionCurrencyAmount11 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TransactionCurrencyAmount12 name="TransactionCurrencyAmount12">TransactionCurrencyAmount12</a>

First included in: Budgeting/BudgetPlanWorksheetEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TransactionCurrencyAmount12 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TransactionCurrencyAmount13 name="TransactionCurrencyAmount13">TransactionCurrencyAmount13</a>

First included in: Budgeting/BudgetPlanWorksheetEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TransactionCurrencyAmount13 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TransactionCurrencyAmount14 name="TransactionCurrencyAmount14">TransactionCurrencyAmount14</a>

First included in: Budgeting/BudgetPlanWorksheetEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TransactionCurrencyAmount14 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TransactionCurrencyAmount15 name="TransactionCurrencyAmount15">TransactionCurrencyAmount15</a>

First included in: Budgeting/BudgetPlanWorksheetEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TransactionCurrencyAmount15 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TransactionCurrencyAmount16 name="TransactionCurrencyAmount16">TransactionCurrencyAmount16</a>

First included in: Budgeting/BudgetPlanWorksheetEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TransactionCurrencyAmount16 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TransactionCurrencyAmount17 name="TransactionCurrencyAmount17">TransactionCurrencyAmount17</a>

First included in: Budgeting/BudgetPlanWorksheetEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TransactionCurrencyAmount17 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TransactionCurrencyAmount18 name="TransactionCurrencyAmount18">TransactionCurrencyAmount18</a>

First included in: Budgeting/BudgetPlanWorksheetEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TransactionCurrencyAmount18 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TransactionCurrencyAmount19 name="TransactionCurrencyAmount19">TransactionCurrencyAmount19</a>

First included in: Budgeting/BudgetPlanWorksheetEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TransactionCurrencyAmount19 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TransactionCurrencyAmount20 name="TransactionCurrencyAmount20">TransactionCurrencyAmount20</a>

First included in: Budgeting/BudgetPlanWorksheetEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TransactionCurrencyAmount20 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TransactionCurrencyAmount21 name="TransactionCurrencyAmount21">TransactionCurrencyAmount21</a>

First included in: Budgeting/BudgetPlanWorksheetEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TransactionCurrencyAmount21 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TransactionCurrencyAmount22 name="TransactionCurrencyAmount22">TransactionCurrencyAmount22</a>

First included in: Budgeting/BudgetPlanWorksheetEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TransactionCurrencyAmount22 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TransactionCurrencyAmount23 name="TransactionCurrencyAmount23">TransactionCurrencyAmount23</a>

First included in: Budgeting/BudgetPlanWorksheetEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TransactionCurrencyAmount23 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TransactionCurrencyAmount24 name="TransactionCurrencyAmount24">TransactionCurrencyAmount24</a>

First included in: Budgeting/BudgetPlanWorksheetEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TransactionCurrencyAmount24 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TransactionCurrencyAmount25 name="TransactionCurrencyAmount25">TransactionCurrencyAmount25</a>

First included in: Budgeting/BudgetPlanWorksheetEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TransactionCurrencyAmount25 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TransactionCurrencyAmount26 name="TransactionCurrencyAmount26">TransactionCurrencyAmount26</a>

First included in: Budgeting/BudgetPlanWorksheetEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TransactionCurrencyAmount26 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TransactionCurrencyAmount27 name="TransactionCurrencyAmount27">TransactionCurrencyAmount27</a>

First included in: Budgeting/BudgetPlanWorksheetEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TransactionCurrencyAmount27 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TransactionCurrencyAmount28 name="TransactionCurrencyAmount28">TransactionCurrencyAmount28</a>

First included in: Budgeting/BudgetPlanWorksheetEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TransactionCurrencyAmount28 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TransactionCurrencyAmount29 name="TransactionCurrencyAmount29">TransactionCurrencyAmount29</a>

First included in: Budgeting/BudgetPlanWorksheetEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TransactionCurrencyAmount29 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TransactionCurrencyAmount30 name="TransactionCurrencyAmount30">TransactionCurrencyAmount30</a>

First included in: Budgeting/BudgetPlanWorksheetEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TransactionCurrencyAmount30 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TransactionCurrencyAmount31 name="TransactionCurrencyAmount31">TransactionCurrencyAmount31</a>

First included in: Budgeting/BudgetPlanWorksheetEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TransactionCurrencyAmount31 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TransactionCurrencyAmount32 name="TransactionCurrencyAmount32">TransactionCurrencyAmount32</a>

First included in: Budgeting/BudgetPlanWorksheetEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TransactionCurrencyAmount32 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TransactionCurrencyAmount33 name="TransactionCurrencyAmount33">TransactionCurrencyAmount33</a>

First included in: Budgeting/BudgetPlanWorksheetEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TransactionCurrencyAmount33 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TransactionCurrencyAmount34 name="TransactionCurrencyAmount34">TransactionCurrencyAmount34</a>

First included in: Budgeting/BudgetPlanWorksheetEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TransactionCurrencyAmount34 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TransactionCurrencyAmount35 name="TransactionCurrencyAmount35">TransactionCurrencyAmount35</a>

First included in: Budgeting/BudgetPlanWorksheetEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TransactionCurrencyAmount35 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TransactionCurrencyAmount36 name="TransactionCurrencyAmount36">TransactionCurrencyAmount36</a>

First included in: Budgeting/BudgetPlanWorksheetEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TransactionCurrencyAmount36 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Quantity1 name="Quantity1">Quantity1</a>

First included in: Budgeting/BudgetPlanWorksheetEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Quantity1 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Quantity2 name="Quantity2">Quantity2</a>

First included in: Budgeting/BudgetPlanWorksheetEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Quantity2 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Quantity3 name="Quantity3">Quantity3</a>

First included in: Budgeting/BudgetPlanWorksheetEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Quantity3 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Quantity4 name="Quantity4">Quantity4</a>

First included in: Budgeting/BudgetPlanWorksheetEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Quantity4 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Quantity5 name="Quantity5">Quantity5</a>

First included in: Budgeting/BudgetPlanWorksheetEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Quantity5 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Quantity6 name="Quantity6">Quantity6</a>

First included in: Budgeting/BudgetPlanWorksheetEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Quantity6 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Quantity7 name="Quantity7">Quantity7</a>

First included in: Budgeting/BudgetPlanWorksheetEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Quantity7 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Quantity8 name="Quantity8">Quantity8</a>

First included in: Budgeting/BudgetPlanWorksheetEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Quantity8 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Quantity9 name="Quantity9">Quantity9</a>

First included in: Budgeting/BudgetPlanWorksheetEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Quantity9 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Quantity10 name="Quantity10">Quantity10</a>

First included in: Budgeting/BudgetPlanWorksheetEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Quantity10 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Quantity11 name="Quantity11">Quantity11</a>

First included in: Budgeting/BudgetPlanWorksheetEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Quantity11 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Quantity12 name="Quantity12">Quantity12</a>

First included in: Budgeting/BudgetPlanWorksheetEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Quantity12 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Quantity13 name="Quantity13">Quantity13</a>

First included in: Budgeting/BudgetPlanWorksheetEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Quantity13 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Quantity14 name="Quantity14">Quantity14</a>

First included in: Budgeting/BudgetPlanWorksheetEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Quantity14 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Quantity15 name="Quantity15">Quantity15</a>

First included in: Budgeting/BudgetPlanWorksheetEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Quantity15 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Quantity16 name="Quantity16">Quantity16</a>

First included in: Budgeting/BudgetPlanWorksheetEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Quantity16 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Quantity17 name="Quantity17">Quantity17</a>

First included in: Budgeting/BudgetPlanWorksheetEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Quantity17 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Quantity18 name="Quantity18">Quantity18</a>

First included in: Budgeting/BudgetPlanWorksheetEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Quantity18 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Quantity19 name="Quantity19">Quantity19</a>

First included in: Budgeting/BudgetPlanWorksheetEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Quantity19 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Quantity20 name="Quantity20">Quantity20</a>

First included in: Budgeting/BudgetPlanWorksheetEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Quantity20 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Quantity21 name="Quantity21">Quantity21</a>

First included in: Budgeting/BudgetPlanWorksheetEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Quantity21 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Quantity22 name="Quantity22">Quantity22</a>

First included in: Budgeting/BudgetPlanWorksheetEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Quantity22 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Quantity23 name="Quantity23">Quantity23</a>

First included in: Budgeting/BudgetPlanWorksheetEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Quantity23 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Quantity24 name="Quantity24">Quantity24</a>

First included in: Budgeting/BudgetPlanWorksheetEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Quantity24 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Quantity25 name="Quantity25">Quantity25</a>

First included in: Budgeting/BudgetPlanWorksheetEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Quantity25 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Quantity26 name="Quantity26">Quantity26</a>

First included in: Budgeting/BudgetPlanWorksheetEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Quantity26 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Quantity27 name="Quantity27">Quantity27</a>

First included in: Budgeting/BudgetPlanWorksheetEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Quantity27 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Quantity28 name="Quantity28">Quantity28</a>

First included in: Budgeting/BudgetPlanWorksheetEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Quantity28 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Quantity29 name="Quantity29">Quantity29</a>

First included in: Budgeting/BudgetPlanWorksheetEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Quantity29 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Quantity30 name="Quantity30">Quantity30</a>

First included in: Budgeting/BudgetPlanWorksheetEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Quantity30 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Quantity31 name="Quantity31">Quantity31</a>

First included in: Budgeting/BudgetPlanWorksheetEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Quantity31 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Quantity32 name="Quantity32">Quantity32</a>

First included in: Budgeting/BudgetPlanWorksheetEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Quantity32 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Quantity33 name="Quantity33">Quantity33</a>

First included in: Budgeting/BudgetPlanWorksheetEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Quantity33 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Quantity34 name="Quantity34">Quantity34</a>

First included in: Budgeting/BudgetPlanWorksheetEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Quantity34 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Quantity35 name="Quantity35">Quantity35</a>

First included in: Budgeting/BudgetPlanWorksheetEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Quantity35 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Quantity36 name="Quantity36">Quantity36</a>

First included in: Budgeting/BudgetPlanWorksheetEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Quantity36 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BudgetPlanLayout name="BudgetPlanLayout">BudgetPlanLayout</a>

First included in: Budgeting/BudgetPlanWorksheetEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BudgetPlanLayout attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Layout name="Layout">Layout</a>

First included in: Budgeting/BudgetPlanWorksheetEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Layout attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AssetIdDescription name="AssetIdDescription">AssetIdDescription</a>

First included in: Budgeting/BudgetPlanWorksheetEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AssetIdDescription attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProjectIdDescription name="ProjectIdDescription">ProjectIdDescription</a>

First included in: Budgeting/BudgetPlanWorksheetEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProjectIdDescription attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PositionDescription name="PositionDescription">PositionDescription</a>

First included in: Budgeting/BudgetPlanWorksheetEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PositionDescription attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PositionWorkerName name="PositionWorkerName">PositionWorkerName</a>

First included in: Budgeting/BudgetPlanWorksheetEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PositionWorkerName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BackingTable_BudgetPlanLineActiveViewRelationshipId name="BackingTable_BudgetPlanLineActiveViewRelationshipId">BackingTable_BudgetPlanLineActiveViewRelationshipId</a>

First included in: Budgeting/BudgetPlanWorksheetEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_BudgetPlanLineActiveViewRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/Finance/Budget/WorksheetLine/BudgetPlanLineActiveView.md" target="_blank">/core/erp/Tables/Finance/Budget/WorksheetLine/BudgetPlanLineActiveView.cdm.json/BudgetPlanLineActiveView</a></td><td><a href="../../../Tables/Finance/Budget/WorksheetLine/BudgetPlanLineActiveView.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>
