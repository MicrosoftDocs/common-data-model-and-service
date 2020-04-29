---
title: CostingVersionEntity - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/29/2020
ms.author: nebanfic
---

# Costing versions

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/SupplyChain/InventoryAndWarehouseManagement/CostingVersionEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Costing versions</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[AreCostPricesAllowed](#AreCostPricesAllowed)||<a href="CostingVersionEntity.md" target="_blank">InventoryAndWarehouseManagement/CostingVersionEntity</a>|
|[ArePurchasePricesAllowed](#ArePurchasePricesAllowed)||<a href="CostingVersionEntity.md" target="_blank">InventoryAndWarehouseManagement/CostingVersionEntity</a>|
|[AreSalesPricesAllowed](#AreSalesPricesAllowed)||<a href="CostingVersionEntity.md" target="_blank">InventoryAndWarehouseManagement/CostingVersionEntity</a>|
|[IsActivationBlocked](#IsActivationBlocked)||<a href="CostingVersionEntity.md" target="_blank">InventoryAndWarehouseManagement/CostingVersionEntity</a>|
|[IsVersionBlocked](#IsVersionBlocked)||<a href="CostingVersionEntity.md" target="_blank">InventoryAndWarehouseManagement/CostingVersionEntity</a>|
|[ExplosionMode](#ExplosionMode)||<a href="CostingVersionEntity.md" target="_blank">InventoryAndWarehouseManagement/CostingVersionEntity</a>|
|[FallbackPrinciple](#FallbackPrinciple)||<a href="CostingVersionEntity.md" target="_blank">InventoryAndWarehouseManagement/CostingVersionEntity</a>|
|[RestrictCalculation](#RestrictCalculation)||<a href="CostingVersionEntity.md" target="_blank">InventoryAndWarehouseManagement/CostingVersionEntity</a>|
|[IsProductionProcurementModePriceCalculationAllowed](#IsProductionProcurementModePriceCalculationAllowed)||<a href="CostingVersionEntity.md" target="_blank">InventoryAndWarehouseManagement/CostingVersionEntity</a>|
|[CostPriceModel](#CostPriceModel)||<a href="CostingVersionEntity.md" target="_blank">InventoryAndWarehouseManagement/CostingVersionEntity</a>|
|[ProfitSetting](#ProfitSetting)||<a href="CostingVersionEntity.md" target="_blank">InventoryAndWarehouseManagement/CostingVersionEntity</a>|
|[FallbackCostingVersionId](#FallbackCostingVersionId)||<a href="CostingVersionEntity.md" target="_blank">InventoryAndWarehouseManagement/CostingVersionEntity</a>|
|[CostingType](#CostingType)||<a href="CostingVersionEntity.md" target="_blank">InventoryAndWarehouseManagement/CostingVersionEntity</a>|
|[DefaultFromDate](#DefaultFromDate)||<a href="CostingVersionEntity.md" target="_blank">InventoryAndWarehouseManagement/CostingVersionEntity</a>|
|[RestrictingPriceSiteId](#RestrictingPriceSiteId)||<a href="CostingVersionEntity.md" target="_blank">InventoryAndWarehouseManagement/CostingVersionEntity</a>|
|[LastActivationDate](#LastActivationDate)||<a href="CostingVersionEntity.md" target="_blank">InventoryAndWarehouseManagement/CostingVersionEntity</a>|
|[LastUpdateDate](#LastUpdateDate)||<a href="CostingVersionEntity.md" target="_blank">InventoryAndWarehouseManagement/CostingVersionEntity</a>|
|[VersionName](#VersionName)||<a href="CostingVersionEntity.md" target="_blank">InventoryAndWarehouseManagement/CostingVersionEntity</a>|
|[IsUnitPriceIncludingCharge](#IsUnitPriceIncludingCharge)||<a href="CostingVersionEntity.md" target="_blank">InventoryAndWarehouseManagement/CostingVersionEntity</a>|
|[ArePriceCalculationsUsingPurchaseProcurementModeAllowed](#ArePriceCalculationsUsingPurchaseProcurementModeAllowed)||<a href="CostingVersionEntity.md" target="_blank">InventoryAndWarehouseManagement/CostingVersionEntity</a>|
|[PurchasePriceModel](#PurchasePriceModel)||<a href="CostingVersionEntity.md" target="_blank">InventoryAndWarehouseManagement/CostingVersionEntity</a>|
|[RecordingRestriction](#RecordingRestriction)||<a href="CostingVersionEntity.md" target="_blank">InventoryAndWarehouseManagement/CostingVersionEntity</a>|
|[RoundOffCalculation](#RoundOffCalculation)||<a href="CostingVersionEntity.md" target="_blank">InventoryAndWarehouseManagement/CostingVersionEntity</a>|
|[VersionId](#VersionId)||<a href="CostingVersionEntity.md" target="_blank">InventoryAndWarehouseManagement/CostingVersionEntity</a>|
|[BackingTable_CostingVersionRelationshipId](#BackingTable_CostingVersionRelationshipId)||<a href="CostingVersionEntity.md" target="_blank">InventoryAndWarehouseManagement/CostingVersionEntity</a>|
|[Relationship_PrimaryCompanyContextRelationshipId](#Relationship_PrimaryCompanyContextRelationshipId)||<a href="CostingVersionEntity.md" target="_blank">InventoryAndWarehouseManagement/CostingVersionEntity</a>|

### <a href=#AreCostPricesAllowed name="AreCostPricesAllowed">AreCostPricesAllowed</a>

First included in: InventoryAndWarehouseManagement/CostingVersionEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AreCostPricesAllowed attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ArePurchasePricesAllowed name="ArePurchasePricesAllowed">ArePurchasePricesAllowed</a>

First included in: InventoryAndWarehouseManagement/CostingVersionEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ArePurchasePricesAllowed attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AreSalesPricesAllowed name="AreSalesPricesAllowed">AreSalesPricesAllowed</a>

First included in: InventoryAndWarehouseManagement/CostingVersionEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AreSalesPricesAllowed attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsActivationBlocked name="IsActivationBlocked">IsActivationBlocked</a>

First included in: InventoryAndWarehouseManagement/CostingVersionEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsActivationBlocked attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsVersionBlocked name="IsVersionBlocked">IsVersionBlocked</a>

First included in: InventoryAndWarehouseManagement/CostingVersionEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsVersionBlocked attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ExplosionMode name="ExplosionMode">ExplosionMode</a>

First included in: InventoryAndWarehouseManagement/CostingVersionEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ExplosionMode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FallbackPrinciple name="FallbackPrinciple">FallbackPrinciple</a>

First included in: InventoryAndWarehouseManagement/CostingVersionEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FallbackPrinciple attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RestrictCalculation name="RestrictCalculation">RestrictCalculation</a>

First included in: InventoryAndWarehouseManagement/CostingVersionEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RestrictCalculation attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsProductionProcurementModePriceCalculationAllowed name="IsProductionProcurementModePriceCalculationAllowed">IsProductionProcurementModePriceCalculationAllowed</a>

First included in: InventoryAndWarehouseManagement/CostingVersionEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsProductionProcurementModePriceCalculationAllowed attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CostPriceModel name="CostPriceModel">CostPriceModel</a>

First included in: InventoryAndWarehouseManagement/CostingVersionEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CostPriceModel attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProfitSetting name="ProfitSetting">ProfitSetting</a>

First included in: InventoryAndWarehouseManagement/CostingVersionEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProfitSetting attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FallbackCostingVersionId name="FallbackCostingVersionId">FallbackCostingVersionId</a>

First included in: InventoryAndWarehouseManagement/CostingVersionEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FallbackCostingVersionId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CostingType name="CostingType">CostingType</a>

First included in: InventoryAndWarehouseManagement/CostingVersionEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CostingType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DefaultFromDate name="DefaultFromDate">DefaultFromDate</a>

First included in: InventoryAndWarehouseManagement/CostingVersionEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultFromDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RestrictingPriceSiteId name="RestrictingPriceSiteId">RestrictingPriceSiteId</a>

First included in: InventoryAndWarehouseManagement/CostingVersionEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RestrictingPriceSiteId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LastActivationDate name="LastActivationDate">LastActivationDate</a>

First included in: InventoryAndWarehouseManagement/CostingVersionEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LastActivationDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LastUpdateDate name="LastUpdateDate">LastUpdateDate</a>

First included in: InventoryAndWarehouseManagement/CostingVersionEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LastUpdateDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#VersionName name="VersionName">VersionName</a>

First included in: InventoryAndWarehouseManagement/CostingVersionEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VersionName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsUnitPriceIncludingCharge name="IsUnitPriceIncludingCharge">IsUnitPriceIncludingCharge</a>

First included in: InventoryAndWarehouseManagement/CostingVersionEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsUnitPriceIncludingCharge attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ArePriceCalculationsUsingPurchaseProcurementModeAllowed name="ArePriceCalculationsUsingPurchaseProcurementModeAllowed">ArePriceCalculationsUsingPurchaseProcurementModeAllowed</a>

First included in: InventoryAndWarehouseManagement/CostingVersionEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ArePriceCalculationsUsingPurchaseProcurementModeAllowed attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PurchasePriceModel name="PurchasePriceModel">PurchasePriceModel</a>

First included in: InventoryAndWarehouseManagement/CostingVersionEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PurchasePriceModel attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RecordingRestriction name="RecordingRestriction">RecordingRestriction</a>

First included in: InventoryAndWarehouseManagement/CostingVersionEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecordingRestriction attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RoundOffCalculation name="RoundOffCalculation">RoundOffCalculation</a>

First included in: InventoryAndWarehouseManagement/CostingVersionEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RoundOffCalculation attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#VersionId name="VersionId">VersionId</a>

First included in: InventoryAndWarehouseManagement/CostingVersionEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VersionId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BackingTable_CostingVersionRelationshipId name="BackingTable_CostingVersionRelationshipId">BackingTable_CostingVersionRelationshipId</a>

First included in: InventoryAndWarehouseManagement/CostingVersionEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_CostingVersionRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/SupplyChain/Inventory/Group/CostingVersion.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/Inventory/Group/CostingVersion.cdm.json/CostingVersion</a></td><td><a href="../../../Tables/SupplyChain/Inventory/Group/CostingVersion.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PrimaryCompanyContextRelationshipId name="Relationship_PrimaryCompanyContextRelationshipId">Relationship_PrimaryCompanyContextRelationshipId</a>

First included in: InventoryAndWarehouseManagement/CostingVersionEntity (this entity)  

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
