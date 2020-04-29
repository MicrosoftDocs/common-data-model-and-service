---
title: ProdProductionRouteTransactionEntity - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/29/2020
ms.author: nebanfic
---

# Production route transactions

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/SupplyChain/ProductionControl/ProdProductionRouteTransactionEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Production route transactions</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[CostAmount](#CostAmount)||<a href="ProdProductionRouteTransactionEntity.md" target="_blank">ProductionControl/ProdProductionRouteTransactionEntity</a>|
|[IsCostAccounted](#IsCostAccounted)||<a href="ProdProductionRouteTransactionEntity.md" target="_blank">ProductionControl/ProdProductionRouteTransactionEntity</a>|
|[RouteCostCategoryId](#RouteCostCategoryId)||<a href="ProdProductionRouteTransactionEntity.md" target="_blank">ProductionControl/ProdProductionRouteTransactionEntity</a>|
|[RealizedAccountingDate](#RealizedAccountingDate)||<a href="ProdProductionRouteTransactionEntity.md" target="_blank">ProductionControl/ProdProductionRouteTransactionEntity</a>|
|[EstimatedAccountingDate](#EstimatedAccountingDate)||<a href="ProdProductionRouteTransactionEntity.md" target="_blank">ProductionControl/ProdProductionRouteTransactionEntity</a>|
|[ErrorCause](#ErrorCause)||<a href="ProdProductionRouteTransactionEntity.md" target="_blank">ProductionControl/ProdProductionRouteTransactionEntity</a>|
|[JobProcessingPercentage](#JobProcessingPercentage)||<a href="ProdProductionRouteTransactionEntity.md" target="_blank">ProductionControl/ProdProductionRouteTransactionEntity</a>|
|[ScheduledFromTime](#ScheduledFromTime)||<a href="ProdProductionRouteTransactionEntity.md" target="_blank">ProductionControl/ProdProductionRouteTransactionEntity</a>|
|[HourlyCostCategoryRate](#HourlyCostCategoryRate)||<a href="ProdProductionRouteTransactionEntity.md" target="_blank">ProductionControl/ProdProductionRouteTransactionEntity</a>|
|[IsJobEnded](#IsJobEnded)||<a href="ProdProductionRouteTransactionEntity.md" target="_blank">ProductionControl/ProdProductionRouteTransactionEntity</a>|
|[JobId](#JobId)||<a href="ProdProductionRouteTransactionEntity.md" target="_blank">ProductionControl/ProdProductionRouteTransactionEntity</a>|
|[RouteJobType](#RouteJobType)||<a href="ProdProductionRouteTransactionEntity.md" target="_blank">ProductionControl/ProdProductionRouteTransactionEntity</a>|
|[IsOperationCompleted](#IsOperationCompleted)||<a href="ProdProductionRouteTransactionEntity.md" target="_blank">ProductionControl/ProdProductionRouteTransactionEntity</a>|
|[OperationId](#OperationId)||<a href="ProdProductionRouteTransactionEntity.md" target="_blank">ProductionControl/ProdProductionRouteTransactionEntity</a>|
|[OperationNumber](#OperationNumber)||<a href="ProdProductionRouteTransactionEntity.md" target="_blank">ProductionControl/ProdProductionRouteTransactionEntity</a>|
|[OperationPriority](#OperationPriority)||<a href="ProdProductionRouteTransactionEntity.md" target="_blank">ProductionControl/ProdProductionRouteTransactionEntity</a>|
|[ReportedErrorCatchWeightQuantity](#ReportedErrorCatchWeightQuantity)||<a href="ProdProductionRouteTransactionEntity.md" target="_blank">ProductionControl/ProdProductionRouteTransactionEntity</a>|
|[ReportedGoodCatchWeightQuantity](#ReportedGoodCatchWeightQuantity)||<a href="ProdProductionRouteTransactionEntity.md" target="_blank">ProductionControl/ProdProductionRouteTransactionEntity</a>|
|[ProductionUnitId](#ProductionUnitId)||<a href="ProdProductionRouteTransactionEntity.md" target="_blank">ProductionControl/ProdProductionRouteTransactionEntity</a>|
|[ReportedErrorInventoryQuantity](#ReportedErrorInventoryQuantity)||<a href="ProdProductionRouteTransactionEntity.md" target="_blank">ProductionControl/ProdProductionRouteTransactionEntity</a>|
|[ReportedGoodInventoryQuantity](#ReportedGoodInventoryQuantity)||<a href="ProdProductionRouteTransactionEntity.md" target="_blank">ProductionControl/ProdProductionRouteTransactionEntity</a>|
|[QuantityCostCategoryUnitCost](#QuantityCostCategoryUnitCost)||<a href="ProdProductionRouteTransactionEntity.md" target="_blank">ProductionControl/ProdProductionRouteTransactionEntity</a>|
|[OperationsResourceGroupId](#OperationsResourceGroupId)||<a href="ProdProductionRouteTransactionEntity.md" target="_blank">ProductionControl/ProdProductionRouteTransactionEntity</a>|
|[ScheduledEndTime](#ScheduledEndTime)||<a href="ProdProductionRouteTransactionEntity.md" target="_blank">ProductionControl/ProdProductionRouteTransactionEntity</a>|
|[RealizedAccountingVoucherNumber](#RealizedAccountingVoucherNumber)||<a href="ProdProductionRouteTransactionEntity.md" target="_blank">ProductionControl/ProdProductionRouteTransactionEntity</a>|
|[EstimatedAccountingVoucherNumber](#EstimatedAccountingVoucherNumber)||<a href="ProdProductionRouteTransactionEntity.md" target="_blank">ProductionControl/ProdProductionRouteTransactionEntity</a>|
|[OperationResourceId](#OperationResourceId)||<a href="ProdProductionRouteTransactionEntity.md" target="_blank">ProductionControl/ProdProductionRouteTransactionEntity</a>|
|[RecordId](#RecordId)||<a href="ProdProductionRouteTransactionEntity.md" target="_blank">ProductionControl/ProdProductionRouteTransactionEntity</a>|
|[RegisteredHours](#RegisteredHours)||<a href="ProdProductionRouteTransactionEntity.md" target="_blank">ProductionControl/ProdProductionRouteTransactionEntity</a>|
|[BackingTable_ProdRouteTransRelationshipId](#BackingTable_ProdRouteTransRelationshipId)||<a href="ProdProductionRouteTransactionEntity.md" target="_blank">ProductionControl/ProdProductionRouteTransactionEntity</a>|
|[Relationship_PrimaryCompanyContextRelationshipId](#Relationship_PrimaryCompanyContextRelationshipId)||<a href="ProdProductionRouteTransactionEntity.md" target="_blank">ProductionControl/ProdProductionRouteTransactionEntity</a>|

### <a href=#CostAmount name="CostAmount">CostAmount</a>

First included in: ProductionControl/ProdProductionRouteTransactionEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CostAmount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsCostAccounted name="IsCostAccounted">IsCostAccounted</a>

First included in: ProductionControl/ProdProductionRouteTransactionEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsCostAccounted attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RouteCostCategoryId name="RouteCostCategoryId">RouteCostCategoryId</a>

First included in: ProductionControl/ProdProductionRouteTransactionEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RouteCostCategoryId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RealizedAccountingDate name="RealizedAccountingDate">RealizedAccountingDate</a>

First included in: ProductionControl/ProdProductionRouteTransactionEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RealizedAccountingDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#EstimatedAccountingDate name="EstimatedAccountingDate">EstimatedAccountingDate</a>

First included in: ProductionControl/ProdProductionRouteTransactionEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EstimatedAccountingDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ErrorCause name="ErrorCause">ErrorCause</a>

First included in: ProductionControl/ProdProductionRouteTransactionEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ErrorCause attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#JobProcessingPercentage name="JobProcessingPercentage">JobProcessingPercentage</a>

First included in: ProductionControl/ProdProductionRouteTransactionEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the JobProcessingPercentage attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ScheduledFromTime name="ScheduledFromTime">ScheduledFromTime</a>

First included in: ProductionControl/ProdProductionRouteTransactionEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ScheduledFromTime attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#HourlyCostCategoryRate name="HourlyCostCategoryRate">HourlyCostCategoryRate</a>

First included in: ProductionControl/ProdProductionRouteTransactionEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the HourlyCostCategoryRate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsJobEnded name="IsJobEnded">IsJobEnded</a>

First included in: ProductionControl/ProdProductionRouteTransactionEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsJobEnded attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#JobId name="JobId">JobId</a>

First included in: ProductionControl/ProdProductionRouteTransactionEntity (this entity)  

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

### <a href=#RouteJobType name="RouteJobType">RouteJobType</a>

First included in: ProductionControl/ProdProductionRouteTransactionEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RouteJobType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsOperationCompleted name="IsOperationCompleted">IsOperationCompleted</a>

First included in: ProductionControl/ProdProductionRouteTransactionEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsOperationCompleted attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#OperationId name="OperationId">OperationId</a>

First included in: ProductionControl/ProdProductionRouteTransactionEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OperationId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#OperationNumber name="OperationNumber">OperationNumber</a>

First included in: ProductionControl/ProdProductionRouteTransactionEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OperationNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#OperationPriority name="OperationPriority">OperationPriority</a>

First included in: ProductionControl/ProdProductionRouteTransactionEntity (this entity)  

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

### <a href=#ReportedErrorCatchWeightQuantity name="ReportedErrorCatchWeightQuantity">ReportedErrorCatchWeightQuantity</a>

First included in: ProductionControl/ProdProductionRouteTransactionEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReportedErrorCatchWeightQuantity attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ReportedGoodCatchWeightQuantity name="ReportedGoodCatchWeightQuantity">ReportedGoodCatchWeightQuantity</a>

First included in: ProductionControl/ProdProductionRouteTransactionEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReportedGoodCatchWeightQuantity attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProductionUnitId name="ProductionUnitId">ProductionUnitId</a>

First included in: ProductionControl/ProdProductionRouteTransactionEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProductionUnitId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ReportedErrorInventoryQuantity name="ReportedErrorInventoryQuantity">ReportedErrorInventoryQuantity</a>

First included in: ProductionControl/ProdProductionRouteTransactionEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReportedErrorInventoryQuantity attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ReportedGoodInventoryQuantity name="ReportedGoodInventoryQuantity">ReportedGoodInventoryQuantity</a>

First included in: ProductionControl/ProdProductionRouteTransactionEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReportedGoodInventoryQuantity attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#QuantityCostCategoryUnitCost name="QuantityCostCategoryUnitCost">QuantityCostCategoryUnitCost</a>

First included in: ProductionControl/ProdProductionRouteTransactionEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the QuantityCostCategoryUnitCost attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#OperationsResourceGroupId name="OperationsResourceGroupId">OperationsResourceGroupId</a>

First included in: ProductionControl/ProdProductionRouteTransactionEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OperationsResourceGroupId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ScheduledEndTime name="ScheduledEndTime">ScheduledEndTime</a>

First included in: ProductionControl/ProdProductionRouteTransactionEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ScheduledEndTime attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RealizedAccountingVoucherNumber name="RealizedAccountingVoucherNumber">RealizedAccountingVoucherNumber</a>

First included in: ProductionControl/ProdProductionRouteTransactionEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RealizedAccountingVoucherNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#EstimatedAccountingVoucherNumber name="EstimatedAccountingVoucherNumber">EstimatedAccountingVoucherNumber</a>

First included in: ProductionControl/ProdProductionRouteTransactionEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EstimatedAccountingVoucherNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#OperationResourceId name="OperationResourceId">OperationResourceId</a>

First included in: ProductionControl/ProdProductionRouteTransactionEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OperationResourceId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RecordId name="RecordId">RecordId</a>

First included in: ProductionControl/ProdProductionRouteTransactionEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecordId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RegisteredHours name="RegisteredHours">RegisteredHours</a>

First included in: ProductionControl/ProdProductionRouteTransactionEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RegisteredHours attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BackingTable_ProdRouteTransRelationshipId name="BackingTable_ProdRouteTransRelationshipId">BackingTable_ProdRouteTransRelationshipId</a>

First included in: ProductionControl/ProdProductionRouteTransactionEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_ProdRouteTransRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/SupplyChain/ProductionControl/Transaction/ProdRouteTrans.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/ProductionControl/Transaction/ProdRouteTrans.cdm.json/ProdRouteTrans</a></td><td><a href="../../../Tables/SupplyChain/ProductionControl/Transaction/ProdRouteTrans.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PrimaryCompanyContextRelationshipId name="Relationship_PrimaryCompanyContextRelationshipId">Relationship_PrimaryCompanyContextRelationshipId</a>

First included in: ProductionControl/ProdProductionRouteTransactionEntity (this entity)  

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
