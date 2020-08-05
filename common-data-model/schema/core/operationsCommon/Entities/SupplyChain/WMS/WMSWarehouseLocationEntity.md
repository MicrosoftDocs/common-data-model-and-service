---
title: WMSWarehouseLocationEntity in WMS - Common Data Model | Microsoft Docs
description: undefined
author: llawwaii
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 8/5/2020
ms.author: weiluo
---

# Warehouse locations in WMS(WMSWarehouseLocationEntity)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/SupplyChain/WMS/WMSWarehouseLocationEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.1"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Warehouse locations</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[BinId](#BinId)||<a href="WMSWarehouseLocationEntity.md" target="_blank">WMS/WMSWarehouseLocationEntity</a>|
|[CheckDigits](#CheckDigits)||<a href="WMSWarehouseLocationEntity.md" target="_blank">WMS/WMSWarehouseLocationEntity</a>|
|[DestinationWarehouseLocationId](#DestinationWarehouseLocationId)||<a href="WMSWarehouseLocationEntity.md" target="_blank">WMS/WMSWarehouseLocationEntity</a>|
|[GenerateCheckDigits](#GenerateCheckDigits)||<a href="WMSWarehouseLocationEntity.md" target="_blank">WMS/WMSWarehouseLocationEntity</a>|
|[IsSortOrderCodeManual](#IsSortOrderCodeManual)||<a href="WMSWarehouseLocationEntity.md" target="_blank">WMS/WMSWarehouseLocationEntity</a>|
|[IsWarehouseLocationIdManual](#IsWarehouseLocationIdManual)||<a href="WMSWarehouseLocationEntity.md" target="_blank">WMS/WMSWarehouseLocationEntity</a>|
|[LastCountedUTCDateTime](#LastCountedUTCDateTime)||<a href="WMSWarehouseLocationEntity.md" target="_blank">WMS/WMSWarehouseLocationEntity</a>|
|[PhysicalDepth](#PhysicalDepth)||<a href="WMSWarehouseLocationEntity.md" target="_blank">WMS/WMSWarehouseLocationEntity</a>|
|[PhysicalHeight](#PhysicalHeight)||<a href="WMSWarehouseLocationEntity.md" target="_blank">WMS/WMSWarehouseLocationEntity</a>|
|[PhysicalHeightAboveGround](#PhysicalHeightAboveGround)||<a href="WMSWarehouseLocationEntity.md" target="_blank">WMS/WMSWarehouseLocationEntity</a>|
|[PhysicalMaximumStorageVolume](#PhysicalMaximumStorageVolume)||<a href="WMSWarehouseLocationEntity.md" target="_blank">WMS/WMSWarehouseLocationEntity</a>|
|[PhysicalMaximumStorageWeight](#PhysicalMaximumStorageWeight)||<a href="WMSWarehouseLocationEntity.md" target="_blank">WMS/WMSWarehouseLocationEntity</a>|
|[PhysicalWidth](#PhysicalWidth)||<a href="WMSWarehouseLocationEntity.md" target="_blank">WMS/WMSWarehouseLocationEntity</a>|
|[RackId](#RackId)||<a href="WMSWarehouseLocationEntity.md" target="_blank">WMS/WMSWarehouseLocationEntity</a>|
|[ShelfId](#ShelfId)||<a href="WMSWarehouseLocationEntity.md" target="_blank">WMS/WMSWarehouseLocationEntity</a>|
|[SortOrderCode](#SortOrderCode)||<a href="WMSWarehouseLocationEntity.md" target="_blank">WMS/WMSWarehouseLocationEntity</a>|
|[WarehouseAisleId](#WarehouseAisleId)||<a href="WMSWarehouseLocationEntity.md" target="_blank">WMS/WMSWarehouseLocationEntity</a>|
|[WarehouseId](#WarehouseId)||<a href="WMSWarehouseLocationEntity.md" target="_blank">WMS/WMSWarehouseLocationEntity</a>|
|[WarehouseLocationId](#WarehouseLocationId)||<a href="WMSWarehouseLocationEntity.md" target="_blank">WMS/WMSWarehouseLocationEntity</a>|
|[WarehouseLocationProfileId](#WarehouseLocationProfileId)||<a href="WMSWarehouseLocationEntity.md" target="_blank">WMS/WMSWarehouseLocationEntity</a>|
|[WarehouseLocationType](#WarehouseLocationType)||<a href="WMSWarehouseLocationEntity.md" target="_blank">WMS/WMSWarehouseLocationEntity</a>|
|[WarehouseZoneId](#WarehouseZoneId)||<a href="WMSWarehouseLocationEntity.md" target="_blank">WMS/WMSWarehouseLocationEntity</a>|
|[InputWarehouseLocationBlockingCauseId](#InputWarehouseLocationBlockingCauseId)||<a href="WMSWarehouseLocationEntity.md" target="_blank">WMS/WMSWarehouseLocationEntity</a>|
|[OutputWarehouseLocationBlockingCauseId](#OutputWarehouseLocationBlockingCauseId)||<a href="WMSWarehouseLocationEntity.md" target="_blank">WMS/WMSWarehouseLocationEntity</a>|
|[IsDefaultCreditOnlyReturnWarehouseLocation](#IsDefaultCreditOnlyReturnWarehouseLocation)||<a href="WMSWarehouseLocationEntity.md" target="_blank">WMS/WMSWarehouseLocationEntity</a>|
|[IsDefaultIssueWarehouseLocation](#IsDefaultIssueWarehouseLocation)||<a href="WMSWarehouseLocationEntity.md" target="_blank">WMS/WMSWarehouseLocationEntity</a>|
|[IsDefaultKanbanFinishedGoodsWarehouseLocation](#IsDefaultKanbanFinishedGoodsWarehouseLocation)||<a href="WMSWarehouseLocationEntity.md" target="_blank">WMS/WMSWarehouseLocationEntity</a>|
|[IsDefaultProductionFinishedGoodsWarehouseLocation](#IsDefaultProductionFinishedGoodsWarehouseLocation)||<a href="WMSWarehouseLocationEntity.md" target="_blank">WMS/WMSWarehouseLocationEntity</a>|
|[IsDefaultProductionInputWarehouseLocation](#IsDefaultProductionInputWarehouseLocation)||<a href="WMSWarehouseLocationEntity.md" target="_blank">WMS/WMSWarehouseLocationEntity</a>|
|[IsDefaultReceiptWarehouseLocation](#IsDefaultReceiptWarehouseLocation)||<a href="WMSWarehouseLocationEntity.md" target="_blank">WMS/WMSWarehouseLocationEntity</a>|
|[IsDefaultRetailStoreReturnWarehouseLocation](#IsDefaultRetailStoreReturnWarehouseLocation)||<a href="WMSWarehouseLocationEntity.md" target="_blank">WMS/WMSWarehouseLocationEntity</a>|
|[IsDefaultRetailStoreWarehouseLocation](#IsDefaultRetailStoreWarehouseLocation)||<a href="WMSWarehouseLocationEntity.md" target="_blank">WMS/WMSWarehouseLocationEntity</a>|
|[IsDefaultShipmentMaintenanceWarehouseLocation](#IsDefaultShipmentMaintenanceWarehouseLocation)||<a href="WMSWarehouseLocationEntity.md" target="_blank">WMS/WMSWarehouseLocationEntity</a>|
|[FirstAdditionalWarehouseZoneId](#FirstAdditionalWarehouseZoneId)||<a href="WMSWarehouseLocationEntity.md" target="_blank">WMS/WMSWarehouseLocationEntity</a>|
|[SecondAdditionalWarehouseZoneId](#SecondAdditionalWarehouseZoneId)||<a href="WMSWarehouseLocationEntity.md" target="_blank">WMS/WMSWarehouseLocationEntity</a>|
|[ThirdAdditionalWarehouseZoneId](#ThirdAdditionalWarehouseZoneId)||<a href="WMSWarehouseLocationEntity.md" target="_blank">WMS/WMSWarehouseLocationEntity</a>|
|[AgingDate](#AgingDate)||<a href="WMSWarehouseLocationEntity.md" target="_blank">WMS/WMSWarehouseLocationEntity</a>|
|[ItemNumberInLocation](#ItemNumberInLocation)||<a href="WMSWarehouseLocationEntity.md" target="_blank">WMS/WMSWarehouseLocationEntity</a>|
|[LastActivityDateTime](#LastActivityDateTime)||<a href="WMSWarehouseLocationEntity.md" target="_blank">WMS/WMSWarehouseLocationEntity</a>|
|[LocationStatus](#LocationStatus)||<a href="WMSWarehouseLocationEntity.md" target="_blank">WMS/WMSWarehouseLocationEntity</a>|
|[IsItemInLocationMaintained](#IsItemInLocationMaintained)||<a href="WMSWarehouseLocationEntity.md" target="_blank">WMS/WMSWarehouseLocationEntity</a>|
|[IsLocationActivityDateTimeMaintained](#IsLocationActivityDateTimeMaintained)||<a href="WMSWarehouseLocationEntity.md" target="_blank">WMS/WMSWarehouseLocationEntity</a>|
|[IsLocationStatusMaintained](#IsLocationStatusMaintained)||<a href="WMSWarehouseLocationEntity.md" target="_blank">WMS/WMSWarehouseLocationEntity</a>|
|[IsDefaultQualityMaintenanceWarehouseLocation](#IsDefaultQualityMaintenanceWarehouseLocation)||<a href="WMSWarehouseLocationEntity.md" target="_blank">WMS/WMSWarehouseLocationEntity</a>|
|[Relationship_InputWarehouseLocationBlockingCauseRelationshipId](#Relationship_InputWarehouseLocationBlockingCauseRelationshipId)||<a href="WMSWarehouseLocationEntity.md" target="_blank">WMS/WMSWarehouseLocationEntity</a>|
|[Relationship_OutputWarehouseLocationBlockingCauseRelationshipId](#Relationship_OutputWarehouseLocationBlockingCauseRelationshipId)||<a href="WMSWarehouseLocationEntity.md" target="_blank">WMS/WMSWarehouseLocationEntity</a>|
|[Relationship_WarehouseRelationshipId](#Relationship_WarehouseRelationshipId)||<a href="WMSWarehouseLocationEntity.md" target="_blank">WMS/WMSWarehouseLocationEntity</a>|
|[Relationship_WarehouseLocationProfileRelationshipId](#Relationship_WarehouseLocationProfileRelationshipId)||<a href="WMSWarehouseLocationEntity.md" target="_blank">WMS/WMSWarehouseLocationEntity</a>|
|[Relationship_WarehouseZoneRelationshipId](#Relationship_WarehouseZoneRelationshipId)||<a href="WMSWarehouseLocationEntity.md" target="_blank">WMS/WMSWarehouseLocationEntity</a>|
|[Relationship_WarehouseAisleRelationshipId](#Relationship_WarehouseAisleRelationshipId)||<a href="WMSWarehouseLocationEntity.md" target="_blank">WMS/WMSWarehouseLocationEntity</a>|
|[Relationship_WarehouseAdditionalZone1RelationshipId](#Relationship_WarehouseAdditionalZone1RelationshipId)||<a href="WMSWarehouseLocationEntity.md" target="_blank">WMS/WMSWarehouseLocationEntity</a>|
|[Relationship_WarehouseAdditionalZone2RelationshipId](#Relationship_WarehouseAdditionalZone2RelationshipId)||<a href="WMSWarehouseLocationEntity.md" target="_blank">WMS/WMSWarehouseLocationEntity</a>|
|[Relationship_WarehouseAdditionalZone3RelationshipId](#Relationship_WarehouseAdditionalZone3RelationshipId)||<a href="WMSWarehouseLocationEntity.md" target="_blank">WMS/WMSWarehouseLocationEntity</a>|
|[BackingTable_WMSLocationRelationshipId](#BackingTable_WMSLocationRelationshipId)||<a href="WMSWarehouseLocationEntity.md" target="_blank">WMS/WMSWarehouseLocationEntity</a>|
|[Relationship_PrimaryCompanyContextRelationshipId](#Relationship_PrimaryCompanyContextRelationshipId)||<a href="WMSWarehouseLocationEntity.md" target="_blank">WMS/WMSWarehouseLocationEntity</a>|

### <a href=#BinId name="BinId">BinId</a>

First included in: WMS/WMSWarehouseLocationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BinId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CheckDigits name="CheckDigits">CheckDigits</a>

First included in: WMS/WMSWarehouseLocationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CheckDigits attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DestinationWarehouseLocationId name="DestinationWarehouseLocationId">DestinationWarehouseLocationId</a>

First included in: WMS/WMSWarehouseLocationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DestinationWarehouseLocationId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#GenerateCheckDigits name="GenerateCheckDigits">GenerateCheckDigits</a>

First included in: WMS/WMSWarehouseLocationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the GenerateCheckDigits attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsSortOrderCodeManual name="IsSortOrderCodeManual">IsSortOrderCodeManual</a>

First included in: WMS/WMSWarehouseLocationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsSortOrderCodeManual attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsWarehouseLocationIdManual name="IsWarehouseLocationIdManual">IsWarehouseLocationIdManual</a>

First included in: WMS/WMSWarehouseLocationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsWarehouseLocationIdManual attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LastCountedUTCDateTime name="LastCountedUTCDateTime">LastCountedUTCDateTime</a>

First included in: WMS/WMSWarehouseLocationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LastCountedUTCDateTime attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PhysicalDepth name="PhysicalDepth">PhysicalDepth</a>

First included in: WMS/WMSWarehouseLocationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PhysicalDepth attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PhysicalHeight name="PhysicalHeight">PhysicalHeight</a>

First included in: WMS/WMSWarehouseLocationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PhysicalHeight attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PhysicalHeightAboveGround name="PhysicalHeightAboveGround">PhysicalHeightAboveGround</a>

First included in: WMS/WMSWarehouseLocationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PhysicalHeightAboveGround attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PhysicalMaximumStorageVolume name="PhysicalMaximumStorageVolume">PhysicalMaximumStorageVolume</a>

First included in: WMS/WMSWarehouseLocationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PhysicalMaximumStorageVolume attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PhysicalMaximumStorageWeight name="PhysicalMaximumStorageWeight">PhysicalMaximumStorageWeight</a>

First included in: WMS/WMSWarehouseLocationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PhysicalMaximumStorageWeight attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PhysicalWidth name="PhysicalWidth">PhysicalWidth</a>

First included in: WMS/WMSWarehouseLocationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PhysicalWidth attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RackId name="RackId">RackId</a>

First included in: WMS/WMSWarehouseLocationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RackId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ShelfId name="ShelfId">ShelfId</a>

First included in: WMS/WMSWarehouseLocationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ShelfId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SortOrderCode name="SortOrderCode">SortOrderCode</a>

First included in: WMS/WMSWarehouseLocationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SortOrderCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WarehouseAisleId name="WarehouseAisleId">WarehouseAisleId</a>

First included in: WMS/WMSWarehouseLocationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WarehouseAisleId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WarehouseId name="WarehouseId">WarehouseId</a>

First included in: WMS/WMSWarehouseLocationEntity (this entity)  

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

### <a href=#WarehouseLocationId name="WarehouseLocationId">WarehouseLocationId</a>

First included in: WMS/WMSWarehouseLocationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WarehouseLocationId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WarehouseLocationProfileId name="WarehouseLocationProfileId">WarehouseLocationProfileId</a>

First included in: WMS/WMSWarehouseLocationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WarehouseLocationProfileId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WarehouseLocationType name="WarehouseLocationType">WarehouseLocationType</a>

First included in: WMS/WMSWarehouseLocationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WarehouseLocationType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WarehouseZoneId name="WarehouseZoneId">WarehouseZoneId</a>

First included in: WMS/WMSWarehouseLocationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WarehouseZoneId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InputWarehouseLocationBlockingCauseId name="InputWarehouseLocationBlockingCauseId">InputWarehouseLocationBlockingCauseId</a>

First included in: WMS/WMSWarehouseLocationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InputWarehouseLocationBlockingCauseId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#OutputWarehouseLocationBlockingCauseId name="OutputWarehouseLocationBlockingCauseId">OutputWarehouseLocationBlockingCauseId</a>

First included in: WMS/WMSWarehouseLocationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OutputWarehouseLocationBlockingCauseId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsDefaultCreditOnlyReturnWarehouseLocation name="IsDefaultCreditOnlyReturnWarehouseLocation">IsDefaultCreditOnlyReturnWarehouseLocation</a>

First included in: WMS/WMSWarehouseLocationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Default location for credit only returns</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsDefaultCreditOnlyReturnWarehouseLocation attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Default location for credit only returns</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsDefaultIssueWarehouseLocation name="IsDefaultIssueWarehouseLocation">IsDefaultIssueWarehouseLocation</a>

First included in: WMS/WMSWarehouseLocationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Default issue location</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsDefaultIssueWarehouseLocation attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Default issue location</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsDefaultKanbanFinishedGoodsWarehouseLocation name="IsDefaultKanbanFinishedGoodsWarehouseLocation">IsDefaultKanbanFinishedGoodsWarehouseLocation</a>

First included in: WMS/WMSWarehouseLocationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Default kanban finished goods location</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsDefaultKanbanFinishedGoodsWarehouseLocation attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Default kanban finished goods location</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsDefaultProductionFinishedGoodsWarehouseLocation name="IsDefaultProductionFinishedGoodsWarehouseLocation">IsDefaultProductionFinishedGoodsWarehouseLocation</a>

First included in: WMS/WMSWarehouseLocationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Default production finished goods location</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsDefaultProductionFinishedGoodsWarehouseLocation attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Default production finished goods location</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsDefaultProductionInputWarehouseLocation name="IsDefaultProductionInputWarehouseLocation">IsDefaultProductionInputWarehouseLocation</a>

First included in: WMS/WMSWarehouseLocationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Default production input location</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsDefaultProductionInputWarehouseLocation attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Default production input location</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsDefaultReceiptWarehouseLocation name="IsDefaultReceiptWarehouseLocation">IsDefaultReceiptWarehouseLocation</a>

First included in: WMS/WMSWarehouseLocationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Default receipt location</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsDefaultReceiptWarehouseLocation attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Default receipt location</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsDefaultRetailStoreReturnWarehouseLocation name="IsDefaultRetailStoreReturnWarehouseLocation">IsDefaultRetailStoreReturnWarehouseLocation</a>

First included in: WMS/WMSWarehouseLocationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Default return location</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsDefaultRetailStoreReturnWarehouseLocation attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Default return location</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsDefaultRetailStoreWarehouseLocation name="IsDefaultRetailStoreWarehouseLocation">IsDefaultRetailStoreWarehouseLocation</a>

First included in: WMS/WMSWarehouseLocationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Default location</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsDefaultRetailStoreWarehouseLocation attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Default location</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsDefaultShipmentMaintenanceWarehouseLocation name="IsDefaultShipmentMaintenanceWarehouseLocation">IsDefaultShipmentMaintenanceWarehouseLocation</a>

First included in: WMS/WMSWarehouseLocationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Default shipment maintenance location</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsDefaultShipmentMaintenanceWarehouseLocation attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Default shipment maintenance location</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FirstAdditionalWarehouseZoneId name="FirstAdditionalWarehouseZoneId">FirstAdditionalWarehouseZoneId</a>

First included in: WMS/WMSWarehouseLocationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FirstAdditionalWarehouseZoneId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SecondAdditionalWarehouseZoneId name="SecondAdditionalWarehouseZoneId">SecondAdditionalWarehouseZoneId</a>

First included in: WMS/WMSWarehouseLocationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SecondAdditionalWarehouseZoneId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ThirdAdditionalWarehouseZoneId name="ThirdAdditionalWarehouseZoneId">ThirdAdditionalWarehouseZoneId</a>

First included in: WMS/WMSWarehouseLocationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ThirdAdditionalWarehouseZoneId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AgingDate name="AgingDate">AgingDate</a>

First included in: WMS/WMSWarehouseLocationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AgingDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ItemNumberInLocation name="ItemNumberInLocation">ItemNumberInLocation</a>

First included in: WMS/WMSWarehouseLocationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ItemNumberInLocation attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LastActivityDateTime name="LastActivityDateTime">LastActivityDateTime</a>

First included in: WMS/WMSWarehouseLocationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LastActivityDateTime attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LocationStatus name="LocationStatus">LocationStatus</a>

First included in: WMS/WMSWarehouseLocationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LocationStatus attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsItemInLocationMaintained name="IsItemInLocationMaintained">IsItemInLocationMaintained</a>

First included in: WMS/WMSWarehouseLocationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsItemInLocationMaintained attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsLocationActivityDateTimeMaintained name="IsLocationActivityDateTimeMaintained">IsLocationActivityDateTimeMaintained</a>

First included in: WMS/WMSWarehouseLocationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsLocationActivityDateTimeMaintained attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsLocationStatusMaintained name="IsLocationStatusMaintained">IsLocationStatusMaintained</a>

First included in: WMS/WMSWarehouseLocationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsLocationStatusMaintained attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsDefaultQualityMaintenanceWarehouseLocation name="IsDefaultQualityMaintenanceWarehouseLocation">IsDefaultQualityMaintenanceWarehouseLocation</a>

First included in: WMS/WMSWarehouseLocationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Default quality maintenance location</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsDefaultQualityMaintenanceWarehouseLocation attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Default quality maintenance location</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_InputWarehouseLocationBlockingCauseRelationshipId name="Relationship_InputWarehouseLocationBlockingCauseRelationshipId">Relationship_InputWarehouseLocationBlockingCauseRelationshipId</a>

First included in: WMS/WMSWarehouseLocationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_InputWarehouseLocationBlockingCauseRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_OutputWarehouseLocationBlockingCauseRelationshipId name="Relationship_OutputWarehouseLocationBlockingCauseRelationshipId">Relationship_OutputWarehouseLocationBlockingCauseRelationshipId</a>

First included in: WMS/WMSWarehouseLocationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_OutputWarehouseLocationBlockingCauseRelationshipId attribute are listed below.</summary>

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

First included in: WMS/WMSWarehouseLocationEntity (this entity)  

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

### <a href=#Relationship_WarehouseLocationProfileRelationshipId name="Relationship_WarehouseLocationProfileRelationshipId">Relationship_WarehouseLocationProfileRelationshipId</a>

First included in: WMS/WMSWarehouseLocationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_WarehouseLocationProfileRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_WarehouseZoneRelationshipId name="Relationship_WarehouseZoneRelationshipId">Relationship_WarehouseZoneRelationshipId</a>

First included in: WMS/WMSWarehouseLocationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_WarehouseZoneRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_WarehouseAisleRelationshipId name="Relationship_WarehouseAisleRelationshipId">Relationship_WarehouseAisleRelationshipId</a>

First included in: WMS/WMSWarehouseLocationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_WarehouseAisleRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_WarehouseAdditionalZone1RelationshipId name="Relationship_WarehouseAdditionalZone1RelationshipId">Relationship_WarehouseAdditionalZone1RelationshipId</a>

First included in: WMS/WMSWarehouseLocationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_WarehouseAdditionalZone1RelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_WarehouseAdditionalZone2RelationshipId name="Relationship_WarehouseAdditionalZone2RelationshipId">Relationship_WarehouseAdditionalZone2RelationshipId</a>

First included in: WMS/WMSWarehouseLocationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_WarehouseAdditionalZone2RelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_WarehouseAdditionalZone3RelationshipId name="Relationship_WarehouseAdditionalZone3RelationshipId">Relationship_WarehouseAdditionalZone3RelationshipId</a>

First included in: WMS/WMSWarehouseLocationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_WarehouseAdditionalZone3RelationshipId attribute are listed below.</summary>

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

### <a href=#BackingTable_WMSLocationRelationshipId name="BackingTable_WMSLocationRelationshipId">BackingTable_WMSLocationRelationshipId</a>

First included in: WMS/WMSWarehouseLocationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_WMSLocationRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/SupplyChain/Inventory/Main/WMSLocation.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/Inventory/Main/WMSLocation.cdm.json/WMSLocation</a></td><td><a href="../../../Tables/SupplyChain/Inventory/Main/WMSLocation.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PrimaryCompanyContextRelationshipId name="Relationship_PrimaryCompanyContextRelationshipId">Relationship_PrimaryCompanyContextRelationshipId</a>

First included in: WMS/WMSWarehouseLocationEntity (this entity)  

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
