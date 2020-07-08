---
title: ProdProductionOrderRouteOperationEntity in ProductionControl - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 7/8/2020
ms.author: nebanfic
---

# Production route operations in ProductionControl(ProdProductionOrderRouteOperationEntity)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/SupplyChain/ProductionControl/ProdProductionOrderRouteOperationEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Production route operations</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[AccumulatedScrapPercentage](#AccumulatedScrapPercentage)||<a href="ProdProductionOrderRouteOperationEntity.md" target="_blank">ProductionControl/ProdProductionOrderRouteOperationEntity</a>|
|[CostingOperationResourceId](#CostingOperationResourceId)||<a href="ProdProductionOrderRouteOperationEntity.md" target="_blank">ProductionControl/ProdProductionOrderRouteOperationEntity</a>|
|[DefaultLedgerDimensionDisplayValue](#DefaultLedgerDimensionDisplayValue)||<a href="ProdProductionOrderRouteOperationEntity.md" target="_blank">ProductionControl/ProdProductionOrderRouteOperationEntity</a>|
|[DefaultLedgerDimension](#DefaultLedgerDimension)||<a href="ProdProductionOrderRouteOperationEntity.md" target="_blank">ProductionControl/ProdProductionOrderRouteOperationEntity</a>|
|[EstimatedProcessTime](#EstimatedProcessTime)||<a href="ProdProductionOrderRouteOperationEntity.md" target="_blank">ProductionControl/ProdProductionOrderRouteOperationEntity</a>|
|[EstimatedOperationQuantity](#EstimatedOperationQuantity)||<a href="ProdProductionOrderRouteOperationEntity.md" target="_blank">ProductionControl/ProdProductionOrderRouteOperationEntity</a>|
|[EstimatedSetupTime](#EstimatedSetupTime)||<a href="ProdProductionOrderRouteOperationEntity.md" target="_blank">ProductionControl/ProdProductionOrderRouteOperationEntity</a>|
|[IsConstantConsumptionReleased](#IsConstantConsumptionReleased)||<a href="ProdProductionOrderRouteOperationEntity.md" target="_blank">ProductionControl/ProdProductionOrderRouteOperationEntity</a>|
|[IsOperationCompleted](#IsOperationCompleted)||<a href="ProdProductionOrderRouteOperationEntity.md" target="_blank">ProductionControl/ProdProductionOrderRouteOperationEntity</a>|
|[IsOperationStarted](#IsOperationStarted)||<a href="ProdProductionOrderRouteOperationEntity.md" target="_blank">ProductionControl/ProdProductionOrderRouteOperationEntity</a>|
|[NextOperationLinkType](#NextOperationLinkType)||<a href="ProdProductionOrderRouteOperationEntity.md" target="_blank">ProductionControl/ProdProductionOrderRouteOperationEntity</a>|
|[NextOperationNumber](#NextOperationNumber)||<a href="ProdProductionOrderRouteOperationEntity.md" target="_blank">ProductionControl/ProdProductionOrderRouteOperationEntity</a>|
|[OperationId](#OperationId)||<a href="ProdProductionOrderRouteOperationEntity.md" target="_blank">ProductionControl/ProdProductionOrderRouteOperationEntity</a>|
|[OperationNumber](#OperationNumber)||<a href="ProdProductionOrderRouteOperationEntity.md" target="_blank">ProductionControl/ProdProductionOrderRouteOperationEntity</a>|
|[OperationPriority](#OperationPriority)||<a href="ProdProductionOrderRouteOperationEntity.md" target="_blank">ProductionControl/ProdProductionOrderRouteOperationEntity</a>|
|[OperationsTimeToHourConversionFactor](#OperationsTimeToHourConversionFactor)||<a href="ProdProductionOrderRouteOperationEntity.md" target="_blank">ProductionControl/ProdProductionOrderRouteOperationEntity</a>|
|[OverlapOperationQuantity](#OverlapOperationQuantity)||<a href="ProdProductionOrderRouteOperationEntity.md" target="_blank">ProductionControl/ProdProductionOrderRouteOperationEntity</a>|
|[ProcessCostCategoryId](#ProcessCostCategoryId)||<a href="ProdProductionOrderRouteOperationEntity.md" target="_blank">ProductionControl/ProdProductionOrderRouteOperationEntity</a>|
|[ProcessQuantity](#ProcessQuantity)||<a href="ProdProductionOrderRouteOperationEntity.md" target="_blank">ProductionControl/ProdProductionOrderRouteOperationEntity</a>|
|[ProcessTime](#ProcessTime)||<a href="ProdProductionOrderRouteOperationEntity.md" target="_blank">ProductionControl/ProdProductionOrderRouteOperationEntity</a>|
|[ProductionOrderNumber](#ProductionOrderNumber)||<a href="ProdProductionOrderRouteOperationEntity.md" target="_blank">ProductionControl/ProdProductionOrderRouteOperationEntity</a>|
|[LineProductionOrderNumber](#LineProductionOrderNumber)||<a href="ProdProductionOrderRouteOperationEntity.md" target="_blank">ProductionControl/ProdProductionOrderRouteOperationEntity</a>|
|[ProcessProductionJobId](#ProcessProductionJobId)||<a href="ProdProductionOrderRouteOperationEntity.md" target="_blank">ProductionControl/ProdProductionOrderRouteOperationEntity</a>|
|[ProcessCompletionPercentage](#ProcessCompletionPercentage)||<a href="ProdProductionOrderRouteOperationEntity.md" target="_blank">ProductionControl/ProdProductionOrderRouteOperationEntity</a>|
|[LoadPercentage](#LoadPercentage)||<a href="ProdProductionOrderRouteOperationEntity.md" target="_blank">ProductionControl/ProdProductionOrderRouteOperationEntity</a>|
|[QuantityCostCategoryId](#QuantityCostCategoryId)||<a href="ProdProductionOrderRouteOperationEntity.md" target="_blank">ProductionControl/ProdProductionOrderRouteOperationEntity</a>|
|[QueueTimeAfter](#QueueTimeAfter)||<a href="ProdProductionOrderRouteOperationEntity.md" target="_blank">ProductionControl/ProdProductionOrderRouteOperationEntity</a>|
|[QueueTimeBefore](#QueueTimeBefore)||<a href="ProdProductionOrderRouteOperationEntity.md" target="_blank">ProductionControl/ProdProductionOrderRouteOperationEntity</a>|
|[ResourceQuantity](#ResourceQuantity)||<a href="ProdProductionOrderRouteOperationEntity.md" target="_blank">ProductionControl/ProdProductionOrderRouteOperationEntity</a>|
|[RouteGroupId](#RouteGroupId)||<a href="ProdProductionOrderRouteOperationEntity.md" target="_blank">ProductionControl/ProdProductionOrderRouteOperationEntity</a>|
|[RouteOperationRateMethod](#RouteOperationRateMethod)||<a href="ProdProductionOrderRouteOperationEntity.md" target="_blank">ProductionControl/ProdProductionOrderRouteOperationEntity</a>|
|[RouteOperationRemainderStatus](#RouteOperationRemainderStatus)||<a href="ProdProductionOrderRouteOperationEntity.md" target="_blank">ProductionControl/ProdProductionOrderRouteOperationEntity</a>|
|[RouteOperationSequence](#RouteOperationSequence)||<a href="ProdProductionOrderRouteOperationEntity.md" target="_blank">ProductionControl/ProdProductionOrderRouteOperationEntity</a>|
|[RouteType](#RouteType)||<a href="ProdProductionOrderRouteOperationEntity.md" target="_blank">ProductionControl/ProdProductionOrderRouteOperationEntity</a>|
|[ScheduledFromDate](#ScheduledFromDate)||<a href="ProdProductionOrderRouteOperationEntity.md" target="_blank">ProductionControl/ProdProductionOrderRouteOperationEntity</a>|
|[ScheduledFromTime](#ScheduledFromTime)||<a href="ProdProductionOrderRouteOperationEntity.md" target="_blank">ProductionControl/ProdProductionOrderRouteOperationEntity</a>|
|[SetupProductionJobId](#SetupProductionJobId)||<a href="ProdProductionOrderRouteOperationEntity.md" target="_blank">ProductionControl/ProdProductionOrderRouteOperationEntity</a>|
|[ScheduledEndDate](#ScheduledEndDate)||<a href="ProdProductionOrderRouteOperationEntity.md" target="_blank">ProductionControl/ProdProductionOrderRouteOperationEntity</a>|
|[ScheduledEndTime](#ScheduledEndTime)||<a href="ProdProductionOrderRouteOperationEntity.md" target="_blank">ProductionControl/ProdProductionOrderRouteOperationEntity</a>|
|[ScrapPercentage](#ScrapPercentage)||<a href="ProdProductionOrderRouteOperationEntity.md" target="_blank">ProductionControl/ProdProductionOrderRouteOperationEntity</a>|
|[SetupCompletionPercentage](#SetupCompletionPercentage)||<a href="ProdProductionOrderRouteOperationEntity.md" target="_blank">ProductionControl/ProdProductionOrderRouteOperationEntity</a>|
|[SetupCostCategoryId](#SetupCostCategoryId)||<a href="ProdProductionOrderRouteOperationEntity.md" target="_blank">ProductionControl/ProdProductionOrderRouteOperationEntity</a>|
|[SetupTime](#SetupTime)||<a href="ProdProductionOrderRouteOperationEntity.md" target="_blank">ProductionControl/ProdProductionOrderRouteOperationEntity</a>|
|[TransferBatchQuantity](#TransferBatchQuantity)||<a href="ProdProductionOrderRouteOperationEntity.md" target="_blank">ProductionControl/ProdProductionOrderRouteOperationEntity</a>|
|[TransitTime](#TransitTime)||<a href="ProdProductionOrderRouteOperationEntity.md" target="_blank">ProductionControl/ProdProductionOrderRouteOperationEntity</a>|
|[WorkingTimeSchedulingPropertyId](#WorkingTimeSchedulingPropertyId)||<a href="ProdProductionOrderRouteOperationEntity.md" target="_blank">ProductionControl/ProdProductionOrderRouteOperationEntity</a>|
|[WrkCtrActivityRequirementSetRecId](#WrkCtrActivityRequirementSetRecId)||<a href="ProdProductionOrderRouteOperationEntity.md" target="_blank">ProductionControl/ProdProductionOrderRouteOperationEntity</a>|
|[ActivityToCopyRecordId](#ActivityToCopyRecordId)||<a href="ProdProductionOrderRouteOperationEntity.md" target="_blank">ProductionControl/ProdProductionOrderRouteOperationEntity</a>|
|[Relationship_DefaultDimensionDimensionSetRelationshipId](#Relationship_DefaultDimensionDimensionSetRelationshipId)||<a href="ProdProductionOrderRouteOperationEntity.md" target="_blank">ProductionControl/ProdProductionOrderRouteOperationEntity</a>|
|[Relationship_ProductionOrderHeaderRelationshipId](#Relationship_ProductionOrderHeaderRelationshipId)||<a href="ProdProductionOrderRouteOperationEntity.md" target="_blank">ProductionControl/ProdProductionOrderRouteOperationEntity</a>|
|[BackingTable_ProdRouteRelationshipId](#BackingTable_ProdRouteRelationshipId)||<a href="ProdProductionOrderRouteOperationEntity.md" target="_blank">ProductionControl/ProdProductionOrderRouteOperationEntity</a>|
|[Relationship_PrimaryCompanyContextRelationshipId](#Relationship_PrimaryCompanyContextRelationshipId)||<a href="ProdProductionOrderRouteOperationEntity.md" target="_blank">ProductionControl/ProdProductionOrderRouteOperationEntity</a>|

### <a href=#AccumulatedScrapPercentage name="AccumulatedScrapPercentage">AccumulatedScrapPercentage</a>

First included in: ProductionControl/ProdProductionOrderRouteOperationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Accumulated scrap percentage</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AccumulatedScrapPercentage attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Accumulated scrap percentage</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CostingOperationResourceId name="CostingOperationResourceId">CostingOperationResourceId</a>

First included in: ProductionControl/ProdProductionOrderRouteOperationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CostingOperationResourceId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DefaultLedgerDimensionDisplayValue name="DefaultLedgerDimensionDisplayValue">DefaultLedgerDimensionDisplayValue</a>

First included in: ProductionControl/ProdProductionOrderRouteOperationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultLedgerDimensionDisplayValue attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DefaultLedgerDimension name="DefaultLedgerDimension">DefaultLedgerDimension</a>

First included in: ProductionControl/ProdProductionOrderRouteOperationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultLedgerDimension attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#EstimatedProcessTime name="EstimatedProcessTime">EstimatedProcessTime</a>

First included in: ProductionControl/ProdProductionOrderRouteOperationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Estimated process time</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EstimatedProcessTime attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Estimated process time</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#EstimatedOperationQuantity name="EstimatedOperationQuantity">EstimatedOperationQuantity</a>

First included in: ProductionControl/ProdProductionOrderRouteOperationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Estimated operation quantity</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EstimatedOperationQuantity attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Estimated operation quantity</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#EstimatedSetupTime name="EstimatedSetupTime">EstimatedSetupTime</a>

First included in: ProductionControl/ProdProductionOrderRouteOperationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EstimatedSetupTime attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsConstantConsumptionReleased name="IsConstantConsumptionReleased">IsConstantConsumptionReleased</a>

First included in: ProductionControl/ProdProductionOrderRouteOperationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsConstantConsumptionReleased attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsOperationCompleted name="IsOperationCompleted">IsOperationCompleted</a>

First included in: ProductionControl/ProdProductionOrderRouteOperationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Is operation completed</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsOperationCompleted attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Is operation completed</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsOperationStarted name="IsOperationStarted">IsOperationStarted</a>

First included in: ProductionControl/ProdProductionOrderRouteOperationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Is operation started</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsOperationStarted attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Is operation started</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#NextOperationLinkType name="NextOperationLinkType">NextOperationLinkType</a>

First included in: ProductionControl/ProdProductionOrderRouteOperationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Next operation link type</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the NextOperationLinkType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Next operation link type</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#NextOperationNumber name="NextOperationNumber">NextOperationNumber</a>

First included in: ProductionControl/ProdProductionOrderRouteOperationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Next operation number</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the NextOperationNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Next operation number</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#OperationId name="OperationId">OperationId</a>

First included in: ProductionControl/ProdProductionOrderRouteOperationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OperationId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#OperationNumber name="OperationNumber">OperationNumber</a>

First included in: ProductionControl/ProdProductionOrderRouteOperationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Operation number</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OperationNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Operation number</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#OperationPriority name="OperationPriority">OperationPriority</a>

First included in: ProductionControl/ProdProductionOrderRouteOperationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OperationPriority attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#OperationsTimeToHourConversionFactor name="OperationsTimeToHourConversionFactor">OperationsTimeToHourConversionFactor</a>

First included in: ProductionControl/ProdProductionOrderRouteOperationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OperationsTimeToHourConversionFactor attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#OverlapOperationQuantity name="OverlapOperationQuantity">OverlapOperationQuantity</a>

First included in: ProductionControl/ProdProductionOrderRouteOperationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OverlapOperationQuantity attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProcessCostCategoryId name="ProcessCostCategoryId">ProcessCostCategoryId</a>

First included in: ProductionControl/ProdProductionOrderRouteOperationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Process category id</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProcessCostCategoryId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Process category id</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProcessQuantity name="ProcessQuantity">ProcessQuantity</a>

First included in: ProductionControl/ProdProductionOrderRouteOperationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Process quantity</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProcessQuantity attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Process quantity</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProcessTime name="ProcessTime">ProcessTime</a>

First included in: ProductionControl/ProdProductionOrderRouteOperationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProcessTime attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProductionOrderNumber name="ProductionOrderNumber">ProductionOrderNumber</a>

First included in: ProductionControl/ProdProductionOrderRouteOperationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProductionOrderNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LineProductionOrderNumber name="LineProductionOrderNumber">LineProductionOrderNumber</a>

First included in: ProductionControl/ProdProductionOrderRouteOperationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LineProductionOrderNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProcessProductionJobId name="ProcessProductionJobId">ProcessProductionJobId</a>

First included in: ProductionControl/ProdProductionOrderRouteOperationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProcessProductionJobId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProcessCompletionPercentage name="ProcessCompletionPercentage">ProcessCompletionPercentage</a>

First included in: ProductionControl/ProdProductionOrderRouteOperationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProcessCompletionPercentage attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LoadPercentage name="LoadPercentage">LoadPercentage</a>

First included in: ProductionControl/ProdProductionOrderRouteOperationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Load percentage</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LoadPercentage attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Load percentage</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#QuantityCostCategoryId name="QuantityCostCategoryId">QuantityCostCategoryId</a>

First included in: ProductionControl/ProdProductionOrderRouteOperationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Quantity cost category id</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the QuantityCostCategoryId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Quantity cost category id</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#QueueTimeAfter name="QueueTimeAfter">QueueTimeAfter</a>

First included in: ProductionControl/ProdProductionOrderRouteOperationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the QueueTimeAfter attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#QueueTimeBefore name="QueueTimeBefore">QueueTimeBefore</a>

First included in: ProductionControl/ProdProductionOrderRouteOperationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the QueueTimeBefore attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ResourceQuantity name="ResourceQuantity">ResourceQuantity</a>

First included in: ProductionControl/ProdProductionOrderRouteOperationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Resource quantity</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ResourceQuantity attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Resource quantity</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RouteGroupId name="RouteGroupId">RouteGroupId</a>

First included in: ProductionControl/ProdProductionOrderRouteOperationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RouteGroupId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RouteOperationRateMethod name="RouteOperationRateMethod">RouteOperationRateMethod</a>

First included in: ProductionControl/ProdProductionOrderRouteOperationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RouteOperationRateMethod attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RouteOperationRemainderStatus name="RouteOperationRemainderStatus">RouteOperationRemainderStatus</a>

First included in: ProductionControl/ProdProductionOrderRouteOperationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RouteOperationRemainderStatus attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RouteOperationSequence name="RouteOperationSequence">RouteOperationSequence</a>

First included in: ProductionControl/ProdProductionOrderRouteOperationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RouteOperationSequence attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RouteType name="RouteType">RouteType</a>

First included in: ProductionControl/ProdProductionOrderRouteOperationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RouteType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ScheduledFromDate name="ScheduledFromDate">ScheduledFromDate</a>

First included in: ProductionControl/ProdProductionOrderRouteOperationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ScheduledFromDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ScheduledFromTime name="ScheduledFromTime">ScheduledFromTime</a>

First included in: ProductionControl/ProdProductionOrderRouteOperationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ScheduledFromTime attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SetupProductionJobId name="SetupProductionJobId">SetupProductionJobId</a>

First included in: ProductionControl/ProdProductionOrderRouteOperationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SetupProductionJobId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ScheduledEndDate name="ScheduledEndDate">ScheduledEndDate</a>

First included in: ProductionControl/ProdProductionOrderRouteOperationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ScheduledEndDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ScheduledEndTime name="ScheduledEndTime">ScheduledEndTime</a>

First included in: ProductionControl/ProdProductionOrderRouteOperationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ScheduledEndTime attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ScrapPercentage name="ScrapPercentage">ScrapPercentage</a>

First included in: ProductionControl/ProdProductionOrderRouteOperationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ScrapPercentage attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SetupCompletionPercentage name="SetupCompletionPercentage">SetupCompletionPercentage</a>

First included in: ProductionControl/ProdProductionOrderRouteOperationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SetupCompletionPercentage attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SetupCostCategoryId name="SetupCostCategoryId">SetupCostCategoryId</a>

First included in: ProductionControl/ProdProductionOrderRouteOperationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Setup cost category id</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SetupCostCategoryId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Setup cost category id</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SetupTime name="SetupTime">SetupTime</a>

First included in: ProductionControl/ProdProductionOrderRouteOperationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SetupTime attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TransferBatchQuantity name="TransferBatchQuantity">TransferBatchQuantity</a>

First included in: ProductionControl/ProdProductionOrderRouteOperationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TransferBatchQuantity attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TransitTime name="TransitTime">TransitTime</a>

First included in: ProductionControl/ProdProductionOrderRouteOperationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TransitTime attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WorkingTimeSchedulingPropertyId name="WorkingTimeSchedulingPropertyId">WorkingTimeSchedulingPropertyId</a>

First included in: ProductionControl/ProdProductionOrderRouteOperationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WorkingTimeSchedulingPropertyId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WrkCtrActivityRequirementSetRecId name="WrkCtrActivityRequirementSetRecId">WrkCtrActivityRequirementSetRecId</a>

First included in: ProductionControl/ProdProductionOrderRouteOperationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WrkCtrActivityRequirementSetRecId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ActivityToCopyRecordId name="ActivityToCopyRecordId">ActivityToCopyRecordId</a>

First included in: ProductionControl/ProdProductionOrderRouteOperationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ActivityToCopyRecordId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_DefaultDimensionDimensionSetRelationshipId name="Relationship_DefaultDimensionDimensionSetRelationshipId">Relationship_DefaultDimensionDimensionSetRelationshipId</a>

First included in: ProductionControl/ProdProductionOrderRouteOperationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_DefaultDimensionDimensionSetRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_ProductionOrderHeaderRelationshipId name="Relationship_ProductionOrderHeaderRelationshipId">Relationship_ProductionOrderHeaderRelationshipId</a>

First included in: ProductionControl/ProdProductionOrderRouteOperationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_ProductionOrderHeaderRelationshipId attribute are listed below.</summary>

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

### <a href=#BackingTable_ProdRouteRelationshipId name="BackingTable_ProdRouteRelationshipId">BackingTable_ProdRouteRelationshipId</a>

First included in: ProductionControl/ProdProductionOrderRouteOperationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_ProdRouteRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/SupplyChain/ProductionControl/WorksheetLine/ProdRoute.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/ProductionControl/WorksheetLine/ProdRoute.cdm.json/ProdRoute</a></td><td><a href="../../../Tables/SupplyChain/ProductionControl/WorksheetLine/ProdRoute.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PrimaryCompanyContextRelationshipId name="Relationship_PrimaryCompanyContextRelationshipId">Relationship_PrimaryCompanyContextRelationshipId</a>

First included in: ProductionControl/ProdProductionOrderRouteOperationEntity (this entity)  

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
