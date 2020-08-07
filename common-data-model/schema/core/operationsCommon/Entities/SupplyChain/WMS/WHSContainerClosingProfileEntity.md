---
title: WHSContainerClosingProfileEntity in WMS - Common Data Model | Microsoft Docs
description: undefined
author: llawwaii
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 8/7/2020
ms.author: weiluo
---

# Container packing policies in WMS(WHSContainerClosingProfileEntity)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/SupplyChain/WMS/WHSContainerClosingProfileEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.1"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Container packing policies</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[ProfileId](#ProfileId)||<a href="WHSContainerClosingProfileEntity.md" target="_blank">WMS/WHSContainerClosingProfileEntity</a>|
|[FinalShipmentWarehouseLocationId](#FinalShipmentWarehouseLocationId)||<a href="WHSContainerClosingProfileEntity.md" target="_blank">WMS/WHSContainerClosingProfileEntity</a>|
|[ProfileDescription](#ProfileDescription)||<a href="WHSContainerClosingProfileEntity.md" target="_blank">WMS/WHSContainerClosingProfileEntity</a>|
|[ProfileWarehouseId](#ProfileWarehouseId)||<a href="WHSContainerClosingProfileEntity.md" target="_blank">WMS/WHSContainerClosingProfileEntity</a>|
|[ProcessAt](#ProcessAt)||<a href="WHSContainerClosingProfileEntity.md" target="_blank">WMS/WHSContainerClosingProfileEntity</a>|
|[IsContainerContentPrintingEnabled](#IsContainerContentPrintingEnabled)||<a href="WHSContainerClosingProfileEntity.md" target="_blank">WMS/WHSContainerClosingProfileEntity</a>|
|[IsPackingSlipPrintingEnabled](#IsPackingSlipPrintingEnabled)||<a href="WHSContainerClosingProfileEntity.md" target="_blank">WMS/WHSContainerClosingProfileEntity</a>|
|[WeightUnitSymbol](#WeightUnitSymbol)||<a href="WHSContainerClosingProfileEntity.md" target="_blank">WMS/WHSContainerClosingProfileEntity</a>|
|[ContainerClosingWorkCreationProcess](#ContainerClosingWorkCreationProcess)||<a href="WHSContainerClosingProfileEntity.md" target="_blank">WMS/WHSContainerClosingProfileEntity</a>|
|[ManifestingShipmentPolicy](#ManifestingShipmentPolicy)||<a href="WHSContainerClosingProfileEntity.md" target="_blank">WMS/WHSContainerClosingProfileEntity</a>|
|[IsContainerManifestedAtClosing](#IsContainerManifestedAtClosing)||<a href="WHSContainerClosingProfileEntity.md" target="_blank">WMS/WHSContainerClosingProfileEntity</a>|
|[ManifestingContainerPolicy](#ManifestingContainerPolicy)||<a href="WHSContainerClosingProfileEntity.md" target="_blank">WMS/WHSContainerClosingProfileEntity</a>|
|[ContainerClosingAutoReleasePolicy](#ContainerClosingAutoReleasePolicy)||<a href="WHSContainerClosingProfileEntity.md" target="_blank">WMS/WHSContainerClosingProfileEntity</a>|
|[PackedContainerPickingWarehouseWorkTemplateId](#PackedContainerPickingWarehouseWorkTemplateId)||<a href="WHSContainerClosingProfileEntity.md" target="_blank">WMS/WHSContainerClosingProfileEntity</a>|
|[ManifestRequirementsForContainerGroup](#ManifestRequirementsForContainerGroup)||<a href="WHSContainerClosingProfileEntity.md" target="_blank">WMS/WHSContainerClosingProfileEntity</a>|
|[PackedContainerPickingWarehouseWorkTemplateWorkOrderType](#PackedContainerPickingWarehouseWorkTemplateWorkOrderType)||<a href="WHSContainerClosingProfileEntity.md" target="_blank">WMS/WHSContainerClosingProfileEntity</a>|
|[DefaultOutboundSortingWarehouseLocationId](#DefaultOutboundSortingWarehouseLocationId)||<a href="WHSContainerClosingProfileEntity.md" target="_blank">WMS/WHSContainerClosingProfileEntity</a>|
|[PrintContainerShippingLabelRule](#PrintContainerShippingLabelRule)||<a href="WHSContainerClosingProfileEntity.md" target="_blank">WMS/WHSContainerClosingProfileEntity</a>|
|[ContainerShippingLabelPrinterName](#ContainerShippingLabelPrinterName)||<a href="WHSContainerClosingProfileEntity.md" target="_blank">WMS/WHSContainerClosingProfileEntity</a>|
|[Relationship_WarehouseRelationshipId](#Relationship_WarehouseRelationshipId)||<a href="WHSContainerClosingProfileEntity.md" target="_blank">WMS/WHSContainerClosingProfileEntity</a>|
|[Relationship_FinalShipmentWarehouseLocationRelationshipId](#Relationship_FinalShipmentWarehouseLocationRelationshipId)||<a href="WHSContainerClosingProfileEntity.md" target="_blank">WMS/WHSContainerClosingProfileEntity</a>|
|[Relationship_WeightUnitOfMeasureRelationshipId](#Relationship_WeightUnitOfMeasureRelationshipId)||<a href="WHSContainerClosingProfileEntity.md" target="_blank">WMS/WHSContainerClosingProfileEntity</a>|
|[Relationship_DefaultOutboundSortingWarehouseLocationRelationshipId](#Relationship_DefaultOutboundSortingWarehouseLocationRelationshipId)||<a href="WHSContainerClosingProfileEntity.md" target="_blank">WMS/WHSContainerClosingProfileEntity</a>|
|[BackingTable_WHSCloseContainerProfileRelationshipId](#BackingTable_WHSCloseContainerProfileRelationshipId)||<a href="WHSContainerClosingProfileEntity.md" target="_blank">WMS/WHSContainerClosingProfileEntity</a>|
|[Relationship_PrimaryCompanyContextRelationshipId](#Relationship_PrimaryCompanyContextRelationshipId)||<a href="WHSContainerClosingProfileEntity.md" target="_blank">WMS/WHSContainerClosingProfileEntity</a>|

### <a href=#ProfileId name="ProfileId">ProfileId</a>

First included in: WMS/WHSContainerClosingProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProfileId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FinalShipmentWarehouseLocationId name="FinalShipmentWarehouseLocationId">FinalShipmentWarehouseLocationId</a>

First included in: WMS/WHSContainerClosingProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FinalShipmentWarehouseLocationId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProfileDescription name="ProfileDescription">ProfileDescription</a>

First included in: WMS/WHSContainerClosingProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProfileDescription attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProfileWarehouseId name="ProfileWarehouseId">ProfileWarehouseId</a>

First included in: WMS/WHSContainerClosingProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProfileWarehouseId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProcessAt name="ProcessAt">ProcessAt</a>

First included in: WMS/WHSContainerClosingProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProcessAt attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsContainerContentPrintingEnabled name="IsContainerContentPrintingEnabled">IsContainerContentPrintingEnabled</a>

First included in: WMS/WHSContainerClosingProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsContainerContentPrintingEnabled attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsPackingSlipPrintingEnabled name="IsPackingSlipPrintingEnabled">IsPackingSlipPrintingEnabled</a>

First included in: WMS/WHSContainerClosingProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsPackingSlipPrintingEnabled attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WeightUnitSymbol name="WeightUnitSymbol">WeightUnitSymbol</a>

First included in: WMS/WHSContainerClosingProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WeightUnitSymbol attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ContainerClosingWorkCreationProcess name="ContainerClosingWorkCreationProcess">ContainerClosingWorkCreationProcess</a>

First included in: WMS/WHSContainerClosingProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ContainerClosingWorkCreationProcess attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ManifestingShipmentPolicy name="ManifestingShipmentPolicy">ManifestingShipmentPolicy</a>

First included in: WMS/WHSContainerClosingProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ManifestingShipmentPolicy attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsContainerManifestedAtClosing name="IsContainerManifestedAtClosing">IsContainerManifestedAtClosing</a>

First included in: WMS/WHSContainerClosingProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsContainerManifestedAtClosing attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ManifestingContainerPolicy name="ManifestingContainerPolicy">ManifestingContainerPolicy</a>

First included in: WMS/WHSContainerClosingProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ManifestingContainerPolicy attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ContainerClosingAutoReleasePolicy name="ContainerClosingAutoReleasePolicy">ContainerClosingAutoReleasePolicy</a>

First included in: WMS/WHSContainerClosingProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ContainerClosingAutoReleasePolicy attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PackedContainerPickingWarehouseWorkTemplateId name="PackedContainerPickingWarehouseWorkTemplateId">PackedContainerPickingWarehouseWorkTemplateId</a>

First included in: WMS/WHSContainerClosingProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PackedContainerPickingWarehouseWorkTemplateId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ManifestRequirementsForContainerGroup name="ManifestRequirementsForContainerGroup">ManifestRequirementsForContainerGroup</a>

First included in: WMS/WHSContainerClosingProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ManifestRequirementsForContainerGroup attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PackedContainerPickingWarehouseWorkTemplateWorkOrderType name="PackedContainerPickingWarehouseWorkTemplateWorkOrderType">PackedContainerPickingWarehouseWorkTemplateWorkOrderType</a>

First included in: WMS/WHSContainerClosingProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PackedContainerPickingWarehouseWorkTemplateWorkOrderType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DefaultOutboundSortingWarehouseLocationId name="DefaultOutboundSortingWarehouseLocationId">DefaultOutboundSortingWarehouseLocationId</a>

First included in: WMS/WHSContainerClosingProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultOutboundSortingWarehouseLocationId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PrintContainerShippingLabelRule name="PrintContainerShippingLabelRule">PrintContainerShippingLabelRule</a>

First included in: WMS/WHSContainerClosingProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrintContainerShippingLabelRule attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ContainerShippingLabelPrinterName name="ContainerShippingLabelPrinterName">ContainerShippingLabelPrinterName</a>

First included in: WMS/WHSContainerClosingProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ContainerShippingLabelPrinterName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_WarehouseRelationshipId name="Relationship_WarehouseRelationshipId">Relationship_WarehouseRelationshipId</a>

First included in: WMS/WHSContainerClosingProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_WarehouseRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_FinalShipmentWarehouseLocationRelationshipId name="Relationship_FinalShipmentWarehouseLocationRelationshipId">Relationship_FinalShipmentWarehouseLocationRelationshipId</a>

First included in: WMS/WHSContainerClosingProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_FinalShipmentWarehouseLocationRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_WeightUnitOfMeasureRelationshipId name="Relationship_WeightUnitOfMeasureRelationshipId">Relationship_WeightUnitOfMeasureRelationshipId</a>

First included in: WMS/WHSContainerClosingProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_WeightUnitOfMeasureRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_DefaultOutboundSortingWarehouseLocationRelationshipId name="Relationship_DefaultOutboundSortingWarehouseLocationRelationshipId">Relationship_DefaultOutboundSortingWarehouseLocationRelationshipId</a>

First included in: WMS/WHSContainerClosingProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_DefaultOutboundSortingWarehouseLocationRelationshipId attribute are listed below.</summary>

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

### <a href=#BackingTable_WHSCloseContainerProfileRelationshipId name="BackingTable_WHSCloseContainerProfileRelationshipId">BackingTable_WHSCloseContainerProfileRelationshipId</a>

First included in: WMS/WHSContainerClosingProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_WHSCloseContainerProfileRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/SupplyChain/Inventory/Main/WHSCloseContainerProfile.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/Inventory/Main/WHSCloseContainerProfile.cdm.json/WHSCloseContainerProfile</a></td><td><a href="../../../Tables/SupplyChain/Inventory/Main/WHSCloseContainerProfile.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PrimaryCompanyContextRelationshipId name="Relationship_PrimaryCompanyContextRelationshipId">Relationship_PrimaryCompanyContextRelationshipId</a>

First included in: WMS/WHSContainerClosingProfileEntity (this entity)  

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
