---
title: InventItemBatchEntity - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/17/2020
ms.author: nebanfic
---

# InventItemBatchEntity

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/erp/Entities/SupplyChain/InventoryAndWarehouseManagement/InventItemBatchEntity.cdm.json" target="_blank">GitHub</a>.  

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
|[BatchDescription](#BatchDescription)||<a href="InventItemBatchEntity.md" target="_blank">InventoryAndWarehouseManagement/InventItemBatchEntity</a>|
|[BatchExpirationDate](#BatchExpirationDate)||<a href="InventItemBatchEntity.md" target="_blank">InventoryAndWarehouseManagement/InventItemBatchEntity</a>|
|[BatchNumber](#BatchNumber)||<a href="InventItemBatchEntity.md" target="_blank">InventoryAndWarehouseManagement/InventItemBatchEntity</a>|
|[ItemNumber](#ItemNumber)||<a href="InventItemBatchEntity.md" target="_blank">InventoryAndWarehouseManagement/InventItemBatchEntity</a>|
|[BestBeforeDate](#BestBeforeDate)||<a href="InventItemBatchEntity.md" target="_blank">InventoryAndWarehouseManagement/InventItemBatchEntity</a>|
|[PrimaryVendorOriginCountryRegionId](#PrimaryVendorOriginCountryRegionId)||<a href="InventItemBatchEntity.md" target="_blank">InventoryAndWarehouseManagement/InventItemBatchEntity</a>|
|[SecondaryVendorOriginCountryRegionId](#SecondaryVendorOriginCountryRegionId)||<a href="InventItemBatchEntity.md" target="_blank">InventoryAndWarehouseManagement/InventItemBatchEntity</a>|
|[BatchDispositionCode](#BatchDispositionCode)||<a href="InventItemBatchEntity.md" target="_blank">InventoryAndWarehouseManagement/InventItemBatchEntity</a>|
|[MostRecentTestDate](#MostRecentTestDate)||<a href="InventItemBatchEntity.md" target="_blank">InventoryAndWarehouseManagement/InventItemBatchEntity</a>|
|[AreBatchAttributesInherited](#AreBatchAttributesInherited)||<a href="InventItemBatchEntity.md" target="_blank">InventoryAndWarehouseManagement/InventItemBatchEntity</a>|
|[AreShelfLifeDatesInherited](#AreShelfLifeDatesInherited)||<a href="InventItemBatchEntity.md" target="_blank">InventoryAndWarehouseManagement/InventItemBatchEntity</a>|
|[IsBatchConsolidated](#IsBatchConsolidated)||<a href="InventItemBatchEntity.md" target="_blank">InventoryAndWarehouseManagement/InventItemBatchEntity</a>|
|[ShelfLifeAdviceDate](#ShelfLifeAdviceDate)||<a href="InventItemBatchEntity.md" target="_blank">InventoryAndWarehouseManagement/InventItemBatchEntity</a>|
|[IsManufacturingDateVendorBatchDate](#IsManufacturingDateVendorBatchDate)||<a href="InventItemBatchEntity.md" target="_blank">InventoryAndWarehouseManagement/InventItemBatchEntity</a>|
|[IsExpirationDateVendorExpirationDate](#IsExpirationDateVendorExpirationDate)||<a href="InventItemBatchEntity.md" target="_blank">InventoryAndWarehouseManagement/InventItemBatchEntity</a>|
|[VendorBatchDate](#VendorBatchDate)||<a href="InventItemBatchEntity.md" target="_blank">InventoryAndWarehouseManagement/InventItemBatchEntity</a>|
|[VendorBatchNumber](#VendorBatchNumber)||<a href="InventItemBatchEntity.md" target="_blank">InventoryAndWarehouseManagement/InventItemBatchEntity</a>|
|[VendorExpirationDate](#VendorExpirationDate)||<a href="InventItemBatchEntity.md" target="_blank">InventoryAndWarehouseManagement/InventItemBatchEntity</a>|
|[ManufacturingDate](#ManufacturingDate)||<a href="InventItemBatchEntity.md" target="_blank">InventoryAndWarehouseManagement/InventItemBatchEntity</a>|
|[Relationship_ReleasedProductRelationshipId](#Relationship_ReleasedProductRelationshipId)||<a href="InventItemBatchEntity.md" target="_blank">InventoryAndWarehouseManagement/InventItemBatchEntity</a>|
|[Relationship_BatchDispositionRelationshipId](#Relationship_BatchDispositionRelationshipId)||<a href="InventItemBatchEntity.md" target="_blank">InventoryAndWarehouseManagement/InventItemBatchEntity</a>|
|[Relationship_PrimaryVendorOriginCountryRegionRelationshipId](#Relationship_PrimaryVendorOriginCountryRegionRelationshipId)||<a href="InventItemBatchEntity.md" target="_blank">InventoryAndWarehouseManagement/InventItemBatchEntity</a>|
|[Relationship_SecondaryVendorOriginCountryRegionRelationshipId](#Relationship_SecondaryVendorOriginCountryRegionRelationshipId)||<a href="InventItemBatchEntity.md" target="_blank">InventoryAndWarehouseManagement/InventItemBatchEntity</a>|
|[BackingTable_InventBatchRelationshipId](#BackingTable_InventBatchRelationshipId)||<a href="InventItemBatchEntity.md" target="_blank">InventoryAndWarehouseManagement/InventItemBatchEntity</a>|
|[Relationship_PrimaryCompanyContextRelationshipId](#Relationship_PrimaryCompanyContextRelationshipId)||<a href="InventItemBatchEntity.md" target="_blank">InventoryAndWarehouseManagement/InventItemBatchEntity</a>|

### <a href=#BatchDescription name="BatchDescription">BatchDescription</a>

First included in: InventoryAndWarehouseManagement/InventItemBatchEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BatchDescription attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BatchExpirationDate name="BatchExpirationDate">BatchExpirationDate</a>

First included in: InventoryAndWarehouseManagement/InventItemBatchEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BatchExpirationDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BatchNumber name="BatchNumber">BatchNumber</a>

First included in: InventoryAndWarehouseManagement/InventItemBatchEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BatchNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ItemNumber name="ItemNumber">ItemNumber</a>

First included in: InventoryAndWarehouseManagement/InventItemBatchEntity (this entity)  

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

### <a href=#BestBeforeDate name="BestBeforeDate">BestBeforeDate</a>

First included in: InventoryAndWarehouseManagement/InventItemBatchEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BestBeforeDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PrimaryVendorOriginCountryRegionId name="PrimaryVendorOriginCountryRegionId">PrimaryVendorOriginCountryRegionId</a>

First included in: InventoryAndWarehouseManagement/InventItemBatchEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrimaryVendorOriginCountryRegionId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SecondaryVendorOriginCountryRegionId name="SecondaryVendorOriginCountryRegionId">SecondaryVendorOriginCountryRegionId</a>

First included in: InventoryAndWarehouseManagement/InventItemBatchEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SecondaryVendorOriginCountryRegionId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BatchDispositionCode name="BatchDispositionCode">BatchDispositionCode</a>

First included in: InventoryAndWarehouseManagement/InventItemBatchEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BatchDispositionCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MostRecentTestDate name="MostRecentTestDate">MostRecentTestDate</a>

First included in: InventoryAndWarehouseManagement/InventItemBatchEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MostRecentTestDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AreBatchAttributesInherited name="AreBatchAttributesInherited">AreBatchAttributesInherited</a>

First included in: InventoryAndWarehouseManagement/InventItemBatchEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AreBatchAttributesInherited attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AreShelfLifeDatesInherited name="AreShelfLifeDatesInherited">AreShelfLifeDatesInherited</a>

First included in: InventoryAndWarehouseManagement/InventItemBatchEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AreShelfLifeDatesInherited attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsBatchConsolidated name="IsBatchConsolidated">IsBatchConsolidated</a>

First included in: InventoryAndWarehouseManagement/InventItemBatchEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsBatchConsolidated attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ShelfLifeAdviceDate name="ShelfLifeAdviceDate">ShelfLifeAdviceDate</a>

First included in: InventoryAndWarehouseManagement/InventItemBatchEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ShelfLifeAdviceDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsManufacturingDateVendorBatchDate name="IsManufacturingDateVendorBatchDate">IsManufacturingDateVendorBatchDate</a>

First included in: InventoryAndWarehouseManagement/InventItemBatchEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsManufacturingDateVendorBatchDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsExpirationDateVendorExpirationDate name="IsExpirationDateVendorExpirationDate">IsExpirationDateVendorExpirationDate</a>

First included in: InventoryAndWarehouseManagement/InventItemBatchEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsExpirationDateVendorExpirationDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#VendorBatchDate name="VendorBatchDate">VendorBatchDate</a>

First included in: InventoryAndWarehouseManagement/InventItemBatchEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VendorBatchDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#VendorBatchNumber name="VendorBatchNumber">VendorBatchNumber</a>

First included in: InventoryAndWarehouseManagement/InventItemBatchEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VendorBatchNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#VendorExpirationDate name="VendorExpirationDate">VendorExpirationDate</a>

First included in: InventoryAndWarehouseManagement/InventItemBatchEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VendorExpirationDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ManufacturingDate name="ManufacturingDate">ManufacturingDate</a>

First included in: InventoryAndWarehouseManagement/InventItemBatchEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ManufacturingDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_ReleasedProductRelationshipId name="Relationship_ReleasedProductRelationshipId">Relationship_ReleasedProductRelationshipId</a>

First included in: InventoryAndWarehouseManagement/InventItemBatchEntity (this entity)  

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

### <a href=#Relationship_BatchDispositionRelationshipId name="Relationship_BatchDispositionRelationshipId">Relationship_BatchDispositionRelationshipId</a>

First included in: InventoryAndWarehouseManagement/InventItemBatchEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_BatchDispositionRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_PrimaryVendorOriginCountryRegionRelationshipId name="Relationship_PrimaryVendorOriginCountryRegionRelationshipId">Relationship_PrimaryVendorOriginCountryRegionRelationshipId</a>

First included in: InventoryAndWarehouseManagement/InventItemBatchEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_PrimaryVendorOriginCountryRegionRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_SecondaryVendorOriginCountryRegionRelationshipId name="Relationship_SecondaryVendorOriginCountryRegionRelationshipId">Relationship_SecondaryVendorOriginCountryRegionRelationshipId</a>

First included in: InventoryAndWarehouseManagement/InventItemBatchEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_SecondaryVendorOriginCountryRegionRelationshipId attribute are listed below.</summary>

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

### <a href=#BackingTable_InventBatchRelationshipId name="BackingTable_InventBatchRelationshipId">BackingTable_InventBatchRelationshipId</a>

First included in: InventoryAndWarehouseManagement/InventItemBatchEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_InventBatchRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/SupplyChain/Inventory/WorksheetHeader/InventBatch.md" target="_blank">/core/erp/Tables/SupplyChain/Inventory/WorksheetHeader/InventBatch.cdm.json/InventBatch</a></td><td><a href="../../../Tables/SupplyChain/Inventory/WorksheetHeader/InventBatch.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PrimaryCompanyContextRelationshipId name="Relationship_PrimaryCompanyContextRelationshipId">Relationship_PrimaryCompanyContextRelationshipId</a>

First included in: InventoryAndWarehouseManagement/InventItemBatchEntity (this entity)  

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
