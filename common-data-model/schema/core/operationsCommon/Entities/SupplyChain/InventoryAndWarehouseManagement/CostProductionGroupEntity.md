---
title: CostProductionGroupEntity - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/20/2020
ms.author: nebanfic
---

# CostProductionGroupEntity

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/SupplyChain/InventoryAndWarehouseManagement/CostProductionGroupEntity.cdm.json" target="_blank">GitHub</a>.  

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
|[GroupId](#GroupId)||<a href="CostProductionGroupEntity.md" target="_blank">InventoryAndWarehouseManagement/CostProductionGroupEntity</a>|
|[GroupName](#GroupName)||<a href="CostProductionGroupEntity.md" target="_blank">InventoryAndWarehouseManagement/CostProductionGroupEntity</a>|
|[EstimatedCostOfMaterialsConsumedMainAccountId](#EstimatedCostOfMaterialsConsumedMainAccountId)||<a href="CostProductionGroupEntity.md" target="_blank">InventoryAndWarehouseManagement/CostProductionGroupEntity</a>|
|[EstimatedCostOfMaterialsConsumedMainAccountIdDisplayValue](#EstimatedCostOfMaterialsConsumedMainAccountIdDisplayValue)||<a href="CostProductionGroupEntity.md" target="_blank">InventoryAndWarehouseManagement/CostProductionGroupEntity</a>|
|[EstimatedCostOfMaterialsConsumedWIPMainAccountId](#EstimatedCostOfMaterialsConsumedWIPMainAccountId)||<a href="CostProductionGroupEntity.md" target="_blank">InventoryAndWarehouseManagement/CostProductionGroupEntity</a>|
|[EstimatedCostOfMaterialsConsumedWIPMainAccountIdDisplayValue](#EstimatedCostOfMaterialsConsumedWIPMainAccountIdDisplayValue)||<a href="CostProductionGroupEntity.md" target="_blank">InventoryAndWarehouseManagement/CostProductionGroupEntity</a>|
|[EstimatedManufacturedCostMainAccountId](#EstimatedManufacturedCostMainAccountId)||<a href="CostProductionGroupEntity.md" target="_blank">InventoryAndWarehouseManagement/CostProductionGroupEntity</a>|
|[EstimatedManufacturedCostMainAccountIdDisplayValue](#EstimatedManufacturedCostMainAccountIdDisplayValue)||<a href="CostProductionGroupEntity.md" target="_blank">InventoryAndWarehouseManagement/CostProductionGroupEntity</a>|
|[EstimatedManufacturedCostWIPMainAccountId](#EstimatedManufacturedCostWIPMainAccountId)||<a href="CostProductionGroupEntity.md" target="_blank">InventoryAndWarehouseManagement/CostProductionGroupEntity</a>|
|[EstimatedManufacturedCostWIPMainAccountIdDisplayValue](#EstimatedManufacturedCostWIPMainAccountIdDisplayValue)||<a href="CostProductionGroupEntity.md" target="_blank">InventoryAndWarehouseManagement/CostProductionGroupEntity</a>|
|[RealizedCostOfMaterialsConsumedMainAccountId](#RealizedCostOfMaterialsConsumedMainAccountId)||<a href="CostProductionGroupEntity.md" target="_blank">InventoryAndWarehouseManagement/CostProductionGroupEntity</a>|
|[RealizedCostOfMaterialsConsumedMainAccountIdDisplayValue](#RealizedCostOfMaterialsConsumedMainAccountIdDisplayValue)||<a href="CostProductionGroupEntity.md" target="_blank">InventoryAndWarehouseManagement/CostProductionGroupEntity</a>|
|[RealizedCostOfMaterialsConsumedWIPMainAccountId](#RealizedCostOfMaterialsConsumedWIPMainAccountId)||<a href="CostProductionGroupEntity.md" target="_blank">InventoryAndWarehouseManagement/CostProductionGroupEntity</a>|
|[RealizedCostOfMaterialsConsumedWIPMainAccountIdDisplayValue](#RealizedCostOfMaterialsConsumedWIPMainAccountIdDisplayValue)||<a href="CostProductionGroupEntity.md" target="_blank">InventoryAndWarehouseManagement/CostProductionGroupEntity</a>|
|[RealizedManufacturedCostMainAccountId](#RealizedManufacturedCostMainAccountId)||<a href="CostProductionGroupEntity.md" target="_blank">InventoryAndWarehouseManagement/CostProductionGroupEntity</a>|
|[RealizedManufacturedCostMainAccountIdDisplayValue](#RealizedManufacturedCostMainAccountIdDisplayValue)||<a href="CostProductionGroupEntity.md" target="_blank">InventoryAndWarehouseManagement/CostProductionGroupEntity</a>|
|[RealizedManufacturedCostWIPMainAccountId](#RealizedManufacturedCostWIPMainAccountId)||<a href="CostProductionGroupEntity.md" target="_blank">InventoryAndWarehouseManagement/CostProductionGroupEntity</a>|
|[RealizedManufacturedCostWIPMainAccountIdDisplayValue](#RealizedManufacturedCostWIPMainAccountIdDisplayValue)||<a href="CostProductionGroupEntity.md" target="_blank">InventoryAndWarehouseManagement/CostProductionGroupEntity</a>|
|[EstimatedManufacturingCostAbsorbedMainAccountId](#EstimatedManufacturingCostAbsorbedMainAccountId)||<a href="CostProductionGroupEntity.md" target="_blank">InventoryAndWarehouseManagement/CostProductionGroupEntity</a>|
|[EstimatedManufacturingCostAbsorbedMainAccountIdDisplayValue](#EstimatedManufacturingCostAbsorbedMainAccountIdDisplayValue)||<a href="CostProductionGroupEntity.md" target="_blank">InventoryAndWarehouseManagement/CostProductionGroupEntity</a>|
|[EstimatedCostOfManufacturingConsumedMainAccountId](#EstimatedCostOfManufacturingConsumedMainAccountId)||<a href="CostProductionGroupEntity.md" target="_blank">InventoryAndWarehouseManagement/CostProductionGroupEntity</a>|
|[EstimatedCostOfManufacturingConsumedMainAccountIdDisplayValue](#EstimatedCostOfManufacturingConsumedMainAccountIdDisplayValue)||<a href="CostProductionGroupEntity.md" target="_blank">InventoryAndWarehouseManagement/CostProductionGroupEntity</a>|
|[RealizedManufacturingCostAbsorbedMainAccountId](#RealizedManufacturingCostAbsorbedMainAccountId)||<a href="CostProductionGroupEntity.md" target="_blank">InventoryAndWarehouseManagement/CostProductionGroupEntity</a>|
|[RealizedManufacturingCostAbsorbedMainAccountIdDisplayValue](#RealizedManufacturingCostAbsorbedMainAccountIdDisplayValue)||<a href="CostProductionGroupEntity.md" target="_blank">InventoryAndWarehouseManagement/CostProductionGroupEntity</a>|
|[RealizedCostOfManufacturingConsumedMainAccountId](#RealizedCostOfManufacturingConsumedMainAccountId)||<a href="CostProductionGroupEntity.md" target="_blank">InventoryAndWarehouseManagement/CostProductionGroupEntity</a>|
|[RealizedCostOfManufacturingConsumedMainAccountIdDisplayValue](#RealizedCostOfManufacturingConsumedMainAccountIdDisplayValue)||<a href="CostProductionGroupEntity.md" target="_blank">InventoryAndWarehouseManagement/CostProductionGroupEntity</a>|
|[WIPServiceReceiptMainAccountId](#WIPServiceReceiptMainAccountId)||<a href="CostProductionGroupEntity.md" target="_blank">InventoryAndWarehouseManagement/CostProductionGroupEntity</a>|
|[WIPServiceReceiptMainAccountIdDisplayValue](#WIPServiceReceiptMainAccountIdDisplayValue)||<a href="CostProductionGroupEntity.md" target="_blank">InventoryAndWarehouseManagement/CostProductionGroupEntity</a>|
|[WIPServiceClearingMainAccountId](#WIPServiceClearingMainAccountId)||<a href="CostProductionGroupEntity.md" target="_blank">InventoryAndWarehouseManagement/CostProductionGroupEntity</a>|
|[WIPServiceClearingMainAccountIdDisplayValue](#WIPServiceClearingMainAccountIdDisplayValue)||<a href="CostProductionGroupEntity.md" target="_blank">InventoryAndWarehouseManagement/CostProductionGroupEntity</a>|
|[RealizedCostOfIndirectCostConsumedMainAccountId](#RealizedCostOfIndirectCostConsumedMainAccountId)||<a href="CostProductionGroupEntity.md" target="_blank">InventoryAndWarehouseManagement/CostProductionGroupEntity</a>|
|[RealizedCostOfIndirectCostConsumedMainAccountIdDisplayValue](#RealizedCostOfIndirectCostConsumedMainAccountIdDisplayValue)||<a href="CostProductionGroupEntity.md" target="_blank">InventoryAndWarehouseManagement/CostProductionGroupEntity</a>|
|[EstimatedCostOfIndirectCostConsumedMainAccountId](#EstimatedCostOfIndirectCostConsumedMainAccountId)||<a href="CostProductionGroupEntity.md" target="_blank">InventoryAndWarehouseManagement/CostProductionGroupEntity</a>|
|[EstimatedCostOfIndirectCostConsumedMainAccountIdDisplayValue](#EstimatedCostOfIndirectCostConsumedMainAccountIdDisplayValue)||<a href="CostProductionGroupEntity.md" target="_blank">InventoryAndWarehouseManagement/CostProductionGroupEntity</a>|
|[Relationship_EstimatedCostOfIndirectCostConsumedMainAccountIdCombinationRelationshipId](#Relationship_EstimatedCostOfIndirectCostConsumedMainAccountIdCombinationRelationshipId)||<a href="CostProductionGroupEntity.md" target="_blank">InventoryAndWarehouseManagement/CostProductionGroupEntity</a>|
|[Relationship_RealizedCostOfIndirectCostConsumedMainAccountIdCombinationRelationshipId](#Relationship_RealizedCostOfIndirectCostConsumedMainAccountIdCombinationRelationshipId)||<a href="CostProductionGroupEntity.md" target="_blank">InventoryAndWarehouseManagement/CostProductionGroupEntity</a>|
|[Relationship_RealizedCostOfMaterialsConsumedMainAccountIdCombinationRelationshipId](#Relationship_RealizedCostOfMaterialsConsumedMainAccountIdCombinationRelationshipId)||<a href="CostProductionGroupEntity.md" target="_blank">InventoryAndWarehouseManagement/CostProductionGroupEntity</a>|
|[Relationship_RealizedCostOfMaterialsConsumedWIPMainAccountIdCombinationRelationshipId](#Relationship_RealizedCostOfMaterialsConsumedWIPMainAccountIdCombinationRelationshipId)||<a href="CostProductionGroupEntity.md" target="_blank">InventoryAndWarehouseManagement/CostProductionGroupEntity</a>|
|[Relationship_WIPServiceClearingMainAccountIdCombinationRelationshipId](#Relationship_WIPServiceClearingMainAccountIdCombinationRelationshipId)||<a href="CostProductionGroupEntity.md" target="_blank">InventoryAndWarehouseManagement/CostProductionGroupEntity</a>|
|[Relationship_WIPServiceReceiptMainAccountIdCombinationRelationshipId](#Relationship_WIPServiceReceiptMainAccountIdCombinationRelationshipId)||<a href="CostProductionGroupEntity.md" target="_blank">InventoryAndWarehouseManagement/CostProductionGroupEntity</a>|
|[Relationship_EstimatedCostOfMaterialsConsumedMainAccountIdCombinationRelationshipId](#Relationship_EstimatedCostOfMaterialsConsumedMainAccountIdCombinationRelationshipId)||<a href="CostProductionGroupEntity.md" target="_blank">InventoryAndWarehouseManagement/CostProductionGroupEntity</a>|
|[Relationship_EstimatedCostOfMaterialsConsumedWIPMainAccountIdCombinationRelationshipId](#Relationship_EstimatedCostOfMaterialsConsumedWIPMainAccountIdCombinationRelationshipId)||<a href="CostProductionGroupEntity.md" target="_blank">InventoryAndWarehouseManagement/CostProductionGroupEntity</a>|
|[Relationship_RealizedManufacturedCostMainAccountIdCombinationRelationshipId](#Relationship_RealizedManufacturedCostMainAccountIdCombinationRelationshipId)||<a href="CostProductionGroupEntity.md" target="_blank">InventoryAndWarehouseManagement/CostProductionGroupEntity</a>|
|[Relationship_RealizedManufacturedCostWIPMainAccountIdCombinationRelationshipId](#Relationship_RealizedManufacturedCostWIPMainAccountIdCombinationRelationshipId)||<a href="CostProductionGroupEntity.md" target="_blank">InventoryAndWarehouseManagement/CostProductionGroupEntity</a>|
|[Relationship_EstimatedManufacturedCostMainAccountIdCombinationRelationshipId](#Relationship_EstimatedManufacturedCostMainAccountIdCombinationRelationshipId)||<a href="CostProductionGroupEntity.md" target="_blank">InventoryAndWarehouseManagement/CostProductionGroupEntity</a>|
|[Relationship_EstimatedManufacturedCostWIPMainAccountIdCombinationRelationshipId](#Relationship_EstimatedManufacturedCostWIPMainAccountIdCombinationRelationshipId)||<a href="CostProductionGroupEntity.md" target="_blank">InventoryAndWarehouseManagement/CostProductionGroupEntity</a>|
|[Relationship_RealizedManufacturingCostAbsorbedMainAccountIdCombinationRelationshipId](#Relationship_RealizedManufacturingCostAbsorbedMainAccountIdCombinationRelationshipId)||<a href="CostProductionGroupEntity.md" target="_blank">InventoryAndWarehouseManagement/CostProductionGroupEntity</a>|
|[Relationship_RealizedCostOfManufacturingConsumedMainAccountIdCombinationRelationshipId](#Relationship_RealizedCostOfManufacturingConsumedMainAccountIdCombinationRelationshipId)||<a href="CostProductionGroupEntity.md" target="_blank">InventoryAndWarehouseManagement/CostProductionGroupEntity</a>|
|[Relationship_EstimatedManufacturingCostAbsorbedMainAccountIdCombinationRelationshipId](#Relationship_EstimatedManufacturingCostAbsorbedMainAccountIdCombinationRelationshipId)||<a href="CostProductionGroupEntity.md" target="_blank">InventoryAndWarehouseManagement/CostProductionGroupEntity</a>|
|[Relationship_EstimatedCostOfManufacturingConsumedMainAccountIdCombinationRelationshipId](#Relationship_EstimatedCostOfManufacturingConsumedMainAccountIdCombinationRelationshipId)||<a href="CostProductionGroupEntity.md" target="_blank">InventoryAndWarehouseManagement/CostProductionGroupEntity</a>|
|[BackingTable_ProdGroupRelationshipId](#BackingTable_ProdGroupRelationshipId)||<a href="CostProductionGroupEntity.md" target="_blank">InventoryAndWarehouseManagement/CostProductionGroupEntity</a>|
|[Relationship_PrimaryCompanyContextRelationshipId](#Relationship_PrimaryCompanyContextRelationshipId)||<a href="CostProductionGroupEntity.md" target="_blank">InventoryAndWarehouseManagement/CostProductionGroupEntity</a>|

### <a href=#GroupId name="GroupId">GroupId</a>

First included in: InventoryAndWarehouseManagement/CostProductionGroupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the GroupId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#GroupName name="GroupName">GroupName</a>

First included in: InventoryAndWarehouseManagement/CostProductionGroupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the GroupName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#EstimatedCostOfMaterialsConsumedMainAccountId name="EstimatedCostOfMaterialsConsumedMainAccountId">EstimatedCostOfMaterialsConsumedMainAccountId</a>

First included in: InventoryAndWarehouseManagement/CostProductionGroupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EstimatedCostOfMaterialsConsumedMainAccountId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#EstimatedCostOfMaterialsConsumedMainAccountIdDisplayValue name="EstimatedCostOfMaterialsConsumedMainAccountIdDisplayValue">EstimatedCostOfMaterialsConsumedMainAccountIdDisplayValue</a>

First included in: InventoryAndWarehouseManagement/CostProductionGroupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EstimatedCostOfMaterialsConsumedMainAccountIdDisplayValue attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#EstimatedCostOfMaterialsConsumedWIPMainAccountId name="EstimatedCostOfMaterialsConsumedWIPMainAccountId">EstimatedCostOfMaterialsConsumedWIPMainAccountId</a>

First included in: InventoryAndWarehouseManagement/CostProductionGroupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EstimatedCostOfMaterialsConsumedWIPMainAccountId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#EstimatedCostOfMaterialsConsumedWIPMainAccountIdDisplayValue name="EstimatedCostOfMaterialsConsumedWIPMainAccountIdDisplayValue">EstimatedCostOfMaterialsConsumedWIPMainAccountIdDisplayValue</a>

First included in: InventoryAndWarehouseManagement/CostProductionGroupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EstimatedCostOfMaterialsConsumedWIPMainAccountIdDisplayValue attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#EstimatedManufacturedCostMainAccountId name="EstimatedManufacturedCostMainAccountId">EstimatedManufacturedCostMainAccountId</a>

First included in: InventoryAndWarehouseManagement/CostProductionGroupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EstimatedManufacturedCostMainAccountId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#EstimatedManufacturedCostMainAccountIdDisplayValue name="EstimatedManufacturedCostMainAccountIdDisplayValue">EstimatedManufacturedCostMainAccountIdDisplayValue</a>

First included in: InventoryAndWarehouseManagement/CostProductionGroupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EstimatedManufacturedCostMainAccountIdDisplayValue attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#EstimatedManufacturedCostWIPMainAccountId name="EstimatedManufacturedCostWIPMainAccountId">EstimatedManufacturedCostWIPMainAccountId</a>

First included in: InventoryAndWarehouseManagement/CostProductionGroupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EstimatedManufacturedCostWIPMainAccountId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#EstimatedManufacturedCostWIPMainAccountIdDisplayValue name="EstimatedManufacturedCostWIPMainAccountIdDisplayValue">EstimatedManufacturedCostWIPMainAccountIdDisplayValue</a>

First included in: InventoryAndWarehouseManagement/CostProductionGroupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EstimatedManufacturedCostWIPMainAccountIdDisplayValue attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RealizedCostOfMaterialsConsumedMainAccountId name="RealizedCostOfMaterialsConsumedMainAccountId">RealizedCostOfMaterialsConsumedMainAccountId</a>

First included in: InventoryAndWarehouseManagement/CostProductionGroupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RealizedCostOfMaterialsConsumedMainAccountId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RealizedCostOfMaterialsConsumedMainAccountIdDisplayValue name="RealizedCostOfMaterialsConsumedMainAccountIdDisplayValue">RealizedCostOfMaterialsConsumedMainAccountIdDisplayValue</a>

First included in: InventoryAndWarehouseManagement/CostProductionGroupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RealizedCostOfMaterialsConsumedMainAccountIdDisplayValue attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RealizedCostOfMaterialsConsumedWIPMainAccountId name="RealizedCostOfMaterialsConsumedWIPMainAccountId">RealizedCostOfMaterialsConsumedWIPMainAccountId</a>

First included in: InventoryAndWarehouseManagement/CostProductionGroupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RealizedCostOfMaterialsConsumedWIPMainAccountId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RealizedCostOfMaterialsConsumedWIPMainAccountIdDisplayValue name="RealizedCostOfMaterialsConsumedWIPMainAccountIdDisplayValue">RealizedCostOfMaterialsConsumedWIPMainAccountIdDisplayValue</a>

First included in: InventoryAndWarehouseManagement/CostProductionGroupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RealizedCostOfMaterialsConsumedWIPMainAccountIdDisplayValue attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RealizedManufacturedCostMainAccountId name="RealizedManufacturedCostMainAccountId">RealizedManufacturedCostMainAccountId</a>

First included in: InventoryAndWarehouseManagement/CostProductionGroupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RealizedManufacturedCostMainAccountId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RealizedManufacturedCostMainAccountIdDisplayValue name="RealizedManufacturedCostMainAccountIdDisplayValue">RealizedManufacturedCostMainAccountIdDisplayValue</a>

First included in: InventoryAndWarehouseManagement/CostProductionGroupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RealizedManufacturedCostMainAccountIdDisplayValue attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RealizedManufacturedCostWIPMainAccountId name="RealizedManufacturedCostWIPMainAccountId">RealizedManufacturedCostWIPMainAccountId</a>

First included in: InventoryAndWarehouseManagement/CostProductionGroupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RealizedManufacturedCostWIPMainAccountId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RealizedManufacturedCostWIPMainAccountIdDisplayValue name="RealizedManufacturedCostWIPMainAccountIdDisplayValue">RealizedManufacturedCostWIPMainAccountIdDisplayValue</a>

First included in: InventoryAndWarehouseManagement/CostProductionGroupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RealizedManufacturedCostWIPMainAccountIdDisplayValue attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#EstimatedManufacturingCostAbsorbedMainAccountId name="EstimatedManufacturingCostAbsorbedMainAccountId">EstimatedManufacturingCostAbsorbedMainAccountId</a>

First included in: InventoryAndWarehouseManagement/CostProductionGroupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EstimatedManufacturingCostAbsorbedMainAccountId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#EstimatedManufacturingCostAbsorbedMainAccountIdDisplayValue name="EstimatedManufacturingCostAbsorbedMainAccountIdDisplayValue">EstimatedManufacturingCostAbsorbedMainAccountIdDisplayValue</a>

First included in: InventoryAndWarehouseManagement/CostProductionGroupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EstimatedManufacturingCostAbsorbedMainAccountIdDisplayValue attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#EstimatedCostOfManufacturingConsumedMainAccountId name="EstimatedCostOfManufacturingConsumedMainAccountId">EstimatedCostOfManufacturingConsumedMainAccountId</a>

First included in: InventoryAndWarehouseManagement/CostProductionGroupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EstimatedCostOfManufacturingConsumedMainAccountId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#EstimatedCostOfManufacturingConsumedMainAccountIdDisplayValue name="EstimatedCostOfManufacturingConsumedMainAccountIdDisplayValue">EstimatedCostOfManufacturingConsumedMainAccountIdDisplayValue</a>

First included in: InventoryAndWarehouseManagement/CostProductionGroupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EstimatedCostOfManufacturingConsumedMainAccountIdDisplayValue attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RealizedManufacturingCostAbsorbedMainAccountId name="RealizedManufacturingCostAbsorbedMainAccountId">RealizedManufacturingCostAbsorbedMainAccountId</a>

First included in: InventoryAndWarehouseManagement/CostProductionGroupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RealizedManufacturingCostAbsorbedMainAccountId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RealizedManufacturingCostAbsorbedMainAccountIdDisplayValue name="RealizedManufacturingCostAbsorbedMainAccountIdDisplayValue">RealizedManufacturingCostAbsorbedMainAccountIdDisplayValue</a>

First included in: InventoryAndWarehouseManagement/CostProductionGroupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RealizedManufacturingCostAbsorbedMainAccountIdDisplayValue attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RealizedCostOfManufacturingConsumedMainAccountId name="RealizedCostOfManufacturingConsumedMainAccountId">RealizedCostOfManufacturingConsumedMainAccountId</a>

First included in: InventoryAndWarehouseManagement/CostProductionGroupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RealizedCostOfManufacturingConsumedMainAccountId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RealizedCostOfManufacturingConsumedMainAccountIdDisplayValue name="RealizedCostOfManufacturingConsumedMainAccountIdDisplayValue">RealizedCostOfManufacturingConsumedMainAccountIdDisplayValue</a>

First included in: InventoryAndWarehouseManagement/CostProductionGroupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RealizedCostOfManufacturingConsumedMainAccountIdDisplayValue attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WIPServiceReceiptMainAccountId name="WIPServiceReceiptMainAccountId">WIPServiceReceiptMainAccountId</a>

First included in: InventoryAndWarehouseManagement/CostProductionGroupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WIPServiceReceiptMainAccountId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WIPServiceReceiptMainAccountIdDisplayValue name="WIPServiceReceiptMainAccountIdDisplayValue">WIPServiceReceiptMainAccountIdDisplayValue</a>

First included in: InventoryAndWarehouseManagement/CostProductionGroupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WIPServiceReceiptMainAccountIdDisplayValue attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WIPServiceClearingMainAccountId name="WIPServiceClearingMainAccountId">WIPServiceClearingMainAccountId</a>

First included in: InventoryAndWarehouseManagement/CostProductionGroupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WIPServiceClearingMainAccountId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WIPServiceClearingMainAccountIdDisplayValue name="WIPServiceClearingMainAccountIdDisplayValue">WIPServiceClearingMainAccountIdDisplayValue</a>

First included in: InventoryAndWarehouseManagement/CostProductionGroupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WIPServiceClearingMainAccountIdDisplayValue attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RealizedCostOfIndirectCostConsumedMainAccountId name="RealizedCostOfIndirectCostConsumedMainAccountId">RealizedCostOfIndirectCostConsumedMainAccountId</a>

First included in: InventoryAndWarehouseManagement/CostProductionGroupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RealizedCostOfIndirectCostConsumedMainAccountId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RealizedCostOfIndirectCostConsumedMainAccountIdDisplayValue name="RealizedCostOfIndirectCostConsumedMainAccountIdDisplayValue">RealizedCostOfIndirectCostConsumedMainAccountIdDisplayValue</a>

First included in: InventoryAndWarehouseManagement/CostProductionGroupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RealizedCostOfIndirectCostConsumedMainAccountIdDisplayValue attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#EstimatedCostOfIndirectCostConsumedMainAccountId name="EstimatedCostOfIndirectCostConsumedMainAccountId">EstimatedCostOfIndirectCostConsumedMainAccountId</a>

First included in: InventoryAndWarehouseManagement/CostProductionGroupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EstimatedCostOfIndirectCostConsumedMainAccountId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#EstimatedCostOfIndirectCostConsumedMainAccountIdDisplayValue name="EstimatedCostOfIndirectCostConsumedMainAccountIdDisplayValue">EstimatedCostOfIndirectCostConsumedMainAccountIdDisplayValue</a>

First included in: InventoryAndWarehouseManagement/CostProductionGroupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EstimatedCostOfIndirectCostConsumedMainAccountIdDisplayValue attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_EstimatedCostOfIndirectCostConsumedMainAccountIdCombinationRelationshipId name="Relationship_EstimatedCostOfIndirectCostConsumedMainAccountIdCombinationRelationshipId">Relationship_EstimatedCostOfIndirectCostConsumedMainAccountIdCombinationRelationshipId</a>

First included in: InventoryAndWarehouseManagement/CostProductionGroupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_EstimatedCostOfIndirectCostConsumedMainAccountIdCombinationRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_RealizedCostOfIndirectCostConsumedMainAccountIdCombinationRelationshipId name="Relationship_RealizedCostOfIndirectCostConsumedMainAccountIdCombinationRelationshipId">Relationship_RealizedCostOfIndirectCostConsumedMainAccountIdCombinationRelationshipId</a>

First included in: InventoryAndWarehouseManagement/CostProductionGroupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_RealizedCostOfIndirectCostConsumedMainAccountIdCombinationRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_RealizedCostOfMaterialsConsumedMainAccountIdCombinationRelationshipId name="Relationship_RealizedCostOfMaterialsConsumedMainAccountIdCombinationRelationshipId">Relationship_RealizedCostOfMaterialsConsumedMainAccountIdCombinationRelationshipId</a>

First included in: InventoryAndWarehouseManagement/CostProductionGroupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_RealizedCostOfMaterialsConsumedMainAccountIdCombinationRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_RealizedCostOfMaterialsConsumedWIPMainAccountIdCombinationRelationshipId name="Relationship_RealizedCostOfMaterialsConsumedWIPMainAccountIdCombinationRelationshipId">Relationship_RealizedCostOfMaterialsConsumedWIPMainAccountIdCombinationRelationshipId</a>

First included in: InventoryAndWarehouseManagement/CostProductionGroupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_RealizedCostOfMaterialsConsumedWIPMainAccountIdCombinationRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_WIPServiceClearingMainAccountIdCombinationRelationshipId name="Relationship_WIPServiceClearingMainAccountIdCombinationRelationshipId">Relationship_WIPServiceClearingMainAccountIdCombinationRelationshipId</a>

First included in: InventoryAndWarehouseManagement/CostProductionGroupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_WIPServiceClearingMainAccountIdCombinationRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_WIPServiceReceiptMainAccountIdCombinationRelationshipId name="Relationship_WIPServiceReceiptMainAccountIdCombinationRelationshipId">Relationship_WIPServiceReceiptMainAccountIdCombinationRelationshipId</a>

First included in: InventoryAndWarehouseManagement/CostProductionGroupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_WIPServiceReceiptMainAccountIdCombinationRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_EstimatedCostOfMaterialsConsumedMainAccountIdCombinationRelationshipId name="Relationship_EstimatedCostOfMaterialsConsumedMainAccountIdCombinationRelationshipId">Relationship_EstimatedCostOfMaterialsConsumedMainAccountIdCombinationRelationshipId</a>

First included in: InventoryAndWarehouseManagement/CostProductionGroupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_EstimatedCostOfMaterialsConsumedMainAccountIdCombinationRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_EstimatedCostOfMaterialsConsumedWIPMainAccountIdCombinationRelationshipId name="Relationship_EstimatedCostOfMaterialsConsumedWIPMainAccountIdCombinationRelationshipId">Relationship_EstimatedCostOfMaterialsConsumedWIPMainAccountIdCombinationRelationshipId</a>

First included in: InventoryAndWarehouseManagement/CostProductionGroupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_EstimatedCostOfMaterialsConsumedWIPMainAccountIdCombinationRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_RealizedManufacturedCostMainAccountIdCombinationRelationshipId name="Relationship_RealizedManufacturedCostMainAccountIdCombinationRelationshipId">Relationship_RealizedManufacturedCostMainAccountIdCombinationRelationshipId</a>

First included in: InventoryAndWarehouseManagement/CostProductionGroupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_RealizedManufacturedCostMainAccountIdCombinationRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_RealizedManufacturedCostWIPMainAccountIdCombinationRelationshipId name="Relationship_RealizedManufacturedCostWIPMainAccountIdCombinationRelationshipId">Relationship_RealizedManufacturedCostWIPMainAccountIdCombinationRelationshipId</a>

First included in: InventoryAndWarehouseManagement/CostProductionGroupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_RealizedManufacturedCostWIPMainAccountIdCombinationRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_EstimatedManufacturedCostMainAccountIdCombinationRelationshipId name="Relationship_EstimatedManufacturedCostMainAccountIdCombinationRelationshipId">Relationship_EstimatedManufacturedCostMainAccountIdCombinationRelationshipId</a>

First included in: InventoryAndWarehouseManagement/CostProductionGroupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_EstimatedManufacturedCostMainAccountIdCombinationRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_EstimatedManufacturedCostWIPMainAccountIdCombinationRelationshipId name="Relationship_EstimatedManufacturedCostWIPMainAccountIdCombinationRelationshipId">Relationship_EstimatedManufacturedCostWIPMainAccountIdCombinationRelationshipId</a>

First included in: InventoryAndWarehouseManagement/CostProductionGroupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_EstimatedManufacturedCostWIPMainAccountIdCombinationRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_RealizedManufacturingCostAbsorbedMainAccountIdCombinationRelationshipId name="Relationship_RealizedManufacturingCostAbsorbedMainAccountIdCombinationRelationshipId">Relationship_RealizedManufacturingCostAbsorbedMainAccountIdCombinationRelationshipId</a>

First included in: InventoryAndWarehouseManagement/CostProductionGroupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_RealizedManufacturingCostAbsorbedMainAccountIdCombinationRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_RealizedCostOfManufacturingConsumedMainAccountIdCombinationRelationshipId name="Relationship_RealizedCostOfManufacturingConsumedMainAccountIdCombinationRelationshipId">Relationship_RealizedCostOfManufacturingConsumedMainAccountIdCombinationRelationshipId</a>

First included in: InventoryAndWarehouseManagement/CostProductionGroupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_RealizedCostOfManufacturingConsumedMainAccountIdCombinationRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_EstimatedManufacturingCostAbsorbedMainAccountIdCombinationRelationshipId name="Relationship_EstimatedManufacturingCostAbsorbedMainAccountIdCombinationRelationshipId">Relationship_EstimatedManufacturingCostAbsorbedMainAccountIdCombinationRelationshipId</a>

First included in: InventoryAndWarehouseManagement/CostProductionGroupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_EstimatedManufacturingCostAbsorbedMainAccountIdCombinationRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_EstimatedCostOfManufacturingConsumedMainAccountIdCombinationRelationshipId name="Relationship_EstimatedCostOfManufacturingConsumedMainAccountIdCombinationRelationshipId">Relationship_EstimatedCostOfManufacturingConsumedMainAccountIdCombinationRelationshipId</a>

First included in: InventoryAndWarehouseManagement/CostProductionGroupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_EstimatedCostOfManufacturingConsumedMainAccountIdCombinationRelationshipId attribute are listed below.</summary>

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

### <a href=#BackingTable_ProdGroupRelationshipId name="BackingTable_ProdGroupRelationshipId">BackingTable_ProdGroupRelationshipId</a>

First included in: InventoryAndWarehouseManagement/CostProductionGroupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_ProdGroupRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/SupplyChain/ProductionControl/Group/ProdGroup.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/ProductionControl/Group/ProdGroup.cdm.json/ProdGroup</a></td><td><a href="../../../Tables/SupplyChain/ProductionControl/Group/ProdGroup.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PrimaryCompanyContextRelationshipId name="Relationship_PrimaryCompanyContextRelationshipId">Relationship_PrimaryCompanyContextRelationshipId</a>

First included in: InventoryAndWarehouseManagement/CostProductionGroupEntity (this entity)  

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
