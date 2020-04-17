---
title: WHSCycleCountingThresholdEntity - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/17/2020
ms.author: nebanfic
---

# WHSCycleCountingThresholdEntity

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/erp/Entities/SupplyChain/WMS/WHSCycleCountingThresholdEntity.cdm.json" target="_blank">GitHub</a>.  

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
|[ThresholdId](#ThresholdId)||<a href="WHSCycleCountingThresholdEntity.md" target="_blank">WMS/WHSCycleCountingThresholdEntity</a>|
|[ThresholdType](#ThresholdType)||<a href="WHSCycleCountingThresholdEntity.md" target="_blank">WMS/WHSCycleCountingThresholdEntity</a>|
|[DaysAllowedBetweenCycleCounts](#DaysAllowedBetweenCycleCounts)||<a href="WHSCycleCountingThresholdEntity.md" target="_blank">WMS/WHSCycleCountingThresholdEntity</a>|
|[ThresholdDescription](#ThresholdDescription)||<a href="WHSCycleCountingThresholdEntity.md" target="_blank">WMS/WHSCycleCountingThresholdEntity</a>|
|[WillAssignCycleCountingWorkImmediately](#WillAssignCycleCountingWorkImmediately)||<a href="WHSCycleCountingThresholdEntity.md" target="_blank">WMS/WHSCycleCountingThresholdEntity</a>|
|[ProductQuery](#ProductQuery)||<a href="WHSCycleCountingThresholdEntity.md" target="_blank">WMS/WHSCycleCountingThresholdEntity</a>|
|[LocationQuery](#LocationQuery)||<a href="WHSCycleCountingThresholdEntity.md" target="_blank">WMS/WHSCycleCountingThresholdEntity</a>|
|[ThresholdInventoryCapacityPercentage](#ThresholdInventoryCapacityPercentage)||<a href="WHSCycleCountingThresholdEntity.md" target="_blank">WMS/WHSCycleCountingThresholdEntity</a>|
|[ThresholdInventoryQuantity](#ThresholdInventoryQuantity)||<a href="WHSCycleCountingThresholdEntity.md" target="_blank">WMS/WHSCycleCountingThresholdEntity</a>|
|[ThresholdInventoryQuantityUnitSymbol](#ThresholdInventoryQuantityUnitSymbol)||<a href="WHSCycleCountingThresholdEntity.md" target="_blank">WMS/WHSCycleCountingThresholdEntity</a>|
|[WarehouseWorkPoolId](#WarehouseWorkPoolId)||<a href="WHSCycleCountingThresholdEntity.md" target="_blank">WMS/WHSCycleCountingThresholdEntity</a>|
|[Relationship_ThresholdInventoryQuantityUnitOfMeasureRelationshipId](#Relationship_ThresholdInventoryQuantityUnitOfMeasureRelationshipId)||<a href="WHSCycleCountingThresholdEntity.md" target="_blank">WMS/WHSCycleCountingThresholdEntity</a>|
|[Relationship_WarehouseWorkPoolRelationshipId](#Relationship_WarehouseWorkPoolRelationshipId)||<a href="WHSCycleCountingThresholdEntity.md" target="_blank">WMS/WHSCycleCountingThresholdEntity</a>|
|[BackingTable_WHSCycleCountThresholdRelationshipId](#BackingTable_WHSCycleCountThresholdRelationshipId)||<a href="WHSCycleCountingThresholdEntity.md" target="_blank">WMS/WHSCycleCountingThresholdEntity</a>|
|[Relationship_PrimaryCompanyContextRelationshipId](#Relationship_PrimaryCompanyContextRelationshipId)||<a href="WHSCycleCountingThresholdEntity.md" target="_blank">WMS/WHSCycleCountingThresholdEntity</a>|

### <a href=#ThresholdId name="ThresholdId">ThresholdId</a>

First included in: WMS/WHSCycleCountingThresholdEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ThresholdId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ThresholdType name="ThresholdType">ThresholdType</a>

First included in: WMS/WHSCycleCountingThresholdEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ThresholdType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DaysAllowedBetweenCycleCounts name="DaysAllowedBetweenCycleCounts">DaysAllowedBetweenCycleCounts</a>

First included in: WMS/WHSCycleCountingThresholdEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DaysAllowedBetweenCycleCounts attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ThresholdDescription name="ThresholdDescription">ThresholdDescription</a>

First included in: WMS/WHSCycleCountingThresholdEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ThresholdDescription attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WillAssignCycleCountingWorkImmediately name="WillAssignCycleCountingWorkImmediately">WillAssignCycleCountingWorkImmediately</a>

First included in: WMS/WHSCycleCountingThresholdEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WillAssignCycleCountingWorkImmediately attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProductQuery name="ProductQuery">ProductQuery</a>

First included in: WMS/WHSCycleCountingThresholdEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProductQuery attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LocationQuery name="LocationQuery">LocationQuery</a>

First included in: WMS/WHSCycleCountingThresholdEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LocationQuery attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ThresholdInventoryCapacityPercentage name="ThresholdInventoryCapacityPercentage">ThresholdInventoryCapacityPercentage</a>

First included in: WMS/WHSCycleCountingThresholdEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ThresholdInventoryCapacityPercentage attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ThresholdInventoryQuantity name="ThresholdInventoryQuantity">ThresholdInventoryQuantity</a>

First included in: WMS/WHSCycleCountingThresholdEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ThresholdInventoryQuantity attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ThresholdInventoryQuantityUnitSymbol name="ThresholdInventoryQuantityUnitSymbol">ThresholdInventoryQuantityUnitSymbol</a>

First included in: WMS/WHSCycleCountingThresholdEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ThresholdInventoryQuantityUnitSymbol attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WarehouseWorkPoolId name="WarehouseWorkPoolId">WarehouseWorkPoolId</a>

First included in: WMS/WHSCycleCountingThresholdEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WarehouseWorkPoolId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_ThresholdInventoryQuantityUnitOfMeasureRelationshipId name="Relationship_ThresholdInventoryQuantityUnitOfMeasureRelationshipId">Relationship_ThresholdInventoryQuantityUnitOfMeasureRelationshipId</a>

First included in: WMS/WHSCycleCountingThresholdEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_ThresholdInventoryQuantityUnitOfMeasureRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_WarehouseWorkPoolRelationshipId name="Relationship_WarehouseWorkPoolRelationshipId">Relationship_WarehouseWorkPoolRelationshipId</a>

First included in: WMS/WHSCycleCountingThresholdEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_WarehouseWorkPoolRelationshipId attribute are listed below.</summary>

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

### <a href=#BackingTable_WHSCycleCountThresholdRelationshipId name="BackingTable_WHSCycleCountThresholdRelationshipId">BackingTable_WHSCycleCountThresholdRelationshipId</a>

First included in: WMS/WHSCycleCountingThresholdEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_WHSCycleCountThresholdRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/SupplyChain/Inventory/Group/WHSCycleCountThreshold.md" target="_blank">/core/erp/Tables/SupplyChain/Inventory/Group/WHSCycleCountThreshold.cdm.json/WHSCycleCountThreshold</a></td><td><a href="../../../Tables/SupplyChain/Inventory/Group/WHSCycleCountThreshold.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PrimaryCompanyContextRelationshipId name="Relationship_PrimaryCompanyContextRelationshipId">Relationship_PrimaryCompanyContextRelationshipId</a>

First included in: WMS/WHSCycleCountingThresholdEntity (this entity)  

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
