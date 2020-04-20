---
title: InventDimSetupGridEntity - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/20/2020
ms.author: nebanfic
---

# InventDimSetupGridEntity

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/SupplyChain/InventoryAndWarehouseManagement/InventDimSetupGridEntity.cdm.json" target="_blank">GitHub</a>.  

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
|[FieldID](#FieldID)||<a href="InventDimSetupGridEntity.md" target="_blank">InventoryAndWarehouseManagement/InventDimSetupGridEntity</a>|
|[OrderEvent](#OrderEvent)||<a href="InventDimSetupGridEntity.md" target="_blank">InventoryAndWarehouseManagement/InventDimSetupGridEntity</a>|
|[PickingWorkbenchBatch](#PickingWorkbenchBatch)||<a href="InventDimSetupGridEntity.md" target="_blank">InventoryAndWarehouseManagement/InventDimSetupGridEntity</a>|
|[ProdBOMRAF](#ProdBOMRAF)||<a href="InventDimSetupGridEntity.md" target="_blank">InventoryAndWarehouseManagement/InventDimSetupGridEntity</a>|
|[ShipmentItem](#ShipmentItem)||<a href="InventDimSetupGridEntity.md" target="_blank">InventoryAndWarehouseManagement/InventDimSetupGridEntity</a>|
|[ShowGridAsset](#ShowGridAsset)||<a href="InventDimSetupGridEntity.md" target="_blank">InventoryAndWarehouseManagement/InventDimSetupGridEntity</a>|
|[BillsOfMaterials](#BillsOfMaterials)||<a href="InventDimSetupGridEntity.md" target="_blank">InventoryAndWarehouseManagement/InventDimSetupGridEntity</a>|
|[CertificateOfAnalysis](#CertificateOfAnalysis)||<a href="InventDimSetupGridEntity.md" target="_blank">InventoryAndWarehouseManagement/InventDimSetupGridEntity</a>|
|[InventoryBlocking](#InventoryBlocking)||<a href="InventDimSetupGridEntity.md" target="_blank">InventoryAndWarehouseManagement/InventDimSetupGridEntity</a>|
|[Counting](#Counting)||<a href="InventDimSetupGridEntity.md" target="_blank">InventoryAndWarehouseManagement/InventDimSetupGridEntity</a>|
|[InventoryAdjustment](#InventoryAdjustment)||<a href="InventDimSetupGridEntity.md" target="_blank">InventoryAndWarehouseManagement/InventDimSetupGridEntity</a>|
|[QuarantineOrders](#QuarantineOrders)||<a href="InventDimSetupGridEntity.md" target="_blank">InventoryAndWarehouseManagement/InventDimSetupGridEntity</a>|
|[InventoryTransactions](#InventoryTransactions)||<a href="InventDimSetupGridEntity.md" target="_blank">InventoryAndWarehouseManagement/InventDimSetupGridEntity</a>|
|[Movement](#Movement)||<a href="InventDimSetupGridEntity.md" target="_blank">InventoryAndWarehouseManagement/InventDimSetupGridEntity</a>|
|[Transfers](#Transfers)||<a href="InventDimSetupGridEntity.md" target="_blank">InventoryAndWarehouseManagement/InventDimSetupGridEntity</a>|
|[NonConformances](#NonConformances)||<a href="InventDimSetupGridEntity.md" target="_blank">InventoryAndWarehouseManagement/InventDimSetupGridEntity</a>|
|[ShowGridProdJournalBOM](#ShowGridProdJournalBOM)||<a href="InventDimSetupGridEntity.md" target="_blank">InventoryAndWarehouseManagement/InventDimSetupGridEntity</a>|
|[ShowGridProdJournalProduction](#ShowGridProdJournalProduction)||<a href="InventDimSetupGridEntity.md" target="_blank">InventoryAndWarehouseManagement/InventDimSetupGridEntity</a>|
|[ProductionLines](#ProductionLines)||<a href="InventDimSetupGridEntity.md" target="_blank">InventoryAndWarehouseManagement/InventDimSetupGridEntity</a>|
|[ProductionOrders](#ProductionOrders)||<a href="InventDimSetupGridEntity.md" target="_blank">InventoryAndWarehouseManagement/InventDimSetupGridEntity</a>|
|[ItemConsumption](#ItemConsumption)||<a href="InventDimSetupGridEntity.md" target="_blank">InventoryAndWarehouseManagement/InventDimSetupGridEntity</a>|
|[PurchaseOrderLines](#PurchaseOrderLines)||<a href="InventDimSetupGridEntity.md" target="_blank">InventoryAndWarehouseManagement/InventDimSetupGridEntity</a>|
|[QualityOrders](#QualityOrders)||<a href="InventDimSetupGridEntity.md" target="_blank">InventoryAndWarehouseManagement/InventDimSetupGridEntity</a>|
|[OrderLines](#OrderLines)||<a href="InventDimSetupGridEntity.md" target="_blank">InventoryAndWarehouseManagement/InventDimSetupGridEntity</a>|
|[QuotationLines](#QuotationLines)||<a href="InventDimSetupGridEntity.md" target="_blank">InventoryAndWarehouseManagement/InventDimSetupGridEntity</a>|
|[QuotationLinesProject](#QuotationLinesProject)||<a href="InventDimSetupGridEntity.md" target="_blank">InventoryAndWarehouseManagement/InventDimSetupGridEntity</a>|
|[TransferOrders](#TransferOrders)||<a href="InventDimSetupGridEntity.md" target="_blank">InventoryAndWarehouseManagement/InventDimSetupGridEntity</a>|
|[PickingLines](#PickingLines)||<a href="InventDimSetupGridEntity.md" target="_blank">InventoryAndWarehouseManagement/InventDimSetupGridEntity</a>|
|[ItemArrival](#ItemArrival)||<a href="InventDimSetupGridEntity.md" target="_blank">InventoryAndWarehouseManagement/InventDimSetupGridEntity</a>|
|[ProductionInput](#ProductionInput)||<a href="InventDimSetupGridEntity.md" target="_blank">InventoryAndWarehouseManagement/InventDimSetupGridEntity</a>|
|[InventoryOwnershipChange](#InventoryOwnershipChange)||<a href="InventDimSetupGridEntity.md" target="_blank">InventoryAndWarehouseManagement/InventDimSetupGridEntity</a>|
|[ConsignmentReplenishmentOrderLine](#ConsignmentReplenishmentOrderLine)||<a href="InventDimSetupGridEntity.md" target="_blank">InventoryAndWarehouseManagement/InventDimSetupGridEntity</a>|
|[BackingTable_InventDimSetupGridRelationshipId](#BackingTable_InventDimSetupGridRelationshipId)||<a href="InventDimSetupGridEntity.md" target="_blank">InventoryAndWarehouseManagement/InventDimSetupGridEntity</a>|
|[Relationship_PrimaryCompanyContextRelationshipId](#Relationship_PrimaryCompanyContextRelationshipId)||<a href="InventDimSetupGridEntity.md" target="_blank">InventoryAndWarehouseManagement/InventDimSetupGridEntity</a>|

### <a href=#FieldID name="FieldID">FieldID</a>

First included in: InventoryAndWarehouseManagement/InventDimSetupGridEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FieldID attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#OrderEvent name="OrderEvent">OrderEvent</a>

First included in: InventoryAndWarehouseManagement/InventDimSetupGridEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OrderEvent attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PickingWorkbenchBatch name="PickingWorkbenchBatch">PickingWorkbenchBatch</a>

First included in: InventoryAndWarehouseManagement/InventDimSetupGridEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PickingWorkbenchBatch attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProdBOMRAF name="ProdBOMRAF">ProdBOMRAF</a>

First included in: InventoryAndWarehouseManagement/InventDimSetupGridEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProdBOMRAF attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ShipmentItem name="ShipmentItem">ShipmentItem</a>

First included in: InventoryAndWarehouseManagement/InventDimSetupGridEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ShipmentItem attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ShowGridAsset name="ShowGridAsset">ShowGridAsset</a>

First included in: InventoryAndWarehouseManagement/InventDimSetupGridEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ShowGridAsset attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BillsOfMaterials name="BillsOfMaterials">BillsOfMaterials</a>

First included in: InventoryAndWarehouseManagement/InventDimSetupGridEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BillsOfMaterials attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CertificateOfAnalysis name="CertificateOfAnalysis">CertificateOfAnalysis</a>

First included in: InventoryAndWarehouseManagement/InventDimSetupGridEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CertificateOfAnalysis attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InventoryBlocking name="InventoryBlocking">InventoryBlocking</a>

First included in: InventoryAndWarehouseManagement/InventDimSetupGridEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InventoryBlocking attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Counting name="Counting">Counting</a>

First included in: InventoryAndWarehouseManagement/InventDimSetupGridEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Counting attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InventoryAdjustment name="InventoryAdjustment">InventoryAdjustment</a>

First included in: InventoryAndWarehouseManagement/InventDimSetupGridEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InventoryAdjustment attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#QuarantineOrders name="QuarantineOrders">QuarantineOrders</a>

First included in: InventoryAndWarehouseManagement/InventDimSetupGridEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the QuarantineOrders attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InventoryTransactions name="InventoryTransactions">InventoryTransactions</a>

First included in: InventoryAndWarehouseManagement/InventDimSetupGridEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InventoryTransactions attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Movement name="Movement">Movement</a>

First included in: InventoryAndWarehouseManagement/InventDimSetupGridEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Movement attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Transfers name="Transfers">Transfers</a>

First included in: InventoryAndWarehouseManagement/InventDimSetupGridEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Transfers attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#NonConformances name="NonConformances">NonConformances</a>

First included in: InventoryAndWarehouseManagement/InventDimSetupGridEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the NonConformances attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ShowGridProdJournalBOM name="ShowGridProdJournalBOM">ShowGridProdJournalBOM</a>

First included in: InventoryAndWarehouseManagement/InventDimSetupGridEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ShowGridProdJournalBOM attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ShowGridProdJournalProduction name="ShowGridProdJournalProduction">ShowGridProdJournalProduction</a>

First included in: InventoryAndWarehouseManagement/InventDimSetupGridEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ShowGridProdJournalProduction attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProductionLines name="ProductionLines">ProductionLines</a>

First included in: InventoryAndWarehouseManagement/InventDimSetupGridEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProductionLines attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProductionOrders name="ProductionOrders">ProductionOrders</a>

First included in: InventoryAndWarehouseManagement/InventDimSetupGridEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProductionOrders attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ItemConsumption name="ItemConsumption">ItemConsumption</a>

First included in: InventoryAndWarehouseManagement/InventDimSetupGridEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ItemConsumption attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PurchaseOrderLines name="PurchaseOrderLines">PurchaseOrderLines</a>

First included in: InventoryAndWarehouseManagement/InventDimSetupGridEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PurchaseOrderLines attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#QualityOrders name="QualityOrders">QualityOrders</a>

First included in: InventoryAndWarehouseManagement/InventDimSetupGridEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the QualityOrders attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#OrderLines name="OrderLines">OrderLines</a>

First included in: InventoryAndWarehouseManagement/InventDimSetupGridEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OrderLines attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#QuotationLines name="QuotationLines">QuotationLines</a>

First included in: InventoryAndWarehouseManagement/InventDimSetupGridEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the QuotationLines attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#QuotationLinesProject name="QuotationLinesProject">QuotationLinesProject</a>

First included in: InventoryAndWarehouseManagement/InventDimSetupGridEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the QuotationLinesProject attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TransferOrders name="TransferOrders">TransferOrders</a>

First included in: InventoryAndWarehouseManagement/InventDimSetupGridEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TransferOrders attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PickingLines name="PickingLines">PickingLines</a>

First included in: InventoryAndWarehouseManagement/InventDimSetupGridEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PickingLines attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ItemArrival name="ItemArrival">ItemArrival</a>

First included in: InventoryAndWarehouseManagement/InventDimSetupGridEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ItemArrival attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProductionInput name="ProductionInput">ProductionInput</a>

First included in: InventoryAndWarehouseManagement/InventDimSetupGridEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProductionInput attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InventoryOwnershipChange name="InventoryOwnershipChange">InventoryOwnershipChange</a>

First included in: InventoryAndWarehouseManagement/InventDimSetupGridEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InventoryOwnershipChange attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ConsignmentReplenishmentOrderLine name="ConsignmentReplenishmentOrderLine">ConsignmentReplenishmentOrderLine</a>

First included in: InventoryAndWarehouseManagement/InventDimSetupGridEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ConsignmentReplenishmentOrderLine attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BackingTable_InventDimSetupGridRelationshipId name="BackingTable_InventDimSetupGridRelationshipId">BackingTable_InventDimSetupGridRelationshipId</a>

First included in: InventoryAndWarehouseManagement/InventDimSetupGridEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_InventDimSetupGridRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/SupplyChain/Inventory/Parameter/InventDimSetupGrid.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/Inventory/Parameter/InventDimSetupGrid.cdm.json/InventDimSetupGrid</a></td><td><a href="../../../Tables/SupplyChain/Inventory/Parameter/InventDimSetupGrid.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PrimaryCompanyContextRelationshipId name="Relationship_PrimaryCompanyContextRelationshipId">Relationship_PrimaryCompanyContextRelationshipId</a>

First included in: InventoryAndWarehouseManagement/InventDimSetupGridEntity (this entity)  

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
