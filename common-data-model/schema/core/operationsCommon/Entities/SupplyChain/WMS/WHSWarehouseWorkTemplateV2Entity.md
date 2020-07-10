---
title: WHSWarehouseWorkTemplateV2Entity in WMS - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 7/10/2020
ms.author: nebanfic
---

# Warehouse work template V2 in WMS(WHSWarehouseWorkTemplateV2Entity)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/SupplyChain/WMS/WHSWarehouseWorkTemplateV2Entity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Warehouse work template V2</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[WorkOrderType](#WorkOrderType)||<a href="WHSWarehouseWorkTemplateV2Entity.md" target="_blank">WMS/WHSWarehouseWorkTemplateV2Entity</a>|
|[TemplateSequenceNumber](#TemplateSequenceNumber)||<a href="WHSWarehouseWorkTemplateV2Entity.md" target="_blank">WMS/WHSWarehouseWorkTemplateV2Entity</a>|
|[TemplateId](#TemplateId)||<a href="WHSWarehouseWorkTemplateV2Entity.md" target="_blank">WMS/WHSWarehouseWorkTemplateV2Entity</a>|
|[TemplateDescription](#TemplateDescription)||<a href="WHSWarehouseWorkTemplateV2Entity.md" target="_blank">WMS/WHSWarehouseWorkTemplateV2Entity</a>|
|[IsAutomaticProcessingAllowed](#IsAutomaticProcessingAllowed)||<a href="WHSWarehouseWorkTemplateV2Entity.md" target="_blank">WMS/WHSWarehouseWorkTemplateV2Entity</a>|
|[WarehouseWorkPoolId](#WarehouseWorkPoolId)||<a href="WHSWarehouseWorkTemplateV2Entity.md" target="_blank">WMS/WHSWarehouseWorkTemplateV2Entity</a>|
|[ItemBatchAllocationStrategy](#ItemBatchAllocationStrategy)||<a href="WHSWarehouseWorkTemplateV2Entity.md" target="_blank">WMS/WHSWarehouseWorkTemplateV2Entity</a>|
|[DefaultWarehouseWorkOrderPriority](#DefaultWarehouseWorkOrderPriority)||<a href="WHSWarehouseWorkTemplateV2Entity.md" target="_blank">WMS/WHSWarehouseWorkTemplateV2Entity</a>|
|[WarehouseWorkHeaderMaximumEstimatedPickTime](#WarehouseWorkHeaderMaximumEstimatedPickTime)||<a href="WHSWarehouseWorkTemplateV2Entity.md" target="_blank">WMS/WHSWarehouseWorkTemplateV2Entity</a>|
|[MaximumWarehouseWorkOrderPickLines](#MaximumWarehouseWorkOrderPickLines)||<a href="WHSWarehouseWorkTemplateV2Entity.md" target="_blank">WMS/WHSWarehouseWorkTemplateV2Entity</a>|
|[MaximumWarehouseWorkOrderQuantity](#MaximumWarehouseWorkOrderQuantity)||<a href="WHSWarehouseWorkTemplateV2Entity.md" target="_blank">WMS/WHSWarehouseWorkTemplateV2Entity</a>|
|[MaximumWarehouseWorkOrderVolume](#MaximumWarehouseWorkOrderVolume)||<a href="WHSWarehouseWorkTemplateV2Entity.md" target="_blank">WMS/WHSWarehouseWorkTemplateV2Entity</a>|
|[MaximumWarehouseWorkOrderWeight](#MaximumWarehouseWorkOrderWeight)||<a href="WHSWarehouseWorkTemplateV2Entity.md" target="_blank">WMS/WHSWarehouseWorkTemplateV2Entity</a>|
|[MaximumWarehouseWorkOrderLineVolume](#MaximumWarehouseWorkOrderLineVolume)||<a href="WHSWarehouseWorkTemplateV2Entity.md" target="_blank">WMS/WHSWarehouseWorkTemplateV2Entity</a>|
|[MaximumWarehouseWorkOrderLineWeight](#MaximumWarehouseWorkOrderLineWeight)||<a href="WHSWarehouseWorkTemplateV2Entity.md" target="_blank">WMS/WHSWarehouseWorkTemplateV2Entity</a>|
|[MaximumWarehouseWorkOrderLineQuantity](#MaximumWarehouseWorkOrderLineQuantity)||<a href="WHSWarehouseWorkTemplateV2Entity.md" target="_blank">WMS/WHSWarehouseWorkTemplateV2Entity</a>|
|[MaximumWarehouseWorkOrderLineQuantityUnitSymbol](#MaximumWarehouseWorkOrderLineQuantityUnitSymbol)||<a href="WHSWarehouseWorkTemplateV2Entity.md" target="_blank">WMS/WHSWarehouseWorkTemplateV2Entity</a>|
|[IsPackingQuantityUsedAsMaximumQuantity](#IsPackingQuantityUsedAsMaximumQuantity)||<a href="WHSWarehouseWorkTemplateV2Entity.md" target="_blank">WMS/WHSWarehouseWorkTemplateV2Entity</a>|
|[TemplateQuery](#TemplateQuery)||<a href="WHSWarehouseWorkTemplateV2Entity.md" target="_blank">WMS/WHSWarehouseWorkTemplateV2Entity</a>|
|[ReplenishmentDependentWorkBlockingPolicy](#ReplenishmentDependentWorkBlockingPolicy)||<a href="WHSWarehouseWorkTemplateV2Entity.md" target="_blank">WMS/WHSWarehouseWorkTemplateV2Entity</a>|
|[LicensePlateLabelBuildConfigurationId](#LicensePlateLabelBuildConfigurationId)||<a href="WHSWarehouseWorkTemplateV2Entity.md" target="_blank">WMS/WHSWarehouseWorkTemplateV2Entity</a>|
|[LicensePlateLabelBuildConfiguration](#LicensePlateLabelBuildConfiguration)||<a href="WHSWarehouseWorkTemplateV2Entity.md" target="_blank">WMS/WHSWarehouseWorkTemplateV2Entity</a>|
|[Relationship_MaximumWarehouseWorkOrderLineQuantityUnitOfMeasureRelationshipId](#Relationship_MaximumWarehouseWorkOrderLineQuantityUnitOfMeasureRelationshipId)||<a href="WHSWarehouseWorkTemplateV2Entity.md" target="_blank">WMS/WHSWarehouseWorkTemplateV2Entity</a>|
|[Relationship_WarehouseWorkPoolRelationshipId](#Relationship_WarehouseWorkPoolRelationshipId)||<a href="WHSWarehouseWorkTemplateV2Entity.md" target="_blank">WMS/WHSWarehouseWorkTemplateV2Entity</a>|
|[BackingTable_WHSWorkTemplateTableRelationshipId](#BackingTable_WHSWorkTemplateTableRelationshipId)||<a href="WHSWarehouseWorkTemplateV2Entity.md" target="_blank">WMS/WHSWarehouseWorkTemplateV2Entity</a>|
|[Relationship_PrimaryCompanyContextRelationshipId](#Relationship_PrimaryCompanyContextRelationshipId)||<a href="WHSWarehouseWorkTemplateV2Entity.md" target="_blank">WMS/WHSWarehouseWorkTemplateV2Entity</a>|

### <a href=#WorkOrderType name="WorkOrderType">WorkOrderType</a>

First included in: WMS/WHSWarehouseWorkTemplateV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WorkOrderType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TemplateSequenceNumber name="TemplateSequenceNumber">TemplateSequenceNumber</a>

First included in: WMS/WHSWarehouseWorkTemplateV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TemplateSequenceNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TemplateId name="TemplateId">TemplateId</a>

First included in: WMS/WHSWarehouseWorkTemplateV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TemplateId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TemplateDescription name="TemplateDescription">TemplateDescription</a>

First included in: WMS/WHSWarehouseWorkTemplateV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TemplateDescription attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsAutomaticProcessingAllowed name="IsAutomaticProcessingAllowed">IsAutomaticProcessingAllowed</a>

First included in: WMS/WHSWarehouseWorkTemplateV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsAutomaticProcessingAllowed attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WarehouseWorkPoolId name="WarehouseWorkPoolId">WarehouseWorkPoolId</a>

First included in: WMS/WHSWarehouseWorkTemplateV2Entity (this entity)  

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

### <a href=#ItemBatchAllocationStrategy name="ItemBatchAllocationStrategy">ItemBatchAllocationStrategy</a>

First included in: WMS/WHSWarehouseWorkTemplateV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ItemBatchAllocationStrategy attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DefaultWarehouseWorkOrderPriority name="DefaultWarehouseWorkOrderPriority">DefaultWarehouseWorkOrderPriority</a>

First included in: WMS/WHSWarehouseWorkTemplateV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultWarehouseWorkOrderPriority attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WarehouseWorkHeaderMaximumEstimatedPickTime name="WarehouseWorkHeaderMaximumEstimatedPickTime">WarehouseWorkHeaderMaximumEstimatedPickTime</a>

First included in: WMS/WHSWarehouseWorkTemplateV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WarehouseWorkHeaderMaximumEstimatedPickTime attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MaximumWarehouseWorkOrderPickLines name="MaximumWarehouseWorkOrderPickLines">MaximumWarehouseWorkOrderPickLines</a>

First included in: WMS/WHSWarehouseWorkTemplateV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MaximumWarehouseWorkOrderPickLines attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MaximumWarehouseWorkOrderQuantity name="MaximumWarehouseWorkOrderQuantity">MaximumWarehouseWorkOrderQuantity</a>

First included in: WMS/WHSWarehouseWorkTemplateV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MaximumWarehouseWorkOrderQuantity attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MaximumWarehouseWorkOrderVolume name="MaximumWarehouseWorkOrderVolume">MaximumWarehouseWorkOrderVolume</a>

First included in: WMS/WHSWarehouseWorkTemplateV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MaximumWarehouseWorkOrderVolume attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MaximumWarehouseWorkOrderWeight name="MaximumWarehouseWorkOrderWeight">MaximumWarehouseWorkOrderWeight</a>

First included in: WMS/WHSWarehouseWorkTemplateV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MaximumWarehouseWorkOrderWeight attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MaximumWarehouseWorkOrderLineVolume name="MaximumWarehouseWorkOrderLineVolume">MaximumWarehouseWorkOrderLineVolume</a>

First included in: WMS/WHSWarehouseWorkTemplateV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MaximumWarehouseWorkOrderLineVolume attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MaximumWarehouseWorkOrderLineWeight name="MaximumWarehouseWorkOrderLineWeight">MaximumWarehouseWorkOrderLineWeight</a>

First included in: WMS/WHSWarehouseWorkTemplateV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MaximumWarehouseWorkOrderLineWeight attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MaximumWarehouseWorkOrderLineQuantity name="MaximumWarehouseWorkOrderLineQuantity">MaximumWarehouseWorkOrderLineQuantity</a>

First included in: WMS/WHSWarehouseWorkTemplateV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MaximumWarehouseWorkOrderLineQuantity attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MaximumWarehouseWorkOrderLineQuantityUnitSymbol name="MaximumWarehouseWorkOrderLineQuantityUnitSymbol">MaximumWarehouseWorkOrderLineQuantityUnitSymbol</a>

First included in: WMS/WHSWarehouseWorkTemplateV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MaximumWarehouseWorkOrderLineQuantityUnitSymbol attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsPackingQuantityUsedAsMaximumQuantity name="IsPackingQuantityUsedAsMaximumQuantity">IsPackingQuantityUsedAsMaximumQuantity</a>

First included in: WMS/WHSWarehouseWorkTemplateV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsPackingQuantityUsedAsMaximumQuantity attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TemplateQuery name="TemplateQuery">TemplateQuery</a>

First included in: WMS/WHSWarehouseWorkTemplateV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TemplateQuery attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ReplenishmentDependentWorkBlockingPolicy name="ReplenishmentDependentWorkBlockingPolicy">ReplenishmentDependentWorkBlockingPolicy</a>

First included in: WMS/WHSWarehouseWorkTemplateV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReplenishmentDependentWorkBlockingPolicy attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LicensePlateLabelBuildConfigurationId name="LicensePlateLabelBuildConfigurationId">LicensePlateLabelBuildConfigurationId</a>

First included in: WMS/WHSWarehouseWorkTemplateV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LicensePlateLabelBuildConfigurationId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LicensePlateLabelBuildConfiguration name="LicensePlateLabelBuildConfiguration">LicensePlateLabelBuildConfiguration</a>

First included in: WMS/WHSWarehouseWorkTemplateV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LicensePlateLabelBuildConfiguration attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_MaximumWarehouseWorkOrderLineQuantityUnitOfMeasureRelationshipId name="Relationship_MaximumWarehouseWorkOrderLineQuantityUnitOfMeasureRelationshipId">Relationship_MaximumWarehouseWorkOrderLineQuantityUnitOfMeasureRelationshipId</a>

First included in: WMS/WHSWarehouseWorkTemplateV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_MaximumWarehouseWorkOrderLineQuantityUnitOfMeasureRelationshipId attribute are listed below.</summary>

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

First included in: WMS/WHSWarehouseWorkTemplateV2Entity (this entity)  

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

### <a href=#BackingTable_WHSWorkTemplateTableRelationshipId name="BackingTable_WHSWorkTemplateTableRelationshipId">BackingTable_WHSWorkTemplateTableRelationshipId</a>

First included in: WMS/WHSWarehouseWorkTemplateV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_WHSWorkTemplateTableRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/SupplyChain/Inventory/Main/WHSWorkTemplateTable.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/Inventory/Main/WHSWorkTemplateTable.cdm.json/WHSWorkTemplateTable</a></td><td><a href="../../../Tables/SupplyChain/Inventory/Main/WHSWorkTemplateTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PrimaryCompanyContextRelationshipId name="Relationship_PrimaryCompanyContextRelationshipId">Relationship_PrimaryCompanyContextRelationshipId</a>

First included in: WMS/WHSWarehouseWorkTemplateV2Entity (this entity)  

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
