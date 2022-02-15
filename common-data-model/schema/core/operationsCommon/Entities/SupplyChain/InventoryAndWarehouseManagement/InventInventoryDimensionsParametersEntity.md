---
title: InventInventoryDimensionsParametersEntity in InventoryAndWarehouseManagement - Common Data Model | Microsoft Docs
description: undefined
author: llawwaii

ms.reviewer: deonhe
ms.topic: article
ms.date: 8/7/2020
ms.author: weiluo
---

# Inventory dimensions parameters in InventoryAndWarehouseManagement(InventInventoryDimensionsParametersEntity)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/SupplyChain/InventoryAndWarehouseManagement/InventInventoryDimensionsParametersEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.1"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Inventory dimensions parameters</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[InventoryDimensionName](#InventoryDimensionName)||<a href="InventInventoryDimensionsParametersEntity.md" target="_blank">InventoryAndWarehouseManagement/InventInventoryDimensionsParametersEntity</a>|
|[IsSalesOrderLineGridDisplayingDimensionByDefault](#IsSalesOrderLineGridDisplayingDimensionByDefault)||<a href="InventInventoryDimensionsParametersEntity.md" target="_blank">InventoryAndWarehouseManagement/InventInventoryDimensionsParametersEntity</a>|
|[IsSalesQuotationLineGridDisplayingDimensionByDefault](#IsSalesQuotationLineGridDisplayingDimensionByDefault)||<a href="InventInventoryDimensionsParametersEntity.md" target="_blank">InventoryAndWarehouseManagement/InventInventoryDimensionsParametersEntity</a>|
|[IsInventoryMovementJournalLineGridDisplayingDimensionByDefault](#IsInventoryMovementJournalLineGridDisplayingDimensionByDefault)||<a href="InventInventoryDimensionsParametersEntity.md" target="_blank">InventoryAndWarehouseManagement/InventInventoryDimensionsParametersEntity</a>|
|[IsInventoryAdjustmentJournalLineGridDisplayingDimensionByDefault](#IsInventoryAdjustmentJournalLineGridDisplayingDimensionByDefault)||<a href="InventInventoryDimensionsParametersEntity.md" target="_blank">InventoryAndWarehouseManagement/InventInventoryDimensionsParametersEntity</a>|
|[IsInventoryTransferJournalLineGridDisplayingDimensionByDefault](#IsInventoryTransferJournalLineGridDisplayingDimensionByDefault)||<a href="InventInventoryDimensionsParametersEntity.md" target="_blank">InventoryAndWarehouseManagement/InventInventoryDimensionsParametersEntity</a>|
|[IsInventoryCountingJournalLineGridDisplayingDimensionByDefault](#IsInventoryCountingJournalLineGridDisplayingDimensionByDefault)||<a href="InventInventoryDimensionsParametersEntity.md" target="_blank">InventoryAndWarehouseManagement/InventInventoryDimensionsParametersEntity</a>|
|[IsBillOfMaterialsLineGridDisplayingDimensionByDefault](#IsBillOfMaterialsLineGridDisplayingDimensionByDefault)||<a href="InventInventoryDimensionsParametersEntity.md" target="_blank">InventoryAndWarehouseManagement/InventInventoryDimensionsParametersEntity</a>|
|[IsInventoryTransactionGridDisplayingDimensionByDefault](#IsInventoryTransactionGridDisplayingDimensionByDefault)||<a href="InventInventoryDimensionsParametersEntity.md" target="_blank">InventoryAndWarehouseManagement/InventInventoryDimensionsParametersEntity</a>|
|[IsTransferOrderLineGridDisplayingDimensionByDefault](#IsTransferOrderLineGridDisplayingDimensionByDefault)||<a href="InventInventoryDimensionsParametersEntity.md" target="_blank">InventoryAndWarehouseManagement/InventInventoryDimensionsParametersEntity</a>|
|[IsQuarantineOrderGridDisplayingDimensionByDefault](#IsQuarantineOrderGridDisplayingDimensionByDefault)||<a href="InventInventoryDimensionsParametersEntity.md" target="_blank">InventoryAndWarehouseManagement/InventInventoryDimensionsParametersEntity</a>|
|[IsQualityOrderGridDisplayingDimensionByDefault](#IsQualityOrderGridDisplayingDimensionByDefault)||<a href="InventInventoryDimensionsParametersEntity.md" target="_blank">InventoryAndWarehouseManagement/InventInventoryDimensionsParametersEntity</a>|
|[IsNonConformanceGridDisplayingDimensionByDefault](#IsNonConformanceGridDisplayingDimensionByDefault)||<a href="InventInventoryDimensionsParametersEntity.md" target="_blank">InventoryAndWarehouseManagement/InventInventoryDimensionsParametersEntity</a>|
|[IsCertificateOfAnalysisGridDisplayingDimensionByDefault](#IsCertificateOfAnalysisGridDisplayingDimensionByDefault)||<a href="InventInventoryDimensionsParametersEntity.md" target="_blank">InventoryAndWarehouseManagement/InventInventoryDimensionsParametersEntity</a>|
|[IsInventoryBlockingGridDisplayingDimensionByDefault](#IsInventoryBlockingGridDisplayingDimensionByDefault)||<a href="InventInventoryDimensionsParametersEntity.md" target="_blank">InventoryAndWarehouseManagement/InventInventoryDimensionsParametersEntity</a>|
|[IsItemArrivalJournalLineGridDisplayingDimensionByDefault](#IsItemArrivalJournalLineGridDisplayingDimensionByDefault)||<a href="InventInventoryDimensionsParametersEntity.md" target="_blank">InventoryAndWarehouseManagement/InventInventoryDimensionsParametersEntity</a>|
|[IsProductionInputJournalLineGridDisplayingDimensionByDefault](#IsProductionInputJournalLineGridDisplayingDimensionByDefault)||<a href="InventInventoryDimensionsParametersEntity.md" target="_blank">InventoryAndWarehouseManagement/InventInventoryDimensionsParametersEntity</a>|
|[IsWarehousePickingLineGridDisplayingDimensionByDefault](#IsWarehousePickingLineGridDisplayingDimensionByDefault)||<a href="InventInventoryDimensionsParametersEntity.md" target="_blank">InventoryAndWarehouseManagement/InventInventoryDimensionsParametersEntity</a>|
|[IsInventoryFixedAssetTransferJournalLineGridDisplayingDimensionByDefault](#IsInventoryFixedAssetTransferJournalLineGridDisplayingDimensionByDefault)||<a href="InventInventoryDimensionsParametersEntity.md" target="_blank">InventoryAndWarehouseManagement/InventInventoryDimensionsParametersEntity</a>|
|[IsProductionOrderGridDisplayingDimensionByDefault](#IsProductionOrderGridDisplayingDimensionByDefault)||<a href="InventInventoryDimensionsParametersEntity.md" target="_blank">InventoryAndWarehouseManagement/InventInventoryDimensionsParametersEntity</a>|
|[IsProductionOrderLineGridDisplayingDimensionByDefault](#IsProductionOrderLineGridDisplayingDimensionByDefault)||<a href="InventInventoryDimensionsParametersEntity.md" target="_blank">InventoryAndWarehouseManagement/InventInventoryDimensionsParametersEntity</a>|
|[IsProductionPickingListJournalLineGridDisplayingDimensionByDefault](#IsProductionPickingListJournalLineGridDisplayingDimensionByDefault)||<a href="InventInventoryDimensionsParametersEntity.md" target="_blank">InventoryAndWarehouseManagement/InventInventoryDimensionsParametersEntity</a>|
|[IsProductionReportedAsFinishedJournalLineGridDisplayingDimensionByDefault](#IsProductionReportedAsFinishedJournalLineGridDisplayingDimensionByDefault)||<a href="InventInventoryDimensionsParametersEntity.md" target="_blank">InventoryAndWarehouseManagement/InventInventoryDimensionsParametersEntity</a>|
|[IsByProductJournalLineGridDisplayingDimensionByDefault](#IsByProductJournalLineGridDisplayingDimensionByDefault)||<a href="InventInventoryDimensionsParametersEntity.md" target="_blank">InventoryAndWarehouseManagement/InventInventoryDimensionsParametersEntity</a>|
|[IsInventoryProjectConsumptionJournalGridDisplayingDimensionByDefault](#IsInventoryProjectConsumptionJournalGridDisplayingDimensionByDefault)||<a href="InventInventoryDimensionsParametersEntity.md" target="_blank">InventoryAndWarehouseManagement/InventInventoryDimensionsParametersEntity</a>|
|[IsProjectQuotationLineGridDisplayingDimensionByDefault](#IsProjectQuotationLineGridDisplayingDimensionByDefault)||<a href="InventInventoryDimensionsParametersEntity.md" target="_blank">InventoryAndWarehouseManagement/InventInventoryDimensionsParametersEntity</a>|
|[IsPurchaseOrderLineGridDisplayingDimensionByDefault](#IsPurchaseOrderLineGridDisplayingDimensionByDefault)||<a href="InventInventoryDimensionsParametersEntity.md" target="_blank">InventoryAndWarehouseManagement/InventInventoryDimensionsParametersEntity</a>|
|[dimFieldId](#dimFieldId)||<a href="InventInventoryDimensionsParametersEntity.md" target="_blank">InventoryAndWarehouseManagement/InventInventoryDimensionsParametersEntity</a>|
|[IsConsignmentReplenishmentOrderLineGridDisplayingDimensionByDefault](#IsConsignmentReplenishmentOrderLineGridDisplayingDimensionByDefault)||<a href="InventInventoryDimensionsParametersEntity.md" target="_blank">InventoryAndWarehouseManagement/InventInventoryDimensionsParametersEntity</a>|
|[IsInventoryOwnershipChangeLineGridDisplayingDimensionByDefault](#IsInventoryOwnershipChangeLineGridDisplayingDimensionByDefault)||<a href="InventInventoryDimensionsParametersEntity.md" target="_blank">InventoryAndWarehouseManagement/InventInventoryDimensionsParametersEntity</a>|
|[BackingTable_InventDimSetupGridRelationshipId](#BackingTable_InventDimSetupGridRelationshipId)||<a href="InventInventoryDimensionsParametersEntity.md" target="_blank">InventoryAndWarehouseManagement/InventInventoryDimensionsParametersEntity</a>|
|[Relationship_PrimaryCompanyContextRelationshipId](#Relationship_PrimaryCompanyContextRelationshipId)||<a href="InventInventoryDimensionsParametersEntity.md" target="_blank">InventoryAndWarehouseManagement/InventInventoryDimensionsParametersEntity</a>|

### <a href=#InventoryDimensionName name="InventoryDimensionName">InventoryDimensionName</a>

First included in: InventoryAndWarehouseManagement/InventInventoryDimensionsParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InventoryDimensionName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsSalesOrderLineGridDisplayingDimensionByDefault name="IsSalesOrderLineGridDisplayingDimensionByDefault">IsSalesOrderLineGridDisplayingDimensionByDefault</a>

First included in: InventoryAndWarehouseManagement/InventInventoryDimensionsParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsSalesOrderLineGridDisplayingDimensionByDefault attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsSalesQuotationLineGridDisplayingDimensionByDefault name="IsSalesQuotationLineGridDisplayingDimensionByDefault">IsSalesQuotationLineGridDisplayingDimensionByDefault</a>

First included in: InventoryAndWarehouseManagement/InventInventoryDimensionsParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsSalesQuotationLineGridDisplayingDimensionByDefault attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsInventoryMovementJournalLineGridDisplayingDimensionByDefault name="IsInventoryMovementJournalLineGridDisplayingDimensionByDefault">IsInventoryMovementJournalLineGridDisplayingDimensionByDefault</a>

First included in: InventoryAndWarehouseManagement/InventInventoryDimensionsParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsInventoryMovementJournalLineGridDisplayingDimensionByDefault attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsInventoryAdjustmentJournalLineGridDisplayingDimensionByDefault name="IsInventoryAdjustmentJournalLineGridDisplayingDimensionByDefault">IsInventoryAdjustmentJournalLineGridDisplayingDimensionByDefault</a>

First included in: InventoryAndWarehouseManagement/InventInventoryDimensionsParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsInventoryAdjustmentJournalLineGridDisplayingDimensionByDefault attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsInventoryTransferJournalLineGridDisplayingDimensionByDefault name="IsInventoryTransferJournalLineGridDisplayingDimensionByDefault">IsInventoryTransferJournalLineGridDisplayingDimensionByDefault</a>

First included in: InventoryAndWarehouseManagement/InventInventoryDimensionsParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsInventoryTransferJournalLineGridDisplayingDimensionByDefault attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsInventoryCountingJournalLineGridDisplayingDimensionByDefault name="IsInventoryCountingJournalLineGridDisplayingDimensionByDefault">IsInventoryCountingJournalLineGridDisplayingDimensionByDefault</a>

First included in: InventoryAndWarehouseManagement/InventInventoryDimensionsParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsInventoryCountingJournalLineGridDisplayingDimensionByDefault attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsBillOfMaterialsLineGridDisplayingDimensionByDefault name="IsBillOfMaterialsLineGridDisplayingDimensionByDefault">IsBillOfMaterialsLineGridDisplayingDimensionByDefault</a>

First included in: InventoryAndWarehouseManagement/InventInventoryDimensionsParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsBillOfMaterialsLineGridDisplayingDimensionByDefault attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsInventoryTransactionGridDisplayingDimensionByDefault name="IsInventoryTransactionGridDisplayingDimensionByDefault">IsInventoryTransactionGridDisplayingDimensionByDefault</a>

First included in: InventoryAndWarehouseManagement/InventInventoryDimensionsParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsInventoryTransactionGridDisplayingDimensionByDefault attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsTransferOrderLineGridDisplayingDimensionByDefault name="IsTransferOrderLineGridDisplayingDimensionByDefault">IsTransferOrderLineGridDisplayingDimensionByDefault</a>

First included in: InventoryAndWarehouseManagement/InventInventoryDimensionsParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsTransferOrderLineGridDisplayingDimensionByDefault attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsQuarantineOrderGridDisplayingDimensionByDefault name="IsQuarantineOrderGridDisplayingDimensionByDefault">IsQuarantineOrderGridDisplayingDimensionByDefault</a>

First included in: InventoryAndWarehouseManagement/InventInventoryDimensionsParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsQuarantineOrderGridDisplayingDimensionByDefault attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsQualityOrderGridDisplayingDimensionByDefault name="IsQualityOrderGridDisplayingDimensionByDefault">IsQualityOrderGridDisplayingDimensionByDefault</a>

First included in: InventoryAndWarehouseManagement/InventInventoryDimensionsParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsQualityOrderGridDisplayingDimensionByDefault attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsNonConformanceGridDisplayingDimensionByDefault name="IsNonConformanceGridDisplayingDimensionByDefault">IsNonConformanceGridDisplayingDimensionByDefault</a>

First included in: InventoryAndWarehouseManagement/InventInventoryDimensionsParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsNonConformanceGridDisplayingDimensionByDefault attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsCertificateOfAnalysisGridDisplayingDimensionByDefault name="IsCertificateOfAnalysisGridDisplayingDimensionByDefault">IsCertificateOfAnalysisGridDisplayingDimensionByDefault</a>

First included in: InventoryAndWarehouseManagement/InventInventoryDimensionsParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsCertificateOfAnalysisGridDisplayingDimensionByDefault attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsInventoryBlockingGridDisplayingDimensionByDefault name="IsInventoryBlockingGridDisplayingDimensionByDefault">IsInventoryBlockingGridDisplayingDimensionByDefault</a>

First included in: InventoryAndWarehouseManagement/InventInventoryDimensionsParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsInventoryBlockingGridDisplayingDimensionByDefault attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsItemArrivalJournalLineGridDisplayingDimensionByDefault name="IsItemArrivalJournalLineGridDisplayingDimensionByDefault">IsItemArrivalJournalLineGridDisplayingDimensionByDefault</a>

First included in: InventoryAndWarehouseManagement/InventInventoryDimensionsParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsItemArrivalJournalLineGridDisplayingDimensionByDefault attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsProductionInputJournalLineGridDisplayingDimensionByDefault name="IsProductionInputJournalLineGridDisplayingDimensionByDefault">IsProductionInputJournalLineGridDisplayingDimensionByDefault</a>

First included in: InventoryAndWarehouseManagement/InventInventoryDimensionsParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsProductionInputJournalLineGridDisplayingDimensionByDefault attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsWarehousePickingLineGridDisplayingDimensionByDefault name="IsWarehousePickingLineGridDisplayingDimensionByDefault">IsWarehousePickingLineGridDisplayingDimensionByDefault</a>

First included in: InventoryAndWarehouseManagement/InventInventoryDimensionsParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsWarehousePickingLineGridDisplayingDimensionByDefault attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsInventoryFixedAssetTransferJournalLineGridDisplayingDimensionByDefault name="IsInventoryFixedAssetTransferJournalLineGridDisplayingDimensionByDefault">IsInventoryFixedAssetTransferJournalLineGridDisplayingDimensionByDefault</a>

First included in: InventoryAndWarehouseManagement/InventInventoryDimensionsParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsInventoryFixedAssetTransferJournalLineGridDisplayingDimensionByDefault attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsProductionOrderGridDisplayingDimensionByDefault name="IsProductionOrderGridDisplayingDimensionByDefault">IsProductionOrderGridDisplayingDimensionByDefault</a>

First included in: InventoryAndWarehouseManagement/InventInventoryDimensionsParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsProductionOrderGridDisplayingDimensionByDefault attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsProductionOrderLineGridDisplayingDimensionByDefault name="IsProductionOrderLineGridDisplayingDimensionByDefault">IsProductionOrderLineGridDisplayingDimensionByDefault</a>

First included in: InventoryAndWarehouseManagement/InventInventoryDimensionsParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsProductionOrderLineGridDisplayingDimensionByDefault attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsProductionPickingListJournalLineGridDisplayingDimensionByDefault name="IsProductionPickingListJournalLineGridDisplayingDimensionByDefault">IsProductionPickingListJournalLineGridDisplayingDimensionByDefault</a>

First included in: InventoryAndWarehouseManagement/InventInventoryDimensionsParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsProductionPickingListJournalLineGridDisplayingDimensionByDefault attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsProductionReportedAsFinishedJournalLineGridDisplayingDimensionByDefault name="IsProductionReportedAsFinishedJournalLineGridDisplayingDimensionByDefault">IsProductionReportedAsFinishedJournalLineGridDisplayingDimensionByDefault</a>

First included in: InventoryAndWarehouseManagement/InventInventoryDimensionsParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsProductionReportedAsFinishedJournalLineGridDisplayingDimensionByDefault attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsByProductJournalLineGridDisplayingDimensionByDefault name="IsByProductJournalLineGridDisplayingDimensionByDefault">IsByProductJournalLineGridDisplayingDimensionByDefault</a>

First included in: InventoryAndWarehouseManagement/InventInventoryDimensionsParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsByProductJournalLineGridDisplayingDimensionByDefault attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsInventoryProjectConsumptionJournalGridDisplayingDimensionByDefault name="IsInventoryProjectConsumptionJournalGridDisplayingDimensionByDefault">IsInventoryProjectConsumptionJournalGridDisplayingDimensionByDefault</a>

First included in: InventoryAndWarehouseManagement/InventInventoryDimensionsParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsInventoryProjectConsumptionJournalGridDisplayingDimensionByDefault attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsProjectQuotationLineGridDisplayingDimensionByDefault name="IsProjectQuotationLineGridDisplayingDimensionByDefault">IsProjectQuotationLineGridDisplayingDimensionByDefault</a>

First included in: InventoryAndWarehouseManagement/InventInventoryDimensionsParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsProjectQuotationLineGridDisplayingDimensionByDefault attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsPurchaseOrderLineGridDisplayingDimensionByDefault name="IsPurchaseOrderLineGridDisplayingDimensionByDefault">IsPurchaseOrderLineGridDisplayingDimensionByDefault</a>

First included in: InventoryAndWarehouseManagement/InventInventoryDimensionsParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsPurchaseOrderLineGridDisplayingDimensionByDefault attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#dimFieldId name="dimFieldId">dimFieldId</a>

First included in: InventoryAndWarehouseManagement/InventInventoryDimensionsParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the dimFieldId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsConsignmentReplenishmentOrderLineGridDisplayingDimensionByDefault name="IsConsignmentReplenishmentOrderLineGridDisplayingDimensionByDefault">IsConsignmentReplenishmentOrderLineGridDisplayingDimensionByDefault</a>

First included in: InventoryAndWarehouseManagement/InventInventoryDimensionsParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsConsignmentReplenishmentOrderLineGridDisplayingDimensionByDefault attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsInventoryOwnershipChangeLineGridDisplayingDimensionByDefault name="IsInventoryOwnershipChangeLineGridDisplayingDimensionByDefault">IsInventoryOwnershipChangeLineGridDisplayingDimensionByDefault</a>

First included in: InventoryAndWarehouseManagement/InventInventoryDimensionsParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsInventoryOwnershipChangeLineGridDisplayingDimensionByDefault attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BackingTable_InventDimSetupGridRelationshipId name="BackingTable_InventDimSetupGridRelationshipId">BackingTable_InventDimSetupGridRelationshipId</a>

First included in: InventoryAndWarehouseManagement/InventInventoryDimensionsParametersEntity (this entity)  

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

First included in: InventoryAndWarehouseManagement/InventInventoryDimensionsParametersEntity (this entity)  

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
