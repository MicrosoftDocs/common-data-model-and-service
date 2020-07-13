---
title: HcmPositionForecastEntity in HRM - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 7/13/2020
ms.author: nebanfic
---

# Forecast position budget purpose account details in HRM(HcmPositionForecastEntity)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/HumanResources/HRM/HcmPositionForecastEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Forecast position budget purpose account details</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[AnnualAmount](#AnnualAmount)||<a href="HcmPositionForecastEntity.md" target="_blank">HRM/HcmPositionForecastEntity</a>|
|[BudgetAmount](#BudgetAmount)||<a href="HcmPositionForecastEntity.md" target="_blank">HRM/HcmPositionForecastEntity</a>|
|[BudgetCostElement](#BudgetCostElement)||<a href="HcmPositionForecastEntity.md" target="_blank">HRM/HcmPositionForecastEntity</a>|
|[CostElementLineStartDate](#CostElementLineStartDate)||<a href="HcmPositionForecastEntity.md" target="_blank">HRM/HcmPositionForecastEntity</a>|
|[CostElementLineEndDate](#CostElementLineEndDate)||<a href="HcmPositionForecastEntity.md" target="_blank">HRM/HcmPositionForecastEntity</a>|
|[isPercentageBased](#isPercentageBased)||<a href="HcmPositionForecastEntity.md" target="_blank">HRM/HcmPositionForecastEntity</a>|
|[CostElementLineMainAccount](#CostElementLineMainAccount)||<a href="HcmPositionForecastEntity.md" target="_blank">HRM/HcmPositionForecastEntity</a>|
|[Percent](#Percent)||<a href="HcmPositionForecastEntity.md" target="_blank">HRM/HcmPositionForecastEntity</a>|
|[CostElementSource](#CostElementSource)||<a href="HcmPositionForecastEntity.md" target="_blank">HRM/HcmPositionForecastEntity</a>|
|[CostElementLineCompensationGrid](#CostElementLineCompensationGrid)||<a href="HcmPositionForecastEntity.md" target="_blank">HRM/HcmPositionForecastEntity</a>|
|[CostElementRecId](#CostElementRecId)||<a href="HcmPositionForecastEntity.md" target="_blank">HRM/HcmPositionForecastEntity</a>|
|[CostElementEffectiveDate](#CostElementEffectiveDate)||<a href="HcmPositionForecastEntity.md" target="_blank">HRM/HcmPositionForecastEntity</a>|
|[CostElementExpirationDate](#CostElementExpirationDate)||<a href="HcmPositionForecastEntity.md" target="_blank">HRM/HcmPositionForecastEntity</a>|
|[CostElementLegalEntity](#CostElementLegalEntity)||<a href="HcmPositionForecastEntity.md" target="_blank">HRM/HcmPositionForecastEntity</a>|
|[CostElementName](#CostElementName)||<a href="HcmPositionForecastEntity.md" target="_blank">HRM/HcmPositionForecastEntity</a>|
|[CostElementDataAreaId](#CostElementDataAreaId)||<a href="HcmPositionForecastEntity.md" target="_blank">HRM/HcmPositionForecastEntity</a>|
|[ForecastPositionActivationDate](#ForecastPositionActivationDate)||<a href="HcmPositionForecastEntity.md" target="_blank">HRM/HcmPositionForecastEntity</a>|
|[AnniversaryDate](#AnniversaryDate)||<a href="HcmPositionForecastEntity.md" target="_blank">HRM/HcmPositionForecastEntity</a>|
|[ForecastPositionCompensationGroupDataAreaId](#ForecastPositionCompensationGroupDataAreaId)||<a href="HcmPositionForecastEntity.md" target="_blank">HRM/HcmPositionForecastEntity</a>|
|[ForecastPositionCompensationGroupId](#ForecastPositionCompensationGroupId)||<a href="HcmPositionForecastEntity.md" target="_blank">HRM/HcmPositionForecastEntity</a>|
|[ForecastScenario](#ForecastScenario)||<a href="HcmPositionForecastEntity.md" target="_blank">HRM/HcmPositionForecastEntity</a>|
|[ForecastPositionFullTimeEquivalency](#ForecastPositionFullTimeEquivalency)||<a href="HcmPositionForecastEntity.md" target="_blank">HRM/HcmPositionForecastEntity</a>|
|[ForecastPositionPositionLegalEntity](#ForecastPositionPositionLegalEntity)||<a href="HcmPositionForecastEntity.md" target="_blank">HRM/HcmPositionForecastEntity</a>|
|[ForecastPosition](#ForecastPosition)||<a href="HcmPositionForecastEntity.md" target="_blank">HRM/HcmPositionForecastEntity</a>|
|[ForecastPositionCompensationLevelRecId](#ForecastPositionCompensationLevelRecId)||<a href="HcmPositionForecastEntity.md" target="_blank">HRM/HcmPositionForecastEntity</a>|
|[ForecastPositionRetirementDate](#ForecastPositionRetirementDate)||<a href="HcmPositionForecastEntity.md" target="_blank">HRM/HcmPositionForecastEntity</a>|
|[AssignedWorker](#AssignedWorker)||<a href="HcmPositionForecastEntity.md" target="_blank">HRM/HcmPositionForecastEntity</a>|
|[BudgetPlanningProcess](#BudgetPlanningProcess)||<a href="HcmPositionForecastEntity.md" target="_blank">HRM/HcmPositionForecastEntity</a>|
|[BudgetPlanScenario](#BudgetPlanScenario)||<a href="HcmPositionForecastEntity.md" target="_blank">HRM/HcmPositionForecastEntity</a>|
|[BudgetPlanScenarioName](#BudgetPlanScenarioName)||<a href="HcmPositionForecastEntity.md" target="_blank">HRM/HcmPositionForecastEntity</a>|
|[ForecastPositionRecId](#ForecastPositionRecId)||<a href="HcmPositionForecastEntity.md" target="_blank">HRM/HcmPositionForecastEntity</a>|
|[ForecastPositionId](#ForecastPositionId)||<a href="HcmPositionForecastEntity.md" target="_blank">HRM/HcmPositionForecastEntity</a>|
|[ForecastPositionLegalEnitytName](#ForecastPositionLegalEnitytName)||<a href="HcmPositionForecastEntity.md" target="_blank">HRM/HcmPositionForecastEntity</a>|
|[CostElementLineReferencePointId](#CostElementLineReferencePointId)||<a href="HcmPositionForecastEntity.md" target="_blank">HRM/HcmPositionForecastEntity</a>|
|[CostElementLineReferenceSetupId](#CostElementLineReferenceSetupId)||<a href="HcmPositionForecastEntity.md" target="_blank">HRM/HcmPositionForecastEntity</a>|
|[CostElementLineMainAccountDisplayValue](#CostElementLineMainAccountDisplayValue)||<a href="HcmPositionForecastEntity.md" target="_blank">HRM/HcmPositionForecastEntity</a>|
|[ForecastPositionCompensationGrid](#ForecastPositionCompensationGrid)||<a href="HcmPositionForecastEntity.md" target="_blank">HRM/HcmPositionForecastEntity</a>|
|[BudgetPlanningProcessName](#BudgetPlanningProcessName)||<a href="HcmPositionForecastEntity.md" target="_blank">HRM/HcmPositionForecastEntity</a>|
|[ForecastPositionRefPointId](#ForecastPositionRefPointId)||<a href="HcmPositionForecastEntity.md" target="_blank">HRM/HcmPositionForecastEntity</a>|
|[ForecastPositionRefPointSetupId](#ForecastPositionRefPointSetupId)||<a href="HcmPositionForecastEntity.md" target="_blank">HRM/HcmPositionForecastEntity</a>|
|[Department](#Department)||<a href="HcmPositionForecastEntity.md" target="_blank">HRM/HcmPositionForecastEntity</a>|
|[Description](#Description)||<a href="HcmPositionForecastEntity.md" target="_blank">HRM/HcmPositionForecastEntity</a>|
|[Job](#Job)||<a href="HcmPositionForecastEntity.md" target="_blank">HRM/HcmPositionForecastEntity</a>|
|[PositionType](#PositionType)||<a href="HcmPositionForecastEntity.md" target="_blank">HRM/HcmPositionForecastEntity</a>|
|[Title](#Title)||<a href="HcmPositionForecastEntity.md" target="_blank">HRM/HcmPositionForecastEntity</a>|
|[CompLocation](#CompLocation)||<a href="HcmPositionForecastEntity.md" target="_blank">HRM/HcmPositionForecastEntity</a>|
|[JobId](#JobId)||<a href="HcmPositionForecastEntity.md" target="_blank">HRM/HcmPositionForecastEntity</a>|
|[DepartmentNumber](#DepartmentNumber)||<a href="HcmPositionForecastEntity.md" target="_blank">HRM/HcmPositionForecastEntity</a>|
|[CompensationRegionId](#CompensationRegionId)||<a href="HcmPositionForecastEntity.md" target="_blank">HRM/HcmPositionForecastEntity</a>|
|[PositionTypeId](#PositionTypeId)||<a href="HcmPositionForecastEntity.md" target="_blank">HRM/HcmPositionForecastEntity</a>|
|[TitleId](#TitleId)||<a href="HcmPositionForecastEntity.md" target="_blank">HRM/HcmPositionForecastEntity</a>|
|[CompensationLevelId](#CompensationLevelId)||<a href="HcmPositionForecastEntity.md" target="_blank">HRM/HcmPositionForecastEntity</a>|
|[Relationship_MainAccountCombinationsRelationshipId](#Relationship_MainAccountCombinationsRelationshipId)||<a href="HcmPositionForecastEntity.md" target="_blank">HRM/HcmPositionForecastEntity</a>|
|[BackingTable_HcmPositionForecastBudgetAcctLineRelationshipId](#BackingTable_HcmPositionForecastBudgetAcctLineRelationshipId)||<a href="HcmPositionForecastEntity.md" target="_blank">HRM/HcmPositionForecastEntity</a>|

### <a href=#AnnualAmount name="AnnualAmount">AnnualAmount</a>

First included in: HRM/HcmPositionForecastEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AnnualAmount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BudgetAmount name="BudgetAmount">BudgetAmount</a>

First included in: HRM/HcmPositionForecastEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BudgetAmount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BudgetCostElement name="BudgetCostElement">BudgetCostElement</a>

First included in: HRM/HcmPositionForecastEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BudgetCostElement attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CostElementLineStartDate name="CostElementLineStartDate">CostElementLineStartDate</a>

First included in: HRM/HcmPositionForecastEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CostElementLineStartDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CostElementLineEndDate name="CostElementLineEndDate">CostElementLineEndDate</a>

First included in: HRM/HcmPositionForecastEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CostElementLineEndDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#isPercentageBased name="isPercentageBased">isPercentageBased</a>

First included in: HRM/HcmPositionForecastEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the isPercentageBased attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CostElementLineMainAccount name="CostElementLineMainAccount">CostElementLineMainAccount</a>

First included in: HRM/HcmPositionForecastEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CostElementLineMainAccount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Percent name="Percent">Percent</a>

First included in: HRM/HcmPositionForecastEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Percent attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CostElementSource name="CostElementSource">CostElementSource</a>

First included in: HRM/HcmPositionForecastEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CostElementSource attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CostElementLineCompensationGrid name="CostElementLineCompensationGrid">CostElementLineCompensationGrid</a>

First included in: HRM/HcmPositionForecastEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CostElementLineCompensationGrid attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CostElementRecId name="CostElementRecId">CostElementRecId</a>

First included in: HRM/HcmPositionForecastEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CostElementRecId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CostElementEffectiveDate name="CostElementEffectiveDate">CostElementEffectiveDate</a>

First included in: HRM/HcmPositionForecastEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CostElementEffectiveDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CostElementExpirationDate name="CostElementExpirationDate">CostElementExpirationDate</a>

First included in: HRM/HcmPositionForecastEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CostElementExpirationDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CostElementLegalEntity name="CostElementLegalEntity">CostElementLegalEntity</a>

First included in: HRM/HcmPositionForecastEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CostElementLegalEntity attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CostElementName name="CostElementName">CostElementName</a>

First included in: HRM/HcmPositionForecastEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CostElementName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CostElementDataAreaId name="CostElementDataAreaId">CostElementDataAreaId</a>

First included in: HRM/HcmPositionForecastEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CostElementDataAreaId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ForecastPositionActivationDate name="ForecastPositionActivationDate">ForecastPositionActivationDate</a>

First included in: HRM/HcmPositionForecastEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ForecastPositionActivationDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AnniversaryDate name="AnniversaryDate">AnniversaryDate</a>

First included in: HRM/HcmPositionForecastEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AnniversaryDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ForecastPositionCompensationGroupDataAreaId name="ForecastPositionCompensationGroupDataAreaId">ForecastPositionCompensationGroupDataAreaId</a>

First included in: HRM/HcmPositionForecastEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ForecastPositionCompensationGroupDataAreaId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ForecastPositionCompensationGroupId name="ForecastPositionCompensationGroupId">ForecastPositionCompensationGroupId</a>

First included in: HRM/HcmPositionForecastEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ForecastPositionCompensationGroupId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ForecastScenario name="ForecastScenario">ForecastScenario</a>

First included in: HRM/HcmPositionForecastEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ForecastScenario attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ForecastPositionFullTimeEquivalency name="ForecastPositionFullTimeEquivalency">ForecastPositionFullTimeEquivalency</a>

First included in: HRM/HcmPositionForecastEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ForecastPositionFullTimeEquivalency attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ForecastPositionPositionLegalEntity name="ForecastPositionPositionLegalEntity">ForecastPositionPositionLegalEntity</a>

First included in: HRM/HcmPositionForecastEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ForecastPositionPositionLegalEntity attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ForecastPosition name="ForecastPosition">ForecastPosition</a>

First included in: HRM/HcmPositionForecastEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ForecastPosition attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ForecastPositionCompensationLevelRecId name="ForecastPositionCompensationLevelRecId">ForecastPositionCompensationLevelRecId</a>

First included in: HRM/HcmPositionForecastEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ForecastPositionCompensationLevelRecId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ForecastPositionRetirementDate name="ForecastPositionRetirementDate">ForecastPositionRetirementDate</a>

First included in: HRM/HcmPositionForecastEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ForecastPositionRetirementDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AssignedWorker name="AssignedWorker">AssignedWorker</a>

First included in: HRM/HcmPositionForecastEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AssignedWorker attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BudgetPlanningProcess name="BudgetPlanningProcess">BudgetPlanningProcess</a>

First included in: HRM/HcmPositionForecastEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BudgetPlanningProcess attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BudgetPlanScenario name="BudgetPlanScenario">BudgetPlanScenario</a>

First included in: HRM/HcmPositionForecastEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BudgetPlanScenario attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BudgetPlanScenarioName name="BudgetPlanScenarioName">BudgetPlanScenarioName</a>

First included in: HRM/HcmPositionForecastEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BudgetPlanScenarioName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ForecastPositionRecId name="ForecastPositionRecId">ForecastPositionRecId</a>

First included in: HRM/HcmPositionForecastEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ForecastPositionRecId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ForecastPositionId name="ForecastPositionId">ForecastPositionId</a>

First included in: HRM/HcmPositionForecastEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ForecastPositionId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ForecastPositionLegalEnitytName name="ForecastPositionLegalEnitytName">ForecastPositionLegalEnitytName</a>

First included in: HRM/HcmPositionForecastEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ForecastPositionLegalEnitytName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CostElementLineReferencePointId name="CostElementLineReferencePointId">CostElementLineReferencePointId</a>

First included in: HRM/HcmPositionForecastEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CostElementLineReferencePointId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CostElementLineReferenceSetupId name="CostElementLineReferenceSetupId">CostElementLineReferenceSetupId</a>

First included in: HRM/HcmPositionForecastEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CostElementLineReferenceSetupId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CostElementLineMainAccountDisplayValue name="CostElementLineMainAccountDisplayValue">CostElementLineMainAccountDisplayValue</a>

First included in: HRM/HcmPositionForecastEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CostElementLineMainAccountDisplayValue attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ForecastPositionCompensationGrid name="ForecastPositionCompensationGrid">ForecastPositionCompensationGrid</a>

First included in: HRM/HcmPositionForecastEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ForecastPositionCompensationGrid attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BudgetPlanningProcessName name="BudgetPlanningProcessName">BudgetPlanningProcessName</a>

First included in: HRM/HcmPositionForecastEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BudgetPlanningProcessName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ForecastPositionRefPointId name="ForecastPositionRefPointId">ForecastPositionRefPointId</a>

First included in: HRM/HcmPositionForecastEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ForecastPositionRefPointId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ForecastPositionRefPointSetupId name="ForecastPositionRefPointSetupId">ForecastPositionRefPointSetupId</a>

First included in: HRM/HcmPositionForecastEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ForecastPositionRefPointSetupId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Department name="Department">Department</a>

First included in: HRM/HcmPositionForecastEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Department attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Description name="Description">Description</a>

First included in: HRM/HcmPositionForecastEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Description attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Job name="Job">Job</a>

First included in: HRM/HcmPositionForecastEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Job attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PositionType name="PositionType">PositionType</a>

First included in: HRM/HcmPositionForecastEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PositionType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Title name="Title">Title</a>

First included in: HRM/HcmPositionForecastEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Title attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CompLocation name="CompLocation">CompLocation</a>

First included in: HRM/HcmPositionForecastEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CompLocation attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#JobId name="JobId">JobId</a>

First included in: HRM/HcmPositionForecastEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the JobId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DepartmentNumber name="DepartmentNumber">DepartmentNumber</a>

First included in: HRM/HcmPositionForecastEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Department number</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DepartmentNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Department number</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CompensationRegionId name="CompensationRegionId">CompensationRegionId</a>

First included in: HRM/HcmPositionForecastEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Compensation region</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CompensationRegionId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Compensation region</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PositionTypeId name="PositionTypeId">PositionTypeId</a>

First included in: HRM/HcmPositionForecastEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PositionTypeId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TitleId name="TitleId">TitleId</a>

First included in: HRM/HcmPositionForecastEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TitleId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CompensationLevelId name="CompensationLevelId">CompensationLevelId</a>

First included in: HRM/HcmPositionForecastEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CompensationLevelId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_MainAccountCombinationsRelationshipId name="Relationship_MainAccountCombinationsRelationshipId">Relationship_MainAccountCombinationsRelationshipId</a>

First included in: HRM/HcmPositionForecastEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_MainAccountCombinationsRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td>empty table</td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BackingTable_HcmPositionForecastBudgetAcctLineRelationshipId name="BackingTable_HcmPositionForecastBudgetAcctLineRelationshipId">BackingTable_HcmPositionForecastBudgetAcctLineRelationshipId</a>

First included in: HRM/HcmPositionForecastEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_HcmPositionForecastBudgetAcctLineRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/Finance/Budget/Group/HcmPositionForecastBudgetAcctLine.md" target="_blank">/core/operationsCommon/Tables/Finance/Budget/Group/HcmPositionForecastBudgetAcctLine.cdm.json/HcmPositionForecastBudgetAcctLine</a></td><td><a href="../../../Tables/Finance/Budget/Group/HcmPositionForecastBudgetAcctLine.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>
