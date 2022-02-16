---
title: ProdParameters in Parameter - Common Data Model | Microsoft Docs
description: undefined
author: llawwaii

ms.reviewer: deonhe
ms.topic: article
ms.date: 8/7/2020
ms.author: weiluo
---

# Production parameters in Parameter(ProdParameters)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Tables/SupplyChain/ProductionControl/Parameter/ProdParameters.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[ProdParameters/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.1"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Production parameters</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="ProdParameters.md" target="_blank">Parameter/ProdParameters</a>|
|[AutoReportFinished](#AutoReportFinished)||<a href="ProdParameters.md" target="_blank">Parameter/ProdParameters</a>|
|[BOMJournalDrawNegative](#BOMJournalDrawNegative)||<a href="ProdParameters.md" target="_blank">Parameter/ProdParameters</a>|
|[BOMJournalReducePhysical](#BOMJournalReducePhysical)||<a href="ProdParameters.md" target="_blank">Parameter/ProdParameters</a>|
|[InventControlProposal](#InventControlProposal)||<a href="ProdParameters.md" target="_blank">Parameter/ProdParameters</a>|
|[InventCostProdRecalcMultiBundleSize](#InventCostProdRecalcMultiBundleSize)||<a href="ProdParameters.md" target="_blank">Parameter/ProdParameters</a>|
|[ItemReservation](#ItemReservation)||<a href="ProdParameters.md" target="_blank">Parameter/ProdParameters</a>|
|[JournalAcceptError](#JournalAcceptError)||<a href="ProdParameters.md" target="_blank">Parameter/ProdParameters</a>|
|[Key](#Key)||<a href="ProdParameters.md" target="_blank">Parameter/ProdParameters</a>|
|[LeanCostEnableFullBatchParallelization](#LeanCostEnableFullBatchParallelization)||<a href="ProdParameters.md" target="_blank">Parameter/ProdParameters</a>|
|[LeanCostingTimeBucketPeriod](#LeanCostingTimeBucketPeriod)||<a href="ProdParameters.md" target="_blank">Parameter/ProdParameters</a>|
|[LeanCostingTimeBucketPeriodUnit](#LeanCostingTimeBucketPeriodUnit)||<a href="ProdParameters.md" target="_blank">Parameter/ProdParameters</a>|
|[LeanCostSplitLedgerVoucherTransactions](#LeanCostSplitLedgerVoucherTransactions)||<a href="ProdParameters.md" target="_blank">Parameter/ProdParameters</a>|
|[PmfAlertNonStdVersionUsage](#PmfAlertNonStdVersionUsage)||<a href="ProdParameters.md" target="_blank">Parameter/ProdParameters</a>|
|[PmfBurdenCostCategory](#PmfBurdenCostCategory)||<a href="ProdParameters.md" target="_blank">Parameter/ProdParameters</a>|
|[ProdAutoPickList](#ProdAutoPickList)||<a href="ProdParameters.md" target="_blank">Parameter/ProdParameters</a>|
|[ProdAutoPurchCollectPerBuyer](#ProdAutoPurchCollectPerBuyer)||<a href="ProdParameters.md" target="_blank">Parameter/ProdParameters</a>|
|[ProdAutoPurchCollectPerPurchAgreement](#ProdAutoPurchCollectPerPurchAgreement)||<a href="ProdParameters.md" target="_blank">Parameter/ProdParameters</a>|
|[ProdAutoPurchCollectPerVendor](#ProdAutoPurchCollectPerVendor)||<a href="ProdParameters.md" target="_blank">Parameter/ProdParameters</a>|
|[ProdAutoPurchSearchPurchAgreement](#ProdAutoPurchSearchPurchAgreement)||<a href="ProdParameters.md" target="_blank">Parameter/ProdParameters</a>|
|[ProdParamInventDimLookup](#ProdParamInventDimLookup)||<a href="ProdParameters.md" target="_blank">Parameter/ProdParameters</a>|
|[ProdPostingType](#ProdPostingType)||<a href="ProdParameters.md" target="_blank">Parameter/ProdParameters</a>|
|[ProductionFlowDefaultQuantityUnit](#ProductionFlowDefaultQuantityUnit)||<a href="ProdParameters.md" target="_blank">Parameter/ProdParameters</a>|
|[ProductionFlowDefaultTimeUnit](#ProductionFlowDefaultTimeUnit)||<a href="ProdParameters.md" target="_blank">Parameter/ProdParameters</a>|
|[ProductionInstructionDocumentType](#ProductionInstructionDocumentType)||<a href="ProdParameters.md" target="_blank">Parameter/ProdParameters</a>|
|[ProdWHSReleasePolicy](#ProdWHSReleasePolicy)||<a href="ProdParameters.md" target="_blank">Parameter/ProdParameters</a>|
|[ProfitSet](#ProfitSet)||<a href="ProdParameters.md" target="_blank">Parameter/ProdParameters</a>|
|[RouteAutoPickList](#RouteAutoPickList)||<a href="ProdParameters.md" target="_blank">Parameter/ProdParameters</a>|
|[SkipUpdateOfProdCalcTransWhenPosting](#SkipUpdateOfProdCalcTransWhenPosting)||<a href="ProdParameters.md" target="_blank">Parameter/ProdParameters</a>|
|[MachineNotRespondingThresholdMins](#MachineNotRespondingThresholdMins)||<a href="ProdParameters.md" target="_blank">Parameter/ProdParameters</a>|
|[DataAreaId](#DataAreaId)||<a href="ProdParameters.md" target="_blank">Parameter/ProdParameters</a>|
|[Relationship_DocuTypeRelationshipId](#Relationship_DocuTypeRelationshipId)||<a href="ProdParameters.md" target="_blank">Parameter/ProdParameters</a>|
|[Relationship_PmfBurdenCostCategoryRelationshipId](#Relationship_PmfBurdenCostCategoryRelationshipId)||<a href="ProdParameters.md" target="_blank">Parameter/ProdParameters</a>|
|[Relationship_CompanyRelationshipId](#Relationship_CompanyRelationshipId)||<a href="ProdParameters.md" target="_blank">Parameter/ProdParameters</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: Parameter/ProdParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[ProdParameters/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#AutoReportFinished name="AutoReportFinished">AutoReportFinished</a>

First included in: Parameter/ProdParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AutoReportFinished attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#BOMJournalDrawNegative name="BOMJournalDrawNegative">BOMJournalDrawNegative</a>

First included in: Parameter/ProdParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BOMJournalDrawNegative attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#BOMJournalReducePhysical name="BOMJournalReducePhysical">BOMJournalReducePhysical</a>

First included in: Parameter/ProdParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BOMJournalReducePhysical attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#InventControlProposal name="InventControlProposal">InventControlProposal</a>

First included in: Parameter/ProdParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InventControlProposal attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#InventCostProdRecalcMultiBundleSize name="InventCostProdRecalcMultiBundleSize">InventCostProdRecalcMultiBundleSize</a>

First included in: Parameter/ProdParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InventCostProdRecalcMultiBundleSize attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#ItemReservation name="ItemReservation">ItemReservation</a>

First included in: Parameter/ProdParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ItemReservation attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#JournalAcceptError name="JournalAcceptError">JournalAcceptError</a>

First included in: Parameter/ProdParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the JournalAcceptError attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#Key name="Key">Key</a>

First included in: Parameter/ProdParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Key attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.readOnly**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#LeanCostEnableFullBatchParallelization name="LeanCostEnableFullBatchParallelization">LeanCostEnableFullBatchParallelization</a>

First included in: Parameter/ProdParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LeanCostEnableFullBatchParallelization attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#LeanCostingTimeBucketPeriod name="LeanCostingTimeBucketPeriod">LeanCostingTimeBucketPeriod</a>

First included in: Parameter/ProdParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Lean costing time bucket period</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LeanCostingTimeBucketPeriod attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Lean costing time bucket period</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#LeanCostingTimeBucketPeriodUnit name="LeanCostingTimeBucketPeriodUnit">LeanCostingTimeBucketPeriodUnit</a>

First included in: Parameter/ProdParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LeanCostingTimeBucketPeriodUnit attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#LeanCostSplitLedgerVoucherTransactions name="LeanCostSplitLedgerVoucherTransactions">LeanCostSplitLedgerVoucherTransactions</a>

First included in: Parameter/ProdParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LeanCostSplitLedgerVoucherTransactions attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#PmfAlertNonStdVersionUsage name="PmfAlertNonStdVersionUsage">PmfAlertNonStdVersionUsage</a>

First included in: Parameter/ProdParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Alert user on non-standard version usage</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PmfAlertNonStdVersionUsage attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Alert user on non-standard version usage</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#PmfBurdenCostCategory name="PmfBurdenCostCategory">PmfBurdenCostCategory</a>

First included in: Parameter/ProdParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Burden cost category</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PmfBurdenCostCategory attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Burden cost category</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProdAutoPickList name="ProdAutoPickList">ProdAutoPickList</a>

First included in: Parameter/ProdParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProdAutoPickList attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#ProdAutoPurchCollectPerBuyer name="ProdAutoPurchCollectPerBuyer">ProdAutoPurchCollectPerBuyer</a>

First included in: Parameter/ProdParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProdAutoPurchCollectPerBuyer attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#ProdAutoPurchCollectPerPurchAgreement name="ProdAutoPurchCollectPerPurchAgreement">ProdAutoPurchCollectPerPurchAgreement</a>

First included in: Parameter/ProdParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProdAutoPurchCollectPerPurchAgreement attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#ProdAutoPurchCollectPerVendor name="ProdAutoPurchCollectPerVendor">ProdAutoPurchCollectPerVendor</a>

First included in: Parameter/ProdParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProdAutoPurchCollectPerVendor attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#ProdAutoPurchSearchPurchAgreement name="ProdAutoPurchSearchPurchAgreement">ProdAutoPurchSearchPurchAgreement</a>

First included in: Parameter/ProdParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProdAutoPurchSearchPurchAgreement attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#ProdParamInventDimLookup name="ProdParamInventDimLookup">ProdParamInventDimLookup</a>

First included in: Parameter/ProdParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProdParamInventDimLookup attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#ProdPostingType name="ProdPostingType">ProdPostingType</a>

First included in: Parameter/ProdParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProdPostingType attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#ProductionFlowDefaultQuantityUnit name="ProductionFlowDefaultQuantityUnit">ProductionFlowDefaultQuantityUnit</a>

First included in: Parameter/ProdParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Default quantity unit</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProductionFlowDefaultQuantityUnit attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Default quantity unit</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#ProductionFlowDefaultTimeUnit name="ProductionFlowDefaultTimeUnit">ProductionFlowDefaultTimeUnit</a>

First included in: Parameter/ProdParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Default time unit</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProductionFlowDefaultTimeUnit attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Default time unit</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#ProductionInstructionDocumentType name="ProductionInstructionDocumentType">ProductionInstructionDocumentType</a>

First included in: Parameter/ProdParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProductionInstructionDocumentType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProdWHSReleasePolicy name="ProdWHSReleasePolicy">ProdWHSReleasePolicy</a>

First included in: Parameter/ProdParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Requirement for material reservation</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProdWHSReleasePolicy attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Requirement for material reservation</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#ProfitSet name="ProfitSet">ProfitSet</a>

First included in: Parameter/ProdParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProfitSet attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#RouteAutoPickList name="RouteAutoPickList">RouteAutoPickList</a>

First included in: Parameter/ProdParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RouteAutoPickList attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#SkipUpdateOfProdCalcTransWhenPosting name="SkipUpdateOfProdCalcTransWhenPosting">SkipUpdateOfProdCalcTransWhenPosting</a>

First included in: Parameter/ProdParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Defer updates of cost calculation until  production order reaches ended status.</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SkipUpdateOfProdCalcTransWhenPosting attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Defer updates of cost calculation until  production order reaches ended status.</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#MachineNotRespondingThresholdMins name="MachineNotRespondingThresholdMins">MachineNotRespondingThresholdMins</a>

First included in: Parameter/ProdParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MachineNotRespondingThresholdMins attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#DataAreaId name="DataAreaId">DataAreaId</a>

First included in: Parameter/ProdParameters (this entity)  

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

### <a href=#Relationship_DocuTypeRelationshipId name="Relationship_DocuTypeRelationshipId">Relationship_DocuTypeRelationshipId</a>

First included in: Parameter/ProdParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_DocuTypeRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../System/SystemAdministration/Group/DocuType.md" target="_blank">/core/operationsCommon/Tables/System/SystemAdministration/Group/DocuType.cdm.json/DocuType</a></td><td><a href="../../../System/SystemAdministration/Group/DocuType.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PmfBurdenCostCategoryRelationshipId name="Relationship_PmfBurdenCostCategoryRelationshipId">Relationship_PmfBurdenCostCategoryRelationshipId</a>

First included in: Parameter/ProdParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_PmfBurdenCostCategoryRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Group/RouteCostCategory.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/ProductionControl/Group/RouteCostCategory.cdm.json/RouteCostCategory</a></td><td><a href="../Group/RouteCostCategory.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_CompanyRelationshipId name="Relationship_CompanyRelationshipId">Relationship_CompanyRelationshipId</a>

First included in: Parameter/ProdParameters (this entity)  

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
