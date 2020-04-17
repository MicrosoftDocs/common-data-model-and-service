---
title: ReqItemCoverageSettingsEntity - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/17/2020
ms.author: nebanfic
---

# ReqItemCoverageSettingsEntity

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/erp/Entities/SupplyChain/MasterPlanning/ReqItemCoverageSettingsEntity.cdm.json" target="_blank">GitHub</a>.  

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
|[ItemNumber](#ItemNumber)||<a href="ReqItemCoverageSettingsEntity.md" target="_blank">MasterPlanning/ReqItemCoverageSettingsEntity</a>|
|[CoverageItemBatchNumber](#CoverageItemBatchNumber)||<a href="ReqItemCoverageSettingsEntity.md" target="_blank">MasterPlanning/ReqItemCoverageSettingsEntity</a>|
|[CoverageProductColorId](#CoverageProductColorId)||<a href="ReqItemCoverageSettingsEntity.md" target="_blank">MasterPlanning/ReqItemCoverageSettingsEntity</a>|
|[CoverageProductSizeId](#CoverageProductSizeId)||<a href="ReqItemCoverageSettingsEntity.md" target="_blank">MasterPlanning/ReqItemCoverageSettingsEntity</a>|
|[CoverageProductStyleId](#CoverageProductStyleId)||<a href="ReqItemCoverageSettingsEntity.md" target="_blank">MasterPlanning/ReqItemCoverageSettingsEntity</a>|
|[CoverageWarehouseId](#CoverageWarehouseId)||<a href="ReqItemCoverageSettingsEntity.md" target="_blank">MasterPlanning/ReqItemCoverageSettingsEntity</a>|
|[CoverageItemSerialNumber](#CoverageItemSerialNumber)||<a href="ReqItemCoverageSettingsEntity.md" target="_blank">MasterPlanning/ReqItemCoverageSettingsEntity</a>|
|[CoverageSiteId](#CoverageSiteId)||<a href="ReqItemCoverageSettingsEntity.md" target="_blank">MasterPlanning/ReqItemCoverageSettingsEntity</a>|
|[CoverageInventoryStatusId](#CoverageInventoryStatusId)||<a href="ReqItemCoverageSettingsEntity.md" target="_blank">MasterPlanning/ReqItemCoverageSettingsEntity</a>|
|[CoverageWarehouseLocationId](#CoverageWarehouseLocationId)||<a href="ReqItemCoverageSettingsEntity.md" target="_blank">MasterPlanning/ReqItemCoverageSettingsEntity</a>|
|[CoverageProductConfigurationId](#CoverageProductConfigurationId)||<a href="ReqItemCoverageSettingsEntity.md" target="_blank">MasterPlanning/ReqItemCoverageSettingsEntity</a>|
|[IsPlannedOrderTypeOverridden](#IsPlannedOrderTypeOverridden)||<a href="ReqItemCoverageSettingsEntity.md" target="_blank">MasterPlanning/ReqItemCoverageSettingsEntity</a>|
|[PlannedOrderType](#PlannedOrderType)||<a href="ReqItemCoverageSettingsEntity.md" target="_blank">MasterPlanning/ReqItemCoverageSettingsEntity</a>|
|[DefaultPlannedTransferOrderFromWarehouseId](#DefaultPlannedTransferOrderFromWarehouseId)||<a href="ReqItemCoverageSettingsEntity.md" target="_blank">MasterPlanning/ReqItemCoverageSettingsEntity</a>|
|[AreGeneralSettingsOverridden](#AreGeneralSettingsOverridden)||<a href="ReqItemCoverageSettingsEntity.md" target="_blank">MasterPlanning/ReqItemCoverageSettingsEntity</a>|
|[ProductCoverageGroupId](#ProductCoverageGroupId)||<a href="ReqItemCoverageSettingsEntity.md" target="_blank">MasterPlanning/ReqItemCoverageSettingsEntity</a>|
|[VendorAccountNumber](#VendorAccountNumber)||<a href="ReqItemCoverageSettingsEntity.md" target="_blank">MasterPlanning/ReqItemCoverageSettingsEntity</a>|
|[AreCoverageGroupSettingsOverridden](#AreCoverageGroupSettingsOverridden)||<a href="ReqItemCoverageSettingsEntity.md" target="_blank">MasterPlanning/ReqItemCoverageSettingsEntity</a>|
|[CoverageMethod](#CoverageMethod)||<a href="ReqItemCoverageSettingsEntity.md" target="_blank">MasterPlanning/ReqItemCoverageSettingsEntity</a>|
|[CoveragePeriodDays](#CoveragePeriodDays)||<a href="ReqItemCoverageSettingsEntity.md" target="_blank">MasterPlanning/ReqItemCoverageSettingsEntity</a>|
|[CoverageTimeFenceDays](#CoverageTimeFenceDays)||<a href="ReqItemCoverageSettingsEntity.md" target="_blank">MasterPlanning/ReqItemCoverageSettingsEntity</a>|
|[PositiveDays](#PositiveDays)||<a href="ReqItemCoverageSettingsEntity.md" target="_blank">MasterPlanning/ReqItemCoverageSettingsEntity</a>|
|[NegativeDays](#NegativeDays)||<a href="ReqItemCoverageSettingsEntity.md" target="_blank">MasterPlanning/ReqItemCoverageSettingsEntity</a>|
|[AreTimeFencesOverridden](#AreTimeFencesOverridden)||<a href="ReqItemCoverageSettingsEntity.md" target="_blank">MasterPlanning/ReqItemCoverageSettingsEntity</a>|
|[AutomaticFirmingTimeFenceDays](#AutomaticFirmingTimeFenceDays)||<a href="ReqItemCoverageSettingsEntity.md" target="_blank">MasterPlanning/ReqItemCoverageSettingsEntity</a>|
|[FreezeTimeFenceDays](#FreezeTimeFenceDays)||<a href="ReqItemCoverageSettingsEntity.md" target="_blank">MasterPlanning/ReqItemCoverageSettingsEntity</a>|
|[BOMOrFormulaExplosionTimeFenceDays](#BOMOrFormulaExplosionTimeFenceDays)||<a href="ReqItemCoverageSettingsEntity.md" target="_blank">MasterPlanning/ReqItemCoverageSettingsEntity</a>|
|[CapacitySchedulingTimeFenceDays](#CapacitySchedulingTimeFenceDays)||<a href="ReqItemCoverageSettingsEntity.md" target="_blank">MasterPlanning/ReqItemCoverageSettingsEntity</a>|
|[ApprovedRequisitionTimeFenceDays](#ApprovedRequisitionTimeFenceDays)||<a href="ReqItemCoverageSettingsEntity.md" target="_blank">MasterPlanning/ReqItemCoverageSettingsEntity</a>|
|[MinimumOnHandInventoryQuantity](#MinimumOnHandInventoryQuantity)||<a href="ReqItemCoverageSettingsEntity.md" target="_blank">MasterPlanning/ReqItemCoverageSettingsEntity</a>|
|[MaximumOnHandInventoryQuantity](#MaximumOnHandInventoryQuantity)||<a href="ReqItemCoverageSettingsEntity.md" target="_blank">MasterPlanning/ReqItemCoverageSettingsEntity</a>|
|[MinimumOnHandInventorySafetyKeyId](#MinimumOnHandInventorySafetyKeyId)||<a href="ReqItemCoverageSettingsEntity.md" target="_blank">MasterPlanning/ReqItemCoverageSettingsEntity</a>|
|[MaximumOnHandInventorySafetyKeyId](#MaximumOnHandInventorySafetyKeyId)||<a href="ReqItemCoverageSettingsEntity.md" target="_blank">MasterPlanning/ReqItemCoverageSettingsEntity</a>|
|[MinimumOnHandFulfillmentMethod](#MinimumOnHandFulfillmentMethod)||<a href="ReqItemCoverageSettingsEntity.md" target="_blank">MasterPlanning/ReqItemCoverageSettingsEntity</a>|
|[IsMinimumOnHandSafetyPeriodUsed](#IsMinimumOnHandSafetyPeriodUsed)||<a href="ReqItemCoverageSettingsEntity.md" target="_blank">MasterPlanning/ReqItemCoverageSettingsEntity</a>|
|[PlanningFormulaItemNumber](#PlanningFormulaItemNumber)||<a href="ReqItemCoverageSettingsEntity.md" target="_blank">MasterPlanning/ReqItemCoverageSettingsEntity</a>|
|[DefaultPlanningFormulaPriority](#DefaultPlanningFormulaPriority)||<a href="ReqItemCoverageSettingsEntity.md" target="_blank">MasterPlanning/ReqItemCoverageSettingsEntity</a>|
|[CurrentPlanningFormulaPriority](#CurrentPlanningFormulaPriority)||<a href="ReqItemCoverageSettingsEntity.md" target="_blank">MasterPlanning/ReqItemCoverageSettingsEntity</a>|
|[LastPlanningFormulaPriorityChangedDate](#LastPlanningFormulaPriorityChangedDate)||<a href="ReqItemCoverageSettingsEntity.md" target="_blank">MasterPlanning/ReqItemCoverageSettingsEntity</a>|
|[IsConsumeOnHandOverridden](#IsConsumeOnHandOverridden)||<a href="ReqItemCoverageSettingsEntity.md" target="_blank">MasterPlanning/ReqItemCoverageSettingsEntity</a>|
|[ConsumeOnHandInventoryMethod](#ConsumeOnHandInventoryMethod)||<a href="ReqItemCoverageSettingsEntity.md" target="_blank">MasterPlanning/ReqItemCoverageSettingsEntity</a>|
|[IsProcurementLeadTimeOverridden](#IsProcurementLeadTimeOverridden)||<a href="ReqItemCoverageSettingsEntity.md" target="_blank">MasterPlanning/ReqItemCoverageSettingsEntity</a>|
|[ProcurementLeadTimeDays](#ProcurementLeadTimeDays)||<a href="ReqItemCoverageSettingsEntity.md" target="_blank">MasterPlanning/ReqItemCoverageSettingsEntity</a>|
|[IsProcumentLeadTimeUsingWorkingDays](#IsProcumentLeadTimeUsingWorkingDays)||<a href="ReqItemCoverageSettingsEntity.md" target="_blank">MasterPlanning/ReqItemCoverageSettingsEntity</a>|
|[IsProductionLeadTimeOverridden](#IsProductionLeadTimeOverridden)||<a href="ReqItemCoverageSettingsEntity.md" target="_blank">MasterPlanning/ReqItemCoverageSettingsEntity</a>|
|[ProductionLeadTimeDays](#ProductionLeadTimeDays)||<a href="ReqItemCoverageSettingsEntity.md" target="_blank">MasterPlanning/ReqItemCoverageSettingsEntity</a>|
|[IsProductionLeadTimeUsingWorkingDays](#IsProductionLeadTimeUsingWorkingDays)||<a href="ReqItemCoverageSettingsEntity.md" target="_blank">MasterPlanning/ReqItemCoverageSettingsEntity</a>|
|[IsTransferLeadTimeOverridden](#IsTransferLeadTimeOverridden)||<a href="ReqItemCoverageSettingsEntity.md" target="_blank">MasterPlanning/ReqItemCoverageSettingsEntity</a>|
|[TransferLeadTimeDays](#TransferLeadTimeDays)||<a href="ReqItemCoverageSettingsEntity.md" target="_blank">MasterPlanning/ReqItemCoverageSettingsEntity</a>|
|[IsTransferLeadTimeUsingWorkingDays](#IsTransferLeadTimeUsingWorkingDays)||<a href="ReqItemCoverageSettingsEntity.md" target="_blank">MasterPlanning/ReqItemCoverageSettingsEntity</a>|
|[Relationship_ReleasedProductRelationshipId](#Relationship_ReleasedProductRelationshipId)||<a href="ReqItemCoverageSettingsEntity.md" target="_blank">MasterPlanning/ReqItemCoverageSettingsEntity</a>|
|[Relationship_CoverageSiteRelationshipId](#Relationship_CoverageSiteRelationshipId)||<a href="ReqItemCoverageSettingsEntity.md" target="_blank">MasterPlanning/ReqItemCoverageSettingsEntity</a>|
|[Relationship_CoverageWarehouseRelationshipId](#Relationship_CoverageWarehouseRelationshipId)||<a href="ReqItemCoverageSettingsEntity.md" target="_blank">MasterPlanning/ReqItemCoverageSettingsEntity</a>|
|[Relationship_CoverageWarehouseLocationRelationshipId](#Relationship_CoverageWarehouseLocationRelationshipId)||<a href="ReqItemCoverageSettingsEntity.md" target="_blank">MasterPlanning/ReqItemCoverageSettingsEntity</a>|
|[Relationship_VendorRelationshipId](#Relationship_VendorRelationshipId)||<a href="ReqItemCoverageSettingsEntity.md" target="_blank">MasterPlanning/ReqItemCoverageSettingsEntity</a>|
|[Relationship_CoverageInventoryStatusRelationshipId](#Relationship_CoverageInventoryStatusRelationshipId)||<a href="ReqItemCoverageSettingsEntity.md" target="_blank">MasterPlanning/ReqItemCoverageSettingsEntity</a>|
|[Relationship_DefaultPlannedTransferOrderFromWarehouseRelationshipId](#Relationship_DefaultPlannedTransferOrderFromWarehouseRelationshipId)||<a href="ReqItemCoverageSettingsEntity.md" target="_blank">MasterPlanning/ReqItemCoverageSettingsEntity</a>|
|[Relationship_ProductCoverageGroupRelationshipId](#Relationship_ProductCoverageGroupRelationshipId)||<a href="ReqItemCoverageSettingsEntity.md" target="_blank">MasterPlanning/ReqItemCoverageSettingsEntity</a>|
|[Relationship_PlanningFormulaReleasedProductRelationshipId](#Relationship_PlanningFormulaReleasedProductRelationshipId)||<a href="ReqItemCoverageSettingsEntity.md" target="_blank">MasterPlanning/ReqItemCoverageSettingsEntity</a>|
|[BackingTable_ReqItemTableRelationshipId](#BackingTable_ReqItemTableRelationshipId)||<a href="ReqItemCoverageSettingsEntity.md" target="_blank">MasterPlanning/ReqItemCoverageSettingsEntity</a>|
|[Relationship_PrimaryCompanyContextRelationshipId](#Relationship_PrimaryCompanyContextRelationshipId)||<a href="ReqItemCoverageSettingsEntity.md" target="_blank">MasterPlanning/ReqItemCoverageSettingsEntity</a>|

### <a href=#ItemNumber name="ItemNumber">ItemNumber</a>

First included in: MasterPlanning/ReqItemCoverageSettingsEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ItemNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CoverageItemBatchNumber name="CoverageItemBatchNumber">CoverageItemBatchNumber</a>

First included in: MasterPlanning/ReqItemCoverageSettingsEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CoverageItemBatchNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CoverageProductColorId name="CoverageProductColorId">CoverageProductColorId</a>

First included in: MasterPlanning/ReqItemCoverageSettingsEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CoverageProductColorId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CoverageProductSizeId name="CoverageProductSizeId">CoverageProductSizeId</a>

First included in: MasterPlanning/ReqItemCoverageSettingsEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CoverageProductSizeId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CoverageProductStyleId name="CoverageProductStyleId">CoverageProductStyleId</a>

First included in: MasterPlanning/ReqItemCoverageSettingsEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CoverageProductStyleId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CoverageWarehouseId name="CoverageWarehouseId">CoverageWarehouseId</a>

First included in: MasterPlanning/ReqItemCoverageSettingsEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CoverageWarehouseId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CoverageItemSerialNumber name="CoverageItemSerialNumber">CoverageItemSerialNumber</a>

First included in: MasterPlanning/ReqItemCoverageSettingsEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CoverageItemSerialNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CoverageSiteId name="CoverageSiteId">CoverageSiteId</a>

First included in: MasterPlanning/ReqItemCoverageSettingsEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CoverageSiteId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CoverageInventoryStatusId name="CoverageInventoryStatusId">CoverageInventoryStatusId</a>

First included in: MasterPlanning/ReqItemCoverageSettingsEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CoverageInventoryStatusId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CoverageWarehouseLocationId name="CoverageWarehouseLocationId">CoverageWarehouseLocationId</a>

First included in: MasterPlanning/ReqItemCoverageSettingsEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CoverageWarehouseLocationId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CoverageProductConfigurationId name="CoverageProductConfigurationId">CoverageProductConfigurationId</a>

First included in: MasterPlanning/ReqItemCoverageSettingsEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CoverageProductConfigurationId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsPlannedOrderTypeOverridden name="IsPlannedOrderTypeOverridden">IsPlannedOrderTypeOverridden</a>

First included in: MasterPlanning/ReqItemCoverageSettingsEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsPlannedOrderTypeOverridden attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PlannedOrderType name="PlannedOrderType">PlannedOrderType</a>

First included in: MasterPlanning/ReqItemCoverageSettingsEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PlannedOrderType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DefaultPlannedTransferOrderFromWarehouseId name="DefaultPlannedTransferOrderFromWarehouseId">DefaultPlannedTransferOrderFromWarehouseId</a>

First included in: MasterPlanning/ReqItemCoverageSettingsEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultPlannedTransferOrderFromWarehouseId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AreGeneralSettingsOverridden name="AreGeneralSettingsOverridden">AreGeneralSettingsOverridden</a>

First included in: MasterPlanning/ReqItemCoverageSettingsEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AreGeneralSettingsOverridden attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProductCoverageGroupId name="ProductCoverageGroupId">ProductCoverageGroupId</a>

First included in: MasterPlanning/ReqItemCoverageSettingsEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProductCoverageGroupId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#VendorAccountNumber name="VendorAccountNumber">VendorAccountNumber</a>

First included in: MasterPlanning/ReqItemCoverageSettingsEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VendorAccountNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AreCoverageGroupSettingsOverridden name="AreCoverageGroupSettingsOverridden">AreCoverageGroupSettingsOverridden</a>

First included in: MasterPlanning/ReqItemCoverageSettingsEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AreCoverageGroupSettingsOverridden attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CoverageMethod name="CoverageMethod">CoverageMethod</a>

First included in: MasterPlanning/ReqItemCoverageSettingsEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CoverageMethod attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CoveragePeriodDays name="CoveragePeriodDays">CoveragePeriodDays</a>

First included in: MasterPlanning/ReqItemCoverageSettingsEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CoveragePeriodDays attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CoverageTimeFenceDays name="CoverageTimeFenceDays">CoverageTimeFenceDays</a>

First included in: MasterPlanning/ReqItemCoverageSettingsEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CoverageTimeFenceDays attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PositiveDays name="PositiveDays">PositiveDays</a>

First included in: MasterPlanning/ReqItemCoverageSettingsEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PositiveDays attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#NegativeDays name="NegativeDays">NegativeDays</a>

First included in: MasterPlanning/ReqItemCoverageSettingsEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the NegativeDays attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AreTimeFencesOverridden name="AreTimeFencesOverridden">AreTimeFencesOverridden</a>

First included in: MasterPlanning/ReqItemCoverageSettingsEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AreTimeFencesOverridden attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AutomaticFirmingTimeFenceDays name="AutomaticFirmingTimeFenceDays">AutomaticFirmingTimeFenceDays</a>

First included in: MasterPlanning/ReqItemCoverageSettingsEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AutomaticFirmingTimeFenceDays attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FreezeTimeFenceDays name="FreezeTimeFenceDays">FreezeTimeFenceDays</a>

First included in: MasterPlanning/ReqItemCoverageSettingsEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FreezeTimeFenceDays attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BOMOrFormulaExplosionTimeFenceDays name="BOMOrFormulaExplosionTimeFenceDays">BOMOrFormulaExplosionTimeFenceDays</a>

First included in: MasterPlanning/ReqItemCoverageSettingsEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BOMOrFormulaExplosionTimeFenceDays attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CapacitySchedulingTimeFenceDays name="CapacitySchedulingTimeFenceDays">CapacitySchedulingTimeFenceDays</a>

First included in: MasterPlanning/ReqItemCoverageSettingsEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CapacitySchedulingTimeFenceDays attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ApprovedRequisitionTimeFenceDays name="ApprovedRequisitionTimeFenceDays">ApprovedRequisitionTimeFenceDays</a>

First included in: MasterPlanning/ReqItemCoverageSettingsEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ApprovedRequisitionTimeFenceDays attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MinimumOnHandInventoryQuantity name="MinimumOnHandInventoryQuantity">MinimumOnHandInventoryQuantity</a>

First included in: MasterPlanning/ReqItemCoverageSettingsEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MinimumOnHandInventoryQuantity attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MaximumOnHandInventoryQuantity name="MaximumOnHandInventoryQuantity">MaximumOnHandInventoryQuantity</a>

First included in: MasterPlanning/ReqItemCoverageSettingsEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MaximumOnHandInventoryQuantity attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MinimumOnHandInventorySafetyKeyId name="MinimumOnHandInventorySafetyKeyId">MinimumOnHandInventorySafetyKeyId</a>

First included in: MasterPlanning/ReqItemCoverageSettingsEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MinimumOnHandInventorySafetyKeyId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MaximumOnHandInventorySafetyKeyId name="MaximumOnHandInventorySafetyKeyId">MaximumOnHandInventorySafetyKeyId</a>

First included in: MasterPlanning/ReqItemCoverageSettingsEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MaximumOnHandInventorySafetyKeyId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MinimumOnHandFulfillmentMethod name="MinimumOnHandFulfillmentMethod">MinimumOnHandFulfillmentMethod</a>

First included in: MasterPlanning/ReqItemCoverageSettingsEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MinimumOnHandFulfillmentMethod attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsMinimumOnHandSafetyPeriodUsed name="IsMinimumOnHandSafetyPeriodUsed">IsMinimumOnHandSafetyPeriodUsed</a>

First included in: MasterPlanning/ReqItemCoverageSettingsEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsMinimumOnHandSafetyPeriodUsed attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PlanningFormulaItemNumber name="PlanningFormulaItemNumber">PlanningFormulaItemNumber</a>

First included in: MasterPlanning/ReqItemCoverageSettingsEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PlanningFormulaItemNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DefaultPlanningFormulaPriority name="DefaultPlanningFormulaPriority">DefaultPlanningFormulaPriority</a>

First included in: MasterPlanning/ReqItemCoverageSettingsEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultPlanningFormulaPriority attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CurrentPlanningFormulaPriority name="CurrentPlanningFormulaPriority">CurrentPlanningFormulaPriority</a>

First included in: MasterPlanning/ReqItemCoverageSettingsEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CurrentPlanningFormulaPriority attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LastPlanningFormulaPriorityChangedDate name="LastPlanningFormulaPriorityChangedDate">LastPlanningFormulaPriorityChangedDate</a>

First included in: MasterPlanning/ReqItemCoverageSettingsEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LastPlanningFormulaPriorityChangedDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsConsumeOnHandOverridden name="IsConsumeOnHandOverridden">IsConsumeOnHandOverridden</a>

First included in: MasterPlanning/ReqItemCoverageSettingsEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsConsumeOnHandOverridden attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ConsumeOnHandInventoryMethod name="ConsumeOnHandInventoryMethod">ConsumeOnHandInventoryMethod</a>

First included in: MasterPlanning/ReqItemCoverageSettingsEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ConsumeOnHandInventoryMethod attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsProcurementLeadTimeOverridden name="IsProcurementLeadTimeOverridden">IsProcurementLeadTimeOverridden</a>

First included in: MasterPlanning/ReqItemCoverageSettingsEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsProcurementLeadTimeOverridden attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProcurementLeadTimeDays name="ProcurementLeadTimeDays">ProcurementLeadTimeDays</a>

First included in: MasterPlanning/ReqItemCoverageSettingsEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProcurementLeadTimeDays attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsProcumentLeadTimeUsingWorkingDays name="IsProcumentLeadTimeUsingWorkingDays">IsProcumentLeadTimeUsingWorkingDays</a>

First included in: MasterPlanning/ReqItemCoverageSettingsEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsProcumentLeadTimeUsingWorkingDays attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsProductionLeadTimeOverridden name="IsProductionLeadTimeOverridden">IsProductionLeadTimeOverridden</a>

First included in: MasterPlanning/ReqItemCoverageSettingsEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsProductionLeadTimeOverridden attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProductionLeadTimeDays name="ProductionLeadTimeDays">ProductionLeadTimeDays</a>

First included in: MasterPlanning/ReqItemCoverageSettingsEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProductionLeadTimeDays attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsProductionLeadTimeUsingWorkingDays name="IsProductionLeadTimeUsingWorkingDays">IsProductionLeadTimeUsingWorkingDays</a>

First included in: MasterPlanning/ReqItemCoverageSettingsEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsProductionLeadTimeUsingWorkingDays attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsTransferLeadTimeOverridden name="IsTransferLeadTimeOverridden">IsTransferLeadTimeOverridden</a>

First included in: MasterPlanning/ReqItemCoverageSettingsEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsTransferLeadTimeOverridden attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TransferLeadTimeDays name="TransferLeadTimeDays">TransferLeadTimeDays</a>

First included in: MasterPlanning/ReqItemCoverageSettingsEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TransferLeadTimeDays attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsTransferLeadTimeUsingWorkingDays name="IsTransferLeadTimeUsingWorkingDays">IsTransferLeadTimeUsingWorkingDays</a>

First included in: MasterPlanning/ReqItemCoverageSettingsEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsTransferLeadTimeUsingWorkingDays attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_ReleasedProductRelationshipId name="Relationship_ReleasedProductRelationshipId">Relationship_ReleasedProductRelationshipId</a>

First included in: MasterPlanning/ReqItemCoverageSettingsEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_ReleasedProductRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_CoverageSiteRelationshipId name="Relationship_CoverageSiteRelationshipId">Relationship_CoverageSiteRelationshipId</a>

First included in: MasterPlanning/ReqItemCoverageSettingsEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_CoverageSiteRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_CoverageWarehouseRelationshipId name="Relationship_CoverageWarehouseRelationshipId">Relationship_CoverageWarehouseRelationshipId</a>

First included in: MasterPlanning/ReqItemCoverageSettingsEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_CoverageWarehouseRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_CoverageWarehouseLocationRelationshipId name="Relationship_CoverageWarehouseLocationRelationshipId">Relationship_CoverageWarehouseLocationRelationshipId</a>

First included in: MasterPlanning/ReqItemCoverageSettingsEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_CoverageWarehouseLocationRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_VendorRelationshipId name="Relationship_VendorRelationshipId">Relationship_VendorRelationshipId</a>

First included in: MasterPlanning/ReqItemCoverageSettingsEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_VendorRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_CoverageInventoryStatusRelationshipId name="Relationship_CoverageInventoryStatusRelationshipId">Relationship_CoverageInventoryStatusRelationshipId</a>

First included in: MasterPlanning/ReqItemCoverageSettingsEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_CoverageInventoryStatusRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_DefaultPlannedTransferOrderFromWarehouseRelationshipId name="Relationship_DefaultPlannedTransferOrderFromWarehouseRelationshipId">Relationship_DefaultPlannedTransferOrderFromWarehouseRelationshipId</a>

First included in: MasterPlanning/ReqItemCoverageSettingsEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_DefaultPlannedTransferOrderFromWarehouseRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_ProductCoverageGroupRelationshipId name="Relationship_ProductCoverageGroupRelationshipId">Relationship_ProductCoverageGroupRelationshipId</a>

First included in: MasterPlanning/ReqItemCoverageSettingsEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_ProductCoverageGroupRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_PlanningFormulaReleasedProductRelationshipId name="Relationship_PlanningFormulaReleasedProductRelationshipId">Relationship_PlanningFormulaReleasedProductRelationshipId</a>

First included in: MasterPlanning/ReqItemCoverageSettingsEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_PlanningFormulaReleasedProductRelationshipId attribute are listed below.</summary>

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

### <a href=#BackingTable_ReqItemTableRelationshipId name="BackingTable_ReqItemTableRelationshipId">BackingTable_ReqItemTableRelationshipId</a>

First included in: MasterPlanning/ReqItemCoverageSettingsEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_ReqItemTableRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/SupplyChain/MasterPlanning/Main/ReqItemTable.md" target="_blank">/core/erp/Tables/SupplyChain/MasterPlanning/Main/ReqItemTable.cdm.json/ReqItemTable</a></td><td><a href="../../../Tables/SupplyChain/MasterPlanning/Main/ReqItemTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PrimaryCompanyContextRelationshipId name="Relationship_PrimaryCompanyContextRelationshipId">Relationship_PrimaryCompanyContextRelationshipId</a>

First included in: MasterPlanning/ReqItemCoverageSettingsEntity (this entity)  

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
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/Finance/Ledger/Main/CompanyInfo.md" target="_blank">/core/erp/Tables/Finance/Ledger/Main/CompanyInfo.cdm.json/CompanyInfo</a></td><td><a href="../../../Tables/Finance/Ledger/Main/CompanyInfo.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>
