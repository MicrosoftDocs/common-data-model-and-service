---
title: InventProductSiteSpecificOrderSettingsEntity in InventoryAndWarehouseManagement - Common Data Model | Microsoft Docs
description: undefined
author: llawwaii

ms.reviewer: deonhe
ms.topic: article
ms.date: 8/7/2020
ms.author: weiluo
---

# Site specific order settings in InventoryAndWarehouseManagement(InventProductSiteSpecificOrderSettingsEntity)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/SupplyChain/InventoryAndWarehouseManagement/InventProductSiteSpecificOrderSettingsEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.1"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Site specific order settings</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[ItemNumber](#ItemNumber)||<a href="InventProductSiteSpecificOrderSettingsEntity.md" target="_blank">InventoryAndWarehouseManagement/InventProductSiteSpecificOrderSettingsEntity</a>|
|[OperationalSiteId](#OperationalSiteId)||<a href="InventProductSiteSpecificOrderSettingsEntity.md" target="_blank">InventoryAndWarehouseManagement/InventProductSiteSpecificOrderSettingsEntity</a>|
|[AreInventoryDefaultOrderSettingsOverridden](#AreInventoryDefaultOrderSettingsOverridden)||<a href="InventProductSiteSpecificOrderSettingsEntity.md" target="_blank">InventoryAndWarehouseManagement/InventProductSiteSpecificOrderSettingsEntity</a>|
|[InventoryOrderPromisingMethod](#InventoryOrderPromisingMethod)||<a href="InventProductSiteSpecificOrderSettingsEntity.md" target="_blank">InventoryAndWarehouseManagement/InventProductSiteSpecificOrderSettingsEntity</a>|
|[InventoryATPDelayedDemandOffsetDays](#InventoryATPDelayedDemandOffsetDays)||<a href="InventProductSiteSpecificOrderSettingsEntity.md" target="_blank">InventoryAndWarehouseManagement/InventProductSiteSpecificOrderSettingsEntity</a>|
|[InventoryATPDelayedSupplyOffsetDays](#InventoryATPDelayedSupplyOffsetDays)||<a href="InventProductSiteSpecificOrderSettingsEntity.md" target="_blank">InventoryAndWarehouseManagement/InventProductSiteSpecificOrderSettingsEntity</a>|
|[InventoryATPBackwardDemandTimeFenceDays](#InventoryATPBackwardDemandTimeFenceDays)||<a href="InventProductSiteSpecificOrderSettingsEntity.md" target="_blank">InventoryAndWarehouseManagement/InventProductSiteSpecificOrderSettingsEntity</a>|
|[InventoryATPBackwardSupplyTimeFenceDays](#InventoryATPBackwardSupplyTimeFenceDays)||<a href="InventProductSiteSpecificOrderSettingsEntity.md" target="_blank">InventoryAndWarehouseManagement/InventProductSiteSpecificOrderSettingsEntity</a>|
|[IsInventoryATPIncludingPlannedOrders](#IsInventoryATPIncludingPlannedOrders)||<a href="InventProductSiteSpecificOrderSettingsEntity.md" target="_blank">InventoryAndWarehouseManagement/InventProductSiteSpecificOrderSettingsEntity</a>|
|[InventoryATPTimeFenceDays](#InventoryATPTimeFenceDays)||<a href="InventProductSiteSpecificOrderSettingsEntity.md" target="_blank">InventoryAndWarehouseManagement/InventProductSiteSpecificOrderSettingsEntity</a>|
|[IsInventoryUsingWorkingDays](#IsInventoryUsingWorkingDays)||<a href="InventProductSiteSpecificOrderSettingsEntity.md" target="_blank">InventoryAndWarehouseManagement/InventProductSiteSpecificOrderSettingsEntity</a>|
|[InventoryLeadTimeDays](#InventoryLeadTimeDays)||<a href="InventProductSiteSpecificOrderSettingsEntity.md" target="_blank">InventoryAndWarehouseManagement/InventProductSiteSpecificOrderSettingsEntity</a>|
|[MaximumInventoryOrderQuantity](#MaximumInventoryOrderQuantity)||<a href="InventProductSiteSpecificOrderSettingsEntity.md" target="_blank">InventoryAndWarehouseManagement/InventProductSiteSpecificOrderSettingsEntity</a>|
|[MinimumInventoryOrderQuantity](#MinimumInventoryOrderQuantity)||<a href="InventProductSiteSpecificOrderSettingsEntity.md" target="_blank">InventoryAndWarehouseManagement/InventProductSiteSpecificOrderSettingsEntity</a>|
|[StandardInventoryOrderQuantity](#StandardInventoryOrderQuantity)||<a href="InventProductSiteSpecificOrderSettingsEntity.md" target="_blank">InventoryAndWarehouseManagement/InventProductSiteSpecificOrderSettingsEntity</a>|
|[InventoryQuantityMultiples](#InventoryQuantityMultiples)||<a href="InventProductSiteSpecificOrderSettingsEntity.md" target="_blank">InventoryAndWarehouseManagement/InventProductSiteSpecificOrderSettingsEntity</a>|
|[IsInventoryProcessingStopped](#IsInventoryProcessingStopped)||<a href="InventProductSiteSpecificOrderSettingsEntity.md" target="_blank">InventoryAndWarehouseManagement/InventProductSiteSpecificOrderSettingsEntity</a>|
|[InventoryWarehouseId](#InventoryWarehouseId)||<a href="InventProductSiteSpecificOrderSettingsEntity.md" target="_blank">InventoryAndWarehouseManagement/InventProductSiteSpecificOrderSettingsEntity</a>|
|[IsInventoryWarehouseMandatory](#IsInventoryWarehouseMandatory)||<a href="InventProductSiteSpecificOrderSettingsEntity.md" target="_blank">InventoryAndWarehouseManagement/InventProductSiteSpecificOrderSettingsEntity</a>|
|[AreProcurementDefaultOrderSettingsOverridden](#AreProcurementDefaultOrderSettingsOverridden)||<a href="InventProductSiteSpecificOrderSettingsEntity.md" target="_blank">InventoryAndWarehouseManagement/InventProductSiteSpecificOrderSettingsEntity</a>|
|[IsProcurementProcessingstopped](#IsProcurementProcessingstopped)||<a href="InventProductSiteSpecificOrderSettingsEntity.md" target="_blank">InventoryAndWarehouseManagement/InventProductSiteSpecificOrderSettingsEntity</a>|
|[IsProcurementUsingWorkingDays](#IsProcurementUsingWorkingDays)||<a href="InventProductSiteSpecificOrderSettingsEntity.md" target="_blank">InventoryAndWarehouseManagement/InventProductSiteSpecificOrderSettingsEntity</a>|
|[ProcurementQuantityMultiples](#ProcurementQuantityMultiples)||<a href="InventProductSiteSpecificOrderSettingsEntity.md" target="_blank">InventoryAndWarehouseManagement/InventProductSiteSpecificOrderSettingsEntity</a>|
|[MaximumProcurementOrderQuantity](#MaximumProcurementOrderQuantity)||<a href="InventProductSiteSpecificOrderSettingsEntity.md" target="_blank">InventoryAndWarehouseManagement/InventProductSiteSpecificOrderSettingsEntity</a>|
|[MinimumProcurementOrderQuantity](#MinimumProcurementOrderQuantity)||<a href="InventProductSiteSpecificOrderSettingsEntity.md" target="_blank">InventoryAndWarehouseManagement/InventProductSiteSpecificOrderSettingsEntity</a>|
|[StandardProcurementOrderQuantity](#StandardProcurementOrderQuantity)||<a href="InventProductSiteSpecificOrderSettingsEntity.md" target="_blank">InventoryAndWarehouseManagement/InventProductSiteSpecificOrderSettingsEntity</a>|
|[ProcurementLeadTimeDays](#ProcurementLeadTimeDays)||<a href="InventProductSiteSpecificOrderSettingsEntity.md" target="_blank">InventoryAndWarehouseManagement/InventProductSiteSpecificOrderSettingsEntity</a>|
|[ProcurementWarehouseId](#ProcurementWarehouseId)||<a href="InventProductSiteSpecificOrderSettingsEntity.md" target="_blank">InventoryAndWarehouseManagement/InventProductSiteSpecificOrderSettingsEntity</a>|
|[IsProcurementWarehouseMandatory](#IsProcurementWarehouseMandatory)||<a href="InventProductSiteSpecificOrderSettingsEntity.md" target="_blank">InventoryAndWarehouseManagement/InventProductSiteSpecificOrderSettingsEntity</a>|
|[AreSalesDefaultOrderSettingsOverridden](#AreSalesDefaultOrderSettingsOverridden)||<a href="InventProductSiteSpecificOrderSettingsEntity.md" target="_blank">InventoryAndWarehouseManagement/InventProductSiteSpecificOrderSettingsEntity</a>|
|[SalesOrderPromisingMethod](#SalesOrderPromisingMethod)||<a href="InventProductSiteSpecificOrderSettingsEntity.md" target="_blank">InventoryAndWarehouseManagement/InventProductSiteSpecificOrderSettingsEntity</a>|
|[SalesATPDelayedDemandOffsetDays](#SalesATPDelayedDemandOffsetDays)||<a href="InventProductSiteSpecificOrderSettingsEntity.md" target="_blank">InventoryAndWarehouseManagement/InventProductSiteSpecificOrderSettingsEntity</a>|
|[SalesATPDelayedSupplyOffsetDays](#SalesATPDelayedSupplyOffsetDays)||<a href="InventProductSiteSpecificOrderSettingsEntity.md" target="_blank">InventoryAndWarehouseManagement/InventProductSiteSpecificOrderSettingsEntity</a>|
|[SalesATPBackwardDemandTimeFenceDays](#SalesATPBackwardDemandTimeFenceDays)||<a href="InventProductSiteSpecificOrderSettingsEntity.md" target="_blank">InventoryAndWarehouseManagement/InventProductSiteSpecificOrderSettingsEntity</a>|
|[SalesATPBackwardSupplyTimeFenceDays](#SalesATPBackwardSupplyTimeFenceDays)||<a href="InventProductSiteSpecificOrderSettingsEntity.md" target="_blank">InventoryAndWarehouseManagement/InventProductSiteSpecificOrderSettingsEntity</a>|
|[IsSalesATPIncludingPlannedOrders](#IsSalesATPIncludingPlannedOrders)||<a href="InventProductSiteSpecificOrderSettingsEntity.md" target="_blank">InventoryAndWarehouseManagement/InventProductSiteSpecificOrderSettingsEntity</a>|
|[SalesATPTimeFenceDays](#SalesATPTimeFenceDays)||<a href="InventProductSiteSpecificOrderSettingsEntity.md" target="_blank">InventoryAndWarehouseManagement/InventProductSiteSpecificOrderSettingsEntity</a>|
|[IsSalesProcessingStopped](#IsSalesProcessingStopped)||<a href="InventProductSiteSpecificOrderSettingsEntity.md" target="_blank">InventoryAndWarehouseManagement/InventProductSiteSpecificOrderSettingsEntity</a>|
|[SalesQuantityMultiples](#SalesQuantityMultiples)||<a href="InventProductSiteSpecificOrderSettingsEntity.md" target="_blank">InventoryAndWarehouseManagement/InventProductSiteSpecificOrderSettingsEntity</a>|
|[MaximumSalesOrderQuantity](#MaximumSalesOrderQuantity)||<a href="InventProductSiteSpecificOrderSettingsEntity.md" target="_blank">InventoryAndWarehouseManagement/InventProductSiteSpecificOrderSettingsEntity</a>|
|[MinimumSalesOrderQuantity](#MinimumSalesOrderQuantity)||<a href="InventProductSiteSpecificOrderSettingsEntity.md" target="_blank">InventoryAndWarehouseManagement/InventProductSiteSpecificOrderSettingsEntity</a>|
|[StandardSalesOrderQuantity](#StandardSalesOrderQuantity)||<a href="InventProductSiteSpecificOrderSettingsEntity.md" target="_blank">InventoryAndWarehouseManagement/InventProductSiteSpecificOrderSettingsEntity</a>|
|[SalesLeadTimeDays](#SalesLeadTimeDays)||<a href="InventProductSiteSpecificOrderSettingsEntity.md" target="_blank">InventoryAndWarehouseManagement/InventProductSiteSpecificOrderSettingsEntity</a>|
|[SalesWarehouseId](#SalesWarehouseId)||<a href="InventProductSiteSpecificOrderSettingsEntity.md" target="_blank">InventoryAndWarehouseManagement/InventProductSiteSpecificOrderSettingsEntity</a>|
|[IsSalesWarehouseMandatory](#IsSalesWarehouseMandatory)||<a href="InventProductSiteSpecificOrderSettingsEntity.md" target="_blank">InventoryAndWarehouseManagement/InventProductSiteSpecificOrderSettingsEntity</a>|
|[BackingTable_InventItemInventSetupRelationshipId](#BackingTable_InventItemInventSetupRelationshipId)||<a href="InventProductSiteSpecificOrderSettingsEntity.md" target="_blank">InventoryAndWarehouseManagement/InventProductSiteSpecificOrderSettingsEntity</a>|
|[Relationship_PrimaryCompanyContextRelationshipId](#Relationship_PrimaryCompanyContextRelationshipId)||<a href="InventProductSiteSpecificOrderSettingsEntity.md" target="_blank">InventoryAndWarehouseManagement/InventProductSiteSpecificOrderSettingsEntity</a>|

### <a href=#ItemNumber name="ItemNumber">ItemNumber</a>

First included in: InventoryAndWarehouseManagement/InventProductSiteSpecificOrderSettingsEntity (this entity)  

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

### <a href=#OperationalSiteId name="OperationalSiteId">OperationalSiteId</a>

First included in: InventoryAndWarehouseManagement/InventProductSiteSpecificOrderSettingsEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OperationalSiteId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AreInventoryDefaultOrderSettingsOverridden name="AreInventoryDefaultOrderSettingsOverridden">AreInventoryDefaultOrderSettingsOverridden</a>

First included in: InventoryAndWarehouseManagement/InventProductSiteSpecificOrderSettingsEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AreInventoryDefaultOrderSettingsOverridden attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InventoryOrderPromisingMethod name="InventoryOrderPromisingMethod">InventoryOrderPromisingMethod</a>

First included in: InventoryAndWarehouseManagement/InventProductSiteSpecificOrderSettingsEntity (this entity)  

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

First included in: InventoryAndWarehouseManagement/InventProductSiteSpecificOrderSettingsEntity (this entity)  

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

First included in: InventoryAndWarehouseManagement/InventProductSiteSpecificOrderSettingsEntity (this entity)  

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

First included in: InventoryAndWarehouseManagement/InventProductSiteSpecificOrderSettingsEntity (this entity)  

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

First included in: InventoryAndWarehouseManagement/InventProductSiteSpecificOrderSettingsEntity (this entity)  

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

First included in: InventoryAndWarehouseManagement/InventProductSiteSpecificOrderSettingsEntity (this entity)  

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

First included in: InventoryAndWarehouseManagement/InventProductSiteSpecificOrderSettingsEntity (this entity)  

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

First included in: InventoryAndWarehouseManagement/InventProductSiteSpecificOrderSettingsEntity (this entity)  

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

### <a href=#InventoryLeadTimeDays name="InventoryLeadTimeDays">InventoryLeadTimeDays</a>

First included in: InventoryAndWarehouseManagement/InventProductSiteSpecificOrderSettingsEntity (this entity)  

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

### <a href=#MaximumInventoryOrderQuantity name="MaximumInventoryOrderQuantity">MaximumInventoryOrderQuantity</a>

First included in: InventoryAndWarehouseManagement/InventProductSiteSpecificOrderSettingsEntity (this entity)  

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

First included in: InventoryAndWarehouseManagement/InventProductSiteSpecificOrderSettingsEntity (this entity)  

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

First included in: InventoryAndWarehouseManagement/InventProductSiteSpecificOrderSettingsEntity (this entity)  

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

### <a href=#InventoryQuantityMultiples name="InventoryQuantityMultiples">InventoryQuantityMultiples</a>

First included in: InventoryAndWarehouseManagement/InventProductSiteSpecificOrderSettingsEntity (this entity)  

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

First included in: InventoryAndWarehouseManagement/InventProductSiteSpecificOrderSettingsEntity (this entity)  

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

### <a href=#InventoryWarehouseId name="InventoryWarehouseId">InventoryWarehouseId</a>

First included in: InventoryAndWarehouseManagement/InventProductSiteSpecificOrderSettingsEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InventoryWarehouseId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsInventoryWarehouseMandatory name="IsInventoryWarehouseMandatory">IsInventoryWarehouseMandatory</a>

First included in: InventoryAndWarehouseManagement/InventProductSiteSpecificOrderSettingsEntity (this entity)  

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

### <a href=#AreProcurementDefaultOrderSettingsOverridden name="AreProcurementDefaultOrderSettingsOverridden">AreProcurementDefaultOrderSettingsOverridden</a>

First included in: InventoryAndWarehouseManagement/InventProductSiteSpecificOrderSettingsEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AreProcurementDefaultOrderSettingsOverridden attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsProcurementProcessingstopped name="IsProcurementProcessingstopped">IsProcurementProcessingstopped</a>

First included in: InventoryAndWarehouseManagement/InventProductSiteSpecificOrderSettingsEntity (this entity)  

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

### <a href=#IsProcurementUsingWorkingDays name="IsProcurementUsingWorkingDays">IsProcurementUsingWorkingDays</a>

First included in: InventoryAndWarehouseManagement/InventProductSiteSpecificOrderSettingsEntity (this entity)  

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

### <a href=#ProcurementQuantityMultiples name="ProcurementQuantityMultiples">ProcurementQuantityMultiples</a>

First included in: InventoryAndWarehouseManagement/InventProductSiteSpecificOrderSettingsEntity (this entity)  

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

### <a href=#MaximumProcurementOrderQuantity name="MaximumProcurementOrderQuantity">MaximumProcurementOrderQuantity</a>

First included in: InventoryAndWarehouseManagement/InventProductSiteSpecificOrderSettingsEntity (this entity)  

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

First included in: InventoryAndWarehouseManagement/InventProductSiteSpecificOrderSettingsEntity (this entity)  

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

First included in: InventoryAndWarehouseManagement/InventProductSiteSpecificOrderSettingsEntity (this entity)  

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

### <a href=#ProcurementLeadTimeDays name="ProcurementLeadTimeDays">ProcurementLeadTimeDays</a>

First included in: InventoryAndWarehouseManagement/InventProductSiteSpecificOrderSettingsEntity (this entity)  

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

### <a href=#ProcurementWarehouseId name="ProcurementWarehouseId">ProcurementWarehouseId</a>

First included in: InventoryAndWarehouseManagement/InventProductSiteSpecificOrderSettingsEntity (this entity)  

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

First included in: InventoryAndWarehouseManagement/InventProductSiteSpecificOrderSettingsEntity (this entity)  

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

### <a href=#AreSalesDefaultOrderSettingsOverridden name="AreSalesDefaultOrderSettingsOverridden">AreSalesDefaultOrderSettingsOverridden</a>

First included in: InventoryAndWarehouseManagement/InventProductSiteSpecificOrderSettingsEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AreSalesDefaultOrderSettingsOverridden attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SalesOrderPromisingMethod name="SalesOrderPromisingMethod">SalesOrderPromisingMethod</a>

First included in: InventoryAndWarehouseManagement/InventProductSiteSpecificOrderSettingsEntity (this entity)  

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

First included in: InventoryAndWarehouseManagement/InventProductSiteSpecificOrderSettingsEntity (this entity)  

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

First included in: InventoryAndWarehouseManagement/InventProductSiteSpecificOrderSettingsEntity (this entity)  

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

First included in: InventoryAndWarehouseManagement/InventProductSiteSpecificOrderSettingsEntity (this entity)  

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

First included in: InventoryAndWarehouseManagement/InventProductSiteSpecificOrderSettingsEntity (this entity)  

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

First included in: InventoryAndWarehouseManagement/InventProductSiteSpecificOrderSettingsEntity (this entity)  

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

First included in: InventoryAndWarehouseManagement/InventProductSiteSpecificOrderSettingsEntity (this entity)  

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

### <a href=#IsSalesProcessingStopped name="IsSalesProcessingStopped">IsSalesProcessingStopped</a>

First included in: InventoryAndWarehouseManagement/InventProductSiteSpecificOrderSettingsEntity (this entity)  

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

### <a href=#SalesQuantityMultiples name="SalesQuantityMultiples">SalesQuantityMultiples</a>

First included in: InventoryAndWarehouseManagement/InventProductSiteSpecificOrderSettingsEntity (this entity)  

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

### <a href=#MaximumSalesOrderQuantity name="MaximumSalesOrderQuantity">MaximumSalesOrderQuantity</a>

First included in: InventoryAndWarehouseManagement/InventProductSiteSpecificOrderSettingsEntity (this entity)  

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

First included in: InventoryAndWarehouseManagement/InventProductSiteSpecificOrderSettingsEntity (this entity)  

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

First included in: InventoryAndWarehouseManagement/InventProductSiteSpecificOrderSettingsEntity (this entity)  

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

### <a href=#SalesLeadTimeDays name="SalesLeadTimeDays">SalesLeadTimeDays</a>

First included in: InventoryAndWarehouseManagement/InventProductSiteSpecificOrderSettingsEntity (this entity)  

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

### <a href=#SalesWarehouseId name="SalesWarehouseId">SalesWarehouseId</a>

First included in: InventoryAndWarehouseManagement/InventProductSiteSpecificOrderSettingsEntity (this entity)  

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

First included in: InventoryAndWarehouseManagement/InventProductSiteSpecificOrderSettingsEntity (this entity)  

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

### <a href=#BackingTable_InventItemInventSetupRelationshipId name="BackingTable_InventItemInventSetupRelationshipId">BackingTable_InventItemInventSetupRelationshipId</a>

First included in: InventoryAndWarehouseManagement/InventProductSiteSpecificOrderSettingsEntity (this entity)  

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

First included in: InventoryAndWarehouseManagement/InventProductSiteSpecificOrderSettingsEntity (this entity)  

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
