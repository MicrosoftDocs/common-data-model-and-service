---
title: RetailParametersEx2 in Parameter - Common Data Model | Microsoft Docs
description: undefined
author: llawwaii
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 8/5/2020
ms.author: weiluo
---

# Store inventory parameters in Parameter(RetailParametersEx2)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Tables/Commerce/ChannelManagement/Parameter/RetailParametersEx2.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[RetailParametersEx2/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Store inventory parameters</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="RetailParametersEx2.md" target="_blank">Parameter/RetailParametersEx2</a>|
|[PRPostingTransferJournal](#PRPostingTransferJournal)||<a href="RetailParametersEx2.md" target="_blank">Parameter/RetailParametersEx2</a>|
|[receivingNos](#receivingNos)||<a href="RetailParametersEx2.md" target="_blank">Parameter/RetailParametersEx2</a>|
|[accesLevelType](#accesLevelType)||<a href="RetailParametersEx2.md" target="_blank">Parameter/RetailParametersEx2</a>|
|[allowAddLineToOrder](#allowAddLineToOrder)||<a href="RetailParametersEx2.md" target="_blank">Parameter/RetailParametersEx2</a>|
|[ascendingDescending](#ascendingDescending)||<a href="RetailParametersEx2.md" target="_blank">Parameter/RetailParametersEx2</a>|
|[autoProcessLog](#autoProcessLog)||<a href="RetailParametersEx2.md" target="_blank">Parameter/RetailParametersEx2</a>|
|[autoProfitLoss](#autoProfitLoss)||<a href="RetailParametersEx2.md" target="_blank">Parameter/RetailParametersEx2</a>|
|[barcodeUnitofMeasure](#barcodeUnitofMeasure)||<a href="RetailParametersEx2.md" target="_blank">Parameter/RetailParametersEx2</a>|
|[basePickingQtyon](#basePickingQtyon)||<a href="RetailParametersEx2.md" target="_blank">Parameter/RetailParametersEx2</a>|
|[baseReceivingQtyon](#baseReceivingQtyon)||<a href="RetailParametersEx2.md" target="_blank">Parameter/RetailParametersEx2</a>|
|[BTreePath](#BTreePath)||<a href="RetailParametersEx2.md" target="_blank">Parameter/RetailParametersEx2</a>|
|[countingAreaFiltering](#countingAreaFiltering)||<a href="RetailParametersEx2.md" target="_blank">Parameter/RetailParametersEx2</a>|
|[defaultTagCountJournal](#defaultTagCountJournal)||<a href="RetailParametersEx2.md" target="_blank">Parameter/RetailParametersEx2</a>|
|[defaultType](#defaultType)||<a href="RetailParametersEx2.md" target="_blank">Parameter/RetailParametersEx2</a>|
|[dlvDateRange](#dlvDateRange)||<a href="RetailParametersEx2.md" target="_blank">Parameter/RetailParametersEx2</a>|
|[elementName](#elementName)||<a href="RetailParametersEx2.md" target="_blank">Parameter/RetailParametersEx2</a>|
|[elementType](#elementType)||<a href="RetailParametersEx2.md" target="_blank">Parameter/RetailParametersEx2</a>|
|[fieldNum](#fieldNum)||<a href="RetailParametersEx2.md" target="_blank">Parameter/RetailParametersEx2</a>|
|[HHTPrePath](#HHTPrePath)||<a href="RetailParametersEx2.md" target="_blank">Parameter/RetailParametersEx2</a>|
|[itemNotFoundSubstitute](#itemNotFoundSubstitute)||<a href="RetailParametersEx2.md" target="_blank">Parameter/RetailParametersEx2</a>|
|[pickingActivePRO](#pickingActivePRO)||<a href="RetailParametersEx2.md" target="_blank">Parameter/RetailParametersEx2</a>|
|[pickingActiveSO](#pickingActiveSO)||<a href="RetailParametersEx2.md" target="_blank">Parameter/RetailParametersEx2</a>|
|[pickingActiveTO](#pickingActiveTO)||<a href="RetailParametersEx2.md" target="_blank">Parameter/RetailParametersEx2</a>|
|[pickingEnteringTypePRO](#pickingEnteringTypePRO)||<a href="RetailParametersEx2.md" target="_blank">Parameter/RetailParametersEx2</a>|
|[pickingEnteringTypeSO](#pickingEnteringTypeSO)||<a href="RetailParametersEx2.md" target="_blank">Parameter/RetailParametersEx2</a>|
|[pickingEnteringTypeTO](#pickingEnteringTypeTO)||<a href="RetailParametersEx2.md" target="_blank">Parameter/RetailParametersEx2</a>|
|[pickingInfocodeIdPRO](#pickingInfocodeIdPRO)||<a href="RetailParametersEx2.md" target="_blank">Parameter/RetailParametersEx2</a>|
|[pickingInfocodeIdTO](#pickingInfocodeIdTO)||<a href="RetailParametersEx2.md" target="_blank">Parameter/RetailParametersEx2</a>|
|[pickingNos](#pickingNos)||<a href="RetailParametersEx2.md" target="_blank">Parameter/RetailParametersEx2</a>|
|[pickingPosting](#pickingPosting)||<a href="RetailParametersEx2.md" target="_blank">Parameter/RetailParametersEx2</a>|
|[pickingPostMethod](#pickingPostMethod)||<a href="RetailParametersEx2.md" target="_blank">Parameter/RetailParametersEx2</a>|
|[pickingReasonGroup](#pickingReasonGroup)||<a href="RetailParametersEx2.md" target="_blank">Parameter/RetailParametersEx2</a>|
|[pickingRFScr1leading](#pickingRFScr1leading)||<a href="RetailParametersEx2.md" target="_blank">Parameter/RetailParametersEx2</a>|
|[pickingRFScr2leading](#pickingRFScr2leading)||<a href="RetailParametersEx2.md" target="_blank">Parameter/RetailParametersEx2</a>|
|[pickingRFScreen1](#pickingRFScreen1)||<a href="RetailParametersEx2.md" target="_blank">Parameter/RetailParametersEx2</a>|
|[pickingRFScreen2](#pickingRFScreen2)||<a href="RetailParametersEx2.md" target="_blank">Parameter/RetailParametersEx2</a>|
|[pickingSearchforItemby](#pickingSearchforItemby)||<a href="RetailParametersEx2.md" target="_blank">Parameter/RetailParametersEx2</a>|
|[pickingShowinSelectionList](#pickingShowinSelectionList)||<a href="RetailParametersEx2.md" target="_blank">Parameter/RetailParametersEx2</a>|
|[pickingSourceCode](#pickingSourceCode)||<a href="RetailParametersEx2.md" target="_blank">Parameter/RetailParametersEx2</a>|
|[pickingUnitofMeasurePRO](#pickingUnitofMeasurePRO)||<a href="RetailParametersEx2.md" target="_blank">Parameter/RetailParametersEx2</a>|
|[pickingUnitofMeasureSO](#pickingUnitofMeasureSO)||<a href="RetailParametersEx2.md" target="_blank">Parameter/RetailParametersEx2</a>|
|[pickingUnitofMeasureTO](#pickingUnitofMeasureTO)||<a href="RetailParametersEx2.md" target="_blank">Parameter/RetailParametersEx2</a>|
|[POItemLookupMethod](#POItemLookupMethod)||<a href="RetailParametersEx2.md" target="_blank">Parameter/RetailParametersEx2</a>|
|[postedPickingNos](#postedPickingNos)||<a href="RetailParametersEx2.md" target="_blank">Parameter/RetailParametersEx2</a>|
|[postedReceivingNos](#postedReceivingNos)||<a href="RetailParametersEx2.md" target="_blank">Parameter/RetailParametersEx2</a>|
|[PRLineDescription](#PRLineDescription)||<a href="RetailParametersEx2.md" target="_blank">Parameter/RetailParametersEx2</a>|
|[PRPostingProfitLossJournal](#PRPostingProfitLossJournal)||<a href="RetailParametersEx2.md" target="_blank">Parameter/RetailParametersEx2</a>|
|[receivingActivePO](#receivingActivePO)||<a href="RetailParametersEx2.md" target="_blank">Parameter/RetailParametersEx2</a>|
|[receivingEnteringTypePO](#receivingEnteringTypePO)||<a href="RetailParametersEx2.md" target="_blank">Parameter/RetailParametersEx2</a>|
|[receivingFrequencyofChecks](#receivingFrequencyofChecks)||<a href="RetailParametersEx2.md" target="_blank">Parameter/RetailParametersEx2</a>|
|[receivingInfocodeIdPO](#receivingInfocodeIdPO)||<a href="RetailParametersEx2.md" target="_blank">Parameter/RetailParametersEx2</a>|
|[receivingItemLookup](#receivingItemLookup)||<a href="RetailParametersEx2.md" target="_blank">Parameter/RetailParametersEx2</a>|
|[receivingPosting](#receivingPosting)||<a href="RetailParametersEx2.md" target="_blank">Parameter/RetailParametersEx2</a>|
|[receivingPostMethod](#receivingPostMethod)||<a href="RetailParametersEx2.md" target="_blank">Parameter/RetailParametersEx2</a>|
|[receivingReasonGroup](#receivingReasonGroup)||<a href="RetailParametersEx2.md" target="_blank">Parameter/RetailParametersEx2</a>|
|[receivingRFScr1leading](#receivingRFScr1leading)||<a href="RetailParametersEx2.md" target="_blank">Parameter/RetailParametersEx2</a>|
|[receivingRFScr2leading](#receivingRFScr2leading)||<a href="RetailParametersEx2.md" target="_blank">Parameter/RetailParametersEx2</a>|
|[receivingRFScreen1](#receivingRFScreen1)||<a href="RetailParametersEx2.md" target="_blank">Parameter/RetailParametersEx2</a>|
|[receivingRFScreen2](#receivingRFScreen2)||<a href="RetailParametersEx2.md" target="_blank">Parameter/RetailParametersEx2</a>|
|[receivingSearchforItemby](#receivingSearchforItemby)||<a href="RetailParametersEx2.md" target="_blank">Parameter/RetailParametersEx2</a>|
|[receivingSourceCode](#receivingSourceCode)||<a href="RetailParametersEx2.md" target="_blank">Parameter/RetailParametersEx2</a>|
|[receivingUnitofMeasurePO](#receivingUnitofMeasurePO)||<a href="RetailParametersEx2.md" target="_blank">Parameter/RetailParametersEx2</a>|
|[recShowinSelectionList](#recShowinSelectionList)||<a href="RetailParametersEx2.md" target="_blank">Parameter/RetailParametersEx2</a>|
|[RFDebugLogUSER](#RFDebugLogUSER)||<a href="RetailParametersEx2.md" target="_blank">Parameter/RetailParametersEx2</a>|
|[RFMaxQuantityValue](#RFMaxQuantityValue)||<a href="RetailParametersEx2.md" target="_blank">Parameter/RetailParametersEx2</a>|
|[RFRangingScreenNo](#RFRangingScreenNo)||<a href="RetailParametersEx2.md" target="_blank">Parameter/RetailParametersEx2</a>|
|[RFRangingShelfLabel](#RFRangingShelfLabel)||<a href="RetailParametersEx2.md" target="_blank">Parameter/RetailParametersEx2</a>|
|[RFRestartPassword](#RFRestartPassword)||<a href="RetailParametersEx2.md" target="_blank">Parameter/RetailParametersEx2</a>|
|[setCountingDate](#setCountingDate)||<a href="RetailParametersEx2.md" target="_blank">Parameter/RetailParametersEx2</a>|
|[setupId](#setupId)||<a href="RetailParametersEx2.md" target="_blank">Parameter/RetailParametersEx2</a>|
|[shrinkageReasonGroup](#shrinkageReasonGroup)||<a href="RetailParametersEx2.md" target="_blank">Parameter/RetailParametersEx2</a>|
|[useBatchPostingforOrders](#useBatchPostingforOrders)||<a href="RetailParametersEx2.md" target="_blank">Parameter/RetailParametersEx2</a>|
|[usePrimaryVendorType](#usePrimaryVendorType)||<a href="RetailParametersEx2.md" target="_blank">Parameter/RetailParametersEx2</a>|
|[useQtytoShip](#useQtytoShip)||<a href="RetailParametersEx2.md" target="_blank">Parameter/RetailParametersEx2</a>|
|[vendorNameToDescription](#vendorNameToDescription)||<a href="RetailParametersEx2.md" target="_blank">Parameter/RetailParametersEx2</a>|
|[worksheetCreationType](#worksheetCreationType)||<a href="RetailParametersEx2.md" target="_blank">Parameter/RetailParametersEx2</a>|
|[xPickingDefaultPOSType](#xPickingDefaultPOSType)||<a href="RetailParametersEx2.md" target="_blank">Parameter/RetailParametersEx2</a>|
|[DataAreaId](#DataAreaId)||<a href="RetailParametersEx2.md" target="_blank">Parameter/RetailParametersEx2</a>|
|[Relationship_InventJournalNameRelationshipId](#Relationship_InventJournalNameRelationshipId)||<a href="RetailParametersEx2.md" target="_blank">Parameter/RetailParametersEx2</a>|
|[Relationship_InventJournalName1RelationshipId](#Relationship_InventJournalName1RelationshipId)||<a href="RetailParametersEx2.md" target="_blank">Parameter/RetailParametersEx2</a>|
|[Relationship_InventJournalName2RelationshipId](#Relationship_InventJournalName2RelationshipId)||<a href="RetailParametersEx2.md" target="_blank">Parameter/RetailParametersEx2</a>|
|[Relationship_InventTableRelationshipId](#Relationship_InventTableRelationshipId)||<a href="RetailParametersEx2.md" target="_blank">Parameter/RetailParametersEx2</a>|
|[Relationship_NumberSequenceTablePickerRelationshipId](#Relationship_NumberSequenceTablePickerRelationshipId)||<a href="RetailParametersEx2.md" target="_blank">Parameter/RetailParametersEx2</a>|
|[Relationship_NumberSequenceTableReceiverRelationshipId](#Relationship_NumberSequenceTableReceiverRelationshipId)||<a href="RetailParametersEx2.md" target="_blank">Parameter/RetailParametersEx2</a>|
|[Relationship_RetailInfocodeTableRelationshipId](#Relationship_RetailInfocodeTableRelationshipId)||<a href="RetailParametersEx2.md" target="_blank">Parameter/RetailParametersEx2</a>|
|[Relationship_RetailInfocodeTable1RelationshipId](#Relationship_RetailInfocodeTable1RelationshipId)||<a href="RetailParametersEx2.md" target="_blank">Parameter/RetailParametersEx2</a>|
|[Relationship_RetailInfocodeTable2RelationshipId](#Relationship_RetailInfocodeTable2RelationshipId)||<a href="RetailParametersEx2.md" target="_blank">Parameter/RetailParametersEx2</a>|
|[Relationship_CompanyRelationshipId](#Relationship_CompanyRelationshipId)||<a href="RetailParametersEx2.md" target="_blank">Parameter/RetailParametersEx2</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: Parameter/RetailParametersEx2 (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[RetailParametersEx2/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#PRPostingTransferJournal name="PRPostingTransferJournal">PRPostingTransferJournal</a>

First included in: Parameter/RetailParametersEx2 (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PRPostingTransferJournal attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#receivingNos name="receivingNos">receivingNos</a>

First included in: Parameter/RetailParametersEx2 (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the receivingNos attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#accesLevelType name="accesLevelType">accesLevelType</a>

First included in: Parameter/RetailParametersEx2 (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the accesLevelType attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#allowAddLineToOrder name="allowAddLineToOrder">allowAddLineToOrder</a>

First included in: Parameter/RetailParametersEx2 (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the allowAddLineToOrder attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#ascendingDescending name="ascendingDescending">ascendingDescending</a>

First included in: Parameter/RetailParametersEx2 (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ascendingDescending attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#autoProcessLog name="autoProcessLog">autoProcessLog</a>

First included in: Parameter/RetailParametersEx2 (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the autoProcessLog attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#autoProfitLoss name="autoProfitLoss">autoProfitLoss</a>

First included in: Parameter/RetailParametersEx2 (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the autoProfitLoss attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#barcodeUnitofMeasure name="barcodeUnitofMeasure">barcodeUnitofMeasure</a>

First included in: Parameter/RetailParametersEx2 (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the barcodeUnitofMeasure attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#basePickingQtyon name="basePickingQtyon">basePickingQtyon</a>

First included in: Parameter/RetailParametersEx2 (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the basePickingQtyon attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#baseReceivingQtyon name="baseReceivingQtyon">baseReceivingQtyon</a>

First included in: Parameter/RetailParametersEx2 (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the baseReceivingQtyon attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#BTreePath name="BTreePath">BTreePath</a>

First included in: Parameter/RetailParametersEx2 (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Location</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BTreePath attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Location</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#countingAreaFiltering name="countingAreaFiltering">countingAreaFiltering</a>

First included in: Parameter/RetailParametersEx2 (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the countingAreaFiltering attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#defaultTagCountJournal name="defaultTagCountJournal">defaultTagCountJournal</a>

First included in: Parameter/RetailParametersEx2 (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the defaultTagCountJournal attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#defaultType name="defaultType">defaultType</a>

First included in: Parameter/RetailParametersEx2 (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the defaultType attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#dlvDateRange name="dlvDateRange">dlvDateRange</a>

First included in: Parameter/RetailParametersEx2 (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the dlvDateRange attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#elementName name="elementName">elementName</a>

First included in: Parameter/RetailParametersEx2 (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the elementName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#elementType name="elementType">elementType</a>

First included in: Parameter/RetailParametersEx2 (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the elementType attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#fieldNum name="fieldNum">fieldNum</a>

First included in: Parameter/RetailParametersEx2 (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the fieldNum attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#HHTPrePath name="HHTPrePath">HHTPrePath</a>

First included in: Parameter/RetailParametersEx2 (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the HHTPrePath attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#itemNotFoundSubstitute name="itemNotFoundSubstitute">itemNotFoundSubstitute</a>

First included in: Parameter/RetailParametersEx2 (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the itemNotFoundSubstitute attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#pickingActivePRO name="pickingActivePRO">pickingActivePRO</a>

First included in: Parameter/RetailParametersEx2 (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the pickingActivePRO attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#pickingActiveSO name="pickingActiveSO">pickingActiveSO</a>

First included in: Parameter/RetailParametersEx2 (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the pickingActiveSO attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#pickingActiveTO name="pickingActiveTO">pickingActiveTO</a>

First included in: Parameter/RetailParametersEx2 (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the pickingActiveTO attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#pickingEnteringTypePRO name="pickingEnteringTypePRO">pickingEnteringTypePRO</a>

First included in: Parameter/RetailParametersEx2 (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the pickingEnteringTypePRO attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#pickingEnteringTypeSO name="pickingEnteringTypeSO">pickingEnteringTypeSO</a>

First included in: Parameter/RetailParametersEx2 (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the pickingEnteringTypeSO attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#pickingEnteringTypeTO name="pickingEnteringTypeTO">pickingEnteringTypeTO</a>

First included in: Parameter/RetailParametersEx2 (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the pickingEnteringTypeTO attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#pickingInfocodeIdPRO name="pickingInfocodeIdPRO">pickingInfocodeIdPRO</a>

First included in: Parameter/RetailParametersEx2 (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the pickingInfocodeIdPRO attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#pickingInfocodeIdTO name="pickingInfocodeIdTO">pickingInfocodeIdTO</a>

First included in: Parameter/RetailParametersEx2 (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the pickingInfocodeIdTO attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#pickingNos name="pickingNos">pickingNos</a>

First included in: Parameter/RetailParametersEx2 (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the pickingNos attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#pickingPosting name="pickingPosting">pickingPosting</a>

First included in: Parameter/RetailParametersEx2 (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the pickingPosting attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#pickingPostMethod name="pickingPostMethod">pickingPostMethod</a>

First included in: Parameter/RetailParametersEx2 (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the pickingPostMethod attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#pickingReasonGroup name="pickingReasonGroup">pickingReasonGroup</a>

First included in: Parameter/RetailParametersEx2 (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the pickingReasonGroup attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#pickingRFScr1leading name="pickingRFScr1leading">pickingRFScr1leading</a>

First included in: Parameter/RetailParametersEx2 (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the pickingRFScr1leading attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#pickingRFScr2leading name="pickingRFScr2leading">pickingRFScr2leading</a>

First included in: Parameter/RetailParametersEx2 (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the pickingRFScr2leading attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#pickingRFScreen1 name="pickingRFScreen1">pickingRFScreen1</a>

First included in: Parameter/RetailParametersEx2 (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the pickingRFScreen1 attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#pickingRFScreen2 name="pickingRFScreen2">pickingRFScreen2</a>

First included in: Parameter/RetailParametersEx2 (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the pickingRFScreen2 attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#pickingSearchforItemby name="pickingSearchforItemby">pickingSearchforItemby</a>

First included in: Parameter/RetailParametersEx2 (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the pickingSearchforItemby attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#pickingShowinSelectionList name="pickingShowinSelectionList">pickingShowinSelectionList</a>

First included in: Parameter/RetailParametersEx2 (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the pickingShowinSelectionList attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#pickingSourceCode name="pickingSourceCode">pickingSourceCode</a>

First included in: Parameter/RetailParametersEx2 (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the pickingSourceCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#pickingUnitofMeasurePRO name="pickingUnitofMeasurePRO">pickingUnitofMeasurePRO</a>

First included in: Parameter/RetailParametersEx2 (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the pickingUnitofMeasurePRO attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#pickingUnitofMeasureSO name="pickingUnitofMeasureSO">pickingUnitofMeasureSO</a>

First included in: Parameter/RetailParametersEx2 (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the pickingUnitofMeasureSO attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#pickingUnitofMeasureTO name="pickingUnitofMeasureTO">pickingUnitofMeasureTO</a>

First included in: Parameter/RetailParametersEx2 (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the pickingUnitofMeasureTO attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#POItemLookupMethod name="POItemLookupMethod">POItemLookupMethod</a>

First included in: Parameter/RetailParametersEx2 (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the POItemLookupMethod attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#postedPickingNos name="postedPickingNos">postedPickingNos</a>

First included in: Parameter/RetailParametersEx2 (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the postedPickingNos attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#postedReceivingNos name="postedReceivingNos">postedReceivingNos</a>

First included in: Parameter/RetailParametersEx2 (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the postedReceivingNos attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PRLineDescription name="PRLineDescription">PRLineDescription</a>

First included in: Parameter/RetailParametersEx2 (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PRLineDescription attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#PRPostingProfitLossJournal name="PRPostingProfitLossJournal">PRPostingProfitLossJournal</a>

First included in: Parameter/RetailParametersEx2 (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PRPostingProfitLossJournal attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#receivingActivePO name="receivingActivePO">receivingActivePO</a>

First included in: Parameter/RetailParametersEx2 (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the receivingActivePO attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#receivingEnteringTypePO name="receivingEnteringTypePO">receivingEnteringTypePO</a>

First included in: Parameter/RetailParametersEx2 (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the receivingEnteringTypePO attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#receivingFrequencyofChecks name="receivingFrequencyofChecks">receivingFrequencyofChecks</a>

First included in: Parameter/RetailParametersEx2 (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the receivingFrequencyofChecks attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#receivingInfocodeIdPO name="receivingInfocodeIdPO">receivingInfocodeIdPO</a>

First included in: Parameter/RetailParametersEx2 (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the receivingInfocodeIdPO attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#receivingItemLookup name="receivingItemLookup">receivingItemLookup</a>

First included in: Parameter/RetailParametersEx2 (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the receivingItemLookup attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#receivingPosting name="receivingPosting">receivingPosting</a>

First included in: Parameter/RetailParametersEx2 (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the receivingPosting attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#receivingPostMethod name="receivingPostMethod">receivingPostMethod</a>

First included in: Parameter/RetailParametersEx2 (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the receivingPostMethod attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#receivingReasonGroup name="receivingReasonGroup">receivingReasonGroup</a>

First included in: Parameter/RetailParametersEx2 (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the receivingReasonGroup attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#receivingRFScr1leading name="receivingRFScr1leading">receivingRFScr1leading</a>

First included in: Parameter/RetailParametersEx2 (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the receivingRFScr1leading attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#receivingRFScr2leading name="receivingRFScr2leading">receivingRFScr2leading</a>

First included in: Parameter/RetailParametersEx2 (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the receivingRFScr2leading attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#receivingRFScreen1 name="receivingRFScreen1">receivingRFScreen1</a>

First included in: Parameter/RetailParametersEx2 (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the receivingRFScreen1 attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#receivingRFScreen2 name="receivingRFScreen2">receivingRFScreen2</a>

First included in: Parameter/RetailParametersEx2 (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the receivingRFScreen2 attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#receivingSearchforItemby name="receivingSearchforItemby">receivingSearchforItemby</a>

First included in: Parameter/RetailParametersEx2 (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the receivingSearchforItemby attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#receivingSourceCode name="receivingSourceCode">receivingSourceCode</a>

First included in: Parameter/RetailParametersEx2 (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the receivingSourceCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#receivingUnitofMeasurePO name="receivingUnitofMeasurePO">receivingUnitofMeasurePO</a>

First included in: Parameter/RetailParametersEx2 (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the receivingUnitofMeasurePO attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#recShowinSelectionList name="recShowinSelectionList">recShowinSelectionList</a>

First included in: Parameter/RetailParametersEx2 (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the recShowinSelectionList attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#RFDebugLogUSER name="RFDebugLogUSER">RFDebugLogUSER</a>

First included in: Parameter/RetailParametersEx2 (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RFDebugLogUSER attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RFMaxQuantityValue name="RFMaxQuantityValue">RFMaxQuantityValue</a>

First included in: Parameter/RetailParametersEx2 (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RFMaxQuantityValue attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#RFRangingScreenNo name="RFRangingScreenNo">RFRangingScreenNo</a>

First included in: Parameter/RetailParametersEx2 (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RFRangingScreenNo attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#RFRangingShelfLabel name="RFRangingShelfLabel">RFRangingShelfLabel</a>

First included in: Parameter/RetailParametersEx2 (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RFRangingShelfLabel attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RFRestartPassword name="RFRestartPassword">RFRestartPassword</a>

First included in: Parameter/RetailParametersEx2 (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RFRestartPassword attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#setCountingDate name="setCountingDate">setCountingDate</a>

First included in: Parameter/RetailParametersEx2 (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the setCountingDate attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#setupId name="setupId">setupId</a>

First included in: Parameter/RetailParametersEx2 (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the setupId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#shrinkageReasonGroup name="shrinkageReasonGroup">shrinkageReasonGroup</a>

First included in: Parameter/RetailParametersEx2 (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the shrinkageReasonGroup attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#useBatchPostingforOrders name="useBatchPostingforOrders">useBatchPostingforOrders</a>

First included in: Parameter/RetailParametersEx2 (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the useBatchPostingforOrders attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#usePrimaryVendorType name="usePrimaryVendorType">usePrimaryVendorType</a>

First included in: Parameter/RetailParametersEx2 (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the usePrimaryVendorType attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#useQtytoShip name="useQtytoShip">useQtytoShip</a>

First included in: Parameter/RetailParametersEx2 (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the useQtytoShip attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#vendorNameToDescription name="vendorNameToDescription">vendorNameToDescription</a>

First included in: Parameter/RetailParametersEx2 (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the vendorNameToDescription attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#worksheetCreationType name="worksheetCreationType">worksheetCreationType</a>

First included in: Parameter/RetailParametersEx2 (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the worksheetCreationType attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#xPickingDefaultPOSType name="xPickingDefaultPOSType">xPickingDefaultPOSType</a>

First included in: Parameter/RetailParametersEx2 (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the xPickingDefaultPOSType attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#DataAreaId name="DataAreaId">DataAreaId</a>

First included in: Parameter/RetailParametersEx2 (this entity)  

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

### <a href=#Relationship_InventJournalNameRelationshipId name="Relationship_InventJournalNameRelationshipId">Relationship_InventJournalNameRelationshipId</a>

First included in: Parameter/RetailParametersEx2 (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_InventJournalNameRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../SupplyChain/Inventory/Group/InventJournalName.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/Inventory/Group/InventJournalName.cdm.json/InventJournalName</a></td><td><a href="../../../SupplyChain/Inventory/Group/InventJournalName.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_InventJournalName1RelationshipId name="Relationship_InventJournalName1RelationshipId">Relationship_InventJournalName1RelationshipId</a>

First included in: Parameter/RetailParametersEx2 (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_InventJournalName1RelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../SupplyChain/Inventory/Group/InventJournalName.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/Inventory/Group/InventJournalName.cdm.json/InventJournalName</a></td><td><a href="../../../SupplyChain/Inventory/Group/InventJournalName.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_InventJournalName2RelationshipId name="Relationship_InventJournalName2RelationshipId">Relationship_InventJournalName2RelationshipId</a>

First included in: Parameter/RetailParametersEx2 (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_InventJournalName2RelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../SupplyChain/Inventory/Group/InventJournalName.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/Inventory/Group/InventJournalName.cdm.json/InventJournalName</a></td><td><a href="../../../SupplyChain/Inventory/Group/InventJournalName.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_InventTableRelationshipId name="Relationship_InventTableRelationshipId">Relationship_InventTableRelationshipId</a>

First included in: Parameter/RetailParametersEx2 (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_InventTableRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../SupplyChain/ProductInformationManagement/Main/InventTable.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/ProductInformationManagement/Main/InventTable.cdm.json/InventTable</a></td><td><a href="../../../SupplyChain/ProductInformationManagement/Main/InventTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_NumberSequenceTablePickerRelationshipId name="Relationship_NumberSequenceTablePickerRelationshipId">Relationship_NumberSequenceTablePickerRelationshipId</a>

First included in: Parameter/RetailParametersEx2 (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_NumberSequenceTablePickerRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../System/SystemAdministration/Framework/NumberSequenceTable.md" target="_blank">/core/operationsCommon/Tables/System/SystemAdministration/Framework/NumberSequenceTable.cdm.json/NumberSequenceTable</a></td><td><a href="../../../System/SystemAdministration/Framework/NumberSequenceTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_NumberSequenceTableReceiverRelationshipId name="Relationship_NumberSequenceTableReceiverRelationshipId">Relationship_NumberSequenceTableReceiverRelationshipId</a>

First included in: Parameter/RetailParametersEx2 (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_NumberSequenceTableReceiverRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../System/SystemAdministration/Framework/NumberSequenceTable.md" target="_blank">/core/operationsCommon/Tables/System/SystemAdministration/Framework/NumberSequenceTable.cdm.json/NumberSequenceTable</a></td><td><a href="../../../System/SystemAdministration/Framework/NumberSequenceTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_RetailInfocodeTableRelationshipId name="Relationship_RetailInfocodeTableRelationshipId">Relationship_RetailInfocodeTableRelationshipId</a>

First included in: Parameter/RetailParametersEx2 (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_RetailInfocodeTableRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../TransactionsAndOrders/Main/RetailInfocodeTable.md" target="_blank">/core/operationsCommon/Tables/Commerce/TransactionsAndOrders/Main/RetailInfocodeTable.cdm.json/RetailInfocodeTable</a></td><td><a href="../../TransactionsAndOrders/Main/RetailInfocodeTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_RetailInfocodeTable1RelationshipId name="Relationship_RetailInfocodeTable1RelationshipId">Relationship_RetailInfocodeTable1RelationshipId</a>

First included in: Parameter/RetailParametersEx2 (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_RetailInfocodeTable1RelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../TransactionsAndOrders/Main/RetailInfocodeTable.md" target="_blank">/core/operationsCommon/Tables/Commerce/TransactionsAndOrders/Main/RetailInfocodeTable.cdm.json/RetailInfocodeTable</a></td><td><a href="../../TransactionsAndOrders/Main/RetailInfocodeTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_RetailInfocodeTable2RelationshipId name="Relationship_RetailInfocodeTable2RelationshipId">Relationship_RetailInfocodeTable2RelationshipId</a>

First included in: Parameter/RetailParametersEx2 (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_RetailInfocodeTable2RelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../TransactionsAndOrders/Main/RetailInfocodeTable.md" target="_blank">/core/operationsCommon/Tables/Commerce/TransactionsAndOrders/Main/RetailInfocodeTable.cdm.json/RetailInfocodeTable</a></td><td><a href="../../TransactionsAndOrders/Main/RetailInfocodeTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_CompanyRelationshipId name="Relationship_CompanyRelationshipId">Relationship_CompanyRelationshipId</a>

First included in: Parameter/RetailParametersEx2 (this entity)  

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
