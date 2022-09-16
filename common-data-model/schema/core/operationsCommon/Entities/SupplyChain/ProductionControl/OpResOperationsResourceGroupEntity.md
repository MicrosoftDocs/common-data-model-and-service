---
title: OpResOperationsResourceGroupEntity in ProductionControl - Common Data Model | Microsoft Docs
description: undefined
author: llawwaii

ms.reviewer: deonhe
ms.topic: reference
ms.date: 8/7/2020
ms.author: weiluo
---

# Resource groups in ProductionControl(OpResOperationsResourceGroupEntity)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/SupplyChain/ProductionControl/OpResOperationsResourceGroupEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.1"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Resource groups</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[BatchCapacity](#BatchCapacity)||<a href="OpResOperationsResourceGroupEntity.md" target="_blank">ProductionControl/OpResOperationsResourceGroupEntity</a>|
|[Capacity](#Capacity)||<a href="OpResOperationsResourceGroupEntity.md" target="_blank">ProductionControl/OpResOperationsResourceGroupEntity</a>|
|[CapacityUnit](#CapacityUnit)||<a href="OpResOperationsResourceGroupEntity.md" target="_blank">ProductionControl/OpResOperationsResourceGroupEntity</a>|
|[HasFiniteSchedulingCapacity](#HasFiniteSchedulingCapacity)||<a href="OpResOperationsResourceGroupEntity.md" target="_blank">ProductionControl/OpResOperationsResourceGroupEntity</a>|
|[InputWarehouseId](#InputWarehouseId)||<a href="OpResOperationsResourceGroupEntity.md" target="_blank">ProductionControl/OpResOperationsResourceGroupEntity</a>|
|[InputWarehouseLocationId](#InputWarehouseLocationId)||<a href="OpResOperationsResourceGroupEntity.md" target="_blank">ProductionControl/OpResOperationsResourceGroupEntity</a>|
|[IsBottleneckResourceGroup](#IsBottleneckResourceGroup)||<a href="OpResOperationsResourceGroupEntity.md" target="_blank">ProductionControl/OpResOperationsResourceGroupEntity</a>|
|[OperationalSiteId](#OperationalSiteId)||<a href="OpResOperationsResourceGroupEntity.md" target="_blank">ProductionControl/OpResOperationsResourceGroupEntity</a>|
|[OperationSchedulingPercentage](#OperationSchedulingPercentage)||<a href="OpResOperationsResourceGroupEntity.md" target="_blank">ProductionControl/OpResOperationsResourceGroupEntity</a>|
|[OutputWarehouseId](#OutputWarehouseId)||<a href="OpResOperationsResourceGroupEntity.md" target="_blank">ProductionControl/OpResOperationsResourceGroupEntity</a>|
|[OutputWarehouseLocationId](#OutputWarehouseLocationId)||<a href="OpResOperationsResourceGroupEntity.md" target="_blank">ProductionControl/OpResOperationsResourceGroupEntity</a>|
|[IsWorkCell](#IsWorkCell)||<a href="OpResOperationsResourceGroupEntity.md" target="_blank">ProductionControl/OpResOperationsResourceGroupEntity</a>|
|[ProductionUnitId](#ProductionUnitId)||<a href="OpResOperationsResourceGroupEntity.md" target="_blank">ProductionControl/OpResOperationsResourceGroupEntity</a>|
|[QuantityCostCategoryId](#QuantityCostCategoryId)||<a href="OpResOperationsResourceGroupEntity.md" target="_blank">ProductionControl/OpResOperationsResourceGroupEntity</a>|
|[GroupId](#GroupId)||<a href="OpResOperationsResourceGroupEntity.md" target="_blank">ProductionControl/OpResOperationsResourceGroupEntity</a>|
|[GroupName](#GroupName)||<a href="OpResOperationsResourceGroupEntity.md" target="_blank">ProductionControl/OpResOperationsResourceGroupEntity</a>|
|[RuntimeCostCategoryId](#RuntimeCostCategoryId)||<a href="OpResOperationsResourceGroupEntity.md" target="_blank">ProductionControl/OpResOperationsResourceGroupEntity</a>|
|[ScrapPercentage](#ScrapPercentage)||<a href="OpResOperationsResourceGroupEntity.md" target="_blank">ProductionControl/OpResOperationsResourceGroupEntity</a>|
|[SetupCostCategoryId](#SetupCostCategoryId)||<a href="OpResOperationsResourceGroupEntity.md" target="_blank">ProductionControl/OpResOperationsResourceGroupEntity</a>|
|[DefaultDimension](#DefaultDimension)||<a href="OpResOperationsResourceGroupEntity.md" target="_blank">ProductionControl/OpResOperationsResourceGroupEntity</a>|
|[DefaultDimensionDisplayValue](#DefaultDimensionDisplayValue)||<a href="OpResOperationsResourceGroupEntity.md" target="_blank">ProductionControl/OpResOperationsResourceGroupEntity</a>|
|[ResourceIssueLedgerDimension](#ResourceIssueLedgerDimension)||<a href="OpResOperationsResourceGroupEntity.md" target="_blank">ProductionControl/OpResOperationsResourceGroupEntity</a>|
|[ResourceIssueOffsetLedgerDimension](#ResourceIssueOffsetLedgerDimension)||<a href="OpResOperationsResourceGroupEntity.md" target="_blank">ProductionControl/OpResOperationsResourceGroupEntity</a>|
|[WIPIssueLedgerDimension](#WIPIssueLedgerDimension)||<a href="OpResOperationsResourceGroupEntity.md" target="_blank">ProductionControl/OpResOperationsResourceGroupEntity</a>|
|[WIPValuationLedgerDimension](#WIPValuationLedgerDimension)||<a href="OpResOperationsResourceGroupEntity.md" target="_blank">ProductionControl/OpResOperationsResourceGroupEntity</a>|
|[ResourceIssueLedgerDimensionDisplayValue](#ResourceIssueLedgerDimensionDisplayValue)||<a href="OpResOperationsResourceGroupEntity.md" target="_blank">ProductionControl/OpResOperationsResourceGroupEntity</a>|
|[ResourceIssueOffsetLedgerDimensionDisplayValue](#ResourceIssueOffsetLedgerDimensionDisplayValue)||<a href="OpResOperationsResourceGroupEntity.md" target="_blank">ProductionControl/OpResOperationsResourceGroupEntity</a>|
|[WIPIssueLedgerDimensionDisplayValue](#WIPIssueLedgerDimensionDisplayValue)||<a href="OpResOperationsResourceGroupEntity.md" target="_blank">ProductionControl/OpResOperationsResourceGroupEntity</a>|
|[WIPValuationLedgerDimensionDisplayValue](#WIPValuationLedgerDimensionDisplayValue)||<a href="OpResOperationsResourceGroupEntity.md" target="_blank">ProductionControl/OpResOperationsResourceGroupEntity</a>|
|[Relationship_DimensionDimensionSetRelationshipId](#Relationship_DimensionDimensionSetRelationshipId)||<a href="OpResOperationsResourceGroupEntity.md" target="_blank">ProductionControl/OpResOperationsResourceGroupEntity</a>|
|[Relationship_ResourceIssueLedgerDimensionCombinationRelationshipId](#Relationship_ResourceIssueLedgerDimensionCombinationRelationshipId)||<a href="OpResOperationsResourceGroupEntity.md" target="_blank">ProductionControl/OpResOperationsResourceGroupEntity</a>|
|[Relationship_ResourceIssueOffsetLedgerDimensionCombinationRelationshipId](#Relationship_ResourceIssueOffsetLedgerDimensionCombinationRelationshipId)||<a href="OpResOperationsResourceGroupEntity.md" target="_blank">ProductionControl/OpResOperationsResourceGroupEntity</a>|
|[Relationship_WIPIssueLedgerDimensionCombinationRelationshipId](#Relationship_WIPIssueLedgerDimensionCombinationRelationshipId)||<a href="OpResOperationsResourceGroupEntity.md" target="_blank">ProductionControl/OpResOperationsResourceGroupEntity</a>|
|[Relationship_WIPValuationLedgerDimensionCombinationRelationshipId](#Relationship_WIPValuationLedgerDimensionCombinationRelationshipId)||<a href="OpResOperationsResourceGroupEntity.md" target="_blank">ProductionControl/OpResOperationsResourceGroupEntity</a>|
|[BackingTable_WrkCtrResourceGroupRelationshipId](#BackingTable_WrkCtrResourceGroupRelationshipId)||<a href="OpResOperationsResourceGroupEntity.md" target="_blank">ProductionControl/OpResOperationsResourceGroupEntity</a>|
|[Relationship_PrimaryCompanyContextRelationshipId](#Relationship_PrimaryCompanyContextRelationshipId)||<a href="OpResOperationsResourceGroupEntity.md" target="_blank">ProductionControl/OpResOperationsResourceGroupEntity</a>|

### <a href=#BatchCapacity name="BatchCapacity">BatchCapacity</a>

First included in: ProductionControl/OpResOperationsResourceGroupEntity (this entity)  

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

### <a href=#Capacity name="Capacity">Capacity</a>

First included in: ProductionControl/OpResOperationsResourceGroupEntity (this entity)  

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

First included in: ProductionControl/OpResOperationsResourceGroupEntity (this entity)  

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

### <a href=#HasFiniteSchedulingCapacity name="HasFiniteSchedulingCapacity">HasFiniteSchedulingCapacity</a>

First included in: ProductionControl/OpResOperationsResourceGroupEntity (this entity)  

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

### <a href=#InputWarehouseId name="InputWarehouseId">InputWarehouseId</a>

First included in: ProductionControl/OpResOperationsResourceGroupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InputWarehouseId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InputWarehouseLocationId name="InputWarehouseLocationId">InputWarehouseLocationId</a>

First included in: ProductionControl/OpResOperationsResourceGroupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InputWarehouseLocationId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsBottleneckResourceGroup name="IsBottleneckResourceGroup">IsBottleneckResourceGroup</a>

First included in: ProductionControl/OpResOperationsResourceGroupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsBottleneckResourceGroup attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#OperationalSiteId name="OperationalSiteId">OperationalSiteId</a>

First included in: ProductionControl/OpResOperationsResourceGroupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OperationalSiteId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#OperationSchedulingPercentage name="OperationSchedulingPercentage">OperationSchedulingPercentage</a>

First included in: ProductionControl/OpResOperationsResourceGroupEntity (this entity)  

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

### <a href=#OutputWarehouseId name="OutputWarehouseId">OutputWarehouseId</a>

First included in: ProductionControl/OpResOperationsResourceGroupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OutputWarehouseId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#OutputWarehouseLocationId name="OutputWarehouseLocationId">OutputWarehouseLocationId</a>

First included in: ProductionControl/OpResOperationsResourceGroupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OutputWarehouseLocationId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsWorkCell name="IsWorkCell">IsWorkCell</a>

First included in: ProductionControl/OpResOperationsResourceGroupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsWorkCell attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProductionUnitId name="ProductionUnitId">ProductionUnitId</a>

First included in: ProductionControl/OpResOperationsResourceGroupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProductionUnitId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#QuantityCostCategoryId name="QuantityCostCategoryId">QuantityCostCategoryId</a>

First included in: ProductionControl/OpResOperationsResourceGroupEntity (this entity)  

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

### <a href=#GroupId name="GroupId">GroupId</a>

First included in: ProductionControl/OpResOperationsResourceGroupEntity (this entity)  

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

First included in: ProductionControl/OpResOperationsResourceGroupEntity (this entity)  

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

### <a href=#RuntimeCostCategoryId name="RuntimeCostCategoryId">RuntimeCostCategoryId</a>

First included in: ProductionControl/OpResOperationsResourceGroupEntity (this entity)  

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

First included in: ProductionControl/OpResOperationsResourceGroupEntity (this entity)  

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

First included in: ProductionControl/OpResOperationsResourceGroupEntity (this entity)  

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

### <a href=#DefaultDimension name="DefaultDimension">DefaultDimension</a>

First included in: ProductionControl/OpResOperationsResourceGroupEntity (this entity)  

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

First included in: ProductionControl/OpResOperationsResourceGroupEntity (this entity)  

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

First included in: ProductionControl/OpResOperationsResourceGroupEntity (this entity)  

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

First included in: ProductionControl/OpResOperationsResourceGroupEntity (this entity)  

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

First included in: ProductionControl/OpResOperationsResourceGroupEntity (this entity)  

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

First included in: ProductionControl/OpResOperationsResourceGroupEntity (this entity)  

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

First included in: ProductionControl/OpResOperationsResourceGroupEntity (this entity)  

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

First included in: ProductionControl/OpResOperationsResourceGroupEntity (this entity)  

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

First included in: ProductionControl/OpResOperationsResourceGroupEntity (this entity)  

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

First included in: ProductionControl/OpResOperationsResourceGroupEntity (this entity)  

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

### <a href=#Relationship_DimensionDimensionSetRelationshipId name="Relationship_DimensionDimensionSetRelationshipId">Relationship_DimensionDimensionSetRelationshipId</a>

First included in: ProductionControl/OpResOperationsResourceGroupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_DimensionDimensionSetRelationshipId attribute are listed below.</summary>

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

First included in: ProductionControl/OpResOperationsResourceGroupEntity (this entity)  

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

First included in: ProductionControl/OpResOperationsResourceGroupEntity (this entity)  

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

First included in: ProductionControl/OpResOperationsResourceGroupEntity (this entity)  

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

First included in: ProductionControl/OpResOperationsResourceGroupEntity (this entity)  

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

### <a href=#BackingTable_WrkCtrResourceGroupRelationshipId name="BackingTable_WrkCtrResourceGroupRelationshipId">BackingTable_WrkCtrResourceGroupRelationshipId</a>

First included in: ProductionControl/OpResOperationsResourceGroupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_WrkCtrResourceGroupRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/SupplyChain/MasterPlanning/Main/WrkCtrResourceGroup.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/MasterPlanning/Main/WrkCtrResourceGroup.cdm.json/WrkCtrResourceGroup</a></td><td><a href="../../../Tables/SupplyChain/MasterPlanning/Main/WrkCtrResourceGroup.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PrimaryCompanyContextRelationshipId name="Relationship_PrimaryCompanyContextRelationshipId">Relationship_PrimaryCompanyContextRelationshipId</a>

First included in: ProductionControl/OpResOperationsResourceGroupEntity (this entity)  

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
