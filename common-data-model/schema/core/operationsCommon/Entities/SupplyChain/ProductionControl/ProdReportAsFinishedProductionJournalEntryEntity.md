---
title: ProdReportAsFinishedProductionJournalEntryEntity in ProductionControl - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 7/20/2020
ms.author: nebanfic
---

# Report as finished production journal entries in ProductionControl(ProdReportAsFinishedProductionJournalEntryEntity)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/SupplyChain/ProductionControl/ProdReportAsFinishedProductionJournalEntryEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Report as finished production journal entries</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[ErrorCause](#ErrorCause)||<a href="ProdReportAsFinishedProductionJournalEntryEntity.md" target="_blank">ProductionControl/ProdReportAsFinishedProductionJournalEntryEntity</a>|
|[InventDimId](#InventDimId)||<a href="ProdReportAsFinishedProductionJournalEntryEntity.md" target="_blank">ProductionControl/ProdReportAsFinishedProductionJournalEntryEntity</a>|
|[IsReceiptReturned](#IsReceiptReturned)||<a href="ProdReportAsFinishedProductionJournalEntryEntity.md" target="_blank">ProductionControl/ProdReportAsFinishedProductionJournalEntryEntity</a>|
|[InventoryLotId](#InventoryLotId)||<a href="ProdReportAsFinishedProductionJournalEntryEntity.md" target="_blank">ProductionControl/ProdReportAsFinishedProductionJournalEntryEntity</a>|
|[ItemNumber](#ItemNumber)||<a href="ProdReportAsFinishedProductionJournalEntryEntity.md" target="_blank">ProductionControl/ProdReportAsFinishedProductionJournalEntryEntity</a>|
|[JournalLineNumber](#JournalLineNumber)||<a href="ProdReportAsFinishedProductionJournalEntryEntity.md" target="_blank">ProductionControl/ProdReportAsFinishedProductionJournalEntryEntity</a>|
|[ReportedErrorCatchWeightQuantity](#ReportedErrorCatchWeightQuantity)||<a href="ProdReportAsFinishedProductionJournalEntryEntity.md" target="_blank">ProductionControl/ProdReportAsFinishedProductionJournalEntryEntity</a>|
|[ReportedGoodCatchWeightQuantity](#ReportedGoodCatchWeightQuantity)||<a href="ProdReportAsFinishedProductionJournalEntryEntity.md" target="_blank">ProductionControl/ProdReportAsFinishedProductionJournalEntryEntity</a>|
|[WillAsFinishedPostingAcceptQuantityError](#WillAsFinishedPostingAcceptQuantityError)||<a href="ProdReportAsFinishedProductionJournalEntryEntity.md" target="_blank">ProductionControl/ProdReportAsFinishedProductionJournalEntryEntity</a>|
|[ProductionType](#ProductionType)||<a href="ProdReportAsFinishedProductionJournalEntryEntity.md" target="_blank">ProductionControl/ProdReportAsFinishedProductionJournalEntryEntity</a>|
|[IsLastReportAsFinished](#IsLastReportAsFinished)||<a href="ProdReportAsFinishedProductionJournalEntryEntity.md" target="_blank">ProductionControl/ProdReportAsFinishedProductionJournalEntryEntity</a>|
|[ProductionOrderNumber](#ProductionOrderNumber)||<a href="ProdReportAsFinishedProductionJournalEntryEntity.md" target="_blank">ProductionControl/ProdReportAsFinishedProductionJournalEntryEntity</a>|
|[WillReportAsFinishedPostingAutomaticallyPostPickingList](#WillReportAsFinishedPostingAutomaticallyPostPickingList)||<a href="ProdReportAsFinishedProductionJournalEntryEntity.md" target="_blank">ProductionControl/ProdReportAsFinishedProductionJournalEntryEntity</a>|
|[ProductionPickingListJournalNumber](#ProductionPickingListJournalNumber)||<a href="ProdReportAsFinishedProductionJournalEntryEntity.md" target="_blank">ProductionControl/ProdReportAsFinishedProductionJournalEntryEntity</a>|
|[ReportedErrorInventoryQuantity](#ReportedErrorInventoryQuantity)||<a href="ProdReportAsFinishedProductionJournalEntryEntity.md" target="_blank">ProductionControl/ProdReportAsFinishedProductionJournalEntryEntity</a>|
|[ReportedGoodInventoryQuantity](#ReportedGoodInventoryQuantity)||<a href="ProdReportAsFinishedProductionJournalEntryEntity.md" target="_blank">ProductionControl/ProdReportAsFinishedProductionJournalEntryEntity</a>|
|[ReportAsFinishedDate](#ReportAsFinishedDate)||<a href="ProdReportAsFinishedProductionJournalEntryEntity.md" target="_blank">ProductionControl/ProdReportAsFinishedProductionJournalEntryEntity</a>|
|[VoucherNumber](#VoucherNumber)||<a href="ProdReportAsFinishedProductionJournalEntryEntity.md" target="_blank">ProductionControl/ProdReportAsFinishedProductionJournalEntryEntity</a>|
|[IsPosted](#IsPosted)||<a href="ProdReportAsFinishedProductionJournalEntryEntity.md" target="_blank">ProductionControl/ProdReportAsFinishedProductionJournalEntryEntity</a>|
|[PostedDateTime](#PostedDateTime)||<a href="ProdReportAsFinishedProductionJournalEntryEntity.md" target="_blank">ProductionControl/ProdReportAsFinishedProductionJournalEntryEntity</a>|
|[PostedUserId](#PostedUserId)||<a href="ProdReportAsFinishedProductionJournalEntryEntity.md" target="_blank">ProductionControl/ProdReportAsFinishedProductionJournalEntryEntity</a>|
|[JournalName](#JournalName)||<a href="ProdReportAsFinishedProductionJournalEntryEntity.md" target="_blank">ProductionControl/ProdReportAsFinishedProductionJournalEntryEntity</a>|
|[JournalDescription](#JournalDescription)||<a href="ProdReportAsFinishedProductionJournalEntryEntity.md" target="_blank">ProductionControl/ProdReportAsFinishedProductionJournalEntryEntity</a>|
|[ProductConfigurationId](#ProductConfigurationId)||<a href="ProdReportAsFinishedProductionJournalEntryEntity.md" target="_blank">ProductionControl/ProdReportAsFinishedProductionJournalEntryEntity</a>|
|[ItemBatchNumber](#ItemBatchNumber)||<a href="ProdReportAsFinishedProductionJournalEntryEntity.md" target="_blank">ProductionControl/ProdReportAsFinishedProductionJournalEntryEntity</a>|
|[ProductColorId](#ProductColorId)||<a href="ProdReportAsFinishedProductionJournalEntryEntity.md" target="_blank">ProductionControl/ProdReportAsFinishedProductionJournalEntryEntity</a>|
|[WarehouseId](#WarehouseId)||<a href="ProdReportAsFinishedProductionJournalEntryEntity.md" target="_blank">ProductionControl/ProdReportAsFinishedProductionJournalEntryEntity</a>|
|[InventoryOwnerId](#InventoryOwnerId)||<a href="ProdReportAsFinishedProductionJournalEntryEntity.md" target="_blank">ProductionControl/ProdReportAsFinishedProductionJournalEntryEntity</a>|
|[ItemSerialNumber](#ItemSerialNumber)||<a href="ProdReportAsFinishedProductionJournalEntryEntity.md" target="_blank">ProductionControl/ProdReportAsFinishedProductionJournalEntryEntity</a>|
|[ProductionSiteId](#ProductionSiteId)||<a href="ProdReportAsFinishedProductionJournalEntryEntity.md" target="_blank">ProductionControl/ProdReportAsFinishedProductionJournalEntryEntity</a>|
|[ReceivedInventoryStatusId](#ReceivedInventoryStatusId)||<a href="ProdReportAsFinishedProductionJournalEntryEntity.md" target="_blank">ProductionControl/ProdReportAsFinishedProductionJournalEntryEntity</a>|
|[ProductSizeId](#ProductSizeId)||<a href="ProdReportAsFinishedProductionJournalEntryEntity.md" target="_blank">ProductionControl/ProdReportAsFinishedProductionJournalEntryEntity</a>|
|[ProductStyleId](#ProductStyleId)||<a href="ProdReportAsFinishedProductionJournalEntryEntity.md" target="_blank">ProductionControl/ProdReportAsFinishedProductionJournalEntryEntity</a>|
|[LicensePlateNumber](#LicensePlateNumber)||<a href="ProdReportAsFinishedProductionJournalEntryEntity.md" target="_blank">ProductionControl/ProdReportAsFinishedProductionJournalEntryEntity</a>|
|[JournalNumber](#JournalNumber)||<a href="ProdReportAsFinishedProductionJournalEntryEntity.md" target="_blank">ProductionControl/ProdReportAsFinishedProductionJournalEntryEntity</a>|
|[Relationship_ProductionOrderHeaderRelationshipId](#Relationship_ProductionOrderHeaderRelationshipId)||<a href="ProdReportAsFinishedProductionJournalEntryEntity.md" target="_blank">ProductionControl/ProdReportAsFinishedProductionJournalEntryEntity</a>|
|[Relationship_ProductionJournalNameRelationshipId](#Relationship_ProductionJournalNameRelationshipId)||<a href="ProdReportAsFinishedProductionJournalEntryEntity.md" target="_blank">ProductionControl/ProdReportAsFinishedProductionJournalEntryEntity</a>|
|[Relationship_ProductColorRelationshipId](#Relationship_ProductColorRelationshipId)||<a href="ProdReportAsFinishedProductionJournalEntryEntity.md" target="_blank">ProductionControl/ProdReportAsFinishedProductionJournalEntryEntity</a>|
|[Relationship_ProductConfigurationRelationshipId](#Relationship_ProductConfigurationRelationshipId)||<a href="ProdReportAsFinishedProductionJournalEntryEntity.md" target="_blank">ProductionControl/ProdReportAsFinishedProductionJournalEntryEntity</a>|
|[Relationship_ProductSizeRelationshipId](#Relationship_ProductSizeRelationshipId)||<a href="ProdReportAsFinishedProductionJournalEntryEntity.md" target="_blank">ProductionControl/ProdReportAsFinishedProductionJournalEntryEntity</a>|
|[Relationship_ProductStyleRelationshipId](#Relationship_ProductStyleRelationshipId)||<a href="ProdReportAsFinishedProductionJournalEntryEntity.md" target="_blank">ProductionControl/ProdReportAsFinishedProductionJournalEntryEntity</a>|
|[Relationship_ItemBatchRelationshipId](#Relationship_ItemBatchRelationshipId)||<a href="ProdReportAsFinishedProductionJournalEntryEntity.md" target="_blank">ProductionControl/ProdReportAsFinishedProductionJournalEntryEntity</a>|
|[Relationship_ReceivedInventoryStatusRelationshipId](#Relationship_ReceivedInventoryStatusRelationshipId)||<a href="ProdReportAsFinishedProductionJournalEntryEntity.md" target="_blank">ProductionControl/ProdReportAsFinishedProductionJournalEntryEntity</a>|
|[Relationship_WarehouseRelationshipId](#Relationship_WarehouseRelationshipId)||<a href="ProdReportAsFinishedProductionJournalEntryEntity.md" target="_blank">ProductionControl/ProdReportAsFinishedProductionJournalEntryEntity</a>|
|[Relationship_ProductionSiteRelationshipId](#Relationship_ProductionSiteRelationshipId)||<a href="ProdReportAsFinishedProductionJournalEntryEntity.md" target="_blank">ProductionControl/ProdReportAsFinishedProductionJournalEntryEntity</a>|
|[Relationship_ReleasedProductV2RelationshipId](#Relationship_ReleasedProductV2RelationshipId)||<a href="ProdReportAsFinishedProductionJournalEntryEntity.md" target="_blank">ProductionControl/ProdReportAsFinishedProductionJournalEntryEntity</a>|
|[BackingTable_ProdJournalProdRelationshipId](#BackingTable_ProdJournalProdRelationshipId)||<a href="ProdReportAsFinishedProductionJournalEntryEntity.md" target="_blank">ProductionControl/ProdReportAsFinishedProductionJournalEntryEntity</a>|
|[Relationship_PrimaryCompanyContextRelationshipId](#Relationship_PrimaryCompanyContextRelationshipId)||<a href="ProdReportAsFinishedProductionJournalEntryEntity.md" target="_blank">ProductionControl/ProdReportAsFinishedProductionJournalEntryEntity</a>|

### <a href=#ErrorCause name="ErrorCause">ErrorCause</a>

First included in: ProductionControl/ProdReportAsFinishedProductionJournalEntryEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ErrorCause attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InventDimId name="InventDimId">InventDimId</a>

First included in: ProductionControl/ProdReportAsFinishedProductionJournalEntryEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InventDimId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsReceiptReturned name="IsReceiptReturned">IsReceiptReturned</a>

First included in: ProductionControl/ProdReportAsFinishedProductionJournalEntryEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsReceiptReturned attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InventoryLotId name="InventoryLotId">InventoryLotId</a>

First included in: ProductionControl/ProdReportAsFinishedProductionJournalEntryEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InventoryLotId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ItemNumber name="ItemNumber">ItemNumber</a>

First included in: ProductionControl/ProdReportAsFinishedProductionJournalEntryEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ItemNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#JournalLineNumber name="JournalLineNumber">JournalLineNumber</a>

First included in: ProductionControl/ProdReportAsFinishedProductionJournalEntryEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the JournalLineNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ReportedErrorCatchWeightQuantity name="ReportedErrorCatchWeightQuantity">ReportedErrorCatchWeightQuantity</a>

First included in: ProductionControl/ProdReportAsFinishedProductionJournalEntryEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReportedErrorCatchWeightQuantity attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ReportedGoodCatchWeightQuantity name="ReportedGoodCatchWeightQuantity">ReportedGoodCatchWeightQuantity</a>

First included in: ProductionControl/ProdReportAsFinishedProductionJournalEntryEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReportedGoodCatchWeightQuantity attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WillAsFinishedPostingAcceptQuantityError name="WillAsFinishedPostingAcceptQuantityError">WillAsFinishedPostingAcceptQuantityError</a>

First included in: ProductionControl/ProdReportAsFinishedProductionJournalEntryEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WillAsFinishedPostingAcceptQuantityError attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProductionType name="ProductionType">ProductionType</a>

First included in: ProductionControl/ProdReportAsFinishedProductionJournalEntryEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProductionType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsLastReportAsFinished name="IsLastReportAsFinished">IsLastReportAsFinished</a>

First included in: ProductionControl/ProdReportAsFinishedProductionJournalEntryEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsLastReportAsFinished attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProductionOrderNumber name="ProductionOrderNumber">ProductionOrderNumber</a>

First included in: ProductionControl/ProdReportAsFinishedProductionJournalEntryEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProductionOrderNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WillReportAsFinishedPostingAutomaticallyPostPickingList name="WillReportAsFinishedPostingAutomaticallyPostPickingList">WillReportAsFinishedPostingAutomaticallyPostPickingList</a>

First included in: ProductionControl/ProdReportAsFinishedProductionJournalEntryEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WillReportAsFinishedPostingAutomaticallyPostPickingList attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProductionPickingListJournalNumber name="ProductionPickingListJournalNumber">ProductionPickingListJournalNumber</a>

First included in: ProductionControl/ProdReportAsFinishedProductionJournalEntryEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProductionPickingListJournalNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ReportedErrorInventoryQuantity name="ReportedErrorInventoryQuantity">ReportedErrorInventoryQuantity</a>

First included in: ProductionControl/ProdReportAsFinishedProductionJournalEntryEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReportedErrorInventoryQuantity attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ReportedGoodInventoryQuantity name="ReportedGoodInventoryQuantity">ReportedGoodInventoryQuantity</a>

First included in: ProductionControl/ProdReportAsFinishedProductionJournalEntryEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReportedGoodInventoryQuantity attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ReportAsFinishedDate name="ReportAsFinishedDate">ReportAsFinishedDate</a>

First included in: ProductionControl/ProdReportAsFinishedProductionJournalEntryEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReportAsFinishedDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#VoucherNumber name="VoucherNumber">VoucherNumber</a>

First included in: ProductionControl/ProdReportAsFinishedProductionJournalEntryEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VoucherNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsPosted name="IsPosted">IsPosted</a>

First included in: ProductionControl/ProdReportAsFinishedProductionJournalEntryEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsPosted attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PostedDateTime name="PostedDateTime">PostedDateTime</a>

First included in: ProductionControl/ProdReportAsFinishedProductionJournalEntryEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PostedDateTime attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PostedUserId name="PostedUserId">PostedUserId</a>

First included in: ProductionControl/ProdReportAsFinishedProductionJournalEntryEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PostedUserId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#JournalName name="JournalName">JournalName</a>

First included in: ProductionControl/ProdReportAsFinishedProductionJournalEntryEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the JournalName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#JournalDescription name="JournalDescription">JournalDescription</a>

First included in: ProductionControl/ProdReportAsFinishedProductionJournalEntryEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the JournalDescription attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProductConfigurationId name="ProductConfigurationId">ProductConfigurationId</a>

First included in: ProductionControl/ProdReportAsFinishedProductionJournalEntryEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProductConfigurationId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ItemBatchNumber name="ItemBatchNumber">ItemBatchNumber</a>

First included in: ProductionControl/ProdReportAsFinishedProductionJournalEntryEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ItemBatchNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProductColorId name="ProductColorId">ProductColorId</a>

First included in: ProductionControl/ProdReportAsFinishedProductionJournalEntryEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProductColorId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WarehouseId name="WarehouseId">WarehouseId</a>

First included in: ProductionControl/ProdReportAsFinishedProductionJournalEntryEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WarehouseId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InventoryOwnerId name="InventoryOwnerId">InventoryOwnerId</a>

First included in: ProductionControl/ProdReportAsFinishedProductionJournalEntryEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InventoryOwnerId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ItemSerialNumber name="ItemSerialNumber">ItemSerialNumber</a>

First included in: ProductionControl/ProdReportAsFinishedProductionJournalEntryEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ItemSerialNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProductionSiteId name="ProductionSiteId">ProductionSiteId</a>

First included in: ProductionControl/ProdReportAsFinishedProductionJournalEntryEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProductionSiteId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ReceivedInventoryStatusId name="ReceivedInventoryStatusId">ReceivedInventoryStatusId</a>

First included in: ProductionControl/ProdReportAsFinishedProductionJournalEntryEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReceivedInventoryStatusId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProductSizeId name="ProductSizeId">ProductSizeId</a>

First included in: ProductionControl/ProdReportAsFinishedProductionJournalEntryEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProductSizeId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProductStyleId name="ProductStyleId">ProductStyleId</a>

First included in: ProductionControl/ProdReportAsFinishedProductionJournalEntryEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProductStyleId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LicensePlateNumber name="LicensePlateNumber">LicensePlateNumber</a>

First included in: ProductionControl/ProdReportAsFinishedProductionJournalEntryEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LicensePlateNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#JournalNumber name="JournalNumber">JournalNumber</a>

First included in: ProductionControl/ProdReportAsFinishedProductionJournalEntryEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the JournalNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_ProductionOrderHeaderRelationshipId name="Relationship_ProductionOrderHeaderRelationshipId">Relationship_ProductionOrderHeaderRelationshipId</a>

First included in: ProductionControl/ProdReportAsFinishedProductionJournalEntryEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_ProductionOrderHeaderRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_ProductionJournalNameRelationshipId name="Relationship_ProductionJournalNameRelationshipId">Relationship_ProductionJournalNameRelationshipId</a>

First included in: ProductionControl/ProdReportAsFinishedProductionJournalEntryEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_ProductionJournalNameRelationshipId attribute are listed below.</summary>

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

First included in: ProductionControl/ProdReportAsFinishedProductionJournalEntryEntity (this entity)  

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

### <a href=#Relationship_ProductConfigurationRelationshipId name="Relationship_ProductConfigurationRelationshipId">Relationship_ProductConfigurationRelationshipId</a>

First included in: ProductionControl/ProdReportAsFinishedProductionJournalEntryEntity (this entity)  

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

### <a href=#Relationship_ProductSizeRelationshipId name="Relationship_ProductSizeRelationshipId">Relationship_ProductSizeRelationshipId</a>

First included in: ProductionControl/ProdReportAsFinishedProductionJournalEntryEntity (this entity)  

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

First included in: ProductionControl/ProdReportAsFinishedProductionJournalEntryEntity (this entity)  

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

### <a href=#Relationship_ItemBatchRelationshipId name="Relationship_ItemBatchRelationshipId">Relationship_ItemBatchRelationshipId</a>

First included in: ProductionControl/ProdReportAsFinishedProductionJournalEntryEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_ItemBatchRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_ReceivedInventoryStatusRelationshipId name="Relationship_ReceivedInventoryStatusRelationshipId">Relationship_ReceivedInventoryStatusRelationshipId</a>

First included in: ProductionControl/ProdReportAsFinishedProductionJournalEntryEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_ReceivedInventoryStatusRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_WarehouseRelationshipId name="Relationship_WarehouseRelationshipId">Relationship_WarehouseRelationshipId</a>

First included in: ProductionControl/ProdReportAsFinishedProductionJournalEntryEntity (this entity)  

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

### <a href=#Relationship_ProductionSiteRelationshipId name="Relationship_ProductionSiteRelationshipId">Relationship_ProductionSiteRelationshipId</a>

First included in: ProductionControl/ProdReportAsFinishedProductionJournalEntryEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_ProductionSiteRelationshipId attribute are listed below.</summary>

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

First included in: ProductionControl/ProdReportAsFinishedProductionJournalEntryEntity (this entity)  

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

### <a href=#BackingTable_ProdJournalProdRelationshipId name="BackingTable_ProdJournalProdRelationshipId">BackingTable_ProdJournalProdRelationshipId</a>

First included in: ProductionControl/ProdReportAsFinishedProductionJournalEntryEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_ProdJournalProdRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/SupplyChain/ProductionControl/WorksheetLine/ProdJournalProd.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/ProductionControl/WorksheetLine/ProdJournalProd.cdm.json/ProdJournalProd</a></td><td><a href="../../../Tables/SupplyChain/ProductionControl/WorksheetLine/ProdJournalProd.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PrimaryCompanyContextRelationshipId name="Relationship_PrimaryCompanyContextRelationshipId">Relationship_PrimaryCompanyContextRelationshipId</a>

First included in: ProductionControl/ProdReportAsFinishedProductionJournalEntryEntity (this entity)  

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
