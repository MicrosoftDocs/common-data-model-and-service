---
title: InventProductDefaultOrderSettingsEntity in InventoryAndWarehouseManagement - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 7/20/2020
ms.author: nebanfic
---

# Default order settings in InventoryAndWarehouseManagement(InventProductDefaultOrderSettingsEntity)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/SupplyChain/InventoryAndWarehouseManagement/InventProductDefaultOrderSettingsEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Default order settings</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[InventorySiteId](#InventorySiteId)||<a href="InventProductDefaultOrderSettingsEntity.md" target="_blank">InventoryAndWarehouseManagement/InventProductDefaultOrderSettingsEntity</a>|
|[AreInventoryOrderPromisingDefaultsOverridden](#AreInventoryOrderPromisingDefaultsOverridden)||<a href="InventProductDefaultOrderSettingsEntity.md" target="_blank">InventoryAndWarehouseManagement/InventProductDefaultOrderSettingsEntity</a>|
|[InventoryOrderPromisingMethod](#InventoryOrderPromisingMethod)||<a href="InventProductDefaultOrderSettingsEntity.md" target="_blank">InventoryAndWarehouseManagement/InventProductDefaultOrderSettingsEntity</a>|
|[InventoryATPDelayedDemandOffsetDays](#InventoryATPDelayedDemandOffsetDays)||<a href="InventProductDefaultOrderSettingsEntity.md" target="_blank">InventoryAndWarehouseManagement/InventProductDefaultOrderSettingsEntity</a>|
|[InventoryATPDelayedSupplyOffsetDays](#InventoryATPDelayedSupplyOffsetDays)||<a href="InventProductDefaultOrderSettingsEntity.md" target="_blank">InventoryAndWarehouseManagement/InventProductDefaultOrderSettingsEntity</a>|
|[InventoryATPBackwardDemandTimeFenceDays](#InventoryATPBackwardDemandTimeFenceDays)||<a href="InventProductDefaultOrderSettingsEntity.md" target="_blank">InventoryAndWarehouseManagement/InventProductDefaultOrderSettingsEntity</a>|
|[InventoryATPBackwardSupplyTimeFenceDays](#InventoryATPBackwardSupplyTimeFenceDays)||<a href="InventProductDefaultOrderSettingsEntity.md" target="_blank">InventoryAndWarehouseManagement/InventProductDefaultOrderSettingsEntity</a>|
|[IsInventoryATPIncludingPlannedOrders](#IsInventoryATPIncludingPlannedOrders)||<a href="InventProductDefaultOrderSettingsEntity.md" target="_blank">InventoryAndWarehouseManagement/InventProductDefaultOrderSettingsEntity</a>|
|[InventoryATPTimeFenceDays](#InventoryATPTimeFenceDays)||<a href="InventProductDefaultOrderSettingsEntity.md" target="_blank">InventoryAndWarehouseManagement/InventProductDefaultOrderSettingsEntity</a>|
|[IsInventoryUsingWorkingDays](#IsInventoryUsingWorkingDays)||<a href="InventProductDefaultOrderSettingsEntity.md" target="_blank">InventoryAndWarehouseManagement/InventProductDefaultOrderSettingsEntity</a>|
|[MaximumInventoryOrderQuantity](#MaximumInventoryOrderQuantity)||<a href="InventProductDefaultOrderSettingsEntity.md" target="_blank">InventoryAndWarehouseManagement/InventProductDefaultOrderSettingsEntity</a>|
|[MinimumInventoryOrderQuantity](#MinimumInventoryOrderQuantity)||<a href="InventProductDefaultOrderSettingsEntity.md" target="_blank">InventoryAndWarehouseManagement/InventProductDefaultOrderSettingsEntity</a>|
|[StandardInventoryOrderQuantity](#StandardInventoryOrderQuantity)||<a href="InventProductDefaultOrderSettingsEntity.md" target="_blank">InventoryAndWarehouseManagement/InventProductDefaultOrderSettingsEntity</a>|
|[ItemNumber](#ItemNumber)||<a href="InventProductDefaultOrderSettingsEntity.md" target="_blank">InventoryAndWarehouseManagement/InventProductDefaultOrderSettingsEntity</a>|
|[InventoryLeadTimeDays](#InventoryLeadTimeDays)||<a href="InventProductDefaultOrderSettingsEntity.md" target="_blank">InventoryAndWarehouseManagement/InventProductDefaultOrderSettingsEntity</a>|
|[IsInventorySiteMandatory](#IsInventorySiteMandatory)||<a href="InventProductDefaultOrderSettingsEntity.md" target="_blank">InventoryAndWarehouseManagement/InventProductDefaultOrderSettingsEntity</a>|
|[InventoryQuantityMultiples](#InventoryQuantityMultiples)||<a href="InventProductDefaultOrderSettingsEntity.md" target="_blank">InventoryAndWarehouseManagement/InventProductDefaultOrderSettingsEntity</a>|
|[IsInventoryProcessingStopped](#IsInventoryProcessingStopped)||<a href="InventProductDefaultOrderSettingsEntity.md" target="_blank">InventoryAndWarehouseManagement/InventProductDefaultOrderSettingsEntity</a>|
|[ProcurementSiteId](#ProcurementSiteId)||<a href="InventProductDefaultOrderSettingsEntity.md" target="_blank">InventoryAndWarehouseManagement/InventProductDefaultOrderSettingsEntity</a>|
|[IsProcurementUsingWorkingDays](#IsProcurementUsingWorkingDays)||<a href="InventProductDefaultOrderSettingsEntity.md" target="_blank">InventoryAndWarehouseManagement/InventProductDefaultOrderSettingsEntity</a>|
|[ProcurementLeadTimeDays](#ProcurementLeadTimeDays)||<a href="InventProductDefaultOrderSettingsEntity.md" target="_blank">InventoryAndWarehouseManagement/InventProductDefaultOrderSettingsEntity</a>|
|[MaximumProcurementOrderQuantity](#MaximumProcurementOrderQuantity)||<a href="InventProductDefaultOrderSettingsEntity.md" target="_blank">InventoryAndWarehouseManagement/InventProductDefaultOrderSettingsEntity</a>|
|[MinimumProcurementOrderQuantity](#MinimumProcurementOrderQuantity)||<a href="InventProductDefaultOrderSettingsEntity.md" target="_blank">InventoryAndWarehouseManagement/InventProductDefaultOrderSettingsEntity</a>|
|[StandardProcurementOrderQuantity](#StandardProcurementOrderQuantity)||<a href="InventProductDefaultOrderSettingsEntity.md" target="_blank">InventoryAndWarehouseManagement/InventProductDefaultOrderSettingsEntity</a>|
|[IsProcurementSiteMandatory](#IsProcurementSiteMandatory)||<a href="InventProductDefaultOrderSettingsEntity.md" target="_blank">InventoryAndWarehouseManagement/InventProductDefaultOrderSettingsEntity</a>|
|[ProcurementQuantityMultiples](#ProcurementQuantityMultiples)||<a href="InventProductDefaultOrderSettingsEntity.md" target="_blank">InventoryAndWarehouseManagement/InventProductDefaultOrderSettingsEntity</a>|
|[IsProcurementProcessingstopped](#IsProcurementProcessingstopped)||<a href="InventProductDefaultOrderSettingsEntity.md" target="_blank">InventoryAndWarehouseManagement/InventProductDefaultOrderSettingsEntity</a>|
|[SalesSiteId](#SalesSiteId)||<a href="InventProductDefaultOrderSettingsEntity.md" target="_blank">InventoryAndWarehouseManagement/InventProductDefaultOrderSettingsEntity</a>|
|[AreSalesOrderPromisingDefaultsOverridden](#AreSalesOrderPromisingDefaultsOverridden)||<a href="InventProductDefaultOrderSettingsEntity.md" target="_blank">InventoryAndWarehouseManagement/InventProductDefaultOrderSettingsEntity</a>|
|[SalesOrderPromisingMethod](#SalesOrderPromisingMethod)||<a href="InventProductDefaultOrderSettingsEntity.md" target="_blank">InventoryAndWarehouseManagement/InventProductDefaultOrderSettingsEntity</a>|
|[SalesATPDelayedDemandOffsetDays](#SalesATPDelayedDemandOffsetDays)||<a href="InventProductDefaultOrderSettingsEntity.md" target="_blank">InventoryAndWarehouseManagement/InventProductDefaultOrderSettingsEntity</a>|
|[SalesATPDelayedSupplyOffsetDays](#SalesATPDelayedSupplyOffsetDays)||<a href="InventProductDefaultOrderSettingsEntity.md" target="_blank">InventoryAndWarehouseManagement/InventProductDefaultOrderSettingsEntity</a>|
|[SalesATPBackwardDemandTimeFenceDays](#SalesATPBackwardDemandTimeFenceDays)||<a href="InventProductDefaultOrderSettingsEntity.md" target="_blank">InventoryAndWarehouseManagement/InventProductDefaultOrderSettingsEntity</a>|
|[SalesATPBackwardSupplyTimeFenceDays](#SalesATPBackwardSupplyTimeFenceDays)||<a href="InventProductDefaultOrderSettingsEntity.md" target="_blank">InventoryAndWarehouseManagement/InventProductDefaultOrderSettingsEntity</a>|
|[IsSalesATPIncludingPlannedOrders](#IsSalesATPIncludingPlannedOrders)||<a href="InventProductDefaultOrderSettingsEntity.md" target="_blank">InventoryAndWarehouseManagement/InventProductDefaultOrderSettingsEntity</a>|
|[SalesATPTimeFenceDays](#SalesATPTimeFenceDays)||<a href="InventProductDefaultOrderSettingsEntity.md" target="_blank">InventoryAndWarehouseManagement/InventProductDefaultOrderSettingsEntity</a>|
|[MaximumSalesOrderQuantity](#MaximumSalesOrderQuantity)||<a href="InventProductDefaultOrderSettingsEntity.md" target="_blank">InventoryAndWarehouseManagement/InventProductDefaultOrderSettingsEntity</a>|
|[MinimumSalesOrderQuantity](#MinimumSalesOrderQuantity)||<a href="InventProductDefaultOrderSettingsEntity.md" target="_blank">InventoryAndWarehouseManagement/InventProductDefaultOrderSettingsEntity</a>|
|[StandardSalesOrderQuantity](#StandardSalesOrderQuantity)||<a href="InventProductDefaultOrderSettingsEntity.md" target="_blank">InventoryAndWarehouseManagement/InventProductDefaultOrderSettingsEntity</a>|
|[IsSalesSiteMandatory](#IsSalesSiteMandatory)||<a href="InventProductDefaultOrderSettingsEntity.md" target="_blank">InventoryAndWarehouseManagement/InventProductDefaultOrderSettingsEntity</a>|
|[SalesQuantityMultiples](#SalesQuantityMultiples)||<a href="InventProductDefaultOrderSettingsEntity.md" target="_blank">InventoryAndWarehouseManagement/InventProductDefaultOrderSettingsEntity</a>|
|[IsSalesLeadTimeOverridden](#IsSalesLeadTimeOverridden)||<a href="InventProductDefaultOrderSettingsEntity.md" target="_blank">InventoryAndWarehouseManagement/InventProductDefaultOrderSettingsEntity</a>|
|[SalesLeadTimeDays](#SalesLeadTimeDays)||<a href="InventProductDefaultOrderSettingsEntity.md" target="_blank">InventoryAndWarehouseManagement/InventProductDefaultOrderSettingsEntity</a>|
|[IsSalesProcessingStopped](#IsSalesProcessingStopped)||<a href="InventProductDefaultOrderSettingsEntity.md" target="_blank">InventoryAndWarehouseManagement/InventProductDefaultOrderSettingsEntity</a>|
|[InventWarehouseId](#InventWarehouseId)||<a href="InventProductDefaultOrderSettingsEntity.md" target="_blank">InventoryAndWarehouseManagement/InventProductDefaultOrderSettingsEntity</a>|
|[IsInventoryWarehouseMandatory](#IsInventoryWarehouseMandatory)||<a href="InventProductDefaultOrderSettingsEntity.md" target="_blank">InventoryAndWarehouseManagement/InventProductDefaultOrderSettingsEntity</a>|
|[ProcurementWarehouseId](#ProcurementWarehouseId)||<a href="InventProductDefaultOrderSettingsEntity.md" target="_blank">InventoryAndWarehouseManagement/InventProductDefaultOrderSettingsEntity</a>|
|[IsProcurementWarehouseMandatory](#IsProcurementWarehouseMandatory)||<a href="InventProductDefaultOrderSettingsEntity.md" target="_blank">InventoryAndWarehouseManagement/InventProductDefaultOrderSettingsEntity</a>|
|[SalesWarehouseId](#SalesWarehouseId)||<a href="InventProductDefaultOrderSettingsEntity.md" target="_blank">InventoryAndWarehouseManagement/InventProductDefaultOrderSettingsEntity</a>|
|[IsSalesWarehouseMandatory](#IsSalesWarehouseMandatory)||<a href="InventProductDefaultOrderSettingsEntity.md" target="_blank">InventoryAndWarehouseManagement/InventProductDefaultOrderSettingsEntity</a>|
|[Relationship_ReleasedProductRelationshipId](#Relationship_ReleasedProductRelationshipId)||<a href="InventProductDefaultOrderSettingsEntity.md" target="_blank">InventoryAndWarehouseManagement/InventProductDefaultOrderSettingsEntity</a>|
|[Relationship_InventorySiteRelationshipId](#Relationship_InventorySiteRelationshipId)||<a href="InventProductDefaultOrderSettingsEntity.md" target="_blank">InventoryAndWarehouseManagement/InventProductDefaultOrderSettingsEntity</a>|
|[Relationship_InventoryWarehouseRelationshipId](#Relationship_InventoryWarehouseRelationshipId)||<a href="InventProductDefaultOrderSettingsEntity.md" target="_blank">InventoryAndWarehouseManagement/InventProductDefaultOrderSettingsEntity</a>|
|[Relationship_ProcurementSiteRelationshipId](#Relationship_ProcurementSiteRelationshipId)||<a href="InventProductDefaultOrderSettingsEntity.md" target="_blank">InventoryAndWarehouseManagement/InventProductDefaultOrderSettingsEntity</a>|
|[Relationship_ProcurementWarehouseRelationshipId](#Relationship_ProcurementWarehouseRelationshipId)||<a href="InventProductDefaultOrderSettingsEntity.md" target="_blank">InventoryAndWarehouseManagement/InventProductDefaultOrderSettingsEntity</a>|
|[Relationship_SalesSiteRelationshipId](#Relationship_SalesSiteRelationshipId)||<a href="InventProductDefaultOrderSettingsEntity.md" target="_blank">InventoryAndWarehouseManagement/InventProductDefaultOrderSettingsEntity</a>|
|[Relationship_SalesWarehouseRelationshipId](#Relationship_SalesWarehouseRelationshipId)||<a href="InventProductDefaultOrderSettingsEntity.md" target="_blank">InventoryAndWarehouseManagement/InventProductDefaultOrderSettingsEntity</a>|
|[BackingTable_InventItemInventSetupRelationshipId](#BackingTable_InventItemInventSetupRelationshipId)||<a href="InventProductDefaultOrderSettingsEntity.md" target="_blank">InventoryAndWarehouseManagement/InventProductDefaultOrderSettingsEntity</a>|
|[Relationship_PrimaryCompanyContextRelationshipId](#Relationship_PrimaryCompanyContextRelationshipId)||<a href="InventProductDefaultOrderSettingsEntity.md" target="_blank">InventoryAndWarehouseManagement/InventProductDefaultOrderSettingsEntity</a>|

### <a href=#InventorySiteId name="InventorySiteId">InventorySiteId</a>

First included in: InventoryAndWarehouseManagement/InventProductDefaultOrderSettingsEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InventorySiteId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AreInventoryOrderPromisingDefaultsOverridden name="AreInventoryOrderPromisingDefaultsOverridden">AreInventoryOrderPromisingDefaultsOverridden</a>

First included in: InventoryAndWarehouseManagement/InventProductDefaultOrderSettingsEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AreInventoryOrderPromisingDefaultsOverridden attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InventoryOrderPromisingMethod name="InventoryOrderPromisingMethod">InventoryOrderPromisingMethod</a>

First included in: InventoryAndWarehouseManagement/InventProductDefaultOrderSettingsEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InventoryOrderPromisingMethod attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InventoryATPDelayedDemandOffsetDays name="InventoryATPDelayedDemandOffsetDays">InventoryATPDelayedDemandOffsetDays</a>

First included in: InventoryAndWarehouseManagement/InventProductDefaultOrderSettingsEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InventoryATPDelayedDemandOffsetDays attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InventoryATPDelayedSupplyOffsetDays name="InventoryATPDelayedSupplyOffsetDays">InventoryATPDelayedSupplyOffsetDays</a>

First included in: InventoryAndWarehouseManagement/InventProductDefaultOrderSettingsEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InventoryATPDelayedSupplyOffsetDays attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InventoryATPBackwardDemandTimeFenceDays name="InventoryATPBackwardDemandTimeFenceDays">InventoryATPBackwardDemandTimeFenceDays</a>

First included in: InventoryAndWarehouseManagement/InventProductDefaultOrderSettingsEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InventoryATPBackwardDemandTimeFenceDays attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InventoryATPBackwardSupplyTimeFenceDays name="InventoryATPBackwardSupplyTimeFenceDays">InventoryATPBackwardSupplyTimeFenceDays</a>

First included in: InventoryAndWarehouseManagement/InventProductDefaultOrderSettingsEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InventoryATPBackwardSupplyTimeFenceDays attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsInventoryATPIncludingPlannedOrders name="IsInventoryATPIncludingPlannedOrders">IsInventoryATPIncludingPlannedOrders</a>

First included in: InventoryAndWarehouseManagement/InventProductDefaultOrderSettingsEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsInventoryATPIncludingPlannedOrders attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InventoryATPTimeFenceDays name="InventoryATPTimeFenceDays">InventoryATPTimeFenceDays</a>

First included in: InventoryAndWarehouseManagement/InventProductDefaultOrderSettingsEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InventoryATPTimeFenceDays attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsInventoryUsingWorkingDays name="IsInventoryUsingWorkingDays">IsInventoryUsingWorkingDays</a>

First included in: InventoryAndWarehouseManagement/InventProductDefaultOrderSettingsEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsInventoryUsingWorkingDays attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MaximumInventoryOrderQuantity name="MaximumInventoryOrderQuantity">MaximumInventoryOrderQuantity</a>

First included in: InventoryAndWarehouseManagement/InventProductDefaultOrderSettingsEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MaximumInventoryOrderQuantity attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MinimumInventoryOrderQuantity name="MinimumInventoryOrderQuantity">MinimumInventoryOrderQuantity</a>

First included in: InventoryAndWarehouseManagement/InventProductDefaultOrderSettingsEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MinimumInventoryOrderQuantity attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#StandardInventoryOrderQuantity name="StandardInventoryOrderQuantity">StandardInventoryOrderQuantity</a>

First included in: InventoryAndWarehouseManagement/InventProductDefaultOrderSettingsEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the StandardInventoryOrderQuantity attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ItemNumber name="ItemNumber">ItemNumber</a>

First included in: InventoryAndWarehouseManagement/InventProductDefaultOrderSettingsEntity (this entity)  

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

### <a href=#InventoryLeadTimeDays name="InventoryLeadTimeDays">InventoryLeadTimeDays</a>

First included in: InventoryAndWarehouseManagement/InventProductDefaultOrderSettingsEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InventoryLeadTimeDays attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsInventorySiteMandatory name="IsInventorySiteMandatory">IsInventorySiteMandatory</a>

First included in: InventoryAndWarehouseManagement/InventProductDefaultOrderSettingsEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsInventorySiteMandatory attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InventoryQuantityMultiples name="InventoryQuantityMultiples">InventoryQuantityMultiples</a>

First included in: InventoryAndWarehouseManagement/InventProductDefaultOrderSettingsEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InventoryQuantityMultiples attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsInventoryProcessingStopped name="IsInventoryProcessingStopped">IsInventoryProcessingStopped</a>

First included in: InventoryAndWarehouseManagement/InventProductDefaultOrderSettingsEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsInventoryProcessingStopped attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProcurementSiteId name="ProcurementSiteId">ProcurementSiteId</a>

First included in: InventoryAndWarehouseManagement/InventProductDefaultOrderSettingsEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProcurementSiteId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsProcurementUsingWorkingDays name="IsProcurementUsingWorkingDays">IsProcurementUsingWorkingDays</a>

First included in: InventoryAndWarehouseManagement/InventProductDefaultOrderSettingsEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsProcurementUsingWorkingDays attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProcurementLeadTimeDays name="ProcurementLeadTimeDays">ProcurementLeadTimeDays</a>

First included in: InventoryAndWarehouseManagement/InventProductDefaultOrderSettingsEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProcurementLeadTimeDays attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MaximumProcurementOrderQuantity name="MaximumProcurementOrderQuantity">MaximumProcurementOrderQuantity</a>

First included in: InventoryAndWarehouseManagement/InventProductDefaultOrderSettingsEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MaximumProcurementOrderQuantity attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MinimumProcurementOrderQuantity name="MinimumProcurementOrderQuantity">MinimumProcurementOrderQuantity</a>

First included in: InventoryAndWarehouseManagement/InventProductDefaultOrderSettingsEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MinimumProcurementOrderQuantity attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#StandardProcurementOrderQuantity name="StandardProcurementOrderQuantity">StandardProcurementOrderQuantity</a>

First included in: InventoryAndWarehouseManagement/InventProductDefaultOrderSettingsEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the StandardProcurementOrderQuantity attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsProcurementSiteMandatory name="IsProcurementSiteMandatory">IsProcurementSiteMandatory</a>

First included in: InventoryAndWarehouseManagement/InventProductDefaultOrderSettingsEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsProcurementSiteMandatory attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProcurementQuantityMultiples name="ProcurementQuantityMultiples">ProcurementQuantityMultiples</a>

First included in: InventoryAndWarehouseManagement/InventProductDefaultOrderSettingsEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProcurementQuantityMultiples attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsProcurementProcessingstopped name="IsProcurementProcessingstopped">IsProcurementProcessingstopped</a>

First included in: InventoryAndWarehouseManagement/InventProductDefaultOrderSettingsEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsProcurementProcessingstopped attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SalesSiteId name="SalesSiteId">SalesSiteId</a>

First included in: InventoryAndWarehouseManagement/InventProductDefaultOrderSettingsEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SalesSiteId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AreSalesOrderPromisingDefaultsOverridden name="AreSalesOrderPromisingDefaultsOverridden">AreSalesOrderPromisingDefaultsOverridden</a>

First included in: InventoryAndWarehouseManagement/InventProductDefaultOrderSettingsEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AreSalesOrderPromisingDefaultsOverridden attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SalesOrderPromisingMethod name="SalesOrderPromisingMethod">SalesOrderPromisingMethod</a>

First included in: InventoryAndWarehouseManagement/InventProductDefaultOrderSettingsEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SalesOrderPromisingMethod attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SalesATPDelayedDemandOffsetDays name="SalesATPDelayedDemandOffsetDays">SalesATPDelayedDemandOffsetDays</a>

First included in: InventoryAndWarehouseManagement/InventProductDefaultOrderSettingsEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SalesATPDelayedDemandOffsetDays attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SalesATPDelayedSupplyOffsetDays name="SalesATPDelayedSupplyOffsetDays">SalesATPDelayedSupplyOffsetDays</a>

First included in: InventoryAndWarehouseManagement/InventProductDefaultOrderSettingsEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SalesATPDelayedSupplyOffsetDays attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SalesATPBackwardDemandTimeFenceDays name="SalesATPBackwardDemandTimeFenceDays">SalesATPBackwardDemandTimeFenceDays</a>

First included in: InventoryAndWarehouseManagement/InventProductDefaultOrderSettingsEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SalesATPBackwardDemandTimeFenceDays attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SalesATPBackwardSupplyTimeFenceDays name="SalesATPBackwardSupplyTimeFenceDays">SalesATPBackwardSupplyTimeFenceDays</a>

First included in: InventoryAndWarehouseManagement/InventProductDefaultOrderSettingsEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SalesATPBackwardSupplyTimeFenceDays attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsSalesATPIncludingPlannedOrders name="IsSalesATPIncludingPlannedOrders">IsSalesATPIncludingPlannedOrders</a>

First included in: InventoryAndWarehouseManagement/InventProductDefaultOrderSettingsEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsSalesATPIncludingPlannedOrders attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SalesATPTimeFenceDays name="SalesATPTimeFenceDays">SalesATPTimeFenceDays</a>

First included in: InventoryAndWarehouseManagement/InventProductDefaultOrderSettingsEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SalesATPTimeFenceDays attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MaximumSalesOrderQuantity name="MaximumSalesOrderQuantity">MaximumSalesOrderQuantity</a>

First included in: InventoryAndWarehouseManagement/InventProductDefaultOrderSettingsEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MaximumSalesOrderQuantity attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MinimumSalesOrderQuantity name="MinimumSalesOrderQuantity">MinimumSalesOrderQuantity</a>

First included in: InventoryAndWarehouseManagement/InventProductDefaultOrderSettingsEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MinimumSalesOrderQuantity attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#StandardSalesOrderQuantity name="StandardSalesOrderQuantity">StandardSalesOrderQuantity</a>

First included in: InventoryAndWarehouseManagement/InventProductDefaultOrderSettingsEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the StandardSalesOrderQuantity attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsSalesSiteMandatory name="IsSalesSiteMandatory">IsSalesSiteMandatory</a>

First included in: InventoryAndWarehouseManagement/InventProductDefaultOrderSettingsEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsSalesSiteMandatory attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SalesQuantityMultiples name="SalesQuantityMultiples">SalesQuantityMultiples</a>

First included in: InventoryAndWarehouseManagement/InventProductDefaultOrderSettingsEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SalesQuantityMultiples attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsSalesLeadTimeOverridden name="IsSalesLeadTimeOverridden">IsSalesLeadTimeOverridden</a>

First included in: InventoryAndWarehouseManagement/InventProductDefaultOrderSettingsEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsSalesLeadTimeOverridden attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SalesLeadTimeDays name="SalesLeadTimeDays">SalesLeadTimeDays</a>

First included in: InventoryAndWarehouseManagement/InventProductDefaultOrderSettingsEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SalesLeadTimeDays attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsSalesProcessingStopped name="IsSalesProcessingStopped">IsSalesProcessingStopped</a>

First included in: InventoryAndWarehouseManagement/InventProductDefaultOrderSettingsEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsSalesProcessingStopped attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InventWarehouseId name="InventWarehouseId">InventWarehouseId</a>

First included in: InventoryAndWarehouseManagement/InventProductDefaultOrderSettingsEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InventWarehouseId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsInventoryWarehouseMandatory name="IsInventoryWarehouseMandatory">IsInventoryWarehouseMandatory</a>

First included in: InventoryAndWarehouseManagement/InventProductDefaultOrderSettingsEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsInventoryWarehouseMandatory attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProcurementWarehouseId name="ProcurementWarehouseId">ProcurementWarehouseId</a>

First included in: InventoryAndWarehouseManagement/InventProductDefaultOrderSettingsEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProcurementWarehouseId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsProcurementWarehouseMandatory name="IsProcurementWarehouseMandatory">IsProcurementWarehouseMandatory</a>

First included in: InventoryAndWarehouseManagement/InventProductDefaultOrderSettingsEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsProcurementWarehouseMandatory attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SalesWarehouseId name="SalesWarehouseId">SalesWarehouseId</a>

First included in: InventoryAndWarehouseManagement/InventProductDefaultOrderSettingsEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SalesWarehouseId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsSalesWarehouseMandatory name="IsSalesWarehouseMandatory">IsSalesWarehouseMandatory</a>

First included in: InventoryAndWarehouseManagement/InventProductDefaultOrderSettingsEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsSalesWarehouseMandatory attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_ReleasedProductRelationshipId name="Relationship_ReleasedProductRelationshipId">Relationship_ReleasedProductRelationshipId</a>

First included in: InventoryAndWarehouseManagement/InventProductDefaultOrderSettingsEntity (this entity)  

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

### <a href=#Relationship_InventorySiteRelationshipId name="Relationship_InventorySiteRelationshipId">Relationship_InventorySiteRelationshipId</a>

First included in: InventoryAndWarehouseManagement/InventProductDefaultOrderSettingsEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_InventorySiteRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_InventoryWarehouseRelationshipId name="Relationship_InventoryWarehouseRelationshipId">Relationship_InventoryWarehouseRelationshipId</a>

First included in: InventoryAndWarehouseManagement/InventProductDefaultOrderSettingsEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_InventoryWarehouseRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_ProcurementSiteRelationshipId name="Relationship_ProcurementSiteRelationshipId">Relationship_ProcurementSiteRelationshipId</a>

First included in: InventoryAndWarehouseManagement/InventProductDefaultOrderSettingsEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_ProcurementSiteRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_ProcurementWarehouseRelationshipId name="Relationship_ProcurementWarehouseRelationshipId">Relationship_ProcurementWarehouseRelationshipId</a>

First included in: InventoryAndWarehouseManagement/InventProductDefaultOrderSettingsEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_ProcurementWarehouseRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_SalesSiteRelationshipId name="Relationship_SalesSiteRelationshipId">Relationship_SalesSiteRelationshipId</a>

First included in: InventoryAndWarehouseManagement/InventProductDefaultOrderSettingsEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_SalesSiteRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_SalesWarehouseRelationshipId name="Relationship_SalesWarehouseRelationshipId">Relationship_SalesWarehouseRelationshipId</a>

First included in: InventoryAndWarehouseManagement/InventProductDefaultOrderSettingsEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_SalesWarehouseRelationshipId attribute are listed below.</summary>

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

### <a href=#BackingTable_InventItemInventSetupRelationshipId name="BackingTable_InventItemInventSetupRelationshipId">BackingTable_InventItemInventSetupRelationshipId</a>

First included in: InventoryAndWarehouseManagement/InventProductDefaultOrderSettingsEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_InventItemInventSetupRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/SupplyChain/Inventory/Main/InventItemInventSetup.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/Inventory/Main/InventItemInventSetup.cdm.json/InventItemInventSetup</a></td><td><a href="../../../Tables/SupplyChain/Inventory/Main/InventItemInventSetup.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PrimaryCompanyContextRelationshipId name="Relationship_PrimaryCompanyContextRelationshipId">Relationship_PrimaryCompanyContextRelationshipId</a>

First included in: InventoryAndWarehouseManagement/InventProductDefaultOrderSettingsEntity (this entity)  

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
