---
title: RouteGroupEntity in ProductionControl - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 7/7/2020
ms.author: nebanfic
---

# Route groups in ProductionControl

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/SupplyChain/ProductionControl/RouteGroupEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Route groups</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[GroupId](#GroupId)||<a href="RouteGroupEntity.md" target="_blank">ProductionControl/RouteGroupEntity</a>|
|[GroupName](#GroupName)||<a href="RouteGroupEntity.md" target="_blank">ProductionControl/RouteGroupEntity</a>|
|[WillProductionEstimationAndCostingUseSetupTimeAndSetupCategory](#WillProductionEstimationAndCostingUseSetupTimeAndSetupCategory)||<a href="RouteGroupEntity.md" target="_blank">ProductionControl/RouteGroupEntity</a>|
|[WillProductionEstimationAndCostingUseProcessTimeAndProcessCategory](#WillProductionEstimationAndCostingUseProcessTimeAndProcessCategory)||<a href="RouteGroupEntity.md" target="_blank">ProductionControl/RouteGroupEntity</a>|
|[WillProductionEstimationAndCostingUseQuantityAndQuantityCategory](#WillProductionEstimationAndCostingUseQuantityAndQuantityCategory)||<a href="RouteGroupEntity.md" target="_blank">ProductionControl/RouteGroupEntity</a>|
|[WillAutomaticRouteConsumptionUseSetupTime](#WillAutomaticRouteConsumptionUseSetupTime)||<a href="RouteGroupEntity.md" target="_blank">ProductionControl/RouteGroupEntity</a>|
|[WillAutomaticRouteConsumptionUseProcessTime](#WillAutomaticRouteConsumptionUseProcessTime)||<a href="RouteGroupEntity.md" target="_blank">ProductionControl/RouteGroupEntity</a>|
|[WillAutomaticRouteConsumptionUseQuantity](#WillAutomaticRouteConsumptionUseQuantity)||<a href="RouteGroupEntity.md" target="_blank">ProductionControl/RouteGroupEntity</a>|
|[IsOperationManuallyReportedAsFinishedByDefault](#IsOperationManuallyReportedAsFinishedByDefault)||<a href="RouteGroupEntity.md" target="_blank">ProductionControl/RouteGroupEntity</a>|
|[IsQueueBeforeJobActive](#IsQueueBeforeJobActive)||<a href="RouteGroupEntity.md" target="_blank">ProductionControl/RouteGroupEntity</a>|
|[WillQueueBeforeJobSchedulingUseJobManagement](#WillQueueBeforeJobSchedulingUseJobManagement)||<a href="RouteGroupEntity.md" target="_blank">ProductionControl/RouteGroupEntity</a>|
|[WillQueueBeforeJobSchedulingUseWorkingTimeCalendar](#WillQueueBeforeJobSchedulingUseWorkingTimeCalendar)||<a href="RouteGroupEntity.md" target="_blank">ProductionControl/RouteGroupEntity</a>|
|[WillQueueBeforeJobSchedulingCreateResourceCapacityReservations](#WillQueueBeforeJobSchedulingCreateResourceCapacityReservations)||<a href="RouteGroupEntity.md" target="_blank">ProductionControl/RouteGroupEntity</a>|
|[IsSetupJobActive](#IsSetupJobActive)||<a href="RouteGroupEntity.md" target="_blank">ProductionControl/RouteGroupEntity</a>|
|[WillSetupJobSchedulingUseJobManagement](#WillSetupJobSchedulingUseJobManagement)||<a href="RouteGroupEntity.md" target="_blank">ProductionControl/RouteGroupEntity</a>|
|[WillSetupJobSchedulingUseWorkingTimeCalendar](#WillSetupJobSchedulingUseWorkingTimeCalendar)||<a href="RouteGroupEntity.md" target="_blank">ProductionControl/RouteGroupEntity</a>|
|[WillSetupJobSchedulingCreateResourceCapacityReservations](#WillSetupJobSchedulingCreateResourceCapacityReservations)||<a href="RouteGroupEntity.md" target="_blank">ProductionControl/RouteGroupEntity</a>|
|[IsProcessJobActive](#IsProcessJobActive)||<a href="RouteGroupEntity.md" target="_blank">ProductionControl/RouteGroupEntity</a>|
|[WillProcessJobSchedulingUseJobManagement](#WillProcessJobSchedulingUseJobManagement)||<a href="RouteGroupEntity.md" target="_blank">ProductionControl/RouteGroupEntity</a>|
|[WillProcessJobSchedulingUseWorkingTimeCalendar](#WillProcessJobSchedulingUseWorkingTimeCalendar)||<a href="RouteGroupEntity.md" target="_blank">ProductionControl/RouteGroupEntity</a>|
|[WillProcessJobSchedulingCreateResourceCapacityReservations](#WillProcessJobSchedulingCreateResourceCapacityReservations)||<a href="RouteGroupEntity.md" target="_blank">ProductionControl/RouteGroupEntity</a>|
|[IsOverlapJobActive](#IsOverlapJobActive)||<a href="RouteGroupEntity.md" target="_blank">ProductionControl/RouteGroupEntity</a>|
|[WillOverlapJobSchedulingUseJobManagement](#WillOverlapJobSchedulingUseJobManagement)||<a href="RouteGroupEntity.md" target="_blank">ProductionControl/RouteGroupEntity</a>|
|[WillOverlapJobSchedulingUseWorkingTimeCalendar](#WillOverlapJobSchedulingUseWorkingTimeCalendar)||<a href="RouteGroupEntity.md" target="_blank">ProductionControl/RouteGroupEntity</a>|
|[WillOverlapJobSchedulingCreateResourceCapacityReservations](#WillOverlapJobSchedulingCreateResourceCapacityReservations)||<a href="RouteGroupEntity.md" target="_blank">ProductionControl/RouteGroupEntity</a>|
|[IsTransportJobActive](#IsTransportJobActive)||<a href="RouteGroupEntity.md" target="_blank">ProductionControl/RouteGroupEntity</a>|
|[WillTransportJobSchedulingUseJobManagement](#WillTransportJobSchedulingUseJobManagement)||<a href="RouteGroupEntity.md" target="_blank">ProductionControl/RouteGroupEntity</a>|
|[WillTransportJobSchedulingUseWorkingTimeCalendar](#WillTransportJobSchedulingUseWorkingTimeCalendar)||<a href="RouteGroupEntity.md" target="_blank">ProductionControl/RouteGroupEntity</a>|
|[WillTransportJobSchedulingCreateResourceCapacityReservations](#WillTransportJobSchedulingCreateResourceCapacityReservations)||<a href="RouteGroupEntity.md" target="_blank">ProductionControl/RouteGroupEntity</a>|
|[IsQueuAfterJobActive](#IsQueuAfterJobActive)||<a href="RouteGroupEntity.md" target="_blank">ProductionControl/RouteGroupEntity</a>|
|[WillQueueAfterJobSchedulingUseJobManagement](#WillQueueAfterJobSchedulingUseJobManagement)||<a href="RouteGroupEntity.md" target="_blank">ProductionControl/RouteGroupEntity</a>|
|[WillQueueAfterJobSchedulingUseWorkingTimeCalendar](#WillQueueAfterJobSchedulingUseWorkingTimeCalendar)||<a href="RouteGroupEntity.md" target="_blank">ProductionControl/RouteGroupEntity</a>|
|[WillQueueAfterJobSchedulingCreateResourceCapacityReservations](#WillQueueAfterJobSchedulingCreateResourceCapacityReservations)||<a href="RouteGroupEntity.md" target="_blank">ProductionControl/RouteGroupEntity</a>|
|[BackingTable_RouteGroupRelationshipId](#BackingTable_RouteGroupRelationshipId)||<a href="RouteGroupEntity.md" target="_blank">ProductionControl/RouteGroupEntity</a>|
|[Relationship_PrimaryCompanyContextRelationshipId](#Relationship_PrimaryCompanyContextRelationshipId)||<a href="RouteGroupEntity.md" target="_blank">ProductionControl/RouteGroupEntity</a>|

### <a href=#GroupId name="GroupId">GroupId</a>

First included in: ProductionControl/RouteGroupEntity (this entity)  

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

First included in: ProductionControl/RouteGroupEntity (this entity)  

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

### <a href=#WillProductionEstimationAndCostingUseSetupTimeAndSetupCategory name="WillProductionEstimationAndCostingUseSetupTimeAndSetupCategory">WillProductionEstimationAndCostingUseSetupTimeAndSetupCategory</a>

First included in: ProductionControl/RouteGroupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WillProductionEstimationAndCostingUseSetupTimeAndSetupCategory attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WillProductionEstimationAndCostingUseProcessTimeAndProcessCategory name="WillProductionEstimationAndCostingUseProcessTimeAndProcessCategory">WillProductionEstimationAndCostingUseProcessTimeAndProcessCategory</a>

First included in: ProductionControl/RouteGroupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WillProductionEstimationAndCostingUseProcessTimeAndProcessCategory attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WillProductionEstimationAndCostingUseQuantityAndQuantityCategory name="WillProductionEstimationAndCostingUseQuantityAndQuantityCategory">WillProductionEstimationAndCostingUseQuantityAndQuantityCategory</a>

First included in: ProductionControl/RouteGroupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WillProductionEstimationAndCostingUseQuantityAndQuantityCategory attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WillAutomaticRouteConsumptionUseSetupTime name="WillAutomaticRouteConsumptionUseSetupTime">WillAutomaticRouteConsumptionUseSetupTime</a>

First included in: ProductionControl/RouteGroupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WillAutomaticRouteConsumptionUseSetupTime attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WillAutomaticRouteConsumptionUseProcessTime name="WillAutomaticRouteConsumptionUseProcessTime">WillAutomaticRouteConsumptionUseProcessTime</a>

First included in: ProductionControl/RouteGroupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WillAutomaticRouteConsumptionUseProcessTime attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WillAutomaticRouteConsumptionUseQuantity name="WillAutomaticRouteConsumptionUseQuantity">WillAutomaticRouteConsumptionUseQuantity</a>

First included in: ProductionControl/RouteGroupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WillAutomaticRouteConsumptionUseQuantity attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsOperationManuallyReportedAsFinishedByDefault name="IsOperationManuallyReportedAsFinishedByDefault">IsOperationManuallyReportedAsFinishedByDefault</a>

First included in: ProductionControl/RouteGroupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsOperationManuallyReportedAsFinishedByDefault attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsQueueBeforeJobActive name="IsQueueBeforeJobActive">IsQueueBeforeJobActive</a>

First included in: ProductionControl/RouteGroupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsQueueBeforeJobActive attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WillQueueBeforeJobSchedulingUseJobManagement name="WillQueueBeforeJobSchedulingUseJobManagement">WillQueueBeforeJobSchedulingUseJobManagement</a>

First included in: ProductionControl/RouteGroupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WillQueueBeforeJobSchedulingUseJobManagement attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WillQueueBeforeJobSchedulingUseWorkingTimeCalendar name="WillQueueBeforeJobSchedulingUseWorkingTimeCalendar">WillQueueBeforeJobSchedulingUseWorkingTimeCalendar</a>

First included in: ProductionControl/RouteGroupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WillQueueBeforeJobSchedulingUseWorkingTimeCalendar attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WillQueueBeforeJobSchedulingCreateResourceCapacityReservations name="WillQueueBeforeJobSchedulingCreateResourceCapacityReservations">WillQueueBeforeJobSchedulingCreateResourceCapacityReservations</a>

First included in: ProductionControl/RouteGroupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WillQueueBeforeJobSchedulingCreateResourceCapacityReservations attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsSetupJobActive name="IsSetupJobActive">IsSetupJobActive</a>

First included in: ProductionControl/RouteGroupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsSetupJobActive attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WillSetupJobSchedulingUseJobManagement name="WillSetupJobSchedulingUseJobManagement">WillSetupJobSchedulingUseJobManagement</a>

First included in: ProductionControl/RouteGroupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WillSetupJobSchedulingUseJobManagement attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WillSetupJobSchedulingUseWorkingTimeCalendar name="WillSetupJobSchedulingUseWorkingTimeCalendar">WillSetupJobSchedulingUseWorkingTimeCalendar</a>

First included in: ProductionControl/RouteGroupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WillSetupJobSchedulingUseWorkingTimeCalendar attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WillSetupJobSchedulingCreateResourceCapacityReservations name="WillSetupJobSchedulingCreateResourceCapacityReservations">WillSetupJobSchedulingCreateResourceCapacityReservations</a>

First included in: ProductionControl/RouteGroupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WillSetupJobSchedulingCreateResourceCapacityReservations attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsProcessJobActive name="IsProcessJobActive">IsProcessJobActive</a>

First included in: ProductionControl/RouteGroupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsProcessJobActive attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WillProcessJobSchedulingUseJobManagement name="WillProcessJobSchedulingUseJobManagement">WillProcessJobSchedulingUseJobManagement</a>

First included in: ProductionControl/RouteGroupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WillProcessJobSchedulingUseJobManagement attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WillProcessJobSchedulingUseWorkingTimeCalendar name="WillProcessJobSchedulingUseWorkingTimeCalendar">WillProcessJobSchedulingUseWorkingTimeCalendar</a>

First included in: ProductionControl/RouteGroupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WillProcessJobSchedulingUseWorkingTimeCalendar attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WillProcessJobSchedulingCreateResourceCapacityReservations name="WillProcessJobSchedulingCreateResourceCapacityReservations">WillProcessJobSchedulingCreateResourceCapacityReservations</a>

First included in: ProductionControl/RouteGroupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WillProcessJobSchedulingCreateResourceCapacityReservations attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsOverlapJobActive name="IsOverlapJobActive">IsOverlapJobActive</a>

First included in: ProductionControl/RouteGroupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsOverlapJobActive attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WillOverlapJobSchedulingUseJobManagement name="WillOverlapJobSchedulingUseJobManagement">WillOverlapJobSchedulingUseJobManagement</a>

First included in: ProductionControl/RouteGroupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WillOverlapJobSchedulingUseJobManagement attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WillOverlapJobSchedulingUseWorkingTimeCalendar name="WillOverlapJobSchedulingUseWorkingTimeCalendar">WillOverlapJobSchedulingUseWorkingTimeCalendar</a>

First included in: ProductionControl/RouteGroupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WillOverlapJobSchedulingUseWorkingTimeCalendar attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WillOverlapJobSchedulingCreateResourceCapacityReservations name="WillOverlapJobSchedulingCreateResourceCapacityReservations">WillOverlapJobSchedulingCreateResourceCapacityReservations</a>

First included in: ProductionControl/RouteGroupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WillOverlapJobSchedulingCreateResourceCapacityReservations attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsTransportJobActive name="IsTransportJobActive">IsTransportJobActive</a>

First included in: ProductionControl/RouteGroupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsTransportJobActive attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WillTransportJobSchedulingUseJobManagement name="WillTransportJobSchedulingUseJobManagement">WillTransportJobSchedulingUseJobManagement</a>

First included in: ProductionControl/RouteGroupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WillTransportJobSchedulingUseJobManagement attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WillTransportJobSchedulingUseWorkingTimeCalendar name="WillTransportJobSchedulingUseWorkingTimeCalendar">WillTransportJobSchedulingUseWorkingTimeCalendar</a>

First included in: ProductionControl/RouteGroupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WillTransportJobSchedulingUseWorkingTimeCalendar attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WillTransportJobSchedulingCreateResourceCapacityReservations name="WillTransportJobSchedulingCreateResourceCapacityReservations">WillTransportJobSchedulingCreateResourceCapacityReservations</a>

First included in: ProductionControl/RouteGroupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WillTransportJobSchedulingCreateResourceCapacityReservations attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsQueuAfterJobActive name="IsQueuAfterJobActive">IsQueuAfterJobActive</a>

First included in: ProductionControl/RouteGroupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsQueuAfterJobActive attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WillQueueAfterJobSchedulingUseJobManagement name="WillQueueAfterJobSchedulingUseJobManagement">WillQueueAfterJobSchedulingUseJobManagement</a>

First included in: ProductionControl/RouteGroupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WillQueueAfterJobSchedulingUseJobManagement attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WillQueueAfterJobSchedulingUseWorkingTimeCalendar name="WillQueueAfterJobSchedulingUseWorkingTimeCalendar">WillQueueAfterJobSchedulingUseWorkingTimeCalendar</a>

First included in: ProductionControl/RouteGroupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WillQueueAfterJobSchedulingUseWorkingTimeCalendar attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WillQueueAfterJobSchedulingCreateResourceCapacityReservations name="WillQueueAfterJobSchedulingCreateResourceCapacityReservations">WillQueueAfterJobSchedulingCreateResourceCapacityReservations</a>

First included in: ProductionControl/RouteGroupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WillQueueAfterJobSchedulingCreateResourceCapacityReservations attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BackingTable_RouteGroupRelationshipId name="BackingTable_RouteGroupRelationshipId">BackingTable_RouteGroupRelationshipId</a>

First included in: ProductionControl/RouteGroupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_RouteGroupRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/SupplyChain/ProductionControl/Group/RouteGroup.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/ProductionControl/Group/RouteGroup.cdm.json/RouteGroup</a></td><td><a href="../../../Tables/SupplyChain/ProductionControl/Group/RouteGroup.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PrimaryCompanyContextRelationshipId name="Relationship_PrimaryCompanyContextRelationshipId">Relationship_PrimaryCompanyContextRelationshipId</a>

First included in: ProductionControl/RouteGroupEntity (this entity)  

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
