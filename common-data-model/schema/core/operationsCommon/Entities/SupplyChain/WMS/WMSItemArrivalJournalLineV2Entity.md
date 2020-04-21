---
title: WMSItemArrivalJournalLineV2Entity - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/21/2020
ms.author: nebanfic
---

# WMSItemArrivalJournalLineV2Entity

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/SupplyChain/WMS/WMSItemArrivalJournalLineV2Entity.cdm.json" target="_blank">GitHub</a>.  

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
|[JournalNumber](#JournalNumber)||<a href="WMSItemArrivalJournalLineV2Entity.md" target="_blank">WMS/WMSItemArrivalJournalLineV2Entity</a>|
|[LineNumber](#LineNumber)||<a href="WMSItemArrivalJournalLineV2Entity.md" target="_blank">WMS/WMSItemArrivalJournalLineV2Entity</a>|
|[ItemNumber](#ItemNumber)||<a href="WMSItemArrivalJournalLineV2Entity.md" target="_blank">WMS/WMSItemArrivalJournalLineV2Entity</a>|
|[ProductColorId](#ProductColorId)||<a href="WMSItemArrivalJournalLineV2Entity.md" target="_blank">WMS/WMSItemArrivalJournalLineV2Entity</a>|
|[ProductSizeId](#ProductSizeId)||<a href="WMSItemArrivalJournalLineV2Entity.md" target="_blank">WMS/WMSItemArrivalJournalLineV2Entity</a>|
|[ProductStyleId](#ProductStyleId)||<a href="WMSItemArrivalJournalLineV2Entity.md" target="_blank">WMS/WMSItemArrivalJournalLineV2Entity</a>|
|[ProductConfigurationId](#ProductConfigurationId)||<a href="WMSItemArrivalJournalLineV2Entity.md" target="_blank">WMS/WMSItemArrivalJournalLineV2Entity</a>|
|[ReceivingInventorySiteId](#ReceivingInventorySiteId)||<a href="WMSItemArrivalJournalLineV2Entity.md" target="_blank">WMS/WMSItemArrivalJournalLineV2Entity</a>|
|[ReceivingWarehouseId](#ReceivingWarehouseId)||<a href="WMSItemArrivalJournalLineV2Entity.md" target="_blank">WMS/WMSItemArrivalJournalLineV2Entity</a>|
|[ReceivingInventoryStatusId](#ReceivingInventoryStatusId)||<a href="WMSItemArrivalJournalLineV2Entity.md" target="_blank">WMS/WMSItemArrivalJournalLineV2Entity</a>|
|[ReceivingWarehouseLocationId](#ReceivingWarehouseLocationId)||<a href="WMSItemArrivalJournalLineV2Entity.md" target="_blank">WMS/WMSItemArrivalJournalLineV2Entity</a>|
|[ReceivingLicensePlateNumber](#ReceivingLicensePlateNumber)||<a href="WMSItemArrivalJournalLineV2Entity.md" target="_blank">WMS/WMSItemArrivalJournalLineV2Entity</a>|
|[ItemSerialNumber](#ItemSerialNumber)||<a href="WMSItemArrivalJournalLineV2Entity.md" target="_blank">WMS/WMSItemArrivalJournalLineV2Entity</a>|
|[ItemBatchNumber](#ItemBatchNumber)||<a href="WMSItemArrivalJournalLineV2Entity.md" target="_blank">WMS/WMSItemArrivalJournalLineV2Entity</a>|
|[TransactionDate](#TransactionDate)||<a href="WMSItemArrivalJournalLineV2Entity.md" target="_blank">WMS/WMSItemArrivalJournalLineV2Entity</a>|
|[IsItemMovedToDefaultItemPickingWarehouseLocation](#IsItemMovedToDefaultItemPickingWarehouseLocation)||<a href="WMSItemArrivalJournalLineV2Entity.md" target="_blank">WMS/WMSItemArrivalJournalLineV2Entity</a>|
|[IsQuarantineOrderCreatedForReceivedItem](#IsQuarantineOrderCreatedForReceivedItem)||<a href="WMSItemArrivalJournalLineV2Entity.md" target="_blank">WMS/WMSItemArrivalJournalLineV2Entity</a>|
|[TransactionReferenceType](#TransactionReferenceType)||<a href="WMSItemArrivalJournalLineV2Entity.md" target="_blank">WMS/WMSItemArrivalJournalLineV2Entity</a>|
|[TransactionReferenceNumber](#TransactionReferenceNumber)||<a href="WMSItemArrivalJournalLineV2Entity.md" target="_blank">WMS/WMSItemArrivalJournalLineV2Entity</a>|
|[ReferenceInventoryLotId](#ReferenceInventoryLotId)||<a href="WMSItemArrivalJournalLineV2Entity.md" target="_blank">WMS/WMSItemArrivalJournalLineV2Entity</a>|
|[IsReturnOrder](#IsReturnOrder)||<a href="WMSItemArrivalJournalLineV2Entity.md" target="_blank">WMS/WMSItemArrivalJournalLineV2Entity</a>|
|[ItemCatchWeightQuantity](#ItemCatchWeightQuantity)||<a href="WMSItemArrivalJournalLineV2Entity.md" target="_blank">WMS/WMSItemArrivalJournalLineV2Entity</a>|
|[ItemQuantity](#ItemQuantity)||<a href="WMSItemArrivalJournalLineV2Entity.md" target="_blank">WMS/WMSItemArrivalJournalLineV2Entity</a>|
|[ReturnDispositionCodeId](#ReturnDispositionCodeId)||<a href="WMSItemArrivalJournalLineV2Entity.md" target="_blank">WMS/WMSItemArrivalJournalLineV2Entity</a>|
|[ReturnItemNumber](#ReturnItemNumber)||<a href="WMSItemArrivalJournalLineV2Entity.md" target="_blank">WMS/WMSItemArrivalJournalLineV2Entity</a>|
|[AccountNumber](#AccountNumber)||<a href="WMSItemArrivalJournalLineV2Entity.md" target="_blank">WMS/WMSItemArrivalJournalLineV2Entity</a>|
|[Relationship_ItemArrivalJournalHeaderRelationshipId](#Relationship_ItemArrivalJournalHeaderRelationshipId)||<a href="WMSItemArrivalJournalLineV2Entity.md" target="_blank">WMS/WMSItemArrivalJournalLineV2Entity</a>|
|[Relationship_ProductColorRelationshipId](#Relationship_ProductColorRelationshipId)||<a href="WMSItemArrivalJournalLineV2Entity.md" target="_blank">WMS/WMSItemArrivalJournalLineV2Entity</a>|
|[Relationship_ProductSizeRelationshipId](#Relationship_ProductSizeRelationshipId)||<a href="WMSItemArrivalJournalLineV2Entity.md" target="_blank">WMS/WMSItemArrivalJournalLineV2Entity</a>|
|[Relationship_ProductStyleRelationshipId](#Relationship_ProductStyleRelationshipId)||<a href="WMSItemArrivalJournalLineV2Entity.md" target="_blank">WMS/WMSItemArrivalJournalLineV2Entity</a>|
|[Relationship_ProductConfigurationRelationshipId](#Relationship_ProductConfigurationRelationshipId)||<a href="WMSItemArrivalJournalLineV2Entity.md" target="_blank">WMS/WMSItemArrivalJournalLineV2Entity</a>|
|[Relationship_ReceivingInventorySiteRelationshipId](#Relationship_ReceivingInventorySiteRelationshipId)||<a href="WMSItemArrivalJournalLineV2Entity.md" target="_blank">WMS/WMSItemArrivalJournalLineV2Entity</a>|
|[Relationship_ReceivingWarehouseLocationRelationshipId](#Relationship_ReceivingWarehouseLocationRelationshipId)||<a href="WMSItemArrivalJournalLineV2Entity.md" target="_blank">WMS/WMSItemArrivalJournalLineV2Entity</a>|
|[Relationship_ReceivingInventoryStatusRelationshipId](#Relationship_ReceivingInventoryStatusRelationshipId)||<a href="WMSItemArrivalJournalLineV2Entity.md" target="_blank">WMS/WMSItemArrivalJournalLineV2Entity</a>|
|[Relationship_ReceivingLicensePlateRelationshipId](#Relationship_ReceivingLicensePlateRelationshipId)||<a href="WMSItemArrivalJournalLineV2Entity.md" target="_blank">WMS/WMSItemArrivalJournalLineV2Entity</a>|
|[Relationship_ReturnDispositionCodeRelationshipId](#Relationship_ReturnDispositionCodeRelationshipId)||<a href="WMSItemArrivalJournalLineV2Entity.md" target="_blank">WMS/WMSItemArrivalJournalLineV2Entity</a>|
|[Relationship_VendorV2RelationshipId](#Relationship_VendorV2RelationshipId)||<a href="WMSItemArrivalJournalLineV2Entity.md" target="_blank">WMS/WMSItemArrivalJournalLineV2Entity</a>|
|[Relationship_ReceivingWarehouseRelationshipId](#Relationship_ReceivingWarehouseRelationshipId)||<a href="WMSItemArrivalJournalLineV2Entity.md" target="_blank">WMS/WMSItemArrivalJournalLineV2Entity</a>|
|[Relationship_ReleasedProductV2RelationshipId](#Relationship_ReleasedProductV2RelationshipId)||<a href="WMSItemArrivalJournalLineV2Entity.md" target="_blank">WMS/WMSItemArrivalJournalLineV2Entity</a>|
|[BackingTable_WMSJournalTransRelationshipId](#BackingTable_WMSJournalTransRelationshipId)||<a href="WMSItemArrivalJournalLineV2Entity.md" target="_blank">WMS/WMSItemArrivalJournalLineV2Entity</a>|
|[Relationship_PrimaryCompanyContextRelationshipId](#Relationship_PrimaryCompanyContextRelationshipId)||<a href="WMSItemArrivalJournalLineV2Entity.md" target="_blank">WMS/WMSItemArrivalJournalLineV2Entity</a>|

### <a href=#JournalNumber name="JournalNumber">JournalNumber</a>

First included in: WMS/WMSItemArrivalJournalLineV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the JournalNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LineNumber name="LineNumber">LineNumber</a>

First included in: WMS/WMSItemArrivalJournalLineV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LineNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ItemNumber name="ItemNumber">ItemNumber</a>

First included in: WMS/WMSItemArrivalJournalLineV2Entity (this entity)  

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

### <a href=#ProductColorId name="ProductColorId">ProductColorId</a>

First included in: WMS/WMSItemArrivalJournalLineV2Entity (this entity)  

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

First included in: WMS/WMSItemArrivalJournalLineV2Entity (this entity)  

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

### <a href=#ProductStyleId name="ProductStyleId">ProductStyleId</a>

First included in: WMS/WMSItemArrivalJournalLineV2Entity (this entity)  

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

### <a href=#ProductConfigurationId name="ProductConfigurationId">ProductConfigurationId</a>

First included in: WMS/WMSItemArrivalJournalLineV2Entity (this entity)  

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

### <a href=#ReceivingInventorySiteId name="ReceivingInventorySiteId">ReceivingInventorySiteId</a>

First included in: WMS/WMSItemArrivalJournalLineV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReceivingInventorySiteId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ReceivingWarehouseId name="ReceivingWarehouseId">ReceivingWarehouseId</a>

First included in: WMS/WMSItemArrivalJournalLineV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReceivingWarehouseId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ReceivingInventoryStatusId name="ReceivingInventoryStatusId">ReceivingInventoryStatusId</a>

First included in: WMS/WMSItemArrivalJournalLineV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReceivingInventoryStatusId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ReceivingWarehouseLocationId name="ReceivingWarehouseLocationId">ReceivingWarehouseLocationId</a>

First included in: WMS/WMSItemArrivalJournalLineV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReceivingWarehouseLocationId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ReceivingLicensePlateNumber name="ReceivingLicensePlateNumber">ReceivingLicensePlateNumber</a>

First included in: WMS/WMSItemArrivalJournalLineV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReceivingLicensePlateNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ItemSerialNumber name="ItemSerialNumber">ItemSerialNumber</a>

First included in: WMS/WMSItemArrivalJournalLineV2Entity (this entity)  

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

### <a href=#ItemBatchNumber name="ItemBatchNumber">ItemBatchNumber</a>

First included in: WMS/WMSItemArrivalJournalLineV2Entity (this entity)  

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

### <a href=#TransactionDate name="TransactionDate">TransactionDate</a>

First included in: WMS/WMSItemArrivalJournalLineV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TransactionDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsItemMovedToDefaultItemPickingWarehouseLocation name="IsItemMovedToDefaultItemPickingWarehouseLocation">IsItemMovedToDefaultItemPickingWarehouseLocation</a>

First included in: WMS/WMSItemArrivalJournalLineV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsItemMovedToDefaultItemPickingWarehouseLocation attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsQuarantineOrderCreatedForReceivedItem name="IsQuarantineOrderCreatedForReceivedItem">IsQuarantineOrderCreatedForReceivedItem</a>

First included in: WMS/WMSItemArrivalJournalLineV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsQuarantineOrderCreatedForReceivedItem attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TransactionReferenceType name="TransactionReferenceType">TransactionReferenceType</a>

First included in: WMS/WMSItemArrivalJournalLineV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TransactionReferenceType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TransactionReferenceNumber name="TransactionReferenceNumber">TransactionReferenceNumber</a>

First included in: WMS/WMSItemArrivalJournalLineV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TransactionReferenceNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ReferenceInventoryLotId name="ReferenceInventoryLotId">ReferenceInventoryLotId</a>

First included in: WMS/WMSItemArrivalJournalLineV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReferenceInventoryLotId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsReturnOrder name="IsReturnOrder">IsReturnOrder</a>

First included in: WMS/WMSItemArrivalJournalLineV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsReturnOrder attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ItemCatchWeightQuantity name="ItemCatchWeightQuantity">ItemCatchWeightQuantity</a>

First included in: WMS/WMSItemArrivalJournalLineV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ItemCatchWeightQuantity attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ItemQuantity name="ItemQuantity">ItemQuantity</a>

First included in: WMS/WMSItemArrivalJournalLineV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ItemQuantity attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ReturnDispositionCodeId name="ReturnDispositionCodeId">ReturnDispositionCodeId</a>

First included in: WMS/WMSItemArrivalJournalLineV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReturnDispositionCodeId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ReturnItemNumber name="ReturnItemNumber">ReturnItemNumber</a>

First included in: WMS/WMSItemArrivalJournalLineV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReturnItemNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AccountNumber name="AccountNumber">AccountNumber</a>

First included in: WMS/WMSItemArrivalJournalLineV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AccountNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_ItemArrivalJournalHeaderRelationshipId name="Relationship_ItemArrivalJournalHeaderRelationshipId">Relationship_ItemArrivalJournalHeaderRelationshipId</a>

First included in: WMS/WMSItemArrivalJournalLineV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_ItemArrivalJournalHeaderRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_ProductColorRelationshipId name="Relationship_ProductColorRelationshipId">Relationship_ProductColorRelationshipId</a>

First included in: WMS/WMSItemArrivalJournalLineV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_ProductColorRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_ProductSizeRelationshipId name="Relationship_ProductSizeRelationshipId">Relationship_ProductSizeRelationshipId</a>

First included in: WMS/WMSItemArrivalJournalLineV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_ProductSizeRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_ProductStyleRelationshipId name="Relationship_ProductStyleRelationshipId">Relationship_ProductStyleRelationshipId</a>

First included in: WMS/WMSItemArrivalJournalLineV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_ProductStyleRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_ProductConfigurationRelationshipId name="Relationship_ProductConfigurationRelationshipId">Relationship_ProductConfigurationRelationshipId</a>

First included in: WMS/WMSItemArrivalJournalLineV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_ProductConfigurationRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_ReceivingInventorySiteRelationshipId name="Relationship_ReceivingInventorySiteRelationshipId">Relationship_ReceivingInventorySiteRelationshipId</a>

First included in: WMS/WMSItemArrivalJournalLineV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_ReceivingInventorySiteRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_ReceivingWarehouseLocationRelationshipId name="Relationship_ReceivingWarehouseLocationRelationshipId">Relationship_ReceivingWarehouseLocationRelationshipId</a>

First included in: WMS/WMSItemArrivalJournalLineV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_ReceivingWarehouseLocationRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_ReceivingInventoryStatusRelationshipId name="Relationship_ReceivingInventoryStatusRelationshipId">Relationship_ReceivingInventoryStatusRelationshipId</a>

First included in: WMS/WMSItemArrivalJournalLineV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_ReceivingInventoryStatusRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_ReceivingLicensePlateRelationshipId name="Relationship_ReceivingLicensePlateRelationshipId">Relationship_ReceivingLicensePlateRelationshipId</a>

First included in: WMS/WMSItemArrivalJournalLineV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_ReceivingLicensePlateRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_ReturnDispositionCodeRelationshipId name="Relationship_ReturnDispositionCodeRelationshipId">Relationship_ReturnDispositionCodeRelationshipId</a>

First included in: WMS/WMSItemArrivalJournalLineV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_ReturnDispositionCodeRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_VendorV2RelationshipId name="Relationship_VendorV2RelationshipId">Relationship_VendorV2RelationshipId</a>

First included in: WMS/WMSItemArrivalJournalLineV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_VendorV2RelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_ReceivingWarehouseRelationshipId name="Relationship_ReceivingWarehouseRelationshipId">Relationship_ReceivingWarehouseRelationshipId</a>

First included in: WMS/WMSItemArrivalJournalLineV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_ReceivingWarehouseRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_ReleasedProductV2RelationshipId name="Relationship_ReleasedProductV2RelationshipId">Relationship_ReleasedProductV2RelationshipId</a>

First included in: WMS/WMSItemArrivalJournalLineV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_ReleasedProductV2RelationshipId attribute are listed below.</summary>

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

### <a href=#BackingTable_WMSJournalTransRelationshipId name="BackingTable_WMSJournalTransRelationshipId">BackingTable_WMSJournalTransRelationshipId</a>

First included in: WMS/WMSItemArrivalJournalLineV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_WMSJournalTransRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/SupplyChain/Inventory/WorksheetLine/WMSJournalTrans.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/Inventory/WorksheetLine/WMSJournalTrans.cdm.json/WMSJournalTrans</a></td><td><a href="../../../Tables/SupplyChain/Inventory/WorksheetLine/WMSJournalTrans.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PrimaryCompanyContextRelationshipId name="Relationship_PrimaryCompanyContextRelationshipId">Relationship_PrimaryCompanyContextRelationshipId</a>

First included in: WMS/WMSItemArrivalJournalLineV2Entity (this entity)  

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
