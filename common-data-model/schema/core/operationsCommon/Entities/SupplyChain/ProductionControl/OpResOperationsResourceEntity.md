---
title: OpResOperationsResourceEntity in ProductionControl - Common Data Model | Microsoft Docs
description: undefined
author: llawwaii
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: reference
ms.date: 8/7/2020
ms.author: weiluo
---

# Operations resource in ProductionControl(OpResOperationsResourceEntity)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/SupplyChain/ProductionControl/OpResOperationsResourceEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.1"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Operations resource</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[BatchCapacity](#BatchCapacity)||<a href="OpResOperationsResourceEntity.md" target="_blank">ProductionControl/OpResOperationsResourceEntity</a>|
|[BatchTransferQuantity](#BatchTransferQuantity)||<a href="OpResOperationsResourceEntity.md" target="_blank">ProductionControl/OpResOperationsResourceEntity</a>|
|[Capacity](#Capacity)||<a href="OpResOperationsResourceEntity.md" target="_blank">ProductionControl/OpResOperationsResourceEntity</a>|
|[CapacityUnit](#CapacityUnit)||<a href="OpResOperationsResourceEntity.md" target="_blank">ProductionControl/OpResOperationsResourceEntity</a>|
|[DefaultOperationQueueTimeAfter](#DefaultOperationQueueTimeAfter)||<a href="OpResOperationsResourceEntity.md" target="_blank">ProductionControl/OpResOperationsResourceEntity</a>|
|[DefaultOperationQueueTimeBefore](#DefaultOperationQueueTimeBefore)||<a href="OpResOperationsResourceEntity.md" target="_blank">ProductionControl/OpResOperationsResourceEntity</a>|
|[DefaultOperationRunTime](#DefaultOperationRunTime)||<a href="OpResOperationsResourceEntity.md" target="_blank">ProductionControl/OpResOperationsResourceEntity</a>|
|[DefaultOperationSetupTime](#DefaultOperationSetupTime)||<a href="OpResOperationsResourceEntity.md" target="_blank">ProductionControl/OpResOperationsResourceEntity</a>|
|[DefaultOperationTimeToHoursConversionFactor](#DefaultOperationTimeToHoursConversionFactor)||<a href="OpResOperationsResourceEntity.md" target="_blank">ProductionControl/OpResOperationsResourceEntity</a>|
|[DefaultOperationTransitTime](#DefaultOperationTransitTime)||<a href="OpResOperationsResourceEntity.md" target="_blank">ProductionControl/OpResOperationsResourceEntity</a>|
|[DefaultProcessQuantity](#DefaultProcessQuantity)||<a href="OpResOperationsResourceEntity.md" target="_blank">ProductionControl/OpResOperationsResourceEntity</a>|
|[EfficiencyPercentage](#EfficiencyPercentage)||<a href="OpResOperationsResourceEntity.md" target="_blank">ProductionControl/OpResOperationsResourceEntity</a>|
|[HasFiniteSchedulingCapacity](#HasFiniteSchedulingCapacity)||<a href="OpResOperationsResourceEntity.md" target="_blank">ProductionControl/OpResOperationsResourceEntity</a>|
|[IsBottleneckResource](#IsBottleneckResource)||<a href="OpResOperationsResourceEntity.md" target="_blank">ProductionControl/OpResOperationsResourceEntity</a>|
|[IsExclusiveResource](#IsExclusiveResource)||<a href="OpResOperationsResourceEntity.md" target="_blank">ProductionControl/OpResOperationsResourceEntity</a>|
|[OperationSchedulingPercentage](#OperationSchedulingPercentage)||<a href="OpResOperationsResourceEntity.md" target="_blank">ProductionControl/OpResOperationsResourceEntity</a>|
|[QuantityCostCategoryId](#QuantityCostCategoryId)||<a href="OpResOperationsResourceEntity.md" target="_blank">ProductionControl/OpResOperationsResourceEntity</a>|
|[ResourceId](#ResourceId)||<a href="OpResOperationsResourceEntity.md" target="_blank">ProductionControl/OpResOperationsResourceEntity</a>|
|[ResourceName](#ResourceName)||<a href="OpResOperationsResourceEntity.md" target="_blank">ProductionControl/OpResOperationsResourceEntity</a>|
|[OperationsResourceType](#OperationsResourceType)||<a href="OpResOperationsResourceEntity.md" target="_blank">ProductionControl/OpResOperationsResourceEntity</a>|
|[RuntimeCostCategoryId](#RuntimeCostCategoryId)||<a href="OpResOperationsResourceEntity.md" target="_blank">ProductionControl/OpResOperationsResourceEntity</a>|
|[ScrapPercentage](#ScrapPercentage)||<a href="OpResOperationsResourceEntity.md" target="_blank">ProductionControl/OpResOperationsResourceEntity</a>|
|[SetupCostCategoryId](#SetupCostCategoryId)||<a href="OpResOperationsResourceEntity.md" target="_blank">ProductionControl/OpResOperationsResourceEntity</a>|
|[IsScheduledUsingFiniteProperty](#IsScheduledUsingFiniteProperty)||<a href="OpResOperationsResourceEntity.md" target="_blank">ProductionControl/OpResOperationsResourceEntity</a>|
|[VendorAccountNumber](#VendorAccountNumber)||<a href="OpResOperationsResourceEntity.md" target="_blank">ProductionControl/OpResOperationsResourceEntity</a>|
|[ResourceWorkerPersonnelNumber](#ResourceWorkerPersonnelNumber)||<a href="OpResOperationsResourceEntity.md" target="_blank">ProductionControl/OpResOperationsResourceEntity</a>|
|[DefaultDimension](#DefaultDimension)||<a href="OpResOperationsResourceEntity.md" target="_blank">ProductionControl/OpResOperationsResourceEntity</a>|
|[DefaultDimensionDisplayValue](#DefaultDimensionDisplayValue)||<a href="OpResOperationsResourceEntity.md" target="_blank">ProductionControl/OpResOperationsResourceEntity</a>|
|[ResourceIssueLedgerDimension](#ResourceIssueLedgerDimension)||<a href="OpResOperationsResourceEntity.md" target="_blank">ProductionControl/OpResOperationsResourceEntity</a>|
|[ResourceIssueOffsetLedgerDimension](#ResourceIssueOffsetLedgerDimension)||<a href="OpResOperationsResourceEntity.md" target="_blank">ProductionControl/OpResOperationsResourceEntity</a>|
|[WIPIssueLedgerDimension](#WIPIssueLedgerDimension)||<a href="OpResOperationsResourceEntity.md" target="_blank">ProductionControl/OpResOperationsResourceEntity</a>|
|[WIPValuationLedgerDimension](#WIPValuationLedgerDimension)||<a href="OpResOperationsResourceEntity.md" target="_blank">ProductionControl/OpResOperationsResourceEntity</a>|
|[ResourceIssueLedgerDimensionDisplayValue](#ResourceIssueLedgerDimensionDisplayValue)||<a href="OpResOperationsResourceEntity.md" target="_blank">ProductionControl/OpResOperationsResourceEntity</a>|
|[ResourceIssueOffsetLedgerDimensionDisplayValue](#ResourceIssueOffsetLedgerDimensionDisplayValue)||<a href="OpResOperationsResourceEntity.md" target="_blank">ProductionControl/OpResOperationsResourceEntity</a>|
|[WIPIssueLedgerDimensionDisplayValue](#WIPIssueLedgerDimensionDisplayValue)||<a href="OpResOperationsResourceEntity.md" target="_blank">ProductionControl/OpResOperationsResourceEntity</a>|
|[WIPValuationLedgerDimensionDisplayValue](#WIPValuationLedgerDimensionDisplayValue)||<a href="OpResOperationsResourceEntity.md" target="_blank">ProductionControl/OpResOperationsResourceEntity</a>|
|[RouteGroupId](#RouteGroupId)||<a href="OpResOperationsResourceEntity.md" target="_blank">ProductionControl/OpResOperationsResourceEntity</a>|
|[Relationship_DefaultDimensionSetRelationshipId](#Relationship_DefaultDimensionSetRelationshipId)||<a href="OpResOperationsResourceEntity.md" target="_blank">ProductionControl/OpResOperationsResourceEntity</a>|
|[Relationship_ResourceIssueLedgerDimensionCombinationRelationshipId](#Relationship_ResourceIssueLedgerDimensionCombinationRelationshipId)||<a href="OpResOperationsResourceEntity.md" target="_blank">ProductionControl/OpResOperationsResourceEntity</a>|
|[Relationship_ResourceIssueOffsetLedgerDimensionCombinationRelationshipId](#Relationship_ResourceIssueOffsetLedgerDimensionCombinationRelationshipId)||<a href="OpResOperationsResourceEntity.md" target="_blank">ProductionControl/OpResOperationsResourceEntity</a>|
|[Relationship_WIPIssueLedgerDimensionCombinationRelationshipId](#Relationship_WIPIssueLedgerDimensionCombinationRelationshipId)||<a href="OpResOperationsResourceEntity.md" target="_blank">ProductionControl/OpResOperationsResourceEntity</a>|
|[Relationship_WIPValuationLedgerDimensionCombinationRelationshipId](#Relationship_WIPValuationLedgerDimensionCombinationRelationshipId)||<a href="OpResOperationsResourceEntity.md" target="_blank">ProductionControl/OpResOperationsResourceEntity</a>|
|[BackingTable_WrkCtrTableRelationshipId](#BackingTable_WrkCtrTableRelationshipId)||<a href="OpResOperationsResourceEntity.md" target="_blank">ProductionControl/OpResOperationsResourceEntity</a>|
|[Relationship_PrimaryCompanyContextRelationshipId](#Relationship_PrimaryCompanyContextRelationshipId)||<a href="OpResOperationsResourceEntity.md" target="_blank">ProductionControl/OpResOperationsResourceEntity</a>|

### <a href=#BatchCapacity name="BatchCapacity">BatchCapacity</a>

First included in: ProductionControl/OpResOperationsResourceEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BatchCapacity attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BatchTransferQuantity name="BatchTransferQuantity">BatchTransferQuantity</a>

First included in: ProductionControl/OpResOperationsResourceEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BatchTransferQuantity attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Capacity name="Capacity">Capacity</a>

First included in: ProductionControl/OpResOperationsResourceEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Capacity attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CapacityUnit name="CapacityUnit">CapacityUnit</a>

First included in: ProductionControl/OpResOperationsResourceEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CapacityUnit attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DefaultOperationQueueTimeAfter name="DefaultOperationQueueTimeAfter">DefaultOperationQueueTimeAfter</a>

First included in: ProductionControl/OpResOperationsResourceEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultOperationQueueTimeAfter attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DefaultOperationQueueTimeBefore name="DefaultOperationQueueTimeBefore">DefaultOperationQueueTimeBefore</a>

First included in: ProductionControl/OpResOperationsResourceEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultOperationQueueTimeBefore attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DefaultOperationRunTime name="DefaultOperationRunTime">DefaultOperationRunTime</a>

First included in: ProductionControl/OpResOperationsResourceEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultOperationRunTime attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DefaultOperationSetupTime name="DefaultOperationSetupTime">DefaultOperationSetupTime</a>

First included in: ProductionControl/OpResOperationsResourceEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultOperationSetupTime attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DefaultOperationTimeToHoursConversionFactor name="DefaultOperationTimeToHoursConversionFactor">DefaultOperationTimeToHoursConversionFactor</a>

First included in: ProductionControl/OpResOperationsResourceEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultOperationTimeToHoursConversionFactor attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DefaultOperationTransitTime name="DefaultOperationTransitTime">DefaultOperationTransitTime</a>

First included in: ProductionControl/OpResOperationsResourceEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultOperationTransitTime attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DefaultProcessQuantity name="DefaultProcessQuantity">DefaultProcessQuantity</a>

First included in: ProductionControl/OpResOperationsResourceEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultProcessQuantity attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#EfficiencyPercentage name="EfficiencyPercentage">EfficiencyPercentage</a>

First included in: ProductionControl/OpResOperationsResourceEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EfficiencyPercentage attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#HasFiniteSchedulingCapacity name="HasFiniteSchedulingCapacity">HasFiniteSchedulingCapacity</a>

First included in: ProductionControl/OpResOperationsResourceEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the HasFiniteSchedulingCapacity attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsBottleneckResource name="IsBottleneckResource">IsBottleneckResource</a>

First included in: ProductionControl/OpResOperationsResourceEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsBottleneckResource attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsExclusiveResource name="IsExclusiveResource">IsExclusiveResource</a>

First included in: ProductionControl/OpResOperationsResourceEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsExclusiveResource attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#OperationSchedulingPercentage name="OperationSchedulingPercentage">OperationSchedulingPercentage</a>

First included in: ProductionControl/OpResOperationsResourceEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OperationSchedulingPercentage attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#QuantityCostCategoryId name="QuantityCostCategoryId">QuantityCostCategoryId</a>

First included in: ProductionControl/OpResOperationsResourceEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the QuantityCostCategoryId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ResourceId name="ResourceId">ResourceId</a>

First included in: ProductionControl/OpResOperationsResourceEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ResourceId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ResourceName name="ResourceName">ResourceName</a>

First included in: ProductionControl/OpResOperationsResourceEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ResourceName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#OperationsResourceType name="OperationsResourceType">OperationsResourceType</a>

First included in: ProductionControl/OpResOperationsResourceEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OperationsResourceType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RuntimeCostCategoryId name="RuntimeCostCategoryId">RuntimeCostCategoryId</a>

First included in: ProductionControl/OpResOperationsResourceEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RuntimeCostCategoryId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ScrapPercentage name="ScrapPercentage">ScrapPercentage</a>

First included in: ProductionControl/OpResOperationsResourceEntity (this entity)  

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

### <a href=#SetupCostCategoryId name="SetupCostCategoryId">SetupCostCategoryId</a>

First included in: ProductionControl/OpResOperationsResourceEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SetupCostCategoryId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsScheduledUsingFiniteProperty name="IsScheduledUsingFiniteProperty">IsScheduledUsingFiniteProperty</a>

First included in: ProductionControl/OpResOperationsResourceEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsScheduledUsingFiniteProperty attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#VendorAccountNumber name="VendorAccountNumber">VendorAccountNumber</a>

First included in: ProductionControl/OpResOperationsResourceEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VendorAccountNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ResourceWorkerPersonnelNumber name="ResourceWorkerPersonnelNumber">ResourceWorkerPersonnelNumber</a>

First included in: ProductionControl/OpResOperationsResourceEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ResourceWorkerPersonnelNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DefaultDimension name="DefaultDimension">DefaultDimension</a>

First included in: ProductionControl/OpResOperationsResourceEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultDimension attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DefaultDimensionDisplayValue name="DefaultDimensionDisplayValue">DefaultDimensionDisplayValue</a>

First included in: ProductionControl/OpResOperationsResourceEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultDimensionDisplayValue attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ResourceIssueLedgerDimension name="ResourceIssueLedgerDimension">ResourceIssueLedgerDimension</a>

First included in: ProductionControl/OpResOperationsResourceEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ResourceIssueLedgerDimension attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ResourceIssueOffsetLedgerDimension name="ResourceIssueOffsetLedgerDimension">ResourceIssueOffsetLedgerDimension</a>

First included in: ProductionControl/OpResOperationsResourceEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ResourceIssueOffsetLedgerDimension attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WIPIssueLedgerDimension name="WIPIssueLedgerDimension">WIPIssueLedgerDimension</a>

First included in: ProductionControl/OpResOperationsResourceEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WIPIssueLedgerDimension attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WIPValuationLedgerDimension name="WIPValuationLedgerDimension">WIPValuationLedgerDimension</a>

First included in: ProductionControl/OpResOperationsResourceEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WIPValuationLedgerDimension attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ResourceIssueLedgerDimensionDisplayValue name="ResourceIssueLedgerDimensionDisplayValue">ResourceIssueLedgerDimensionDisplayValue</a>

First included in: ProductionControl/OpResOperationsResourceEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ResourceIssueLedgerDimensionDisplayValue attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ResourceIssueOffsetLedgerDimensionDisplayValue name="ResourceIssueOffsetLedgerDimensionDisplayValue">ResourceIssueOffsetLedgerDimensionDisplayValue</a>

First included in: ProductionControl/OpResOperationsResourceEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ResourceIssueOffsetLedgerDimensionDisplayValue attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WIPIssueLedgerDimensionDisplayValue name="WIPIssueLedgerDimensionDisplayValue">WIPIssueLedgerDimensionDisplayValue</a>

First included in: ProductionControl/OpResOperationsResourceEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WIPIssueLedgerDimensionDisplayValue attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WIPValuationLedgerDimensionDisplayValue name="WIPValuationLedgerDimensionDisplayValue">WIPValuationLedgerDimensionDisplayValue</a>

First included in: ProductionControl/OpResOperationsResourceEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WIPValuationLedgerDimensionDisplayValue attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RouteGroupId name="RouteGroupId">RouteGroupId</a>

First included in: ProductionControl/OpResOperationsResourceEntity (this entity)  

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

### <a href=#Relationship_DefaultDimensionSetRelationshipId name="Relationship_DefaultDimensionSetRelationshipId">Relationship_DefaultDimensionSetRelationshipId</a>

First included in: ProductionControl/OpResOperationsResourceEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_DefaultDimensionSetRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_ResourceIssueLedgerDimensionCombinationRelationshipId name="Relationship_ResourceIssueLedgerDimensionCombinationRelationshipId">Relationship_ResourceIssueLedgerDimensionCombinationRelationshipId</a>

First included in: ProductionControl/OpResOperationsResourceEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_ResourceIssueLedgerDimensionCombinationRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_ResourceIssueOffsetLedgerDimensionCombinationRelationshipId name="Relationship_ResourceIssueOffsetLedgerDimensionCombinationRelationshipId">Relationship_ResourceIssueOffsetLedgerDimensionCombinationRelationshipId</a>

First included in: ProductionControl/OpResOperationsResourceEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_ResourceIssueOffsetLedgerDimensionCombinationRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_WIPIssueLedgerDimensionCombinationRelationshipId name="Relationship_WIPIssueLedgerDimensionCombinationRelationshipId">Relationship_WIPIssueLedgerDimensionCombinationRelationshipId</a>

First included in: ProductionControl/OpResOperationsResourceEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_WIPIssueLedgerDimensionCombinationRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_WIPValuationLedgerDimensionCombinationRelationshipId name="Relationship_WIPValuationLedgerDimensionCombinationRelationshipId">Relationship_WIPValuationLedgerDimensionCombinationRelationshipId</a>

First included in: ProductionControl/OpResOperationsResourceEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_WIPValuationLedgerDimensionCombinationRelationshipId attribute are listed below.</summary>

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

### <a href=#BackingTable_WrkCtrTableRelationshipId name="BackingTable_WrkCtrTableRelationshipId">BackingTable_WrkCtrTableRelationshipId</a>

First included in: ProductionControl/OpResOperationsResourceEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_WrkCtrTableRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/SupplyChain/SalesAndMarketing/Main/WrkCtrTable.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/SalesAndMarketing/Main/WrkCtrTable.cdm.json/WrkCtrTable</a></td><td><a href="../../../Tables/SupplyChain/SalesAndMarketing/Main/WrkCtrTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PrimaryCompanyContextRelationshipId name="Relationship_PrimaryCompanyContextRelationshipId">Relationship_PrimaryCompanyContextRelationshipId</a>

First included in: ProductionControl/OpResOperationsResourceEntity (this entity)  

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
