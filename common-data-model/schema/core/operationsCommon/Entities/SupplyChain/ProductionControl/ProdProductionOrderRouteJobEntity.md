---
title: ProdProductionOrderRouteJobEntity - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/21/2020
ms.author: nebanfic
---

# ProdProductionOrderRouteJobEntity

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/SupplyChain/ProductionControl/ProdProductionOrderRouteJobEntity.cdm.json" target="_blank">GitHub</a>.  

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
|[CalculatedJobDurationHours](#CalculatedJobDurationHours)||<a href="ProdProductionOrderRouteJobEntity.md" target="_blank">ProductionControl/ProdProductionOrderRouteJobEntity</a>|
|[JobProcessingPercentage](#JobProcessingPercentage)||<a href="ProdProductionOrderRouteJobEntity.md" target="_blank">ProductionControl/ProdProductionOrderRouteJobEntity</a>|
|[ScheduledFromDate](#ScheduledFromDate)||<a href="ProdProductionOrderRouteJobEntity.md" target="_blank">ProductionControl/ProdProductionOrderRouteJobEntity</a>|
|[ScheduledFromTime](#ScheduledFromTime)||<a href="ProdProductionOrderRouteJobEntity.md" target="_blank">ProductionControl/ProdProductionOrderRouteJobEntity</a>|
|[IsJobManagementUsed](#IsJobManagementUsed)||<a href="ProdProductionOrderRouteJobEntity.md" target="_blank">ProductionControl/ProdProductionOrderRouteJobEntity</a>|
|[IsJobEnded](#IsJobEnded)||<a href="ProdProductionOrderRouteJobEntity.md" target="_blank">ProductionControl/ProdProductionOrderRouteJobEntity</a>|
|[JobId](#JobId)||<a href="ProdProductionOrderRouteJobEntity.md" target="_blank">ProductionControl/ProdProductionOrderRouteJobEntity</a>|
|[JobStatus](#JobStatus)||<a href="ProdProductionOrderRouteJobEntity.md" target="_blank">ProductionControl/ProdProductionOrderRouteJobEntity</a>|
|[RouteJobType](#RouteJobType)||<a href="ProdProductionOrderRouteJobEntity.md" target="_blank">ProductionControl/ProdProductionOrderRouteJobEntity</a>|
|[NextOperationLink](#NextOperationLink)||<a href="ProdProductionOrderRouteJobEntity.md" target="_blank">ProductionControl/ProdProductionOrderRouteJobEntity</a>|
|[NextOperationLinkType](#NextOperationLinkType)||<a href="ProdProductionOrderRouteJobEntity.md" target="_blank">ProductionControl/ProdProductionOrderRouteJobEntity</a>|
|[PrimaryJobNumber](#PrimaryJobNumber)||<a href="ProdProductionOrderRouteJobEntity.md" target="_blank">ProductionControl/ProdProductionOrderRouteJobEntity</a>|
|[SecondaryJobNumber](#SecondaryJobNumber)||<a href="ProdProductionOrderRouteJobEntity.md" target="_blank">ProductionControl/ProdProductionOrderRouteJobEntity</a>|
|[JobSequence](#JobSequence)||<a href="ProdProductionOrderRouteJobEntity.md" target="_blank">ProductionControl/ProdProductionOrderRouteJobEntity</a>|
|[OperationNumber](#OperationNumber)||<a href="ProdProductionOrderRouteJobEntity.md" target="_blank">ProductionControl/ProdProductionOrderRouteJobEntity</a>|
|[OperationPriority](#OperationPriority)||<a href="ProdProductionOrderRouteJobEntity.md" target="_blank">ProductionControl/ProdProductionOrderRouteJobEntity</a>|
|[ProductionOrderNumber](#ProductionOrderNumber)||<a href="ProdProductionOrderRouteJobEntity.md" target="_blank">ProductionControl/ProdProductionOrderRouteJobEntity</a>|
|[WorkingTimeSchedulingPropertyId](#WorkingTimeSchedulingPropertyId)||<a href="ProdProductionOrderRouteJobEntity.md" target="_blank">ProductionControl/ProdProductionOrderRouteJobEntity</a>|
|[ActualEndDate](#ActualEndDate)||<a href="ProdProductionOrderRouteJobEntity.md" target="_blank">ProductionControl/ProdProductionOrderRouteJobEntity</a>|
|[ActualEndTime](#ActualEndTime)||<a href="ProdProductionOrderRouteJobEntity.md" target="_blank">ProductionControl/ProdProductionOrderRouteJobEntity</a>|
|[ActualFromDate](#ActualFromDate)||<a href="ProdProductionOrderRouteJobEntity.md" target="_blank">ProductionControl/ProdProductionOrderRouteJobEntity</a>|
|[ActualFromTime](#ActualFromTime)||<a href="ProdProductionOrderRouteJobEntity.md" target="_blank">ProductionControl/ProdProductionOrderRouteJobEntity</a>|
|[IsJobCancelled](#IsJobCancelled)||<a href="ProdProductionOrderRouteJobEntity.md" target="_blank">ProductionControl/ProdProductionOrderRouteJobEntity</a>|
|[ScheduledJobDurationHours](#ScheduledJobDurationHours)||<a href="ProdProductionOrderRouteJobEntity.md" target="_blank">ProductionControl/ProdProductionOrderRouteJobEntity</a>|
|[ScheduledEndDate](#ScheduledEndDate)||<a href="ProdProductionOrderRouteJobEntity.md" target="_blank">ProductionControl/ProdProductionOrderRouteJobEntity</a>|
|[OperationsResourceId](#OperationsResourceId)||<a href="ProdProductionOrderRouteJobEntity.md" target="_blank">ProductionControl/ProdProductionOrderRouteJobEntity</a>|
|[ScheduledEndTime](#ScheduledEndTime)||<a href="ProdProductionOrderRouteJobEntity.md" target="_blank">ProductionControl/ProdProductionOrderRouteJobEntity</a>|
|[BackingTable_ProdRouteJobRelationshipId](#BackingTable_ProdRouteJobRelationshipId)||<a href="ProdProductionOrderRouteJobEntity.md" target="_blank">ProductionControl/ProdProductionOrderRouteJobEntity</a>|
|[Relationship_PrimaryCompanyContextRelationshipId](#Relationship_PrimaryCompanyContextRelationshipId)||<a href="ProdProductionOrderRouteJobEntity.md" target="_blank">ProductionControl/ProdProductionOrderRouteJobEntity</a>|

### <a href=#CalculatedJobDurationHours name="CalculatedJobDurationHours">CalculatedJobDurationHours</a>

First included in: ProductionControl/ProdProductionOrderRouteJobEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CalculatedJobDurationHours attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#JobProcessingPercentage name="JobProcessingPercentage">JobProcessingPercentage</a>

First included in: ProductionControl/ProdProductionOrderRouteJobEntity (this entity)  

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

### <a href=#ScheduledFromDate name="ScheduledFromDate">ScheduledFromDate</a>

First included in: ProductionControl/ProdProductionOrderRouteJobEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ScheduledFromDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ScheduledFromTime name="ScheduledFromTime">ScheduledFromTime</a>

First included in: ProductionControl/ProdProductionOrderRouteJobEntity (this entity)  

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

### <a href=#IsJobManagementUsed name="IsJobManagementUsed">IsJobManagementUsed</a>

First included in: ProductionControl/ProdProductionOrderRouteJobEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsJobManagementUsed attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsJobEnded name="IsJobEnded">IsJobEnded</a>

First included in: ProductionControl/ProdProductionOrderRouteJobEntity (this entity)  

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

First included in: ProductionControl/ProdProductionOrderRouteJobEntity (this entity)  

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

### <a href=#JobStatus name="JobStatus">JobStatus</a>

First included in: ProductionControl/ProdProductionOrderRouteJobEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the JobStatus attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RouteJobType name="RouteJobType">RouteJobType</a>

First included in: ProductionControl/ProdProductionOrderRouteJobEntity (this entity)  

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

### <a href=#NextOperationLink name="NextOperationLink">NextOperationLink</a>

First included in: ProductionControl/ProdProductionOrderRouteJobEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the NextOperationLink attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#NextOperationLinkType name="NextOperationLinkType">NextOperationLinkType</a>

First included in: ProductionControl/ProdProductionOrderRouteJobEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the NextOperationLinkType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PrimaryJobNumber name="PrimaryJobNumber">PrimaryJobNumber</a>

First included in: ProductionControl/ProdProductionOrderRouteJobEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrimaryJobNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SecondaryJobNumber name="SecondaryJobNumber">SecondaryJobNumber</a>

First included in: ProductionControl/ProdProductionOrderRouteJobEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SecondaryJobNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#JobSequence name="JobSequence">JobSequence</a>

First included in: ProductionControl/ProdProductionOrderRouteJobEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the JobSequence attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#OperationNumber name="OperationNumber">OperationNumber</a>

First included in: ProductionControl/ProdProductionOrderRouteJobEntity (this entity)  

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

First included in: ProductionControl/ProdProductionOrderRouteJobEntity (this entity)  

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

### <a href=#ProductionOrderNumber name="ProductionOrderNumber">ProductionOrderNumber</a>

First included in: ProductionControl/ProdProductionOrderRouteJobEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProductionOrderNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WorkingTimeSchedulingPropertyId name="WorkingTimeSchedulingPropertyId">WorkingTimeSchedulingPropertyId</a>

First included in: ProductionControl/ProdProductionOrderRouteJobEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WorkingTimeSchedulingPropertyId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ActualEndDate name="ActualEndDate">ActualEndDate</a>

First included in: ProductionControl/ProdProductionOrderRouteJobEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ActualEndDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ActualEndTime name="ActualEndTime">ActualEndTime</a>

First included in: ProductionControl/ProdProductionOrderRouteJobEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ActualEndTime attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ActualFromDate name="ActualFromDate">ActualFromDate</a>

First included in: ProductionControl/ProdProductionOrderRouteJobEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ActualFromDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ActualFromTime name="ActualFromTime">ActualFromTime</a>

First included in: ProductionControl/ProdProductionOrderRouteJobEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ActualFromTime attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsJobCancelled name="IsJobCancelled">IsJobCancelled</a>

First included in: ProductionControl/ProdProductionOrderRouteJobEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsJobCancelled attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ScheduledJobDurationHours name="ScheduledJobDurationHours">ScheduledJobDurationHours</a>

First included in: ProductionControl/ProdProductionOrderRouteJobEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ScheduledJobDurationHours attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ScheduledEndDate name="ScheduledEndDate">ScheduledEndDate</a>

First included in: ProductionControl/ProdProductionOrderRouteJobEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ScheduledEndDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#OperationsResourceId name="OperationsResourceId">OperationsResourceId</a>

First included in: ProductionControl/ProdProductionOrderRouteJobEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OperationsResourceId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ScheduledEndTime name="ScheduledEndTime">ScheduledEndTime</a>

First included in: ProductionControl/ProdProductionOrderRouteJobEntity (this entity)  

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

### <a href=#BackingTable_ProdRouteJobRelationshipId name="BackingTable_ProdRouteJobRelationshipId">BackingTable_ProdRouteJobRelationshipId</a>

First included in: ProductionControl/ProdProductionOrderRouteJobEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_ProdRouteJobRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/SupplyChain/ProductionControl/WorksheetLine/ProdRouteJob.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/ProductionControl/WorksheetLine/ProdRouteJob.cdm.json/ProdRouteJob</a></td><td><a href="../../../Tables/SupplyChain/ProductionControl/WorksheetLine/ProdRouteJob.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PrimaryCompanyContextRelationshipId name="Relationship_PrimaryCompanyContextRelationshipId">Relationship_PrimaryCompanyContextRelationshipId</a>

First included in: ProductionControl/ProdProductionOrderRouteJobEntity (this entity)  

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
