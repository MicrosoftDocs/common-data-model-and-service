---
title: PdsBatchDispositionEntity - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 5/5/2020
ms.author: nebanfic
---

# Batch dispositions

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/SupplyChain/InventoryAndWarehouseManagement/PdsBatchDispositionEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Batch dispositions</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[DispositionCode](#DispositionCode)||<a href="PdsBatchDispositionEntity.md" target="_blank">InventoryAndWarehouseManagement/PdsBatchDispositionEntity</a>|
|[DispositionDescription](#DispositionDescription)||<a href="PdsBatchDispositionEntity.md" target="_blank">InventoryAndWarehouseManagement/PdsBatchDispositionEntity</a>|
|[DispositionStatus](#DispositionStatus)||<a href="PdsBatchDispositionEntity.md" target="_blank">InventoryAndWarehouseManagement/PdsBatchDispositionEntity</a>|
|[WillNetRequirementCalculationIncludeBatches](#WillNetRequirementCalculationIncludeBatches)||<a href="PdsBatchDispositionEntity.md" target="_blank">InventoryAndWarehouseManagement/PdsBatchDispositionEntity</a>|
|[WillBlockProductionPicking](#WillBlockProductionPicking)||<a href="PdsBatchDispositionEntity.md" target="_blank">InventoryAndWarehouseManagement/PdsBatchDispositionEntity</a>|
|[WillBlockProductionPickingJournal](#WillBlockProductionPickingJournal)||<a href="PdsBatchDispositionEntity.md" target="_blank">InventoryAndWarehouseManagement/PdsBatchDispositionEntity</a>|
|[WillBlockProductionReservation](#WillBlockProductionReservation)||<a href="PdsBatchDispositionEntity.md" target="_blank">InventoryAndWarehouseManagement/PdsBatchDispositionEntity</a>|
|[WillBlockSalesPicking](#WillBlockSalesPicking)||<a href="PdsBatchDispositionEntity.md" target="_blank">InventoryAndWarehouseManagement/PdsBatchDispositionEntity</a>|
|[WillBlockSalesReservation](#WillBlockSalesReservation)||<a href="PdsBatchDispositionEntity.md" target="_blank">InventoryAndWarehouseManagement/PdsBatchDispositionEntity</a>|
|[WillBlockSalesShipping](#WillBlockSalesShipping)||<a href="PdsBatchDispositionEntity.md" target="_blank">InventoryAndWarehouseManagement/PdsBatchDispositionEntity</a>|
|[WillBlockTransferPicking](#WillBlockTransferPicking)||<a href="PdsBatchDispositionEntity.md" target="_blank">InventoryAndWarehouseManagement/PdsBatchDispositionEntity</a>|
|[WillBlockTransferReservation](#WillBlockTransferReservation)||<a href="PdsBatchDispositionEntity.md" target="_blank">InventoryAndWarehouseManagement/PdsBatchDispositionEntity</a>|
|[WillBlockTransferShipping](#WillBlockTransferShipping)||<a href="PdsBatchDispositionEntity.md" target="_blank">InventoryAndWarehouseManagement/PdsBatchDispositionEntity</a>|
|[BackingTable_PdsDispositionMasterRelationshipId](#BackingTable_PdsDispositionMasterRelationshipId)||<a href="PdsBatchDispositionEntity.md" target="_blank">InventoryAndWarehouseManagement/PdsBatchDispositionEntity</a>|
|[Relationship_PrimaryCompanyContextRelationshipId](#Relationship_PrimaryCompanyContextRelationshipId)||<a href="PdsBatchDispositionEntity.md" target="_blank">InventoryAndWarehouseManagement/PdsBatchDispositionEntity</a>|

### <a href=#DispositionCode name="DispositionCode">DispositionCode</a>

First included in: InventoryAndWarehouseManagement/PdsBatchDispositionEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DispositionCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DispositionDescription name="DispositionDescription">DispositionDescription</a>

First included in: InventoryAndWarehouseManagement/PdsBatchDispositionEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DispositionDescription attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DispositionStatus name="DispositionStatus">DispositionStatus</a>

First included in: InventoryAndWarehouseManagement/PdsBatchDispositionEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DispositionStatus attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WillNetRequirementCalculationIncludeBatches name="WillNetRequirementCalculationIncludeBatches">WillNetRequirementCalculationIncludeBatches</a>

First included in: InventoryAndWarehouseManagement/PdsBatchDispositionEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WillNetRequirementCalculationIncludeBatches attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WillBlockProductionPicking name="WillBlockProductionPicking">WillBlockProductionPicking</a>

First included in: InventoryAndWarehouseManagement/PdsBatchDispositionEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WillBlockProductionPicking attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WillBlockProductionPickingJournal name="WillBlockProductionPickingJournal">WillBlockProductionPickingJournal</a>

First included in: InventoryAndWarehouseManagement/PdsBatchDispositionEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WillBlockProductionPickingJournal attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WillBlockProductionReservation name="WillBlockProductionReservation">WillBlockProductionReservation</a>

First included in: InventoryAndWarehouseManagement/PdsBatchDispositionEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WillBlockProductionReservation attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WillBlockSalesPicking name="WillBlockSalesPicking">WillBlockSalesPicking</a>

First included in: InventoryAndWarehouseManagement/PdsBatchDispositionEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WillBlockSalesPicking attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WillBlockSalesReservation name="WillBlockSalesReservation">WillBlockSalesReservation</a>

First included in: InventoryAndWarehouseManagement/PdsBatchDispositionEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WillBlockSalesReservation attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WillBlockSalesShipping name="WillBlockSalesShipping">WillBlockSalesShipping</a>

First included in: InventoryAndWarehouseManagement/PdsBatchDispositionEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WillBlockSalesShipping attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WillBlockTransferPicking name="WillBlockTransferPicking">WillBlockTransferPicking</a>

First included in: InventoryAndWarehouseManagement/PdsBatchDispositionEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WillBlockTransferPicking attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WillBlockTransferReservation name="WillBlockTransferReservation">WillBlockTransferReservation</a>

First included in: InventoryAndWarehouseManagement/PdsBatchDispositionEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WillBlockTransferReservation attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WillBlockTransferShipping name="WillBlockTransferShipping">WillBlockTransferShipping</a>

First included in: InventoryAndWarehouseManagement/PdsBatchDispositionEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WillBlockTransferShipping attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BackingTable_PdsDispositionMasterRelationshipId name="BackingTable_PdsDispositionMasterRelationshipId">BackingTable_PdsDispositionMasterRelationshipId</a>

First included in: InventoryAndWarehouseManagement/PdsBatchDispositionEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_PdsDispositionMasterRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/SupplyChain/Inventory/Group/PdsDispositionMaster.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/Inventory/Group/PdsDispositionMaster.cdm.json/PdsDispositionMaster</a></td><td><a href="../../../Tables/SupplyChain/Inventory/Group/PdsDispositionMaster.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PrimaryCompanyContextRelationshipId name="Relationship_PrimaryCompanyContextRelationshipId">Relationship_PrimaryCompanyContextRelationshipId</a>

First included in: InventoryAndWarehouseManagement/PdsBatchDispositionEntity (this entity)  

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
