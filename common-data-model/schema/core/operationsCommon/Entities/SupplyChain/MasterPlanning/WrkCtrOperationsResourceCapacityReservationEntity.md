---
title: WrkCtrOperationsResourceCapacityReservationEntity in MasterPlanning - Common Data Model | Microsoft Docs
description: undefined
author: llawwaii

ms.reviewer: deonhe
ms.topic: reference
ms.date: 8/7/2020
ms.author: weiluo
---

# Operations resource capacity reservations in MasterPlanning(WrkCtrOperationsResourceCapacityReservationEntity)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/SupplyChain/MasterPlanning/WrkCtrOperationsResourceCapacityReservationEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.1"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Operations resource capacity reservations</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[ScheduledEndTime](#ScheduledEndTime)||<a href="WrkCtrOperationsResourceCapacityReservationEntity.md" target="_blank">MasterPlanning/WrkCtrOperationsResourceCapacityReservationEntity</a>|
|[ProductionOrderRouteJobId](#ProductionOrderRouteJobId)||<a href="WrkCtrOperationsResourceCapacityReservationEntity.md" target="_blank">MasterPlanning/WrkCtrOperationsResourceCapacityReservationEntity</a>|
|[IsReservationLocked](#IsReservationLocked)||<a href="WrkCtrOperationsResourceCapacityReservationEntity.md" target="_blank">MasterPlanning/WrkCtrOperationsResourceCapacityReservationEntity</a>|
|[CapacitySchedulingType](#CapacitySchedulingType)||<a href="WrkCtrOperationsResourceCapacityReservationEntity.md" target="_blank">MasterPlanning/WrkCtrOperationsResourceCapacityReservationEntity</a>|
|[RouteJobType](#RouteJobType)||<a href="WrkCtrOperationsResourceCapacityReservationEntity.md" target="_blank">MasterPlanning/WrkCtrOperationsResourceCapacityReservationEntity</a>|
|[RouteOperationNumber](#RouteOperationNumber)||<a href="WrkCtrOperationsResourceCapacityReservationEntity.md" target="_blank">MasterPlanning/WrkCtrOperationsResourceCapacityReservationEntity</a>|
|[RouteOperationPriority](#RouteOperationPriority)||<a href="WrkCtrOperationsResourceCapacityReservationEntity.md" target="_blank">MasterPlanning/WrkCtrOperationsResourceCapacityReservationEntity</a>|
|[PlanVersionRecId](#PlanVersionRecId)||<a href="WrkCtrOperationsResourceCapacityReservationEntity.md" target="_blank">MasterPlanning/WrkCtrOperationsResourceCapacityReservationEntity</a>|
|[WorkingTimeSchedulingPropertyId](#WorkingTimeSchedulingPropertyId)||<a href="WrkCtrOperationsResourceCapacityReservationEntity.md" target="_blank">MasterPlanning/WrkCtrOperationsResourceCapacityReservationEntity</a>|
|[RecordId](#RecordId)||<a href="WrkCtrOperationsResourceCapacityReservationEntity.md" target="_blank">MasterPlanning/WrkCtrOperationsResourceCapacityReservationEntity</a>|
|[CapacityReservationSeconds](#CapacityReservationSeconds)||<a href="WrkCtrOperationsResourceCapacityReservationEntity.md" target="_blank">MasterPlanning/WrkCtrOperationsResourceCapacityReservationEntity</a>|
|[LoadPercentage](#LoadPercentage)||<a href="WrkCtrOperationsResourceCapacityReservationEntity.md" target="_blank">MasterPlanning/WrkCtrOperationsResourceCapacityReservationEntity</a>|
|[ReservationReferenceNumber](#ReservationReferenceNumber)||<a href="WrkCtrOperationsResourceCapacityReservationEntity.md" target="_blank">MasterPlanning/WrkCtrOperationsResourceCapacityReservationEntity</a>|
|[ReservationSourceType](#ReservationSourceType)||<a href="WrkCtrOperationsResourceCapacityReservationEntity.md" target="_blank">MasterPlanning/WrkCtrOperationsResourceCapacityReservationEntity</a>|
|[ScheduledStartTime](#ScheduledStartTime)||<a href="WrkCtrOperationsResourceCapacityReservationEntity.md" target="_blank">MasterPlanning/WrkCtrOperationsResourceCapacityReservationEntity</a>|
|[ReservationDate](#ReservationDate)||<a href="WrkCtrOperationsResourceCapacityReservationEntity.md" target="_blank">MasterPlanning/WrkCtrOperationsResourceCapacityReservationEntity</a>|
|[ProductionOrderNumber](#ProductionOrderNumber)||<a href="WrkCtrOperationsResourceCapacityReservationEntity.md" target="_blank">MasterPlanning/WrkCtrOperationsResourceCapacityReservationEntity</a>|
|[ProjectId](#ProjectId)||<a href="WrkCtrOperationsResourceCapacityReservationEntity.md" target="_blank">MasterPlanning/WrkCtrOperationsResourceCapacityReservationEntity</a>|
|[ProjectActivityId](#ProjectActivityId)||<a href="WrkCtrOperationsResourceCapacityReservationEntity.md" target="_blank">MasterPlanning/WrkCtrOperationsResourceCapacityReservationEntity</a>|
|[PlannedOrderNumber](#PlannedOrderNumber)||<a href="WrkCtrOperationsResourceCapacityReservationEntity.md" target="_blank">MasterPlanning/WrkCtrOperationsResourceCapacityReservationEntity</a>|
|[RequirementPlanId](#RequirementPlanId)||<a href="WrkCtrOperationsResourceCapacityReservationEntity.md" target="_blank">MasterPlanning/WrkCtrOperationsResourceCapacityReservationEntity</a>|
|[ReserveHours](#ReserveHours)||<a href="WrkCtrOperationsResourceCapacityReservationEntity.md" target="_blank">MasterPlanning/WrkCtrOperationsResourceCapacityReservationEntity</a>|
|[OperationsResourceId](#OperationsResourceId)||<a href="WrkCtrOperationsResourceCapacityReservationEntity.md" target="_blank">MasterPlanning/WrkCtrOperationsResourceCapacityReservationEntity</a>|
|[BackingTable_WrkCtrCapResRelationshipId](#BackingTable_WrkCtrCapResRelationshipId)||<a href="WrkCtrOperationsResourceCapacityReservationEntity.md" target="_blank">MasterPlanning/WrkCtrOperationsResourceCapacityReservationEntity</a>|
|[Relationship_PrimaryCompanyContextRelationshipId](#Relationship_PrimaryCompanyContextRelationshipId)||<a href="WrkCtrOperationsResourceCapacityReservationEntity.md" target="_blank">MasterPlanning/WrkCtrOperationsResourceCapacityReservationEntity</a>|

### <a href=#ScheduledEndTime name="ScheduledEndTime">ScheduledEndTime</a>

First included in: MasterPlanning/WrkCtrOperationsResourceCapacityReservationEntity (this entity)  

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

### <a href=#ProductionOrderRouteJobId name="ProductionOrderRouteJobId">ProductionOrderRouteJobId</a>

First included in: MasterPlanning/WrkCtrOperationsResourceCapacityReservationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProductionOrderRouteJobId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsReservationLocked name="IsReservationLocked">IsReservationLocked</a>

First included in: MasterPlanning/WrkCtrOperationsResourceCapacityReservationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsReservationLocked attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CapacitySchedulingType name="CapacitySchedulingType">CapacitySchedulingType</a>

First included in: MasterPlanning/WrkCtrOperationsResourceCapacityReservationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CapacitySchedulingType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RouteJobType name="RouteJobType">RouteJobType</a>

First included in: MasterPlanning/WrkCtrOperationsResourceCapacityReservationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RouteJobType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RouteOperationNumber name="RouteOperationNumber">RouteOperationNumber</a>

First included in: MasterPlanning/WrkCtrOperationsResourceCapacityReservationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RouteOperationNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RouteOperationPriority name="RouteOperationPriority">RouteOperationPriority</a>

First included in: MasterPlanning/WrkCtrOperationsResourceCapacityReservationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RouteOperationPriority attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PlanVersionRecId name="PlanVersionRecId">PlanVersionRecId</a>

First included in: MasterPlanning/WrkCtrOperationsResourceCapacityReservationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PlanVersionRecId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WorkingTimeSchedulingPropertyId name="WorkingTimeSchedulingPropertyId">WorkingTimeSchedulingPropertyId</a>

First included in: MasterPlanning/WrkCtrOperationsResourceCapacityReservationEntity (this entity)  

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

### <a href=#RecordId name="RecordId">RecordId</a>

First included in: MasterPlanning/WrkCtrOperationsResourceCapacityReservationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecordId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CapacityReservationSeconds name="CapacityReservationSeconds">CapacityReservationSeconds</a>

First included in: MasterPlanning/WrkCtrOperationsResourceCapacityReservationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CapacityReservationSeconds attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LoadPercentage name="LoadPercentage">LoadPercentage</a>

First included in: MasterPlanning/WrkCtrOperationsResourceCapacityReservationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LoadPercentage attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ReservationReferenceNumber name="ReservationReferenceNumber">ReservationReferenceNumber</a>

First included in: MasterPlanning/WrkCtrOperationsResourceCapacityReservationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReservationReferenceNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ReservationSourceType name="ReservationSourceType">ReservationSourceType</a>

First included in: MasterPlanning/WrkCtrOperationsResourceCapacityReservationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReservationSourceType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ScheduledStartTime name="ScheduledStartTime">ScheduledStartTime</a>

First included in: MasterPlanning/WrkCtrOperationsResourceCapacityReservationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ScheduledStartTime attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ReservationDate name="ReservationDate">ReservationDate</a>

First included in: MasterPlanning/WrkCtrOperationsResourceCapacityReservationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReservationDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProductionOrderNumber name="ProductionOrderNumber">ProductionOrderNumber</a>

First included in: MasterPlanning/WrkCtrOperationsResourceCapacityReservationEntity (this entity)  

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

### <a href=#ProjectId name="ProjectId">ProjectId</a>

First included in: MasterPlanning/WrkCtrOperationsResourceCapacityReservationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProjectId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProjectActivityId name="ProjectActivityId">ProjectActivityId</a>

First included in: MasterPlanning/WrkCtrOperationsResourceCapacityReservationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProjectActivityId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PlannedOrderNumber name="PlannedOrderNumber">PlannedOrderNumber</a>

First included in: MasterPlanning/WrkCtrOperationsResourceCapacityReservationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PlannedOrderNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RequirementPlanId name="RequirementPlanId">RequirementPlanId</a>

First included in: MasterPlanning/WrkCtrOperationsResourceCapacityReservationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RequirementPlanId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ReserveHours name="ReserveHours">ReserveHours</a>

First included in: MasterPlanning/WrkCtrOperationsResourceCapacityReservationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReserveHours attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#OperationsResourceId name="OperationsResourceId">OperationsResourceId</a>

First included in: MasterPlanning/WrkCtrOperationsResourceCapacityReservationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OperationsResourceId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BackingTable_WrkCtrCapResRelationshipId name="BackingTable_WrkCtrCapResRelationshipId">BackingTable_WrkCtrCapResRelationshipId</a>

First included in: MasterPlanning/WrkCtrOperationsResourceCapacityReservationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_WrkCtrCapResRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/SupplyChain/MasterPlanning/Transaction/WrkCtrCapRes.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/MasterPlanning/Transaction/WrkCtrCapRes.cdm.json/WrkCtrCapRes</a></td><td><a href="../../../Tables/SupplyChain/MasterPlanning/Transaction/WrkCtrCapRes.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PrimaryCompanyContextRelationshipId name="Relationship_PrimaryCompanyContextRelationshipId">Relationship_PrimaryCompanyContextRelationshipId</a>

First included in: MasterPlanning/WrkCtrOperationsResourceCapacityReservationEntity (this entity)  

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
