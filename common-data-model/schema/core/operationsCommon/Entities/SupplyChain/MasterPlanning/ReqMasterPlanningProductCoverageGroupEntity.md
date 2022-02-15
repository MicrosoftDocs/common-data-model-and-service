---
title: ReqMasterPlanningProductCoverageGroupEntity in MasterPlanning - Common Data Model | Microsoft Docs
description: undefined
author: llawwaii

ms.reviewer: deonhe
ms.topic: article
ms.date: 8/7/2020
ms.author: weiluo
---

# Item coverage groups in MasterPlanning(ReqMasterPlanningProductCoverageGroupEntity)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/SupplyChain/MasterPlanning/ReqMasterPlanningProductCoverageGroupEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.1"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Item coverage groups</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[GroupId](#GroupId)||<a href="ReqMasterPlanningProductCoverageGroupEntity.md" target="_blank">MasterPlanning/ReqMasterPlanningProductCoverageGroupEntity</a>|
|[GroupName](#GroupName)||<a href="ReqMasterPlanningProductCoverageGroupEntity.md" target="_blank">MasterPlanning/ReqMasterPlanningProductCoverageGroupEntity</a>|
|[WorkCalendarId](#WorkCalendarId)||<a href="ReqMasterPlanningProductCoverageGroupEntity.md" target="_blank">MasterPlanning/ReqMasterPlanningProductCoverageGroupEntity</a>|
|[CoverageMethod](#CoverageMethod)||<a href="ReqMasterPlanningProductCoverageGroupEntity.md" target="_blank">MasterPlanning/ReqMasterPlanningProductCoverageGroupEntity</a>|
|[CoveragePeriodDays](#CoveragePeriodDays)||<a href="ReqMasterPlanningProductCoverageGroupEntity.md" target="_blank">MasterPlanning/ReqMasterPlanningProductCoverageGroupEntity</a>|
|[CoverageTimeFenceDays](#CoverageTimeFenceDays)||<a href="ReqMasterPlanningProductCoverageGroupEntity.md" target="_blank">MasterPlanning/ReqMasterPlanningProductCoverageGroupEntity</a>|
|[NegativeDays](#NegativeDays)||<a href="ReqMasterPlanningProductCoverageGroupEntity.md" target="_blank">MasterPlanning/ReqMasterPlanningProductCoverageGroupEntity</a>|
|[PositiveDays](#PositiveDays)||<a href="ReqMasterPlanningProductCoverageGroupEntity.md" target="_blank">MasterPlanning/ReqMasterPlanningProductCoverageGroupEntity</a>|
|[OnHandInventoryConsumptionStrategy](#OnHandInventoryConsumptionStrategy)||<a href="ReqMasterPlanningProductCoverageGroupEntity.md" target="_blank">MasterPlanning/ReqMasterPlanningProductCoverageGroupEntity</a>|
|[UseSpecifiedBOMOrFormulaVersion](#UseSpecifiedBOMOrFormulaVersion)||<a href="ReqMasterPlanningProductCoverageGroupEntity.md" target="_blank">MasterPlanning/ReqMasterPlanningProductCoverageGroupEntity</a>|
|[UseSpecifiedRouteVersion](#UseSpecifiedRouteVersion)||<a href="ReqMasterPlanningProductCoverageGroupEntity.md" target="_blank">MasterPlanning/ReqMasterPlanningProductCoverageGroupEntity</a>|
|[PeriodTemplateId](#PeriodTemplateId)||<a href="ReqMasterPlanningProductCoverageGroupEntity.md" target="_blank">MasterPlanning/ReqMasterPlanningProductCoverageGroupEntity</a>|
|[RequestedProductionStatus](#RequestedProductionStatus)||<a href="ReqMasterPlanningProductCoverageGroupEntity.md" target="_blank">MasterPlanning/ReqMasterPlanningProductCoverageGroupEntity</a>|
|[AutomaticFirmingTimeFenceDays](#AutomaticFirmingTimeFenceDays)||<a href="ReqMasterPlanningProductCoverageGroupEntity.md" target="_blank">MasterPlanning/ReqMasterPlanningProductCoverageGroupEntity</a>|
|[FreezeTimeFenceDays](#FreezeTimeFenceDays)||<a href="ReqMasterPlanningProductCoverageGroupEntity.md" target="_blank">MasterPlanning/ReqMasterPlanningProductCoverageGroupEntity</a>|
|[BOMOrFormulaExplosionTimeFenceDays](#BOMOrFormulaExplosionTimeFenceDays)||<a href="ReqMasterPlanningProductCoverageGroupEntity.md" target="_blank">MasterPlanning/ReqMasterPlanningProductCoverageGroupEntity</a>|
|[CapacitySchedulingTimeFenceDays](#CapacitySchedulingTimeFenceDays)||<a href="ReqMasterPlanningProductCoverageGroupEntity.md" target="_blank">MasterPlanning/ReqMasterPlanningProductCoverageGroupEntity</a>|
|[ApprovedRequisitionTimeFenceDays](#ApprovedRequisitionTimeFenceDays)||<a href="ReqMasterPlanningProductCoverageGroupEntity.md" target="_blank">MasterPlanning/ReqMasterPlanningProductCoverageGroupEntity</a>|
|[ForecastDemandPlanTimeFenceDays](#ForecastDemandPlanTimeFenceDays)||<a href="ReqMasterPlanningProductCoverageGroupEntity.md" target="_blank">MasterPlanning/ReqMasterPlanningProductCoverageGroupEntity</a>|
|[ForecastReductionKeyId](#ForecastReductionKeyId)||<a href="ReqMasterPlanningProductCoverageGroupEntity.md" target="_blank">MasterPlanning/ReqMasterPlanningProductCoverageGroupEntity</a>|
|[ForecastReductionMethod](#ForecastReductionMethod)||<a href="ReqMasterPlanningProductCoverageGroupEntity.md" target="_blank">MasterPlanning/ReqMasterPlanningProductCoverageGroupEntity</a>|
|[WillDemandForecastIncludeIntercompanyOrders](#WillDemandForecastIncludeIntercompanyOrders)||<a href="ReqMasterPlanningProductCoverageGroupEntity.md" target="_blank">MasterPlanning/ReqMasterPlanningProductCoverageGroupEntity</a>|
|[WillDemandForecastIncludeCustomerForecast](#WillDemandForecastIncludeCustomerForecast)||<a href="ReqMasterPlanningProductCoverageGroupEntity.md" target="_blank">MasterPlanning/ReqMasterPlanningProductCoverageGroupEntity</a>|
|[ReceiptSafetyMarginDays](#ReceiptSafetyMarginDays)||<a href="ReqMasterPlanningProductCoverageGroupEntity.md" target="_blank">MasterPlanning/ReqMasterPlanningProductCoverageGroupEntity</a>|
|[IssueSafetyMarginDays](#IssueSafetyMarginDays)||<a href="ReqMasterPlanningProductCoverageGroupEntity.md" target="_blank">MasterPlanning/ReqMasterPlanningProductCoverageGroupEntity</a>|
|[ReorderSafetyMarginDay](#ReorderSafetyMarginDay)||<a href="ReqMasterPlanningProductCoverageGroupEntity.md" target="_blank">MasterPlanning/ReqMasterPlanningProductCoverageGroupEntity</a>|
|[IsActionMessageEnabled](#IsActionMessageEnabled)||<a href="ReqMasterPlanningProductCoverageGroupEntity.md" target="_blank">MasterPlanning/ReqMasterPlanningProductCoverageGroupEntity</a>|
|[ActionTimeFenceDays](#ActionTimeFenceDays)||<a href="ReqMasterPlanningProductCoverageGroupEntity.md" target="_blank">MasterPlanning/ReqMasterPlanningProductCoverageGroupEntity</a>|
|[MaximumPostponeMarginDays](#MaximumPostponeMarginDays)||<a href="ReqMasterPlanningProductCoverageGroupEntity.md" target="_blank">MasterPlanning/ReqMasterPlanningProductCoverageGroupEntity</a>|
|[MaximumAdvanceMarginDays](#MaximumAdvanceMarginDays)||<a href="ReqMasterPlanningProductCoverageGroupEntity.md" target="_blank">MasterPlanning/ReqMasterPlanningProductCoverageGroupEntity</a>|
|[ActionBasisDateType](#ActionBasisDateType)||<a href="ReqMasterPlanningProductCoverageGroupEntity.md" target="_blank">MasterPlanning/ReqMasterPlanningProductCoverageGroupEntity</a>|
|[IsAdvanceActionEnabled](#IsAdvanceActionEnabled)||<a href="ReqMasterPlanningProductCoverageGroupEntity.md" target="_blank">MasterPlanning/ReqMasterPlanningProductCoverageGroupEntity</a>|
|[IsPostponeActionEnabled](#IsPostponeActionEnabled)||<a href="ReqMasterPlanningProductCoverageGroupEntity.md" target="_blank">MasterPlanning/ReqMasterPlanningProductCoverageGroupEntity</a>|
|[IsActionDecreaseEnabled](#IsActionDecreaseEnabled)||<a href="ReqMasterPlanningProductCoverageGroupEntity.md" target="_blank">MasterPlanning/ReqMasterPlanningProductCoverageGroupEntity</a>|
|[IsActionIncreaseEnabled](#IsActionIncreaseEnabled)||<a href="ReqMasterPlanningProductCoverageGroupEntity.md" target="_blank">MasterPlanning/ReqMasterPlanningProductCoverageGroupEntity</a>|
|[AreDerivedActionsEnabled](#AreDerivedActionsEnabled)||<a href="ReqMasterPlanningProductCoverageGroupEntity.md" target="_blank">MasterPlanning/ReqMasterPlanningProductCoverageGroupEntity</a>|
|[IsDelayCalculationEnabled](#IsDelayCalculationEnabled)||<a href="ReqMasterPlanningProductCoverageGroupEntity.md" target="_blank">MasterPlanning/ReqMasterPlanningProductCoverageGroupEntity</a>|
|[CalculateDelayTimeFenceDays](#CalculateDelayTimeFenceDays)||<a href="ReqMasterPlanningProductCoverageGroupEntity.md" target="_blank">MasterPlanning/ReqMasterPlanningProductCoverageGroupEntity</a>|
|[PeriodTemplate](#PeriodTemplate)||<a href="ReqMasterPlanningProductCoverageGroupEntity.md" target="_blank">MasterPlanning/ReqMasterPlanningProductCoverageGroupEntity</a>|
|[BackingTable_ReqGroupRelationshipId](#BackingTable_ReqGroupRelationshipId)||<a href="ReqMasterPlanningProductCoverageGroupEntity.md" target="_blank">MasterPlanning/ReqMasterPlanningProductCoverageGroupEntity</a>|
|[Relationship_PrimaryCompanyContextRelationshipId](#Relationship_PrimaryCompanyContextRelationshipId)||<a href="ReqMasterPlanningProductCoverageGroupEntity.md" target="_blank">MasterPlanning/ReqMasterPlanningProductCoverageGroupEntity</a>|

### <a href=#GroupId name="GroupId">GroupId</a>

First included in: MasterPlanning/ReqMasterPlanningProductCoverageGroupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the GroupId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#GroupName name="GroupName">GroupName</a>

First included in: MasterPlanning/ReqMasterPlanningProductCoverageGroupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the GroupName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WorkCalendarId name="WorkCalendarId">WorkCalendarId</a>

First included in: MasterPlanning/ReqMasterPlanningProductCoverageGroupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WorkCalendarId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CoverageMethod name="CoverageMethod">CoverageMethod</a>

First included in: MasterPlanning/ReqMasterPlanningProductCoverageGroupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CoverageMethod attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CoveragePeriodDays name="CoveragePeriodDays">CoveragePeriodDays</a>

First included in: MasterPlanning/ReqMasterPlanningProductCoverageGroupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CoveragePeriodDays attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CoverageTimeFenceDays name="CoverageTimeFenceDays">CoverageTimeFenceDays</a>

First included in: MasterPlanning/ReqMasterPlanningProductCoverageGroupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CoverageTimeFenceDays attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#NegativeDays name="NegativeDays">NegativeDays</a>

First included in: MasterPlanning/ReqMasterPlanningProductCoverageGroupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the NegativeDays attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PositiveDays name="PositiveDays">PositiveDays</a>

First included in: MasterPlanning/ReqMasterPlanningProductCoverageGroupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PositiveDays attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#OnHandInventoryConsumptionStrategy name="OnHandInventoryConsumptionStrategy">OnHandInventoryConsumptionStrategy</a>

First included in: MasterPlanning/ReqMasterPlanningProductCoverageGroupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OnHandInventoryConsumptionStrategy attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#UseSpecifiedBOMOrFormulaVersion name="UseSpecifiedBOMOrFormulaVersion">UseSpecifiedBOMOrFormulaVersion</a>

First included in: MasterPlanning/ReqMasterPlanningProductCoverageGroupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the UseSpecifiedBOMOrFormulaVersion attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#UseSpecifiedRouteVersion name="UseSpecifiedRouteVersion">UseSpecifiedRouteVersion</a>

First included in: MasterPlanning/ReqMasterPlanningProductCoverageGroupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the UseSpecifiedRouteVersion attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PeriodTemplateId name="PeriodTemplateId">PeriodTemplateId</a>

First included in: MasterPlanning/ReqMasterPlanningProductCoverageGroupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PeriodTemplateId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RequestedProductionStatus name="RequestedProductionStatus">RequestedProductionStatus</a>

First included in: MasterPlanning/ReqMasterPlanningProductCoverageGroupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RequestedProductionStatus attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AutomaticFirmingTimeFenceDays name="AutomaticFirmingTimeFenceDays">AutomaticFirmingTimeFenceDays</a>

First included in: MasterPlanning/ReqMasterPlanningProductCoverageGroupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AutomaticFirmingTimeFenceDays attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FreezeTimeFenceDays name="FreezeTimeFenceDays">FreezeTimeFenceDays</a>

First included in: MasterPlanning/ReqMasterPlanningProductCoverageGroupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FreezeTimeFenceDays attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BOMOrFormulaExplosionTimeFenceDays name="BOMOrFormulaExplosionTimeFenceDays">BOMOrFormulaExplosionTimeFenceDays</a>

First included in: MasterPlanning/ReqMasterPlanningProductCoverageGroupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BOMOrFormulaExplosionTimeFenceDays attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CapacitySchedulingTimeFenceDays name="CapacitySchedulingTimeFenceDays">CapacitySchedulingTimeFenceDays</a>

First included in: MasterPlanning/ReqMasterPlanningProductCoverageGroupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CapacitySchedulingTimeFenceDays attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ApprovedRequisitionTimeFenceDays name="ApprovedRequisitionTimeFenceDays">ApprovedRequisitionTimeFenceDays</a>

First included in: MasterPlanning/ReqMasterPlanningProductCoverageGroupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ApprovedRequisitionTimeFenceDays attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ForecastDemandPlanTimeFenceDays name="ForecastDemandPlanTimeFenceDays">ForecastDemandPlanTimeFenceDays</a>

First included in: MasterPlanning/ReqMasterPlanningProductCoverageGroupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ForecastDemandPlanTimeFenceDays attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ForecastReductionKeyId name="ForecastReductionKeyId">ForecastReductionKeyId</a>

First included in: MasterPlanning/ReqMasterPlanningProductCoverageGroupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ForecastReductionKeyId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ForecastReductionMethod name="ForecastReductionMethod">ForecastReductionMethod</a>

First included in: MasterPlanning/ReqMasterPlanningProductCoverageGroupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ForecastReductionMethod attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WillDemandForecastIncludeIntercompanyOrders name="WillDemandForecastIncludeIntercompanyOrders">WillDemandForecastIncludeIntercompanyOrders</a>

First included in: MasterPlanning/ReqMasterPlanningProductCoverageGroupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WillDemandForecastIncludeIntercompanyOrders attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WillDemandForecastIncludeCustomerForecast name="WillDemandForecastIncludeCustomerForecast">WillDemandForecastIncludeCustomerForecast</a>

First included in: MasterPlanning/ReqMasterPlanningProductCoverageGroupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WillDemandForecastIncludeCustomerForecast attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ReceiptSafetyMarginDays name="ReceiptSafetyMarginDays">ReceiptSafetyMarginDays</a>

First included in: MasterPlanning/ReqMasterPlanningProductCoverageGroupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReceiptSafetyMarginDays attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IssueSafetyMarginDays name="IssueSafetyMarginDays">IssueSafetyMarginDays</a>

First included in: MasterPlanning/ReqMasterPlanningProductCoverageGroupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IssueSafetyMarginDays attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ReorderSafetyMarginDay name="ReorderSafetyMarginDay">ReorderSafetyMarginDay</a>

First included in: MasterPlanning/ReqMasterPlanningProductCoverageGroupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReorderSafetyMarginDay attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsActionMessageEnabled name="IsActionMessageEnabled">IsActionMessageEnabled</a>

First included in: MasterPlanning/ReqMasterPlanningProductCoverageGroupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsActionMessageEnabled attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ActionTimeFenceDays name="ActionTimeFenceDays">ActionTimeFenceDays</a>

First included in: MasterPlanning/ReqMasterPlanningProductCoverageGroupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ActionTimeFenceDays attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MaximumPostponeMarginDays name="MaximumPostponeMarginDays">MaximumPostponeMarginDays</a>

First included in: MasterPlanning/ReqMasterPlanningProductCoverageGroupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MaximumPostponeMarginDays attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MaximumAdvanceMarginDays name="MaximumAdvanceMarginDays">MaximumAdvanceMarginDays</a>

First included in: MasterPlanning/ReqMasterPlanningProductCoverageGroupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MaximumAdvanceMarginDays attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ActionBasisDateType name="ActionBasisDateType">ActionBasisDateType</a>

First included in: MasterPlanning/ReqMasterPlanningProductCoverageGroupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ActionBasisDateType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsAdvanceActionEnabled name="IsAdvanceActionEnabled">IsAdvanceActionEnabled</a>

First included in: MasterPlanning/ReqMasterPlanningProductCoverageGroupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsAdvanceActionEnabled attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsPostponeActionEnabled name="IsPostponeActionEnabled">IsPostponeActionEnabled</a>

First included in: MasterPlanning/ReqMasterPlanningProductCoverageGroupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsPostponeActionEnabled attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsActionDecreaseEnabled name="IsActionDecreaseEnabled">IsActionDecreaseEnabled</a>

First included in: MasterPlanning/ReqMasterPlanningProductCoverageGroupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsActionDecreaseEnabled attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsActionIncreaseEnabled name="IsActionIncreaseEnabled">IsActionIncreaseEnabled</a>

First included in: MasterPlanning/ReqMasterPlanningProductCoverageGroupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsActionIncreaseEnabled attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AreDerivedActionsEnabled name="AreDerivedActionsEnabled">AreDerivedActionsEnabled</a>

First included in: MasterPlanning/ReqMasterPlanningProductCoverageGroupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AreDerivedActionsEnabled attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsDelayCalculationEnabled name="IsDelayCalculationEnabled">IsDelayCalculationEnabled</a>

First included in: MasterPlanning/ReqMasterPlanningProductCoverageGroupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsDelayCalculationEnabled attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CalculateDelayTimeFenceDays name="CalculateDelayTimeFenceDays">CalculateDelayTimeFenceDays</a>

First included in: MasterPlanning/ReqMasterPlanningProductCoverageGroupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CalculateDelayTimeFenceDays attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PeriodTemplate name="PeriodTemplate">PeriodTemplate</a>

First included in: MasterPlanning/ReqMasterPlanningProductCoverageGroupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PeriodTemplate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BackingTable_ReqGroupRelationshipId name="BackingTable_ReqGroupRelationshipId">BackingTable_ReqGroupRelationshipId</a>

First included in: MasterPlanning/ReqMasterPlanningProductCoverageGroupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_ReqGroupRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/SupplyChain/MasterPlanning/Group/ReqGroup.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/MasterPlanning/Group/ReqGroup.cdm.json/ReqGroup</a></td><td><a href="../../../Tables/SupplyChain/MasterPlanning/Group/ReqGroup.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PrimaryCompanyContextRelationshipId name="Relationship_PrimaryCompanyContextRelationshipId">Relationship_PrimaryCompanyContextRelationshipId</a>

First included in: MasterPlanning/ReqMasterPlanningProductCoverageGroupEntity (this entity)  

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
