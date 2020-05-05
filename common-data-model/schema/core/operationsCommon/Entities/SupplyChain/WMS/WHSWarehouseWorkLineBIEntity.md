---
title: WHSWarehouseWorkLineBIEntity - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 5/5/2020
ms.author: nebanfic
---

# Work lines

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/SupplyChain/WMS/WHSWarehouseWorkLineBIEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Work lines</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[ActualWorkLineProcessingTime](#ActualWorkLineProcessingTime)||<a href="WHSWarehouseWorkLineBIEntity.md" target="_blank">WMS/WHSWarehouseWorkLineBIEntity</a>|
|[ActualWorkProcessingTime](#ActualWorkProcessingTime)||<a href="WHSWarehouseWorkLineBIEntity.md" target="_blank">WMS/WHSWarehouseWorkLineBIEntity</a>|
|[ContainerId](#ContainerId)||<a href="WHSWarehouseWorkLineBIEntity.md" target="_blank">WMS/WHSWarehouseWorkLineBIEntity</a>|
|[EstimatedWorkLineProcessingTime](#EstimatedWorkLineProcessingTime)||<a href="WHSWarehouseWorkLineBIEntity.md" target="_blank">WMS/WHSWarehouseWorkLineBIEntity</a>|
|[EstimatedWorkProcessingTime](#EstimatedWorkProcessingTime)||<a href="WHSWarehouseWorkLineBIEntity.md" target="_blank">WMS/WHSWarehouseWorkLineBIEntity</a>|
|[InventoryGTDNumber](#InventoryGTDNumber)||<a href="WHSWarehouseWorkLineBIEntity.md" target="_blank">WMS/WHSWarehouseWorkLineBIEntity</a>|
|[InventoryOwnerId](#InventoryOwnerId)||<a href="WHSWarehouseWorkLineBIEntity.md" target="_blank">WMS/WHSWarehouseWorkLineBIEntity</a>|
|[InventoryProfileId](#InventoryProfileId)||<a href="WHSWarehouseWorkLineBIEntity.md" target="_blank">WMS/WHSWarehouseWorkLineBIEntity</a>|
|[InventoryStatusId](#InventoryStatusId)||<a href="WHSWarehouseWorkLineBIEntity.md" target="_blank">WMS/WHSWarehouseWorkLineBIEntity</a>|
|[ItemBatchNumber](#ItemBatchNumber)||<a href="WHSWarehouseWorkLineBIEntity.md" target="_blank">WMS/WHSWarehouseWorkLineBIEntity</a>|
|[ItemNumber](#ItemNumber)||<a href="WHSWarehouseWorkLineBIEntity.md" target="_blank">WMS/WHSWarehouseWorkLineBIEntity</a>|
|[ItemSerialNumber](#ItemSerialNumber)||<a href="WHSWarehouseWorkLineBIEntity.md" target="_blank">WMS/WHSWarehouseWorkLineBIEntity</a>|
|[IsWorkFrozen](#IsWorkFrozen)||<a href="WHSWarehouseWorkLineBIEntity.md" target="_blank">WMS/WHSWarehouseWorkLineBIEntity</a>|
|[IsWorkStepMandatory](#IsWorkStepMandatory)||<a href="WHSWarehouseWorkLineBIEntity.md" target="_blank">WMS/WHSWarehouseWorkLineBIEntity</a>|
|[IsWorkStepSkipped](#IsWorkStepSkipped)||<a href="WHSWarehouseWorkLineBIEntity.md" target="_blank">WMS/WHSWarehouseWorkLineBIEntity</a>|
|[IsWorkStepStopped](#IsWorkStepStopped)||<a href="WHSWarehouseWorkLineBIEntity.md" target="_blank">WMS/WHSWarehouseWorkLineBIEntity</a>|
|[LoadId](#LoadId)||<a href="WHSWarehouseWorkLineBIEntity.md" target="_blank">WMS/WHSWarehouseWorkLineBIEntity</a>|
|[PhysicalAvailableInventoryQuantity](#PhysicalAvailableInventoryQuantity)||<a href="WHSWarehouseWorkLineBIEntity.md" target="_blank">WMS/WHSWarehouseWorkLineBIEntity</a>|
|[ProductColorId](#ProductColorId)||<a href="WHSWarehouseWorkLineBIEntity.md" target="_blank">WMS/WHSWarehouseWorkLineBIEntity</a>|
|[ProductConfigurationId](#ProductConfigurationId)||<a href="WHSWarehouseWorkLineBIEntity.md" target="_blank">WMS/WHSWarehouseWorkLineBIEntity</a>|
|[ProductionPickOrderNumber](#ProductionPickOrderNumber)||<a href="WHSWarehouseWorkLineBIEntity.md" target="_blank">WMS/WHSWarehouseWorkLineBIEntity</a>|
|[ProductionPutOrderNumber](#ProductionPutOrderNumber)||<a href="WHSWarehouseWorkLineBIEntity.md" target="_blank">WMS/WHSWarehouseWorkLineBIEntity</a>|
|[ProductSizeId](#ProductSizeId)||<a href="WHSWarehouseWorkLineBIEntity.md" target="_blank">WMS/WHSWarehouseWorkLineBIEntity</a>|
|[ProductStyleId](#ProductStyleId)||<a href="WHSWarehouseWorkLineBIEntity.md" target="_blank">WMS/WHSWarehouseWorkLineBIEntity</a>|
|[ProductVersionId](#ProductVersionId)||<a href="WHSWarehouseWorkLineBIEntity.md" target="_blank">WMS/WHSWarehouseWorkLineBIEntity</a>|
|[PurchaseOrderNumber](#PurchaseOrderNumber)||<a href="WHSWarehouseWorkLineBIEntity.md" target="_blank">WMS/WHSWarehouseWorkLineBIEntity</a>|
|[RemainingInventoryQuantity](#RemainingInventoryQuantity)||<a href="WHSWarehouseWorkLineBIEntity.md" target="_blank">WMS/WHSWarehouseWorkLineBIEntity</a>|
|[RemainingWorkQuantity](#RemainingWorkQuantity)||<a href="WHSWarehouseWorkLineBIEntity.md" target="_blank">WMS/WHSWarehouseWorkLineBIEntity</a>|
|[SalesOrderNumber](#SalesOrderNumber)||<a href="WHSWarehouseWorkLineBIEntity.md" target="_blank">WMS/WHSWarehouseWorkLineBIEntity</a>|
|[ShipmentId](#ShipmentId)||<a href="WHSWarehouseWorkLineBIEntity.md" target="_blank">WMS/WHSWarehouseWorkLineBIEntity</a>|
|[SortOrderCode](#SortOrderCode)||<a href="WHSWarehouseWorkLineBIEntity.md" target="_blank">WMS/WHSWarehouseWorkLineBIEntity</a>|
|[TargetLicensePlateId](#TargetLicensePlateId)||<a href="WHSWarehouseWorkLineBIEntity.md" target="_blank">WMS/WHSWarehouseWorkLineBIEntity</a>|
|[TransferIssueOrderNumber](#TransferIssueOrderNumber)||<a href="WHSWarehouseWorkLineBIEntity.md" target="_blank">WMS/WHSWarehouseWorkLineBIEntity</a>|
|[TransferReceiptOrderNumber](#TransferReceiptOrderNumber)||<a href="WHSWarehouseWorkLineBIEntity.md" target="_blank">WMS/WHSWarehouseWorkLineBIEntity</a>|
|[UnitSymbol](#UnitSymbol)||<a href="WHSWarehouseWorkLineBIEntity.md" target="_blank">WMS/WHSWarehouseWorkLineBIEntity</a>|
|[WarehouseMobileDeviceUserId](#WarehouseMobileDeviceUserId)||<a href="WHSWarehouseWorkLineBIEntity.md" target="_blank">WMS/WHSWarehouseWorkLineBIEntity</a>|
|[WarehouseWorkBuildId](#WarehouseWorkBuildId)||<a href="WHSWarehouseWorkLineBIEntity.md" target="_blank">WMS/WHSWarehouseWorkLineBIEntity</a>|
|[WarehouseWorkClassId](#WarehouseWorkClassId)||<a href="WHSWarehouseWorkLineBIEntity.md" target="_blank">WMS/WHSWarehouseWorkLineBIEntity</a>|
|[WarehouseWorkPoolId](#WarehouseWorkPoolId)||<a href="WHSWarehouseWorkLineBIEntity.md" target="_blank">WMS/WHSWarehouseWorkLineBIEntity</a>|
|[WarehouseWorkTemplateId](#WarehouseWorkTemplateId)||<a href="WHSWarehouseWorkLineBIEntity.md" target="_blank">WMS/WHSWarehouseWorkLineBIEntity</a>|
|[WarehouseId](#WarehouseId)||<a href="WHSWarehouseWorkLineBIEntity.md" target="_blank">WMS/WHSWarehouseWorkLineBIEntity</a>|
|[WarehouseLocationId](#WarehouseLocationId)||<a href="WHSWarehouseWorkLineBIEntity.md" target="_blank">WMS/WHSWarehouseWorkLineBIEntity</a>|
|[WarehouseWaveId](#WarehouseWaveId)||<a href="WHSWarehouseWorkLineBIEntity.md" target="_blank">WMS/WHSWarehouseWorkLineBIEntity</a>|
|[WarehouseWorkId](#WarehouseWorkId)||<a href="WHSWarehouseWorkLineBIEntity.md" target="_blank">WMS/WHSWarehouseWorkLineBIEntity</a>|
|[WarehouseZoneId](#WarehouseZoneId)||<a href="WHSWarehouseWorkLineBIEntity.md" target="_blank">WMS/WHSWarehouseWorkLineBIEntity</a>|
|[WorkClosedDateTime](#WorkClosedDateTime)||<a href="WHSWarehouseWorkLineBIEntity.md" target="_blank">WMS/WHSWarehouseWorkLineBIEntity</a>|
|[WorkCreatedDateTime](#WorkCreatedDateTime)||<a href="WHSWarehouseWorkLineBIEntity.md" target="_blank">WMS/WHSWarehouseWorkLineBIEntity</a>|
|[WorkInventoryQuantity](#WorkInventoryQuantity)||<a href="WHSWarehouseWorkLineBIEntity.md" target="_blank">WMS/WHSWarehouseWorkLineBIEntity</a>|
|[WorkLineClosedDateTime](#WorkLineClosedDateTime)||<a href="WHSWarehouseWorkLineBIEntity.md" target="_blank">WMS/WHSWarehouseWorkLineBIEntity</a>|
|[WorkLineInventoryTransactionId](#WorkLineInventoryTransactionId)||<a href="WHSWarehouseWorkLineBIEntity.md" target="_blank">WMS/WHSWarehouseWorkLineBIEntity</a>|
|[WorkLineStartedDateTime](#WorkLineStartedDateTime)||<a href="WHSWarehouseWorkLineBIEntity.md" target="_blank">WMS/WHSWarehouseWorkLineBIEntity</a>|
|[WorkLineNumber](#WorkLineNumber)||<a href="WHSWarehouseWorkLineBIEntity.md" target="_blank">WMS/WHSWarehouseWorkLineBIEntity</a>|
|[WorkLineStatus](#WorkLineStatus)||<a href="WHSWarehouseWorkLineBIEntity.md" target="_blank">WMS/WHSWarehouseWorkLineBIEntity</a>|
|[WorkPriority](#WorkPriority)||<a href="WHSWarehouseWorkLineBIEntity.md" target="_blank">WMS/WHSWarehouseWorkLineBIEntity</a>|
|[WorkProcessingUserId](#WorkProcessingUserId)||<a href="WHSWarehouseWorkLineBIEntity.md" target="_blank">WMS/WHSWarehouseWorkLineBIEntity</a>|
|[WorkStartedDateTime](#WorkStartedDateTime)||<a href="WHSWarehouseWorkLineBIEntity.md" target="_blank">WMS/WHSWarehouseWorkLineBIEntity</a>|
|[WorkQuantity](#WorkQuantity)||<a href="WHSWarehouseWorkLineBIEntity.md" target="_blank">WMS/WHSWarehouseWorkLineBIEntity</a>|
|[WorkStatus](#WorkStatus)||<a href="WHSWarehouseWorkLineBIEntity.md" target="_blank">WMS/WHSWarehouseWorkLineBIEntity</a>|
|[WorkTransactionType](#WorkTransactionType)||<a href="WHSWarehouseWorkLineBIEntity.md" target="_blank">WMS/WHSWarehouseWorkLineBIEntity</a>|
|[WorkType](#WorkType)||<a href="WHSWarehouseWorkLineBIEntity.md" target="_blank">WMS/WHSWarehouseWorkLineBIEntity</a>|
|[Relationship_WarehouseZoneGroupRelationshipId](#Relationship_WarehouseZoneGroupRelationshipId)||<a href="WHSWarehouseWorkLineBIEntity.md" target="_blank">WMS/WHSWarehouseWorkLineBIEntity</a>|
|[Relationship_PrimaryCompanyContextRelationshipId](#Relationship_PrimaryCompanyContextRelationshipId)||<a href="WHSWarehouseWorkLineBIEntity.md" target="_blank">WMS/WHSWarehouseWorkLineBIEntity</a>|

### <a href=#ActualWorkLineProcessingTime name="ActualWorkLineProcessingTime">ActualWorkLineProcessingTime</a>

First included in: WMS/WHSWarehouseWorkLineBIEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ActualWorkLineProcessingTime attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ActualWorkProcessingTime name="ActualWorkProcessingTime">ActualWorkProcessingTime</a>

First included in: WMS/WHSWarehouseWorkLineBIEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ActualWorkProcessingTime attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ContainerId name="ContainerId">ContainerId</a>

First included in: WMS/WHSWarehouseWorkLineBIEntity (this entity)  

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

### <a href=#EstimatedWorkLineProcessingTime name="EstimatedWorkLineProcessingTime">EstimatedWorkLineProcessingTime</a>

First included in: WMS/WHSWarehouseWorkLineBIEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EstimatedWorkLineProcessingTime attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#EstimatedWorkProcessingTime name="EstimatedWorkProcessingTime">EstimatedWorkProcessingTime</a>

First included in: WMS/WHSWarehouseWorkLineBIEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EstimatedWorkProcessingTime attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InventoryGTDNumber name="InventoryGTDNumber">InventoryGTDNumber</a>

First included in: WMS/WHSWarehouseWorkLineBIEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InventoryGTDNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InventoryOwnerId name="InventoryOwnerId">InventoryOwnerId</a>

First included in: WMS/WHSWarehouseWorkLineBIEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InventoryOwnerId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InventoryProfileId name="InventoryProfileId">InventoryProfileId</a>

First included in: WMS/WHSWarehouseWorkLineBIEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InventoryProfileId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InventoryStatusId name="InventoryStatusId">InventoryStatusId</a>

First included in: WMS/WHSWarehouseWorkLineBIEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InventoryStatusId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ItemBatchNumber name="ItemBatchNumber">ItemBatchNumber</a>

First included in: WMS/WHSWarehouseWorkLineBIEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ItemBatchNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ItemNumber name="ItemNumber">ItemNumber</a>

First included in: WMS/WHSWarehouseWorkLineBIEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ItemNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ItemSerialNumber name="ItemSerialNumber">ItemSerialNumber</a>

First included in: WMS/WHSWarehouseWorkLineBIEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ItemSerialNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsWorkFrozen name="IsWorkFrozen">IsWorkFrozen</a>

First included in: WMS/WHSWarehouseWorkLineBIEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsWorkFrozen attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsWorkStepMandatory name="IsWorkStepMandatory">IsWorkStepMandatory</a>

First included in: WMS/WHSWarehouseWorkLineBIEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsWorkStepMandatory attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsWorkStepSkipped name="IsWorkStepSkipped">IsWorkStepSkipped</a>

First included in: WMS/WHSWarehouseWorkLineBIEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsWorkStepSkipped attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsWorkStepStopped name="IsWorkStepStopped">IsWorkStepStopped</a>

First included in: WMS/WHSWarehouseWorkLineBIEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsWorkStepStopped attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LoadId name="LoadId">LoadId</a>

First included in: WMS/WHSWarehouseWorkLineBIEntity (this entity)  

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

### <a href=#PhysicalAvailableInventoryQuantity name="PhysicalAvailableInventoryQuantity">PhysicalAvailableInventoryQuantity</a>

First included in: WMS/WHSWarehouseWorkLineBIEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PhysicalAvailableInventoryQuantity attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProductColorId name="ProductColorId">ProductColorId</a>

First included in: WMS/WHSWarehouseWorkLineBIEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProductColorId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProductConfigurationId name="ProductConfigurationId">ProductConfigurationId</a>

First included in: WMS/WHSWarehouseWorkLineBIEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProductConfigurationId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProductionPickOrderNumber name="ProductionPickOrderNumber">ProductionPickOrderNumber</a>

First included in: WMS/WHSWarehouseWorkLineBIEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProductionPickOrderNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProductionPutOrderNumber name="ProductionPutOrderNumber">ProductionPutOrderNumber</a>

First included in: WMS/WHSWarehouseWorkLineBIEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProductionPutOrderNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProductSizeId name="ProductSizeId">ProductSizeId</a>

First included in: WMS/WHSWarehouseWorkLineBIEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProductSizeId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProductStyleId name="ProductStyleId">ProductStyleId</a>

First included in: WMS/WHSWarehouseWorkLineBIEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProductStyleId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProductVersionId name="ProductVersionId">ProductVersionId</a>

First included in: WMS/WHSWarehouseWorkLineBIEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProductVersionId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PurchaseOrderNumber name="PurchaseOrderNumber">PurchaseOrderNumber</a>

First included in: WMS/WHSWarehouseWorkLineBIEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PurchaseOrderNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RemainingInventoryQuantity name="RemainingInventoryQuantity">RemainingInventoryQuantity</a>

First included in: WMS/WHSWarehouseWorkLineBIEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RemainingInventoryQuantity attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RemainingWorkQuantity name="RemainingWorkQuantity">RemainingWorkQuantity</a>

First included in: WMS/WHSWarehouseWorkLineBIEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RemainingWorkQuantity attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SalesOrderNumber name="SalesOrderNumber">SalesOrderNumber</a>

First included in: WMS/WHSWarehouseWorkLineBIEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SalesOrderNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ShipmentId name="ShipmentId">ShipmentId</a>

First included in: WMS/WHSWarehouseWorkLineBIEntity (this entity)  

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

### <a href=#SortOrderCode name="SortOrderCode">SortOrderCode</a>

First included in: WMS/WHSWarehouseWorkLineBIEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SortOrderCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TargetLicensePlateId name="TargetLicensePlateId">TargetLicensePlateId</a>

First included in: WMS/WHSWarehouseWorkLineBIEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TargetLicensePlateId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TransferIssueOrderNumber name="TransferIssueOrderNumber">TransferIssueOrderNumber</a>

First included in: WMS/WHSWarehouseWorkLineBIEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TransferIssueOrderNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TransferReceiptOrderNumber name="TransferReceiptOrderNumber">TransferReceiptOrderNumber</a>

First included in: WMS/WHSWarehouseWorkLineBIEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TransferReceiptOrderNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#UnitSymbol name="UnitSymbol">UnitSymbol</a>

First included in: WMS/WHSWarehouseWorkLineBIEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the UnitSymbol attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WarehouseMobileDeviceUserId name="WarehouseMobileDeviceUserId">WarehouseMobileDeviceUserId</a>

First included in: WMS/WHSWarehouseWorkLineBIEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WarehouseMobileDeviceUserId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WarehouseWorkBuildId name="WarehouseWorkBuildId">WarehouseWorkBuildId</a>

First included in: WMS/WHSWarehouseWorkLineBIEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WarehouseWorkBuildId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WarehouseWorkClassId name="WarehouseWorkClassId">WarehouseWorkClassId</a>

First included in: WMS/WHSWarehouseWorkLineBIEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WarehouseWorkClassId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WarehouseWorkPoolId name="WarehouseWorkPoolId">WarehouseWorkPoolId</a>

First included in: WMS/WHSWarehouseWorkLineBIEntity (this entity)  

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

### <a href=#WarehouseWorkTemplateId name="WarehouseWorkTemplateId">WarehouseWorkTemplateId</a>

First included in: WMS/WHSWarehouseWorkLineBIEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WarehouseWorkTemplateId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WarehouseId name="WarehouseId">WarehouseId</a>

First included in: WMS/WHSWarehouseWorkLineBIEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WarehouseId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WarehouseLocationId name="WarehouseLocationId">WarehouseLocationId</a>

First included in: WMS/WHSWarehouseWorkLineBIEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WarehouseLocationId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WarehouseWaveId name="WarehouseWaveId">WarehouseWaveId</a>

First included in: WMS/WHSWarehouseWorkLineBIEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WarehouseWaveId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WarehouseWorkId name="WarehouseWorkId">WarehouseWorkId</a>

First included in: WMS/WHSWarehouseWorkLineBIEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WarehouseWorkId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WarehouseZoneId name="WarehouseZoneId">WarehouseZoneId</a>

First included in: WMS/WHSWarehouseWorkLineBIEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WarehouseZoneId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WorkClosedDateTime name="WorkClosedDateTime">WorkClosedDateTime</a>

First included in: WMS/WHSWarehouseWorkLineBIEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WorkClosedDateTime attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WorkCreatedDateTime name="WorkCreatedDateTime">WorkCreatedDateTime</a>

First included in: WMS/WHSWarehouseWorkLineBIEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WorkCreatedDateTime attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WorkInventoryQuantity name="WorkInventoryQuantity">WorkInventoryQuantity</a>

First included in: WMS/WHSWarehouseWorkLineBIEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WorkInventoryQuantity attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WorkLineClosedDateTime name="WorkLineClosedDateTime">WorkLineClosedDateTime</a>

First included in: WMS/WHSWarehouseWorkLineBIEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WorkLineClosedDateTime attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WorkLineInventoryTransactionId name="WorkLineInventoryTransactionId">WorkLineInventoryTransactionId</a>

First included in: WMS/WHSWarehouseWorkLineBIEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WorkLineInventoryTransactionId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WorkLineStartedDateTime name="WorkLineStartedDateTime">WorkLineStartedDateTime</a>

First included in: WMS/WHSWarehouseWorkLineBIEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WorkLineStartedDateTime attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WorkLineNumber name="WorkLineNumber">WorkLineNumber</a>

First included in: WMS/WHSWarehouseWorkLineBIEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WorkLineNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WorkLineStatus name="WorkLineStatus">WorkLineStatus</a>

First included in: WMS/WHSWarehouseWorkLineBIEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WorkLineStatus attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WorkPriority name="WorkPriority">WorkPriority</a>

First included in: WMS/WHSWarehouseWorkLineBIEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WorkPriority attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WorkProcessingUserId name="WorkProcessingUserId">WorkProcessingUserId</a>

First included in: WMS/WHSWarehouseWorkLineBIEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WorkProcessingUserId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WorkStartedDateTime name="WorkStartedDateTime">WorkStartedDateTime</a>

First included in: WMS/WHSWarehouseWorkLineBIEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WorkStartedDateTime attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WorkQuantity name="WorkQuantity">WorkQuantity</a>

First included in: WMS/WHSWarehouseWorkLineBIEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WorkQuantity attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WorkStatus name="WorkStatus">WorkStatus</a>

First included in: WMS/WHSWarehouseWorkLineBIEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WorkStatus attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WorkTransactionType name="WorkTransactionType">WorkTransactionType</a>

First included in: WMS/WHSWarehouseWorkLineBIEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WorkTransactionType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WorkType name="WorkType">WorkType</a>

First included in: WMS/WHSWarehouseWorkLineBIEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WorkType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_WarehouseZoneGroupRelationshipId name="Relationship_WarehouseZoneGroupRelationshipId">Relationship_WarehouseZoneGroupRelationshipId</a>

First included in: WMS/WHSWarehouseWorkLineBIEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_WarehouseZoneGroupRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_PrimaryCompanyContextRelationshipId name="Relationship_PrimaryCompanyContextRelationshipId">Relationship_PrimaryCompanyContextRelationshipId</a>

First included in: WMS/WHSWarehouseWorkLineBIEntity (this entity)  

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
