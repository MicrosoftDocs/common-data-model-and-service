---
title: ReqPlannedOrderRouteJobEntity - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/29/2020
ms.author: nebanfic
---

# Planned order route jobs

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/SupplyChain/MasterPlanning/ReqPlannedOrderRouteJobEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Planned order route jobs</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[CalculatedJobDurationHours](#CalculatedJobDurationHours)||<a href="ReqPlannedOrderRouteJobEntity.md" target="_blank">MasterPlanning/ReqPlannedOrderRouteJobEntity</a>|
|[ScheduledStartDate](#ScheduledStartDate)||<a href="ReqPlannedOrderRouteJobEntity.md" target="_blank">MasterPlanning/ReqPlannedOrderRouteJobEntity</a>|
|[ScheduledStartTime](#ScheduledStartTime)||<a href="ReqPlannedOrderRouteJobEntity.md" target="_blank">MasterPlanning/ReqPlannedOrderRouteJobEntity</a>|
|[IsJobManagementUsed](#IsJobManagementUsed)||<a href="ReqPlannedOrderRouteJobEntity.md" target="_blank">MasterPlanning/ReqPlannedOrderRouteJobEntity</a>|
|[RouteJobType](#RouteJobType)||<a href="ReqPlannedOrderRouteJobEntity.md" target="_blank">MasterPlanning/ReqPlannedOrderRouteJobEntity</a>|
|[NextOperationLink](#NextOperationLink)||<a href="ReqPlannedOrderRouteJobEntity.md" target="_blank">MasterPlanning/ReqPlannedOrderRouteJobEntity</a>|
|[NextOperationLinkType](#NextOperationLinkType)||<a href="ReqPlannedOrderRouteJobEntity.md" target="_blank">MasterPlanning/ReqPlannedOrderRouteJobEntity</a>|
|[PrimaryJobNumber](#PrimaryJobNumber)||<a href="ReqPlannedOrderRouteJobEntity.md" target="_blank">MasterPlanning/ReqPlannedOrderRouteJobEntity</a>|
|[SecondaryJobNumber](#SecondaryJobNumber)||<a href="ReqPlannedOrderRouteJobEntity.md" target="_blank">MasterPlanning/ReqPlannedOrderRouteJobEntity</a>|
|[JobSequence](#JobSequence)||<a href="ReqPlannedOrderRouteJobEntity.md" target="_blank">MasterPlanning/ReqPlannedOrderRouteJobEntity</a>|
|[RouteOperationNumber](#RouteOperationNumber)||<a href="ReqPlannedOrderRouteJobEntity.md" target="_blank">MasterPlanning/ReqPlannedOrderRouteJobEntity</a>|
|[RouteOperationPriority](#RouteOperationPriority)||<a href="ReqPlannedOrderRouteJobEntity.md" target="_blank">MasterPlanning/ReqPlannedOrderRouteJobEntity</a>|
|[WorkingTimeSchedulingPropertyId](#WorkingTimeSchedulingPropertyId)||<a href="ReqPlannedOrderRouteJobEntity.md" target="_blank">MasterPlanning/ReqPlannedOrderRouteJobEntity</a>|
|[PlannedOrderNumber](#PlannedOrderNumber)||<a href="ReqPlannedOrderRouteJobEntity.md" target="_blank">MasterPlanning/ReqPlannedOrderRouteJobEntity</a>|
|[IsJobCancelled](#IsJobCancelled)||<a href="ReqPlannedOrderRouteJobEntity.md" target="_blank">MasterPlanning/ReqPlannedOrderRouteJobEntity</a>|
|[ScheduledJobDurationHours](#ScheduledJobDurationHours)||<a href="ReqPlannedOrderRouteJobEntity.md" target="_blank">MasterPlanning/ReqPlannedOrderRouteJobEntity</a>|
|[ScheduledEndDate](#ScheduledEndDate)||<a href="ReqPlannedOrderRouteJobEntity.md" target="_blank">MasterPlanning/ReqPlannedOrderRouteJobEntity</a>|
|[ScheduledEndTime](#ScheduledEndTime)||<a href="ReqPlannedOrderRouteJobEntity.md" target="_blank">MasterPlanning/ReqPlannedOrderRouteJobEntity</a>|
|[OperationsResourceId](#OperationsResourceId)||<a href="ReqPlannedOrderRouteJobEntity.md" target="_blank">MasterPlanning/ReqPlannedOrderRouteJobEntity</a>|
|[RequirementPlanId](#RequirementPlanId)||<a href="ReqPlannedOrderRouteJobEntity.md" target="_blank">MasterPlanning/ReqPlannedOrderRouteJobEntity</a>|
|[RouteJobDataAreaId](#RouteJobDataAreaId)||<a href="ReqPlannedOrderRouteJobEntity.md" target="_blank">MasterPlanning/ReqPlannedOrderRouteJobEntity</a>|
|[BackingTable_ReqRouteJobRelationshipId](#BackingTable_ReqRouteJobRelationshipId)||<a href="ReqPlannedOrderRouteJobEntity.md" target="_blank">MasterPlanning/ReqPlannedOrderRouteJobEntity</a>|
|[Relationship_PrimaryCompanyContextRelationshipId](#Relationship_PrimaryCompanyContextRelationshipId)||<a href="ReqPlannedOrderRouteJobEntity.md" target="_blank">MasterPlanning/ReqPlannedOrderRouteJobEntity</a>|

### <a href=#CalculatedJobDurationHours name="CalculatedJobDurationHours">CalculatedJobDurationHours</a>

First included in: MasterPlanning/ReqPlannedOrderRouteJobEntity (this entity)  

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

### <a href=#ScheduledStartDate name="ScheduledStartDate">ScheduledStartDate</a>

First included in: MasterPlanning/ReqPlannedOrderRouteJobEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ScheduledStartDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ScheduledStartTime name="ScheduledStartTime">ScheduledStartTime</a>

First included in: MasterPlanning/ReqPlannedOrderRouteJobEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ScheduledStartTime attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsJobManagementUsed name="IsJobManagementUsed">IsJobManagementUsed</a>

First included in: MasterPlanning/ReqPlannedOrderRouteJobEntity (this entity)  

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

### <a href=#RouteJobType name="RouteJobType">RouteJobType</a>

First included in: MasterPlanning/ReqPlannedOrderRouteJobEntity (this entity)  

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

First included in: MasterPlanning/ReqPlannedOrderRouteJobEntity (this entity)  

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

First included in: MasterPlanning/ReqPlannedOrderRouteJobEntity (this entity)  

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

First included in: MasterPlanning/ReqPlannedOrderRouteJobEntity (this entity)  

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

First included in: MasterPlanning/ReqPlannedOrderRouteJobEntity (this entity)  

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

First included in: MasterPlanning/ReqPlannedOrderRouteJobEntity (this entity)  

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

### <a href=#RouteOperationNumber name="RouteOperationNumber">RouteOperationNumber</a>

First included in: MasterPlanning/ReqPlannedOrderRouteJobEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Operation number</td></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RouteOperationNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Operation number</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RouteOperationPriority name="RouteOperationPriority">RouteOperationPriority</a>

First included in: MasterPlanning/ReqPlannedOrderRouteJobEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RouteOperationPriority attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WorkingTimeSchedulingPropertyId name="WorkingTimeSchedulingPropertyId">WorkingTimeSchedulingPropertyId</a>

First included in: MasterPlanning/ReqPlannedOrderRouteJobEntity (this entity)  

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

### <a href=#PlannedOrderNumber name="PlannedOrderNumber">PlannedOrderNumber</a>

First included in: MasterPlanning/ReqPlannedOrderRouteJobEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Planned order number</td></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PlannedOrderNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Planned order number</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsJobCancelled name="IsJobCancelled">IsJobCancelled</a>

First included in: MasterPlanning/ReqPlannedOrderRouteJobEntity (this entity)  

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

First included in: MasterPlanning/ReqPlannedOrderRouteJobEntity (this entity)  

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

First included in: MasterPlanning/ReqPlannedOrderRouteJobEntity (this entity)  

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

### <a href=#ScheduledEndTime name="ScheduledEndTime">ScheduledEndTime</a>

First included in: MasterPlanning/ReqPlannedOrderRouteJobEntity (this entity)  

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

### <a href=#OperationsResourceId name="OperationsResourceId">OperationsResourceId</a>

First included in: MasterPlanning/ReqPlannedOrderRouteJobEntity (this entity)  

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

### <a href=#RequirementPlanId name="RequirementPlanId">RequirementPlanId</a>

First included in: MasterPlanning/ReqPlannedOrderRouteJobEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Requirement plan ID</td></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RequirementPlanId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Requirement plan ID</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RouteJobDataAreaId name="RouteJobDataAreaId">RouteJobDataAreaId</a>

First included in: MasterPlanning/ReqPlannedOrderRouteJobEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RouteJobDataAreaId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BackingTable_ReqRouteJobRelationshipId name="BackingTable_ReqRouteJobRelationshipId">BackingTable_ReqRouteJobRelationshipId</a>

First included in: MasterPlanning/ReqPlannedOrderRouteJobEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_ReqRouteJobRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/SupplyChain/MasterPlanning/WorksheetLine/ReqRouteJob.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/MasterPlanning/WorksheetLine/ReqRouteJob.cdm.json/ReqRouteJob</a></td><td><a href="../../../Tables/SupplyChain/MasterPlanning/WorksheetLine/ReqRouteJob.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PrimaryCompanyContextRelationshipId name="Relationship_PrimaryCompanyContextRelationshipId">Relationship_PrimaryCompanyContextRelationshipId</a>

First included in: MasterPlanning/ReqPlannedOrderRouteJobEntity (this entity)  

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
