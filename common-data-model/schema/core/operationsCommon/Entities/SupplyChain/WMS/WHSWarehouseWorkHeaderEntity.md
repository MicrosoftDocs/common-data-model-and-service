---
title: WHSWarehouseWorkHeaderEntity in WMS - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 7/10/2020
ms.author: nebanfic
---

# Warehouse work headers in WMS(WHSWarehouseWorkHeaderEntity)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/SupplyChain/WMS/WHSWarehouseWorkHeaderEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Warehouse work headers</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[ActualProcessingTimeSeconds](#ActualProcessingTimeSeconds)||<a href="WHSWarehouseWorkHeaderEntity.md" target="_blank">WMS/WHSWarehouseWorkHeaderEntity</a>|
|[ContainerId](#ContainerId)||<a href="WHSWarehouseWorkHeaderEntity.md" target="_blank">WMS/WHSWarehouseWorkHeaderEntity</a>|
|[EstimatedProcessingTimeSeconds](#EstimatedProcessingTimeSeconds)||<a href="WHSWarehouseWorkHeaderEntity.md" target="_blank">WMS/WHSWarehouseWorkHeaderEntity</a>|
|[IsWarehouseWorkBlocked](#IsWarehouseWorkBlocked)||<a href="WHSWarehouseWorkHeaderEntity.md" target="_blank">WMS/WHSWarehouseWorkHeaderEntity</a>|
|[WarehouseId](#WarehouseId)||<a href="WHSWarehouseWorkHeaderEntity.md" target="_blank">WMS/WHSWarehouseWorkHeaderEntity</a>|
|[InventorySiteId](#InventorySiteId)||<a href="WHSWarehouseWorkHeaderEntity.md" target="_blank">WMS/WHSWarehouseWorkHeaderEntity</a>|
|[LoadId](#LoadId)||<a href="WHSWarehouseWorkHeaderEntity.md" target="_blank">WMS/WHSWarehouseWorkHeaderEntity</a>|
|[WarehouseWorkLockingWarehouseMobileDeviceUserId](#WarehouseWorkLockingWarehouseMobileDeviceUserId)||<a href="WHSWarehouseWorkHeaderEntity.md" target="_blank">WMS/WHSWarehouseWorkHeaderEntity</a>|
|[SourceOrderNumber](#SourceOrderNumber)||<a href="WHSWarehouseWorkHeaderEntity.md" target="_blank">WMS/WHSWarehouseWorkHeaderEntity</a>|
|[ShipmentId](#ShipmentId)||<a href="WHSWarehouseWorkHeaderEntity.md" target="_blank">WMS/WHSWarehouseWorkHeaderEntity</a>|
|[TargetLicensePlateNumber](#TargetLicensePlateNumber)||<a href="WHSWarehouseWorkHeaderEntity.md" target="_blank">WMS/WHSWarehouseWorkHeaderEntity</a>|
|[IsWarehouseWorkerManuallyAssigned](#IsWarehouseWorkerManuallyAssigned)||<a href="WHSWarehouseWorkHeaderEntity.md" target="_blank">WMS/WHSWarehouseWorkHeaderEntity</a>|
|[WaveId](#WaveId)||<a href="WHSWarehouseWorkHeaderEntity.md" target="_blank">WMS/WHSWarehouseWorkHeaderEntity</a>|
|[WarehouseWorkCancellingUserId](#WarehouseWorkCancellingUserId)||<a href="WHSWarehouseWorkHeaderEntity.md" target="_blank">WMS/WHSWarehouseWorkHeaderEntity</a>|
|[WarehouseWorkCancelledDateTime](#WarehouseWorkCancelledDateTime)||<a href="WHSWarehouseWorkHeaderEntity.md" target="_blank">WMS/WHSWarehouseWorkHeaderEntity</a>|
|[WarehouseWorkClosedDateTime](#WarehouseWorkClosedDateTime)||<a href="WHSWarehouseWorkHeaderEntity.md" target="_blank">WMS/WHSWarehouseWorkHeaderEntity</a>|
|[WarehouseWorkId](#WarehouseWorkId)||<a href="WHSWarehouseWorkHeaderEntity.md" target="_blank">WMS/WHSWarehouseWorkHeaderEntity</a>|
|[WarehouseWorkProcessingStartDateTime](#WarehouseWorkProcessingStartDateTime)||<a href="WHSWarehouseWorkHeaderEntity.md" target="_blank">WMS/WHSWarehouseWorkHeaderEntity</a>|
|[WarehouseWorkManuallyCompletingUserId](#WarehouseWorkManuallyCompletingUserId)||<a href="WHSWarehouseWorkHeaderEntity.md" target="_blank">WMS/WHSWarehouseWorkHeaderEntity</a>|
|[WarehouseWorkPoolId](#WarehouseWorkPoolId)||<a href="WHSWarehouseWorkHeaderEntity.md" target="_blank">WMS/WHSWarehouseWorkHeaderEntity</a>|
|[WarehouseWorkPriority](#WarehouseWorkPriority)||<a href="WHSWarehouseWorkHeaderEntity.md" target="_blank">WMS/WHSWarehouseWorkHeaderEntity</a>|
|[WarehouseWorkStatus](#WarehouseWorkStatus)||<a href="WHSWarehouseWorkHeaderEntity.md" target="_blank">WMS/WHSWarehouseWorkHeaderEntity</a>|
|[WarehouseWorkOrderType](#WarehouseWorkOrderType)||<a href="WHSWarehouseWorkHeaderEntity.md" target="_blank">WMS/WHSWarehouseWorkHeaderEntity</a>|
|[BackingTable_WHSWorkTableRelationshipId](#BackingTable_WHSWorkTableRelationshipId)||<a href="WHSWarehouseWorkHeaderEntity.md" target="_blank">WMS/WHSWarehouseWorkHeaderEntity</a>|
|[Relationship_PrimaryCompanyContextRelationshipId](#Relationship_PrimaryCompanyContextRelationshipId)||<a href="WHSWarehouseWorkHeaderEntity.md" target="_blank">WMS/WHSWarehouseWorkHeaderEntity</a>|

### <a href=#ActualProcessingTimeSeconds name="ActualProcessingTimeSeconds">ActualProcessingTimeSeconds</a>

First included in: WMS/WHSWarehouseWorkHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ActualProcessingTimeSeconds attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ContainerId name="ContainerId">ContainerId</a>

First included in: WMS/WHSWarehouseWorkHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ContainerId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#EstimatedProcessingTimeSeconds name="EstimatedProcessingTimeSeconds">EstimatedProcessingTimeSeconds</a>

First included in: WMS/WHSWarehouseWorkHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EstimatedProcessingTimeSeconds attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsWarehouseWorkBlocked name="IsWarehouseWorkBlocked">IsWarehouseWorkBlocked</a>

First included in: WMS/WHSWarehouseWorkHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsWarehouseWorkBlocked attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WarehouseId name="WarehouseId">WarehouseId</a>

First included in: WMS/WHSWarehouseWorkHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WarehouseId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InventorySiteId name="InventorySiteId">InventorySiteId</a>

First included in: WMS/WHSWarehouseWorkHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InventorySiteId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LoadId name="LoadId">LoadId</a>

First included in: WMS/WHSWarehouseWorkHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LoadId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WarehouseWorkLockingWarehouseMobileDeviceUserId name="WarehouseWorkLockingWarehouseMobileDeviceUserId">WarehouseWorkLockingWarehouseMobileDeviceUserId</a>

First included in: WMS/WHSWarehouseWorkHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WarehouseWorkLockingWarehouseMobileDeviceUserId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SourceOrderNumber name="SourceOrderNumber">SourceOrderNumber</a>

First included in: WMS/WHSWarehouseWorkHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SourceOrderNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ShipmentId name="ShipmentId">ShipmentId</a>

First included in: WMS/WHSWarehouseWorkHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ShipmentId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TargetLicensePlateNumber name="TargetLicensePlateNumber">TargetLicensePlateNumber</a>

First included in: WMS/WHSWarehouseWorkHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TargetLicensePlateNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsWarehouseWorkerManuallyAssigned name="IsWarehouseWorkerManuallyAssigned">IsWarehouseWorkerManuallyAssigned</a>

First included in: WMS/WHSWarehouseWorkHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsWarehouseWorkerManuallyAssigned attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WaveId name="WaveId">WaveId</a>

First included in: WMS/WHSWarehouseWorkHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WaveId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WarehouseWorkCancellingUserId name="WarehouseWorkCancellingUserId">WarehouseWorkCancellingUserId</a>

First included in: WMS/WHSWarehouseWorkHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WarehouseWorkCancellingUserId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WarehouseWorkCancelledDateTime name="WarehouseWorkCancelledDateTime">WarehouseWorkCancelledDateTime</a>

First included in: WMS/WHSWarehouseWorkHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WarehouseWorkCancelledDateTime attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WarehouseWorkClosedDateTime name="WarehouseWorkClosedDateTime">WarehouseWorkClosedDateTime</a>

First included in: WMS/WHSWarehouseWorkHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WarehouseWorkClosedDateTime attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WarehouseWorkId name="WarehouseWorkId">WarehouseWorkId</a>

First included in: WMS/WHSWarehouseWorkHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WarehouseWorkId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WarehouseWorkProcessingStartDateTime name="WarehouseWorkProcessingStartDateTime">WarehouseWorkProcessingStartDateTime</a>

First included in: WMS/WHSWarehouseWorkHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WarehouseWorkProcessingStartDateTime attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WarehouseWorkManuallyCompletingUserId name="WarehouseWorkManuallyCompletingUserId">WarehouseWorkManuallyCompletingUserId</a>

First included in: WMS/WHSWarehouseWorkHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WarehouseWorkManuallyCompletingUserId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WarehouseWorkPoolId name="WarehouseWorkPoolId">WarehouseWorkPoolId</a>

First included in: WMS/WHSWarehouseWorkHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WarehouseWorkPoolId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WarehouseWorkPriority name="WarehouseWorkPriority">WarehouseWorkPriority</a>

First included in: WMS/WHSWarehouseWorkHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WarehouseWorkPriority attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WarehouseWorkStatus name="WarehouseWorkStatus">WarehouseWorkStatus</a>

First included in: WMS/WHSWarehouseWorkHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WarehouseWorkStatus attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WarehouseWorkOrderType name="WarehouseWorkOrderType">WarehouseWorkOrderType</a>

First included in: WMS/WHSWarehouseWorkHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WarehouseWorkOrderType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BackingTable_WHSWorkTableRelationshipId name="BackingTable_WHSWorkTableRelationshipId">BackingTable_WHSWorkTableRelationshipId</a>

First included in: WMS/WHSWarehouseWorkHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_WHSWorkTableRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/SupplyChain/Inventory/WorksheetHeader/WHSWorkTable.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/Inventory/WorksheetHeader/WHSWorkTable.cdm.json/WHSWorkTable</a></td><td><a href="../../../Tables/SupplyChain/Inventory/WorksheetHeader/WHSWorkTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PrimaryCompanyContextRelationshipId name="Relationship_PrimaryCompanyContextRelationshipId">Relationship_PrimaryCompanyContextRelationshipId</a>

First included in: WMS/WHSWarehouseWorkHeaderEntity (this entity)  

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
