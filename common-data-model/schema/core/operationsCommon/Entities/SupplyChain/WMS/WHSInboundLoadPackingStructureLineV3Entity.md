---
title: WHSInboundLoadPackingStructureLineV3Entity - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/29/2020
ms.author: nebanfic
---

# Inbound load packing structure lines V3

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/SupplyChain/WMS/WHSInboundLoadPackingStructureLineV3Entity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Inbound load packing structure lines V3</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[InboundShipmentId](#InboundShipmentId)||<a href="WHSInboundLoadPackingStructureLineV3Entity.md" target="_blank">WMS/WHSInboundLoadPackingStructureLineV3Entity</a>|
|[PackingStructureLicensePlateNumber](#PackingStructureLicensePlateNumber)||<a href="WHSInboundLoadPackingStructureLineV3Entity.md" target="_blank">WMS/WHSInboundLoadPackingStructureLineV3Entity</a>|
|[Description](#Description)||<a href="WHSInboundLoadPackingStructureLineV3Entity.md" target="_blank">WMS/WHSInboundLoadPackingStructureLineV3Entity</a>|
|[PurchaseOrderNumber](#PurchaseOrderNumber)||<a href="WHSInboundLoadPackingStructureLineV3Entity.md" target="_blank">WMS/WHSInboundLoadPackingStructureLineV3Entity</a>|
|[ItemNumber](#ItemNumber)||<a href="WHSInboundLoadPackingStructureLineV3Entity.md" target="_blank">WMS/WHSInboundLoadPackingStructureLineV3Entity</a>|
|[Quantity](#Quantity)||<a href="WHSInboundLoadPackingStructureLineV3Entity.md" target="_blank">WMS/WHSInboundLoadPackingStructureLineV3Entity</a>|
|[CapturedWeight](#CapturedWeight)||<a href="WHSInboundLoadPackingStructureLineV3Entity.md" target="_blank">WMS/WHSInboundLoadPackingStructureLineV3Entity</a>|
|[UnitSymbol](#UnitSymbol)||<a href="WHSInboundLoadPackingStructureLineV3Entity.md" target="_blank">WMS/WHSInboundLoadPackingStructureLineV3Entity</a>|
|[ProductColorId](#ProductColorId)||<a href="WHSInboundLoadPackingStructureLineV3Entity.md" target="_blank">WMS/WHSInboundLoadPackingStructureLineV3Entity</a>|
|[ProductSizeId](#ProductSizeId)||<a href="WHSInboundLoadPackingStructureLineV3Entity.md" target="_blank">WMS/WHSInboundLoadPackingStructureLineV3Entity</a>|
|[ProductConfigurationId](#ProductConfigurationId)||<a href="WHSInboundLoadPackingStructureLineV3Entity.md" target="_blank">WMS/WHSInboundLoadPackingStructureLineV3Entity</a>|
|[ProductStyleId](#ProductStyleId)||<a href="WHSInboundLoadPackingStructureLineV3Entity.md" target="_blank">WMS/WHSInboundLoadPackingStructureLineV3Entity</a>|
|[ProductVersionId](#ProductVersionId)||<a href="WHSInboundLoadPackingStructureLineV3Entity.md" target="_blank">WMS/WHSInboundLoadPackingStructureLineV3Entity</a>|
|[ItemBatchNumber](#ItemBatchNumber)||<a href="WHSInboundLoadPackingStructureLineV3Entity.md" target="_blank">WMS/WHSInboundLoadPackingStructureLineV3Entity</a>|
|[ItemBatchExpirationDate](#ItemBatchExpirationDate)||<a href="WHSInboundLoadPackingStructureLineV3Entity.md" target="_blank">WMS/WHSInboundLoadPackingStructureLineV3Entity</a>|
|[ItemSerialNumber](#ItemSerialNumber)||<a href="WHSInboundLoadPackingStructureLineV3Entity.md" target="_blank">WMS/WHSInboundLoadPackingStructureLineV3Entity</a>|
|[PurchaseOrderLineNumber](#PurchaseOrderLineNumber)||<a href="WHSInboundLoadPackingStructureLineV3Entity.md" target="_blank">WMS/WHSInboundLoadPackingStructureLineV3Entity</a>|
|[Relationship_LoadPackingStructureRelationshipId](#Relationship_LoadPackingStructureRelationshipId)||<a href="WHSInboundLoadPackingStructureLineV3Entity.md" target="_blank">WMS/WHSInboundLoadPackingStructureLineV3Entity</a>|
|[BackingTable_WHSASNItemRelationshipId](#BackingTable_WHSASNItemRelationshipId)||<a href="WHSInboundLoadPackingStructureLineV3Entity.md" target="_blank">WMS/WHSInboundLoadPackingStructureLineV3Entity</a>|
|[Relationship_PrimaryCompanyContextRelationshipId](#Relationship_PrimaryCompanyContextRelationshipId)||<a href="WHSInboundLoadPackingStructureLineV3Entity.md" target="_blank">WMS/WHSInboundLoadPackingStructureLineV3Entity</a>|

### <a href=#InboundShipmentId name="InboundShipmentId">InboundShipmentId</a>

First included in: WMS/WHSInboundLoadPackingStructureLineV3Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InboundShipmentId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PackingStructureLicensePlateNumber name="PackingStructureLicensePlateNumber">PackingStructureLicensePlateNumber</a>

First included in: WMS/WHSInboundLoadPackingStructureLineV3Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PackingStructureLicensePlateNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Description name="Description">Description</a>

First included in: WMS/WHSInboundLoadPackingStructureLineV3Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Description attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PurchaseOrderNumber name="PurchaseOrderNumber">PurchaseOrderNumber</a>

First included in: WMS/WHSInboundLoadPackingStructureLineV3Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PurchaseOrderNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ItemNumber name="ItemNumber">ItemNumber</a>

First included in: WMS/WHSInboundLoadPackingStructureLineV3Entity (this entity)  

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

### <a href=#Quantity name="Quantity">Quantity</a>

First included in: WMS/WHSInboundLoadPackingStructureLineV3Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Quantity attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CapturedWeight name="CapturedWeight">CapturedWeight</a>

First included in: WMS/WHSInboundLoadPackingStructureLineV3Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CapturedWeight attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#UnitSymbol name="UnitSymbol">UnitSymbol</a>

First included in: WMS/WHSInboundLoadPackingStructureLineV3Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the UnitSymbol attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProductColorId name="ProductColorId">ProductColorId</a>

First included in: WMS/WHSInboundLoadPackingStructureLineV3Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProductColorId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProductSizeId name="ProductSizeId">ProductSizeId</a>

First included in: WMS/WHSInboundLoadPackingStructureLineV3Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProductSizeId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProductConfigurationId name="ProductConfigurationId">ProductConfigurationId</a>

First included in: WMS/WHSInboundLoadPackingStructureLineV3Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProductConfigurationId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProductStyleId name="ProductStyleId">ProductStyleId</a>

First included in: WMS/WHSInboundLoadPackingStructureLineV3Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProductStyleId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProductVersionId name="ProductVersionId">ProductVersionId</a>

First included in: WMS/WHSInboundLoadPackingStructureLineV3Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProductVersionId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ItemBatchNumber name="ItemBatchNumber">ItemBatchNumber</a>

First included in: WMS/WHSInboundLoadPackingStructureLineV3Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ItemBatchNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ItemBatchExpirationDate name="ItemBatchExpirationDate">ItemBatchExpirationDate</a>

First included in: WMS/WHSInboundLoadPackingStructureLineV3Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ItemBatchExpirationDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ItemSerialNumber name="ItemSerialNumber">ItemSerialNumber</a>

First included in: WMS/WHSInboundLoadPackingStructureLineV3Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ItemSerialNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PurchaseOrderLineNumber name="PurchaseOrderLineNumber">PurchaseOrderLineNumber</a>

First included in: WMS/WHSInboundLoadPackingStructureLineV3Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PurchaseOrderLineNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_LoadPackingStructureRelationshipId name="Relationship_LoadPackingStructureRelationshipId">Relationship_LoadPackingStructureRelationshipId</a>

First included in: WMS/WHSInboundLoadPackingStructureLineV3Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_LoadPackingStructureRelationshipId attribute are listed below.</summary>

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

### <a href=#BackingTable_WHSASNItemRelationshipId name="BackingTable_WHSASNItemRelationshipId">BackingTable_WHSASNItemRelationshipId</a>

First included in: WMS/WHSInboundLoadPackingStructureLineV3Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_WHSASNItemRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/SupplyChain/Inventory/Main/WHSASNItem.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/Inventory/Main/WHSASNItem.cdm.json/WHSASNItem</a></td><td><a href="../../../Tables/SupplyChain/Inventory/Main/WHSASNItem.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PrimaryCompanyContextRelationshipId name="Relationship_PrimaryCompanyContextRelationshipId">Relationship_PrimaryCompanyContextRelationshipId</a>

First included in: WMS/WHSInboundLoadPackingStructureLineV3Entity (this entity)  

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
