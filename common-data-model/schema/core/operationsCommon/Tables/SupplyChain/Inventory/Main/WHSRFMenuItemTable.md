---
title: WHSRFMenuItemTable in Main - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 7/7/2020
ms.author: nebanfic
---

# Menu Items in Main

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Tables/SupplyChain/Inventory/Main/WHSRFMenuItemTable.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[WHSRFMenuItemTable/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Menu Items</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="WHSRFMenuItemTable.md" target="_blank">Main/WHSRFMenuItemTable</a>|
|[AdjustmentTypeCode](#AdjustmentTypeCode)||<a href="WHSRFMenuItemTable.md" target="_blank">Main/WHSRFMenuItemTable</a>|
|[AllowFullSplit](#AllowFullSplit)||<a href="WHSRFMenuItemTable.md" target="_blank">Main/WHSRFMenuItemTable</a>|
|[AllowLicensePlatePutOverride](#AllowLicensePlatePutOverride)||<a href="WHSRFMenuItemTable.md" target="_blank">Main/WHSRFMenuItemTable</a>|
|[AllowLocationOverflow](#AllowLocationOverflow)||<a href="WHSRFMenuItemTable.md" target="_blank">Main/WHSRFMenuItemTable</a>|
|[Anchor](#Anchor)||<a href="WHSRFMenuItemTable.md" target="_blank">Main/WHSRFMenuItemTable</a>|
|[AnchorBy](#AnchorBy)||<a href="WHSRFMenuItemTable.md" target="_blank">Main/WHSRFMenuItemTable</a>|
|[ClusterProfileId](#ClusterProfileId)||<a href="WHSRFMenuItemTable.md" target="_blank">Main/WHSRFMenuItemTable</a>|
|[CycleCountFirstPass](#CycleCountFirstPass)||<a href="WHSRFMenuItemTable.md" target="_blank">Main/WHSRFMenuItemTable</a>|
|[DefaultData](#DefaultData)||<a href="WHSRFMenuItemTable.md" target="_blank">Main/WHSRFMenuItemTable</a>|
|[DisableCycleCountThreshold](#DisableCycleCountThreshold)||<a href="WHSRFMenuItemTable.md" target="_blank">Main/WHSRFMenuItemTable</a>|
|[GenerateLP](#GenerateLP)||<a href="WHSRFMenuItemTable.md" target="_blank">Main/WHSRFMenuItemTable</a>|
|[GroupPutaway](#GroupPutaway)||<a href="WHSRFMenuItemTable.md" target="_blank">Main/WHSRFMenuItemTable</a>|
|[LocDirHintCode](#LocDirHintCode)||<a href="WHSRFMenuItemTable.md" target="_blank">Main/WHSRFMenuItemTable</a>|
|[LocVerification](#LocVerification)||<a href="WHSRFMenuItemTable.md" target="_blank">Main/WHSRFMenuItemTable</a>|
|[MenuItemDirectedBy](#MenuItemDirectedBy)||<a href="WHSRFMenuItemTable.md" target="_blank">Main/WHSRFMenuItemTable</a>|
|[MenuItemMode](#MenuItemMode)||<a href="WHSRFMenuItemTable.md" target="_blank">Main/WHSRFMenuItemTable</a>|
|[MenuItemName](#MenuItemName)||<a href="WHSRFMenuItemTable.md" target="_blank">Main/WHSRFMenuItemTable</a>|
|[OverrideInventBatchId](#OverrideInventBatchId)||<a href="WHSRFMenuItemTable.md" target="_blank">Main/WHSRFMenuItemTable</a>|
|[OverrideTargetLP](#OverrideTargetLP)||<a href="WHSRFMenuItemTable.md" target="_blank">Main/WHSRFMenuItemTable</a>|
|[PageSize](#PageSize)||<a href="WHSRFMenuItemTable.md" target="_blank">Main/WHSRFMenuItemTable</a>|
|[PickOldestBatch](#PickOldestBatch)||<a href="WHSRFMenuItemTable.md" target="_blank">Main/WHSRFMenuItemTable</a>|
|[PickPack](#PickPack)||<a href="WHSRFMenuItemTable.md" target="_blank">Main/WHSRFMenuItemTable</a>|
|[PrintLabel](#PrintLabel)||<a href="WHSRFMenuItemTable.md" target="_blank">Main/WHSRFMenuItemTable</a>|
|[RFDisplayPickSummary](#RFDisplayPickSummary)||<a href="WHSRFMenuItemTable.md" target="_blank">Main/WHSRFMenuItemTable</a>|
|[RFDisplayStatus](#RFDisplayStatus)||<a href="WHSRFMenuItemTable.md" target="_blank">Main/WHSRFMenuItemTable</a>|
|[RFSysGroupField](#RFSysGroupField)||<a href="WHSRFMenuItemTable.md" target="_blank">Main/WHSRFMenuItemTable</a>|
|[RFSysGroupFieldNum](#RFSysGroupFieldNum)||<a href="WHSRFMenuItemTable.md" target="_blank">Main/WHSRFMenuItemTable</a>|
|[RFSysGroupLabel](#RFSysGroupLabel)||<a href="WHSRFMenuItemTable.md" target="_blank">Main/WHSRFMenuItemTable</a>|
|[RFTitle](#RFTitle)||<a href="WHSRFMenuItemTable.md" target="_blank">Main/WHSRFMenuItemTable</a>|
|[ScheduleMovement](#ScheduleMovement)||<a href="WHSRFMenuItemTable.md" target="_blank">Main/WHSRFMenuItemTable</a>|
|[ShowBatchDisposition](#ShowBatchDisposition)||<a href="WHSRFMenuItemTable.md" target="_blank">Main/WHSRFMenuItemTable</a>|
|[ShowDisposition](#ShowDisposition)||<a href="WHSRFMenuItemTable.md" target="_blank">Main/WHSRFMenuItemTable</a>|
|[ShowFilter](#ShowFilter)||<a href="WHSRFMenuItemTable.md" target="_blank">Main/WHSRFMenuItemTable</a>|
|[Unitization](#Unitization)||<a href="WHSRFMenuItemTable.md" target="_blank">Main/WHSRFMenuItemTable</a>|
|[UseExistingWork](#UseExistingWork)||<a href="WHSRFMenuItemTable.md" target="_blank">Main/WHSRFMenuItemTable</a>|
|[WorkActivity](#WorkActivity)||<a href="WHSRFMenuItemTable.md" target="_blank">Main/WHSRFMenuItemTable</a>|
|[WorkAuditTemplateId](#WorkAuditTemplateId)||<a href="WHSRFMenuItemTable.md" target="_blank">Main/WHSRFMenuItemTable</a>|
|[WorkCreationProcess](#WorkCreationProcess)||<a href="WHSRFMenuItemTable.md" target="_blank">Main/WHSRFMenuItemTable</a>|
|[WorkTemplateCode](#WorkTemplateCode)||<a href="WHSRFMenuItemTable.md" target="_blank">Main/WHSRFMenuItemTable</a>|
|[HandleByLP](#HandleByLP)||<a href="WHSRFMenuItemTable.md" target="_blank">Main/WHSRFMenuItemTable</a>|
|[WorkerKeepsOrigWork](#WorkerKeepsOrigWork)||<a href="WHSRFMenuItemTable.md" target="_blank">Main/WHSRFMenuItemTable</a>|
|[ConfirmCancel](#ConfirmCancel)||<a href="WHSRFMenuItemTable.md" target="_blank">Main/WHSRFMenuItemTable</a>|
|[WHSAllowEndJob](#WHSAllowEndJob)||<a href="WHSRFMenuItemTable.md" target="_blank">Main/WHSRFMenuItemTable</a>|
|[WorkListFieldList](#WorkListFieldList)||<a href="WHSRFMenuItemTable.md" target="_blank">Main/WHSRFMenuItemTable</a>|
|[WorkListQuery](#WorkListQuery)||<a href="WHSRFMenuItemTable.md" target="_blank">Main/WHSRFMenuItemTable</a>|
|[AllowShippingOverpick](#AllowShippingOverpick)||<a href="WHSRFMenuItemTable.md" target="_blank">Main/WHSRFMenuItemTable</a>|
|[BlockReceivingASNItem](#BlockReceivingASNItem)||<a href="WHSRFMenuItemTable.md" target="_blank">Main/WHSRFMenuItemTable</a>|
|[LicensePlateConsolidationCancelRemainingOriginWorkLines](#LicensePlateConsolidationCancelRemainingOriginWorkLines)||<a href="WHSRFMenuItemTable.md" target="_blank">Main/WHSRFMenuItemTable</a>|
|[MixedLPReceivingMode](#MixedLPReceivingMode)||<a href="WHSRFMenuItemTable.md" target="_blank">Main/WHSRFMenuItemTable</a>|
|[DisplayContainerTypeCode](#DisplayContainerTypeCode)||<a href="WHSRFMenuItemTable.md" target="_blank">Main/WHSRFMenuItemTable</a>|
|[WillContainerRemovalCancelRelatedWork](#WillContainerRemovalCancelRelatedWork)||<a href="WHSRFMenuItemTable.md" target="_blank">Main/WHSRFMenuItemTable</a>|
|[CancelReplenishmentWorkWithDependentWork](#CancelReplenishmentWorkWithDependentWork)||<a href="WHSRFMenuItemTable.md" target="_blank">Main/WHSRFMenuItemTable</a>|
|[WHSWorkListFieldList](#WHSWorkListFieldList)||<a href="WHSRFMenuItemTable.md" target="_blank">Main/WHSRFMenuItemTable</a>|
|[WHSWorkListQuery](#WHSWorkListQuery)||<a href="WHSRFMenuItemTable.md" target="_blank">Main/WHSRFMenuItemTable</a>|
|[WorkListMaximumDisplayedRecords](#WorkListMaximumDisplayedRecords)||<a href="WHSRFMenuItemTable.md" target="_blank">Main/WHSRFMenuItemTable</a>|
|[AreOlderBatchesWithinWarehouseDisplayed](#AreOlderBatchesWithinWarehouseDisplayed)||<a href="WHSRFMenuItemTable.md" target="_blank">Main/WHSRFMenuItemTable</a>|
|[IsWorkListGroupingFilterDisplayed](#IsWorkListGroupingFilterDisplayed)||<a href="WHSRFMenuItemTable.md" target="_blank">Main/WHSRFMenuItemTable</a>|
|[EditCountingReasonCode](#EditCountingReasonCode)||<a href="WHSRFMenuItemTable.md" target="_blank">Main/WHSRFMenuItemTable</a>|
|[DisplayCountingReasonCode](#DisplayCountingReasonCode)||<a href="WHSRFMenuItemTable.md" target="_blank">Main/WHSRFMenuItemTable</a>|
|[DefaultCountingReasonCode](#DefaultCountingReasonCode)||<a href="WHSRFMenuItemTable.md" target="_blank">Main/WHSRFMenuItemTable</a>|
|[AllowedShipConfirmationType](#AllowedShipConfirmationType)||<a href="WHSRFMenuItemTable.md" target="_blank">Main/WHSRFMenuItemTable</a>|
|[GenerateCatchWeightTag](#GenerateCatchWeightTag)||<a href="WHSRFMenuItemTable.md" target="_blank">Main/WHSRFMenuItemTable</a>|
|[ProcessGuideUseFramework](#ProcessGuideUseFramework)||<a href="WHSRFMenuItemTable.md" target="_blank">Main/WHSRFMenuItemTable</a>|
|[GroupPick](#GroupPick)||<a href="WHSRFMenuItemTable.md" target="_blank">Main/WHSRFMenuItemTable</a>|
|[CartonGroupQuery](#CartonGroupQuery)||<a href="WHSRFMenuItemTable.md" target="_blank">Main/WHSRFMenuItemTable</a>|
|[SortTemplateId](#SortTemplateId)||<a href="WHSRFMenuItemTable.md" target="_blank">Main/WHSRFMenuItemTable</a>|
|[WaveLabelPrintMode](#WaveLabelPrintMode)||<a href="WHSRFMenuItemTable.md" target="_blank">Main/WHSRFMenuItemTable</a>|
|[DeferredPutProcessingPolicy](#DeferredPutProcessingPolicy)||<a href="WHSRFMenuItemTable.md" target="_blank">Main/WHSRFMenuItemTable</a>|
|[AssignPutawayCluster](#AssignPutawayCluster)||<a href="WHSRFMenuItemTable.md" target="_blank">Main/WHSRFMenuItemTable</a>|
|[LoadLineQuantityOverreceipt](#LoadLineQuantityOverreceipt)||<a href="WHSRFMenuItemTable.md" target="_blank">Main/WHSRFMenuItemTable</a>|
|[UseExistingCatchWeightTag](#UseExistingCatchWeightTag)||<a href="WHSRFMenuItemTable.md" target="_blank">Main/WHSRFMenuItemTable</a>|
|[ReceivingSummaryPageDisplayRule](#ReceivingSummaryPageDisplayRule)||<a href="WHSRFMenuItemTable.md" target="_blank">Main/WHSRFMenuItemTable</a>|
|[RFFastValidation](#RFFastValidation)||<a href="WHSRFMenuItemTable.md" target="_blank">Main/WHSRFMenuItemTable</a>|
|[DataAreaId](#DataAreaId)||<a href="WHSRFMenuItemTable.md" target="_blank">Main/WHSRFMenuItemTable</a>|
|[Relationship_WHSAdjustmentTypeRelationshipId](#Relationship_WHSAdjustmentTypeRelationshipId)||<a href="WHSRFMenuItemTable.md" target="_blank">Main/WHSRFMenuItemTable</a>|
|[Relationship_WHSClusterProfileRelationshipId](#Relationship_WHSClusterProfileRelationshipId)||<a href="WHSRFMenuItemTable.md" target="_blank">Main/WHSRFMenuItemTable</a>|
|[Relationship_WHSLocDirHintRelationshipId](#Relationship_WHSLocDirHintRelationshipId)||<a href="WHSRFMenuItemTable.md" target="_blank">Main/WHSRFMenuItemTable</a>|
|[Relationship_WHSWorkAuditTemplateTableRelationshipId](#Relationship_WHSWorkAuditTemplateTableRelationshipId)||<a href="WHSRFMenuItemTable.md" target="_blank">Main/WHSRFMenuItemTable</a>|
|[Relationship_WHSWorkTemplateTableRelationshipId](#Relationship_WHSWorkTemplateTableRelationshipId)||<a href="WHSRFMenuItemTable.md" target="_blank">Main/WHSRFMenuItemTable</a>|
|[Relationship_InventCountingReasonCodeRelationshipId](#Relationship_InventCountingReasonCodeRelationshipId)||<a href="WHSRFMenuItemTable.md" target="_blank">Main/WHSRFMenuItemTable</a>|
|[Relationship_SortTemplateRelationshipId](#Relationship_SortTemplateRelationshipId)||<a href="WHSRFMenuItemTable.md" target="_blank">Main/WHSRFMenuItemTable</a>|
|[Relationship_CompanyRelationshipId](#Relationship_CompanyRelationshipId)||<a href="WHSRFMenuItemTable.md" target="_blank">Main/WHSRFMenuItemTable</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: Main/WHSRFMenuItemTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[WHSRFMenuItemTable/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#AdjustmentTypeCode name="AdjustmentTypeCode">AdjustmentTypeCode</a>

First included in: Main/WHSRFMenuItemTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AdjustmentTypeCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AllowFullSplit name="AllowFullSplit">AllowFullSplit</a>

First included in: Main/WHSRFMenuItemTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AllowFullSplit attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#AllowLicensePlatePutOverride name="AllowLicensePlatePutOverride">AllowLicensePlatePutOverride</a>

First included in: Main/WHSRFMenuItemTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AllowLicensePlatePutOverride attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#AllowLocationOverflow name="AllowLocationOverflow">AllowLocationOverflow</a>

First included in: Main/WHSRFMenuItemTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AllowLocationOverflow attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#Anchor name="Anchor">Anchor</a>

First included in: Main/WHSRFMenuItemTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Anchor attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#AnchorBy name="AnchorBy">AnchorBy</a>

First included in: Main/WHSRFMenuItemTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AnchorBy attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#ClusterProfileId name="ClusterProfileId">ClusterProfileId</a>

First included in: Main/WHSRFMenuItemTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ClusterProfileId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CycleCountFirstPass name="CycleCountFirstPass">CycleCountFirstPass</a>

First included in: Main/WHSRFMenuItemTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CycleCountFirstPass attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#DefaultData name="DefaultData">DefaultData</a>

First included in: Main/WHSRFMenuItemTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultData attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#DisableCycleCountThreshold name="DisableCycleCountThreshold">DisableCycleCountThreshold</a>

First included in: Main/WHSRFMenuItemTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DisableCycleCountThreshold attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#GenerateLP name="GenerateLP">GenerateLP</a>

First included in: Main/WHSRFMenuItemTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the GenerateLP attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#GroupPutaway name="GroupPutaway">GroupPutaway</a>

First included in: Main/WHSRFMenuItemTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the GroupPutaway attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#LocDirHintCode name="LocDirHintCode">LocDirHintCode</a>

First included in: Main/WHSRFMenuItemTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LocDirHintCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LocVerification name="LocVerification">LocVerification</a>

First included in: Main/WHSRFMenuItemTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LocVerification attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#MenuItemDirectedBy name="MenuItemDirectedBy">MenuItemDirectedBy</a>

First included in: Main/WHSRFMenuItemTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MenuItemDirectedBy attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#MenuItemMode name="MenuItemMode">MenuItemMode</a>

First included in: Main/WHSRFMenuItemTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MenuItemMode attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#MenuItemName name="MenuItemName">MenuItemName</a>

First included in: Main/WHSRFMenuItemTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MenuItemName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#OverrideInventBatchId name="OverrideInventBatchId">OverrideInventBatchId</a>

First included in: Main/WHSRFMenuItemTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OverrideInventBatchId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#OverrideTargetLP name="OverrideTargetLP">OverrideTargetLP</a>

First included in: Main/WHSRFMenuItemTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OverrideTargetLP attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#PageSize name="PageSize">PageSize</a>

First included in: Main/WHSRFMenuItemTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PageSize attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#PickOldestBatch name="PickOldestBatch">PickOldestBatch</a>

First included in: Main/WHSRFMenuItemTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PickOldestBatch attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#PickPack name="PickPack">PickPack</a>

First included in: Main/WHSRFMenuItemTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PickPack attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#PrintLabel name="PrintLabel">PrintLabel</a>

First included in: Main/WHSRFMenuItemTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrintLabel attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#RFDisplayPickSummary name="RFDisplayPickSummary">RFDisplayPickSummary</a>

First included in: Main/WHSRFMenuItemTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RFDisplayPickSummary attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#RFDisplayStatus name="RFDisplayStatus">RFDisplayStatus</a>

First included in: Main/WHSRFMenuItemTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RFDisplayStatus attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#RFSysGroupField name="RFSysGroupField">RFSysGroupField</a>

First included in: Main/WHSRFMenuItemTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RFSysGroupField attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RFSysGroupFieldNum name="RFSysGroupFieldNum">RFSysGroupFieldNum</a>

First included in: Main/WHSRFMenuItemTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RFSysGroupFieldNum attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#RFSysGroupLabel name="RFSysGroupLabel">RFSysGroupLabel</a>

First included in: Main/WHSRFMenuItemTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RFSysGroupLabel attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RFTitle name="RFTitle">RFTitle</a>

First included in: Main/WHSRFMenuItemTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RFTitle attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ScheduleMovement name="ScheduleMovement">ScheduleMovement</a>

First included in: Main/WHSRFMenuItemTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ScheduleMovement attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#ShowBatchDisposition name="ShowBatchDisposition">ShowBatchDisposition</a>

First included in: Main/WHSRFMenuItemTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ShowBatchDisposition attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#ShowDisposition name="ShowDisposition">ShowDisposition</a>

First included in: Main/WHSRFMenuItemTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ShowDisposition attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#ShowFilter name="ShowFilter">ShowFilter</a>

First included in: Main/WHSRFMenuItemTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ShowFilter attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#Unitization name="Unitization">Unitization</a>

First included in: Main/WHSRFMenuItemTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Unitization attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#UseExistingWork name="UseExistingWork">UseExistingWork</a>

First included in: Main/WHSRFMenuItemTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the UseExistingWork attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#WorkActivity name="WorkActivity">WorkActivity</a>

First included in: Main/WHSRFMenuItemTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WorkActivity attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#WorkAuditTemplateId name="WorkAuditTemplateId">WorkAuditTemplateId</a>

First included in: Main/WHSRFMenuItemTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WorkAuditTemplateId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WorkCreationProcess name="WorkCreationProcess">WorkCreationProcess</a>

First included in: Main/WHSRFMenuItemTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WorkCreationProcess attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#WorkTemplateCode name="WorkTemplateCode">WorkTemplateCode</a>

First included in: Main/WHSRFMenuItemTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WorkTemplateCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#HandleByLP name="HandleByLP">HandleByLP</a>

First included in: Main/WHSRFMenuItemTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the HandleByLP attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#WorkerKeepsOrigWork name="WorkerKeepsOrigWork">WorkerKeepsOrigWork</a>

First included in: Main/WHSRFMenuItemTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WorkerKeepsOrigWork attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#ConfirmCancel name="ConfirmCancel">ConfirmCancel</a>

First included in: Main/WHSRFMenuItemTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ConfirmCancel attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#WHSAllowEndJob name="WHSAllowEndJob">WHSAllowEndJob</a>

First included in: Main/WHSRFMenuItemTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WHSAllowEndJob attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#WorkListFieldList name="WorkListFieldList">WorkListFieldList</a>

First included in: Main/WHSRFMenuItemTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>binary</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WorkListFieldList attribute are listed below.</summary>

**is.dataFormat.byte**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.byte**  
**is.dataFormat.array**  
</details>

### <a href=#WorkListQuery name="WorkListQuery">WorkListQuery</a>

First included in: Main/WHSRFMenuItemTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>binary</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WorkListQuery attribute are listed below.</summary>

**is.dataFormat.byte**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.byte**  
**is.dataFormat.array**  
</details>

### <a href=#AllowShippingOverpick name="AllowShippingOverpick">AllowShippingOverpick</a>

First included in: Main/WHSRFMenuItemTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AllowShippingOverpick attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#BlockReceivingASNItem name="BlockReceivingASNItem">BlockReceivingASNItem</a>

First included in: Main/WHSRFMenuItemTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BlockReceivingASNItem attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#LicensePlateConsolidationCancelRemainingOriginWorkLines name="LicensePlateConsolidationCancelRemainingOriginWorkLines">LicensePlateConsolidationCancelRemainingOriginWorkLines</a>

First included in: Main/WHSRFMenuItemTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LicensePlateConsolidationCancelRemainingOriginWorkLines attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#MixedLPReceivingMode name="MixedLPReceivingMode">MixedLPReceivingMode</a>

First included in: Main/WHSRFMenuItemTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MixedLPReceivingMode attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#DisplayContainerTypeCode name="DisplayContainerTypeCode">DisplayContainerTypeCode</a>

First included in: Main/WHSRFMenuItemTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DisplayContainerTypeCode attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#WillContainerRemovalCancelRelatedWork name="WillContainerRemovalCancelRelatedWork">WillContainerRemovalCancelRelatedWork</a>

First included in: Main/WHSRFMenuItemTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WillContainerRemovalCancelRelatedWork attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#CancelReplenishmentWorkWithDependentWork name="CancelReplenishmentWorkWithDependentWork">CancelReplenishmentWorkWithDependentWork</a>

First included in: Main/WHSRFMenuItemTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CancelReplenishmentWorkWithDependentWork attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#WHSWorkListFieldList name="WHSWorkListFieldList">WHSWorkListFieldList</a>

First included in: Main/WHSRFMenuItemTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>binary</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WHSWorkListFieldList attribute are listed below.</summary>

**is.dataFormat.byte**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.byte**  
**is.dataFormat.array**  
</details>

### <a href=#WHSWorkListQuery name="WHSWorkListQuery">WHSWorkListQuery</a>

First included in: Main/WHSRFMenuItemTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>binary</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WHSWorkListQuery attribute are listed below.</summary>

**is.dataFormat.byte**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.byte**  
**is.dataFormat.array**  
</details>

### <a href=#WorkListMaximumDisplayedRecords name="WorkListMaximumDisplayedRecords">WorkListMaximumDisplayedRecords</a>

First included in: Main/WHSRFMenuItemTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WorkListMaximumDisplayedRecords attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#AreOlderBatchesWithinWarehouseDisplayed name="AreOlderBatchesWithinWarehouseDisplayed">AreOlderBatchesWithinWarehouseDisplayed</a>

First included in: Main/WHSRFMenuItemTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AreOlderBatchesWithinWarehouseDisplayed attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#IsWorkListGroupingFilterDisplayed name="IsWorkListGroupingFilterDisplayed">IsWorkListGroupingFilterDisplayed</a>

First included in: Main/WHSRFMenuItemTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsWorkListGroupingFilterDisplayed attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#EditCountingReasonCode name="EditCountingReasonCode">EditCountingReasonCode</a>

First included in: Main/WHSRFMenuItemTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EditCountingReasonCode attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#DisplayCountingReasonCode name="DisplayCountingReasonCode">DisplayCountingReasonCode</a>

First included in: Main/WHSRFMenuItemTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DisplayCountingReasonCode attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#DefaultCountingReasonCode name="DefaultCountingReasonCode">DefaultCountingReasonCode</a>

First included in: Main/WHSRFMenuItemTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultCountingReasonCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AllowedShipConfirmationType name="AllowedShipConfirmationType">AllowedShipConfirmationType</a>

First included in: Main/WHSRFMenuItemTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AllowedShipConfirmationType attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#GenerateCatchWeightTag name="GenerateCatchWeightTag">GenerateCatchWeightTag</a>

First included in: Main/WHSRFMenuItemTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the GenerateCatchWeightTag attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#ProcessGuideUseFramework name="ProcessGuideUseFramework">ProcessGuideUseFramework</a>

First included in: Main/WHSRFMenuItemTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProcessGuideUseFramework attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#GroupPick name="GroupPick">GroupPick</a>

First included in: Main/WHSRFMenuItemTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the GroupPick attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#CartonGroupQuery name="CartonGroupQuery">CartonGroupQuery</a>

First included in: Main/WHSRFMenuItemTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>binary</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CartonGroupQuery attribute are listed below.</summary>

**is.dataFormat.byte**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.byte**  
**is.dataFormat.array**  
</details>

### <a href=#SortTemplateId name="SortTemplateId">SortTemplateId</a>

First included in: Main/WHSRFMenuItemTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SortTemplateId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WaveLabelPrintMode name="WaveLabelPrintMode">WaveLabelPrintMode</a>

First included in: Main/WHSRFMenuItemTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WaveLabelPrintMode attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#DeferredPutProcessingPolicy name="DeferredPutProcessingPolicy">DeferredPutProcessingPolicy</a>

First included in: Main/WHSRFMenuItemTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DeferredPutProcessingPolicy attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#AssignPutawayCluster name="AssignPutawayCluster">AssignPutawayCluster</a>

First included in: Main/WHSRFMenuItemTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AssignPutawayCluster attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#LoadLineQuantityOverreceipt name="LoadLineQuantityOverreceipt">LoadLineQuantityOverreceipt</a>

First included in: Main/WHSRFMenuItemTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LoadLineQuantityOverreceipt attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#UseExistingCatchWeightTag name="UseExistingCatchWeightTag">UseExistingCatchWeightTag</a>

First included in: Main/WHSRFMenuItemTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the UseExistingCatchWeightTag attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#ReceivingSummaryPageDisplayRule name="ReceivingSummaryPageDisplayRule">ReceivingSummaryPageDisplayRule</a>

First included in: Main/WHSRFMenuItemTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReceivingSummaryPageDisplayRule attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#RFFastValidation name="RFFastValidation">RFFastValidation</a>

First included in: Main/WHSRFMenuItemTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RFFastValidation attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#DataAreaId name="DataAreaId">DataAreaId</a>

First included in: Main/WHSRFMenuItemTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DataAreaId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.readOnly**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_WHSAdjustmentTypeRelationshipId name="Relationship_WHSAdjustmentTypeRelationshipId">Relationship_WHSAdjustmentTypeRelationshipId</a>

First included in: Main/WHSRFMenuItemTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_WHSAdjustmentTypeRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Group/WHSAdjustmentType.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/Inventory/Group/WHSAdjustmentType.cdm.json/WHSAdjustmentType</a></td><td><a href="../Group/WHSAdjustmentType.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_WHSClusterProfileRelationshipId name="Relationship_WHSClusterProfileRelationshipId">Relationship_WHSClusterProfileRelationshipId</a>

First included in: Main/WHSRFMenuItemTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_WHSClusterProfileRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Group/WHSClusterProfile.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/Inventory/Group/WHSClusterProfile.cdm.json/WHSClusterProfile</a></td><td><a href="../Group/WHSClusterProfile.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_WHSLocDirHintRelationshipId name="Relationship_WHSLocDirHintRelationshipId">Relationship_WHSLocDirHintRelationshipId</a>

First included in: Main/WHSRFMenuItemTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_WHSLocDirHintRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Group/WHSLocDirHint.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/Inventory/Group/WHSLocDirHint.cdm.json/WHSLocDirHint</a></td><td><a href="../Group/WHSLocDirHint.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_WHSWorkAuditTemplateTableRelationshipId name="Relationship_WHSWorkAuditTemplateTableRelationshipId">Relationship_WHSWorkAuditTemplateTableRelationshipId</a>

First included in: Main/WHSRFMenuItemTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_WHSWorkAuditTemplateTableRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="WHSWorkAuditTemplateTable.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/Inventory/Main/WHSWorkAuditTemplateTable.cdm.json/WHSWorkAuditTemplateTable</a></td><td><a href="WHSWorkAuditTemplateTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_WHSWorkTemplateTableRelationshipId name="Relationship_WHSWorkTemplateTableRelationshipId">Relationship_WHSWorkTemplateTableRelationshipId</a>

First included in: Main/WHSRFMenuItemTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_WHSWorkTemplateTableRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="WHSWorkTemplateTable.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/Inventory/Main/WHSWorkTemplateTable.cdm.json/WHSWorkTemplateTable</a></td><td><a href="WHSWorkTemplateTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_InventCountingReasonCodeRelationshipId name="Relationship_InventCountingReasonCodeRelationshipId">Relationship_InventCountingReasonCodeRelationshipId</a>

First included in: Main/WHSRFMenuItemTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_InventCountingReasonCodeRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="InventCountingReasonCode.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/Inventory/Main/InventCountingReasonCode.cdm.json/InventCountingReasonCode</a></td><td><a href="InventCountingReasonCode.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_SortTemplateRelationshipId name="Relationship_SortTemplateRelationshipId">Relationship_SortTemplateRelationshipId</a>

First included in: Main/WHSRFMenuItemTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_SortTemplateRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="WHSOutboundSortTemplate.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/Inventory/Main/WHSOutboundSortTemplate.cdm.json/WHSOutboundSortTemplate</a></td><td><a href="WHSOutboundSortTemplate.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_CompanyRelationshipId name="Relationship_CompanyRelationshipId">Relationship_CompanyRelationshipId</a>

First included in: Main/WHSRFMenuItemTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_CompanyRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Finance/Ledger/Main/CompanyInfo.md" target="_blank">/core/operationsCommon/Tables/Finance/Ledger/Main/CompanyInfo.cdm.json/CompanyInfo</a></td><td><a href="../../../Finance/Ledger/Main/CompanyInfo.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>
