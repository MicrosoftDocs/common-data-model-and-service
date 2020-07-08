---
title: WHSWarehouseReplenishmentTemplateLineEntity in WMS - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 7/8/2020
ms.author: nebanfic
---

# Warehouse replenishment template lines in WMS(WHSWarehouseReplenishmentTemplateLineEntity)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/SupplyChain/WMS/WHSWarehouseReplenishmentTemplateLineEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Warehouse replenishment template lines</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[WarehouseReplenishmentTemplateId](#WarehouseReplenishmentTemplateId)||<a href="WHSWarehouseReplenishmentTemplateLineEntity.md" target="_blank">WMS/WHSWarehouseReplenishmentTemplateLineEntity</a>|
|[SequenceNumber](#SequenceNumber)||<a href="WHSWarehouseReplenishmentTemplateLineEntity.md" target="_blank">WMS/WHSWarehouseReplenishmentTemplateLineEntity</a>|
|[LineDescription](#LineDescription)||<a href="WHSWarehouseReplenishmentTemplateLineEntity.md" target="_blank">WMS/WHSWarehouseReplenishmentTemplateLineEntity</a>|
|[ReplenishmentUnitSymbol](#ReplenishmentUnitSymbol)||<a href="WHSWarehouseReplenishmentTemplateLineEntity.md" target="_blank">WMS/WHSWarehouseReplenishmentTemplateLineEntity</a>|
|[WarehouseReplenishmentRequestTypeId](#WarehouseReplenishmentRequestTypeId)||<a href="WHSWarehouseReplenishmentTemplateLineEntity.md" target="_blank">WMS/WHSWarehouseReplenishmentTemplateLineEntity</a>|
|[WarehouseLocationDirectiveCode](#WarehouseLocationDirectiveCode)||<a href="WHSWarehouseReplenishmentTemplateLineEntity.md" target="_blank">WMS/WHSWarehouseReplenishmentTemplateLineEntity</a>|
|[WarehouseWorkTemplateId](#WarehouseWorkTemplateId)||<a href="WHSWarehouseReplenishmentTemplateLineEntity.md" target="_blank">WMS/WHSWarehouseReplenishmentTemplateLineEntity</a>|
|[MinimumReplenishmentQuantity](#MinimumReplenishmentQuantity)||<a href="WHSWarehouseReplenishmentTemplateLineEntity.md" target="_blank">WMS/WHSWarehouseReplenishmentTemplateLineEntity</a>|
|[MaximumReplenishmentQuantity](#MaximumReplenishmentQuantity)||<a href="WHSWarehouseReplenishmentTemplateLineEntity.md" target="_blank">WMS/WHSWarehouseReplenishmentTemplateLineEntity</a>|
|[ReplenishmentQuantityUnitSymbol](#ReplenishmentQuantityUnitSymbol)||<a href="WHSWarehouseReplenishmentTemplateLineEntity.md" target="_blank">WMS/WHSWarehouseReplenishmentTemplateLineEntity</a>|
|[DemandIncrementRoundingMethod](#DemandIncrementRoundingMethod)||<a href="WHSWarehouseReplenishmentTemplateLineEntity.md" target="_blank">WMS/WHSWarehouseReplenishmentTemplateLineEntity</a>|
|[WillTemplateReplenishEmptyFixedLocations](#WillTemplateReplenishEmptyFixedLocations)||<a href="WHSWarehouseReplenishmentTemplateLineEntity.md" target="_blank">WMS/WHSWarehouseReplenishmentTemplateLineEntity</a>|
|[WillTemplateReplenishOnlyFixedLocations](#WillTemplateReplenishOnlyFixedLocations)||<a href="WHSWarehouseReplenishmentTemplateLineEntity.md" target="_blank">WMS/WHSWarehouseReplenishmentTemplateLineEntity</a>|
|[ApplicableDemandMethod](#ApplicableDemandMethod)||<a href="WHSWarehouseReplenishmentTemplateLineEntity.md" target="_blank">WMS/WHSWarehouseReplenishmentTemplateLineEntity</a>|
|[ProductQueryMode](#ProductQueryMode)||<a href="WHSWarehouseReplenishmentTemplateLineEntity.md" target="_blank">WMS/WHSWarehouseReplenishmentTemplateLineEntity</a>|
|[ProductQuery](#ProductQuery)||<a href="WHSWarehouseReplenishmentTemplateLineEntity.md" target="_blank">WMS/WHSWarehouseReplenishmentTemplateLineEntity</a>|
|[LocationQuery](#LocationQuery)||<a href="WHSWarehouseReplenishmentTemplateLineEntity.md" target="_blank">WMS/WHSWarehouseReplenishmentTemplateLineEntity</a>|
|[ProductVariantQuery](#ProductVariantQuery)||<a href="WHSWarehouseReplenishmentTemplateLineEntity.md" target="_blank">WMS/WHSWarehouseReplenishmentTemplateLineEntity</a>|
|[WarehouseWorkTemplateWorkOrderType](#WarehouseWorkTemplateWorkOrderType)||<a href="WHSWarehouseReplenishmentTemplateLineEntity.md" target="_blank">WMS/WHSWarehouseReplenishmentTemplateLineEntity</a>|
|[ReplenishmentStrategy](#ReplenishmentStrategy)||<a href="WHSWarehouseReplenishmentTemplateLineEntity.md" target="_blank">WMS/WHSWarehouseReplenishmentTemplateLineEntity</a>|
|[ReplenishmentThresholdScope](#ReplenishmentThresholdScope)||<a href="WHSWarehouseReplenishmentTemplateLineEntity.md" target="_blank">WMS/WHSWarehouseReplenishmentTemplateLineEntity</a>|
|[ZoneQuery](#ZoneQuery)||<a href="WHSWarehouseReplenishmentTemplateLineEntity.md" target="_blank">WMS/WHSWarehouseReplenishmentTemplateLineEntity</a>|
|[ReplenishmentWarehouseId](#ReplenishmentWarehouseId)||<a href="WHSWarehouseReplenishmentTemplateLineEntity.md" target="_blank">WMS/WHSWarehouseReplenishmentTemplateLineEntity</a>|
|[Relationship_ReplenishmentUnitOfMeasureRelationshipId](#Relationship_ReplenishmentUnitOfMeasureRelationshipId)||<a href="WHSWarehouseReplenishmentTemplateLineEntity.md" target="_blank">WMS/WHSWarehouseReplenishmentTemplateLineEntity</a>|
|[Relationship_ReplenishmentQuantityUnitOfMeasureRelationshipId](#Relationship_ReplenishmentQuantityUnitOfMeasureRelationshipId)||<a href="WHSWarehouseReplenishmentTemplateLineEntity.md" target="_blank">WMS/WHSWarehouseReplenishmentTemplateLineEntity</a>|
|[Relationship_WarehouseLocationDirectiveCodeRelationshipId](#Relationship_WarehouseLocationDirectiveCodeRelationshipId)||<a href="WHSWarehouseReplenishmentTemplateLineEntity.md" target="_blank">WMS/WHSWarehouseReplenishmentTemplateLineEntity</a>|
|[Relationship_WarehouseReplenishmentTemplateRelationshipId](#Relationship_WarehouseReplenishmentTemplateRelationshipId)||<a href="WHSWarehouseReplenishmentTemplateLineEntity.md" target="_blank">WMS/WHSWarehouseReplenishmentTemplateLineEntity</a>|
|[Relationship_WarehouseReplenishmentRequestTypeRelationshipId](#Relationship_WarehouseReplenishmentRequestTypeRelationshipId)||<a href="WHSWarehouseReplenishmentTemplateLineEntity.md" target="_blank">WMS/WHSWarehouseReplenishmentTemplateLineEntity</a>|
|[BackingTable_WHSReplenishmentTemplateLineRelationshipId](#BackingTable_WHSReplenishmentTemplateLineRelationshipId)||<a href="WHSWarehouseReplenishmentTemplateLineEntity.md" target="_blank">WMS/WHSWarehouseReplenishmentTemplateLineEntity</a>|
|[Relationship_PrimaryCompanyContextRelationshipId](#Relationship_PrimaryCompanyContextRelationshipId)||<a href="WHSWarehouseReplenishmentTemplateLineEntity.md" target="_blank">WMS/WHSWarehouseReplenishmentTemplateLineEntity</a>|

### <a href=#WarehouseReplenishmentTemplateId name="WarehouseReplenishmentTemplateId">WarehouseReplenishmentTemplateId</a>

First included in: WMS/WHSWarehouseReplenishmentTemplateLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WarehouseReplenishmentTemplateId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SequenceNumber name="SequenceNumber">SequenceNumber</a>

First included in: WMS/WHSWarehouseReplenishmentTemplateLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SequenceNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LineDescription name="LineDescription">LineDescription</a>

First included in: WMS/WHSWarehouseReplenishmentTemplateLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LineDescription attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ReplenishmentUnitSymbol name="ReplenishmentUnitSymbol">ReplenishmentUnitSymbol</a>

First included in: WMS/WHSWarehouseReplenishmentTemplateLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReplenishmentUnitSymbol attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WarehouseReplenishmentRequestTypeId name="WarehouseReplenishmentRequestTypeId">WarehouseReplenishmentRequestTypeId</a>

First included in: WMS/WHSWarehouseReplenishmentTemplateLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WarehouseReplenishmentRequestTypeId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WarehouseLocationDirectiveCode name="WarehouseLocationDirectiveCode">WarehouseLocationDirectiveCode</a>

First included in: WMS/WHSWarehouseReplenishmentTemplateLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WarehouseLocationDirectiveCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WarehouseWorkTemplateId name="WarehouseWorkTemplateId">WarehouseWorkTemplateId</a>

First included in: WMS/WHSWarehouseReplenishmentTemplateLineEntity (this entity)  

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

### <a href=#MinimumReplenishmentQuantity name="MinimumReplenishmentQuantity">MinimumReplenishmentQuantity</a>

First included in: WMS/WHSWarehouseReplenishmentTemplateLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MinimumReplenishmentQuantity attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MaximumReplenishmentQuantity name="MaximumReplenishmentQuantity">MaximumReplenishmentQuantity</a>

First included in: WMS/WHSWarehouseReplenishmentTemplateLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MaximumReplenishmentQuantity attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ReplenishmentQuantityUnitSymbol name="ReplenishmentQuantityUnitSymbol">ReplenishmentQuantityUnitSymbol</a>

First included in: WMS/WHSWarehouseReplenishmentTemplateLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReplenishmentQuantityUnitSymbol attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DemandIncrementRoundingMethod name="DemandIncrementRoundingMethod">DemandIncrementRoundingMethod</a>

First included in: WMS/WHSWarehouseReplenishmentTemplateLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DemandIncrementRoundingMethod attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WillTemplateReplenishEmptyFixedLocations name="WillTemplateReplenishEmptyFixedLocations">WillTemplateReplenishEmptyFixedLocations</a>

First included in: WMS/WHSWarehouseReplenishmentTemplateLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WillTemplateReplenishEmptyFixedLocations attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WillTemplateReplenishOnlyFixedLocations name="WillTemplateReplenishOnlyFixedLocations">WillTemplateReplenishOnlyFixedLocations</a>

First included in: WMS/WHSWarehouseReplenishmentTemplateLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WillTemplateReplenishOnlyFixedLocations attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ApplicableDemandMethod name="ApplicableDemandMethod">ApplicableDemandMethod</a>

First included in: WMS/WHSWarehouseReplenishmentTemplateLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ApplicableDemandMethod attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProductQueryMode name="ProductQueryMode">ProductQueryMode</a>

First included in: WMS/WHSWarehouseReplenishmentTemplateLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProductQueryMode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProductQuery name="ProductQuery">ProductQuery</a>

First included in: WMS/WHSWarehouseReplenishmentTemplateLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProductQuery attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LocationQuery name="LocationQuery">LocationQuery</a>

First included in: WMS/WHSWarehouseReplenishmentTemplateLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LocationQuery attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProductVariantQuery name="ProductVariantQuery">ProductVariantQuery</a>

First included in: WMS/WHSWarehouseReplenishmentTemplateLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProductVariantQuery attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WarehouseWorkTemplateWorkOrderType name="WarehouseWorkTemplateWorkOrderType">WarehouseWorkTemplateWorkOrderType</a>

First included in: WMS/WHSWarehouseReplenishmentTemplateLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WarehouseWorkTemplateWorkOrderType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ReplenishmentStrategy name="ReplenishmentStrategy">ReplenishmentStrategy</a>

First included in: WMS/WHSWarehouseReplenishmentTemplateLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReplenishmentStrategy attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ReplenishmentThresholdScope name="ReplenishmentThresholdScope">ReplenishmentThresholdScope</a>

First included in: WMS/WHSWarehouseReplenishmentTemplateLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReplenishmentThresholdScope attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ZoneQuery name="ZoneQuery">ZoneQuery</a>

First included in: WMS/WHSWarehouseReplenishmentTemplateLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ZoneQuery attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ReplenishmentWarehouseId name="ReplenishmentWarehouseId">ReplenishmentWarehouseId</a>

First included in: WMS/WHSWarehouseReplenishmentTemplateLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReplenishmentWarehouseId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_ReplenishmentUnitOfMeasureRelationshipId name="Relationship_ReplenishmentUnitOfMeasureRelationshipId">Relationship_ReplenishmentUnitOfMeasureRelationshipId</a>

First included in: WMS/WHSWarehouseReplenishmentTemplateLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_ReplenishmentUnitOfMeasureRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_ReplenishmentQuantityUnitOfMeasureRelationshipId name="Relationship_ReplenishmentQuantityUnitOfMeasureRelationshipId">Relationship_ReplenishmentQuantityUnitOfMeasureRelationshipId</a>

First included in: WMS/WHSWarehouseReplenishmentTemplateLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_ReplenishmentQuantityUnitOfMeasureRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_WarehouseLocationDirectiveCodeRelationshipId name="Relationship_WarehouseLocationDirectiveCodeRelationshipId">Relationship_WarehouseLocationDirectiveCodeRelationshipId</a>

First included in: WMS/WHSWarehouseReplenishmentTemplateLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_WarehouseLocationDirectiveCodeRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_WarehouseReplenishmentTemplateRelationshipId name="Relationship_WarehouseReplenishmentTemplateRelationshipId">Relationship_WarehouseReplenishmentTemplateRelationshipId</a>

First included in: WMS/WHSWarehouseReplenishmentTemplateLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_WarehouseReplenishmentTemplateRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_WarehouseReplenishmentRequestTypeRelationshipId name="Relationship_WarehouseReplenishmentRequestTypeRelationshipId">Relationship_WarehouseReplenishmentRequestTypeRelationshipId</a>

First included in: WMS/WHSWarehouseReplenishmentTemplateLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_WarehouseReplenishmentRequestTypeRelationshipId attribute are listed below.</summary>

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

### <a href=#BackingTable_WHSReplenishmentTemplateLineRelationshipId name="BackingTable_WHSReplenishmentTemplateLineRelationshipId">BackingTable_WHSReplenishmentTemplateLineRelationshipId</a>

First included in: WMS/WHSWarehouseReplenishmentTemplateLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_WHSReplenishmentTemplateLineRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/SupplyChain/Inventory/Group/WHSReplenishmentTemplateLine.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/Inventory/Group/WHSReplenishmentTemplateLine.cdm.json/WHSReplenishmentTemplateLine</a></td><td><a href="../../../Tables/SupplyChain/Inventory/Group/WHSReplenishmentTemplateLine.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PrimaryCompanyContextRelationshipId name="Relationship_PrimaryCompanyContextRelationshipId">Relationship_PrimaryCompanyContextRelationshipId</a>

First included in: WMS/WHSWarehouseReplenishmentTemplateLineEntity (this entity)  

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
