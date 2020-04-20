---
title: InventInventoryValueReportLayoutEntity - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/20/2020
ms.author: nebanfic
---

# InventInventoryValueReportLayoutEntity

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/SupplyChain/InventoryAndWarehouseManagement/InventInventoryValueReportLayoutEntity.cdm.json" target="_blank">GitHub</a>.  

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
|[ReportId](#ReportId)||<a href="InventInventoryValueReportLayoutEntity.md" target="_blank">InventoryAndWarehouseManagement/InventInventoryValueReportLayoutEntity</a>|
|[ReportName](#ReportName)||<a href="InventInventoryValueReportLayoutEntity.md" target="_blank">InventoryAndWarehouseManagement/InventInventoryValueReportLayoutEntity</a>|
|[DateIntervalCode](#DateIntervalCode)||<a href="InventInventoryValueReportLayoutEntity.md" target="_blank">InventoryAndWarehouseManagement/InventInventoryValueReportLayoutEntity</a>|
|[FilterOnDateField](#FilterOnDateField)||<a href="InventInventoryValueReportLayoutEntity.md" target="_blank">InventoryAndWarehouseManagement/InventInventoryValueReportLayoutEntity</a>|
|[DimensionSet](#DimensionSet)||<a href="InventInventoryValueReportLayoutEntity.md" target="_blank">InventoryAndWarehouseManagement/InventInventoryValueReportLayoutEntity</a>|
|[FinancialDimensionSetName](#FinancialDimensionSetName)||<a href="InventInventoryValueReportLayoutEntity.md" target="_blank">InventoryAndWarehouseManagement/InventInventoryValueReportLayoutEntity</a>|
|[IsInventoryDisplayed](#IsInventoryDisplayed)||<a href="InventInventoryValueReportLayoutEntity.md" target="_blank">InventoryAndWarehouseManagement/InventInventoryValueReportLayoutEntity</a>|
|[IsWIPDisplayed](#IsWIPDisplayed)||<a href="InventInventoryValueReportLayoutEntity.md" target="_blank">InventoryAndWarehouseManagement/InventInventoryValueReportLayoutEntity</a>|
|[IsDeferredCOGSDisplayed](#IsDeferredCOGSDisplayed)||<a href="InventInventoryValueReportLayoutEntity.md" target="_blank">InventoryAndWarehouseManagement/InventInventoryValueReportLayoutEntity</a>|
|[IsCOGSDisplayed](#IsCOGSDisplayed)||<a href="InventInventoryValueReportLayoutEntity.md" target="_blank">InventoryAndWarehouseManagement/InventInventoryValueReportLayoutEntity</a>|
|[IsProfitLossDisplayed](#IsProfitLossDisplayed)||<a href="InventInventoryValueReportLayoutEntity.md" target="_blank">InventoryAndWarehouseManagement/InventInventoryValueReportLayoutEntity</a>|
|[IsProductConfigurationTotalDisplayed](#IsProductConfigurationTotalDisplayed)||<a href="InventInventoryValueReportLayoutEntity.md" target="_blank">InventoryAndWarehouseManagement/InventInventoryValueReportLayoutEntity</a>|
|[IsProductConfigurationDisplayed](#IsProductConfigurationDisplayed)||<a href="InventInventoryValueReportLayoutEntity.md" target="_blank">InventoryAndWarehouseManagement/InventInventoryValueReportLayoutEntity</a>|
|[IsProductColorTotalDisplayed](#IsProductColorTotalDisplayed)||<a href="InventInventoryValueReportLayoutEntity.md" target="_blank">InventoryAndWarehouseManagement/InventInventoryValueReportLayoutEntity</a>|
|[IsProductColorDisplayed](#IsProductColorDisplayed)||<a href="InventInventoryValueReportLayoutEntity.md" target="_blank">InventoryAndWarehouseManagement/InventInventoryValueReportLayoutEntity</a>|
|[IsProductSizeTotalDisplayed](#IsProductSizeTotalDisplayed)||<a href="InventInventoryValueReportLayoutEntity.md" target="_blank">InventoryAndWarehouseManagement/InventInventoryValueReportLayoutEntity</a>|
|[IsProductSizeDisplayed](#IsProductSizeDisplayed)||<a href="InventInventoryValueReportLayoutEntity.md" target="_blank">InventoryAndWarehouseManagement/InventInventoryValueReportLayoutEntity</a>|
|[IsProductStyleTotalDisplayed](#IsProductStyleTotalDisplayed)||<a href="InventInventoryValueReportLayoutEntity.md" target="_blank">InventoryAndWarehouseManagement/InventInventoryValueReportLayoutEntity</a>|
|[IsProductStyleDisplayed](#IsProductStyleDisplayed)||<a href="InventInventoryValueReportLayoutEntity.md" target="_blank">InventoryAndWarehouseManagement/InventInventoryValueReportLayoutEntity</a>|
|[IsInventorySiteTotalDisplayed](#IsInventorySiteTotalDisplayed)||<a href="InventInventoryValueReportLayoutEntity.md" target="_blank">InventoryAndWarehouseManagement/InventInventoryValueReportLayoutEntity</a>|
|[IsInventorySiteDisplayed](#IsInventorySiteDisplayed)||<a href="InventInventoryValueReportLayoutEntity.md" target="_blank">InventoryAndWarehouseManagement/InventInventoryValueReportLayoutEntity</a>|
|[IsInventoryWarehouseTotalDisplayed](#IsInventoryWarehouseTotalDisplayed)||<a href="InventInventoryValueReportLayoutEntity.md" target="_blank">InventoryAndWarehouseManagement/InventInventoryValueReportLayoutEntity</a>|
|[IsInventoryWarehouseDisplayed](#IsInventoryWarehouseDisplayed)||<a href="InventInventoryValueReportLayoutEntity.md" target="_blank">InventoryAndWarehouseManagement/InventInventoryValueReportLayoutEntity</a>|
|[IsWarehouseLocationTotalDisplayed](#IsWarehouseLocationTotalDisplayed)||<a href="InventInventoryValueReportLayoutEntity.md" target="_blank">InventoryAndWarehouseManagement/InventInventoryValueReportLayoutEntity</a>|
|[IsWarehouseLocationDisplayed](#IsWarehouseLocationDisplayed)||<a href="InventInventoryValueReportLayoutEntity.md" target="_blank">InventoryAndWarehouseManagement/InventInventoryValueReportLayoutEntity</a>|
|[IsBatchNumberTotalDisplayed](#IsBatchNumberTotalDisplayed)||<a href="InventInventoryValueReportLayoutEntity.md" target="_blank">InventoryAndWarehouseManagement/InventInventoryValueReportLayoutEntity</a>|
|[IsBatchNumberDisplayed](#IsBatchNumberDisplayed)||<a href="InventInventoryValueReportLayoutEntity.md" target="_blank">InventoryAndWarehouseManagement/InventInventoryValueReportLayoutEntity</a>|
|[IsSerialNumberTotalDisplayed](#IsSerialNumberTotalDisplayed)||<a href="InventInventoryValueReportLayoutEntity.md" target="_blank">InventoryAndWarehouseManagement/InventInventoryValueReportLayoutEntity</a>|
|[IsSerialNumberDisplayed](#IsSerialNumberDisplayed)||<a href="InventInventoryValueReportLayoutEntity.md" target="_blank">InventoryAndWarehouseManagement/InventInventoryValueReportLayoutEntity</a>|
|[IsInventoryStatusTotalDisplayed](#IsInventoryStatusTotalDisplayed)||<a href="InventInventoryValueReportLayoutEntity.md" target="_blank">InventoryAndWarehouseManagement/InventInventoryValueReportLayoutEntity</a>|
|[IsInventoryStatusDisplayed](#IsInventoryStatusDisplayed)||<a href="InventInventoryValueReportLayoutEntity.md" target="_blank">InventoryAndWarehouseManagement/InventInventoryValueReportLayoutEntity</a>|
|[IsLicensePlateTotalDisplayed](#IsLicensePlateTotalDisplayed)||<a href="InventInventoryValueReportLayoutEntity.md" target="_blank">InventoryAndWarehouseManagement/InventInventoryValueReportLayoutEntity</a>|
|[IsLicensePlateDisplayed](#IsLicensePlateDisplayed)||<a href="InventInventoryValueReportLayoutEntity.md" target="_blank">InventoryAndWarehouseManagement/InventInventoryValueReportLayoutEntity</a>|
|[IsCostResourceIdDisplayed](#IsCostResourceIdDisplayed)||<a href="InventInventoryValueReportLayoutEntity.md" target="_blank">InventoryAndWarehouseManagement/InventInventoryValueReportLayoutEntity</a>|
|[IsCostResourceIdTotalDisplayed](#IsCostResourceIdTotalDisplayed)||<a href="InventInventoryValueReportLayoutEntity.md" target="_blank">InventoryAndWarehouseManagement/InventInventoryValueReportLayoutEntity</a>|
|[IsCostResourceGroupDisplayed](#IsCostResourceGroupDisplayed)||<a href="InventInventoryValueReportLayoutEntity.md" target="_blank">InventoryAndWarehouseManagement/InventInventoryValueReportLayoutEntity</a>|
|[IsCostResourceGroupTotalDisplayed](#IsCostResourceGroupTotalDisplayed)||<a href="InventInventoryValueReportLayoutEntity.md" target="_blank">InventoryAndWarehouseManagement/InventInventoryValueReportLayoutEntity</a>|
|[IsSubLedgerAndGeneralLedgerReconciled](#IsSubLedgerAndGeneralLedgerReconciled)||<a href="InventInventoryValueReportLayoutEntity.md" target="_blank">InventoryAndWarehouseManagement/InventInventoryValueReportLayoutEntity</a>|
|[ReconciledInventoryMainAccountId](#ReconciledInventoryMainAccountId)||<a href="InventInventoryValueReportLayoutEntity.md" target="_blank">InventoryAndWarehouseManagement/InventInventoryValueReportLayoutEntity</a>|
|[ReconciledInventoryMainAccountIdDisplayValue](#ReconciledInventoryMainAccountIdDisplayValue)||<a href="InventInventoryValueReportLayoutEntity.md" target="_blank">InventoryAndWarehouseManagement/InventInventoryValueReportLayoutEntity</a>|
|[ReconciledWIPMainAccountId](#ReconciledWIPMainAccountId)||<a href="InventInventoryValueReportLayoutEntity.md" target="_blank">InventoryAndWarehouseManagement/InventInventoryValueReportLayoutEntity</a>|
|[ReconciledWIPMainAccountIdDisplayValue](#ReconciledWIPMainAccountIdDisplayValue)||<a href="InventInventoryValueReportLayoutEntity.md" target="_blank">InventoryAndWarehouseManagement/InventInventoryValueReportLayoutEntity</a>|
|[ReconciledDeferredCOGSMainAccountId](#ReconciledDeferredCOGSMainAccountId)||<a href="InventInventoryValueReportLayoutEntity.md" target="_blank">InventoryAndWarehouseManagement/InventInventoryValueReportLayoutEntity</a>|
|[ReconciledDeferredCOGSMainAccountIdDisplayValue](#ReconciledDeferredCOGSMainAccountIdDisplayValue)||<a href="InventInventoryValueReportLayoutEntity.md" target="_blank">InventoryAndWarehouseManagement/InventInventoryValueReportLayoutEntity</a>|
|[ReconciledCOGSMainAccountId](#ReconciledCOGSMainAccountId)||<a href="InventInventoryValueReportLayoutEntity.md" target="_blank">InventoryAndWarehouseManagement/InventInventoryValueReportLayoutEntity</a>|
|[ReconciledCOGSMainAccountIdDisplayValue](#ReconciledCOGSMainAccountIdDisplayValue)||<a href="InventInventoryValueReportLayoutEntity.md" target="_blank">InventoryAndWarehouseManagement/InventInventoryValueReportLayoutEntity</a>|
|[ArePhysicalAndFinancialValuesSummarized](#ArePhysicalAndFinancialValuesSummarized)||<a href="InventInventoryValueReportLayoutEntity.md" target="_blank">InventoryAndWarehouseManagement/InventInventoryValueReportLayoutEntity</a>|
|[AreNonePostedSubLedgerValuesIncluded](#AreNonePostedSubLedgerValuesIncluded)||<a href="InventInventoryValueReportLayoutEntity.md" target="_blank">InventoryAndWarehouseManagement/InventInventoryValueReportLayoutEntity</a>|
|[IsAverageUnitCostDisplayed](#IsAverageUnitCostDisplayed)||<a href="InventInventoryValueReportLayoutEntity.md" target="_blank">InventoryAndWarehouseManagement/InventInventoryValueReportLayoutEntity</a>|
|[IsTotalQuantityAndValueDisplayed](#IsTotalQuantityAndValueDisplayed)||<a href="InventInventoryValueReportLayoutEntity.md" target="_blank">InventoryAndWarehouseManagement/InventInventoryValueReportLayoutEntity</a>|
|[IsCostResourceTypeLaborDisplayed](#IsCostResourceTypeLaborDisplayed)||<a href="InventInventoryValueReportLayoutEntity.md" target="_blank">InventoryAndWarehouseManagement/InventInventoryValueReportLayoutEntity</a>|
|[IsCostResourceTypeIndirectCostDisplayed](#IsCostResourceTypeIndirectCostDisplayed)||<a href="InventInventoryValueReportLayoutEntity.md" target="_blank">InventoryAndWarehouseManagement/InventInventoryValueReportLayoutEntity</a>|
|[IsCostResourceTypeDirectOutsourcingDisplayed](#IsCostResourceTypeDirectOutsourcingDisplayed)||<a href="InventInventoryValueReportLayoutEntity.md" target="_blank">InventoryAndWarehouseManagement/InventInventoryValueReportLayoutEntity</a>|
|[ReportDetailLevel](#ReportDetailLevel)||<a href="InventInventoryValueReportLayoutEntity.md" target="_blank">InventoryAndWarehouseManagement/InventInventoryValueReportLayoutEntity</a>|
|[IsSubLedgerBeginningBalanceIncluded](#IsSubLedgerBeginningBalanceIncluded)||<a href="InventInventoryValueReportLayoutEntity.md" target="_blank">InventoryAndWarehouseManagement/InventInventoryValueReportLayoutEntity</a>|
|[Relationship_COGSMainAccountIdCombinationRelationshipId](#Relationship_COGSMainAccountIdCombinationRelationshipId)||<a href="InventInventoryValueReportLayoutEntity.md" target="_blank">InventoryAndWarehouseManagement/InventInventoryValueReportLayoutEntity</a>|
|[Relationship_DeferredCOGSLedgerDimensionCombinationRelationshipId](#Relationship_DeferredCOGSLedgerDimensionCombinationRelationshipId)||<a href="InventInventoryValueReportLayoutEntity.md" target="_blank">InventoryAndWarehouseManagement/InventInventoryValueReportLayoutEntity</a>|
|[Relationship_InventoryMainAccountIdCombinationRelationshipId](#Relationship_InventoryMainAccountIdCombinationRelationshipId)||<a href="InventInventoryValueReportLayoutEntity.md" target="_blank">InventoryAndWarehouseManagement/InventInventoryValueReportLayoutEntity</a>|
|[Relationship_WIPMainAccountIdCombinationRelationshipId](#Relationship_WIPMainAccountIdCombinationRelationshipId)||<a href="InventInventoryValueReportLayoutEntity.md" target="_blank">InventoryAndWarehouseManagement/InventInventoryValueReportLayoutEntity</a>|
|[BackingTable_InventValueReportRelationshipId](#BackingTable_InventValueReportRelationshipId)||<a href="InventInventoryValueReportLayoutEntity.md" target="_blank">InventoryAndWarehouseManagement/InventInventoryValueReportLayoutEntity</a>|
|[Relationship_PrimaryCompanyContextRelationshipId](#Relationship_PrimaryCompanyContextRelationshipId)||<a href="InventInventoryValueReportLayoutEntity.md" target="_blank">InventoryAndWarehouseManagement/InventInventoryValueReportLayoutEntity</a>|

### <a href=#ReportId name="ReportId">ReportId</a>

First included in: InventoryAndWarehouseManagement/InventInventoryValueReportLayoutEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReportId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ReportName name="ReportName">ReportName</a>

First included in: InventoryAndWarehouseManagement/InventInventoryValueReportLayoutEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReportName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DateIntervalCode name="DateIntervalCode">DateIntervalCode</a>

First included in: InventoryAndWarehouseManagement/InventInventoryValueReportLayoutEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DateIntervalCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FilterOnDateField name="FilterOnDateField">FilterOnDateField</a>

First included in: InventoryAndWarehouseManagement/InventInventoryValueReportLayoutEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FilterOnDateField attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DimensionSet name="DimensionSet">DimensionSet</a>

First included in: InventoryAndWarehouseManagement/InventInventoryValueReportLayoutEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DimensionSet attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FinancialDimensionSetName name="FinancialDimensionSetName">FinancialDimensionSetName</a>

First included in: InventoryAndWarehouseManagement/InventInventoryValueReportLayoutEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FinancialDimensionSetName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsInventoryDisplayed name="IsInventoryDisplayed">IsInventoryDisplayed</a>

First included in: InventoryAndWarehouseManagement/InventInventoryValueReportLayoutEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsInventoryDisplayed attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsWIPDisplayed name="IsWIPDisplayed">IsWIPDisplayed</a>

First included in: InventoryAndWarehouseManagement/InventInventoryValueReportLayoutEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsWIPDisplayed attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsDeferredCOGSDisplayed name="IsDeferredCOGSDisplayed">IsDeferredCOGSDisplayed</a>

First included in: InventoryAndWarehouseManagement/InventInventoryValueReportLayoutEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsDeferredCOGSDisplayed attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsCOGSDisplayed name="IsCOGSDisplayed">IsCOGSDisplayed</a>

First included in: InventoryAndWarehouseManagement/InventInventoryValueReportLayoutEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsCOGSDisplayed attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsProfitLossDisplayed name="IsProfitLossDisplayed">IsProfitLossDisplayed</a>

First included in: InventoryAndWarehouseManagement/InventInventoryValueReportLayoutEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsProfitLossDisplayed attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsProductConfigurationTotalDisplayed name="IsProductConfigurationTotalDisplayed">IsProductConfigurationTotalDisplayed</a>

First included in: InventoryAndWarehouseManagement/InventInventoryValueReportLayoutEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsProductConfigurationTotalDisplayed attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsProductConfigurationDisplayed name="IsProductConfigurationDisplayed">IsProductConfigurationDisplayed</a>

First included in: InventoryAndWarehouseManagement/InventInventoryValueReportLayoutEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsProductConfigurationDisplayed attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsProductColorTotalDisplayed name="IsProductColorTotalDisplayed">IsProductColorTotalDisplayed</a>

First included in: InventoryAndWarehouseManagement/InventInventoryValueReportLayoutEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsProductColorTotalDisplayed attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsProductColorDisplayed name="IsProductColorDisplayed">IsProductColorDisplayed</a>

First included in: InventoryAndWarehouseManagement/InventInventoryValueReportLayoutEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsProductColorDisplayed attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsProductSizeTotalDisplayed name="IsProductSizeTotalDisplayed">IsProductSizeTotalDisplayed</a>

First included in: InventoryAndWarehouseManagement/InventInventoryValueReportLayoutEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsProductSizeTotalDisplayed attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsProductSizeDisplayed name="IsProductSizeDisplayed">IsProductSizeDisplayed</a>

First included in: InventoryAndWarehouseManagement/InventInventoryValueReportLayoutEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsProductSizeDisplayed attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsProductStyleTotalDisplayed name="IsProductStyleTotalDisplayed">IsProductStyleTotalDisplayed</a>

First included in: InventoryAndWarehouseManagement/InventInventoryValueReportLayoutEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsProductStyleTotalDisplayed attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsProductStyleDisplayed name="IsProductStyleDisplayed">IsProductStyleDisplayed</a>

First included in: InventoryAndWarehouseManagement/InventInventoryValueReportLayoutEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsProductStyleDisplayed attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsInventorySiteTotalDisplayed name="IsInventorySiteTotalDisplayed">IsInventorySiteTotalDisplayed</a>

First included in: InventoryAndWarehouseManagement/InventInventoryValueReportLayoutEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsInventorySiteTotalDisplayed attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsInventorySiteDisplayed name="IsInventorySiteDisplayed">IsInventorySiteDisplayed</a>

First included in: InventoryAndWarehouseManagement/InventInventoryValueReportLayoutEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsInventorySiteDisplayed attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsInventoryWarehouseTotalDisplayed name="IsInventoryWarehouseTotalDisplayed">IsInventoryWarehouseTotalDisplayed</a>

First included in: InventoryAndWarehouseManagement/InventInventoryValueReportLayoutEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsInventoryWarehouseTotalDisplayed attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsInventoryWarehouseDisplayed name="IsInventoryWarehouseDisplayed">IsInventoryWarehouseDisplayed</a>

First included in: InventoryAndWarehouseManagement/InventInventoryValueReportLayoutEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsInventoryWarehouseDisplayed attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsWarehouseLocationTotalDisplayed name="IsWarehouseLocationTotalDisplayed">IsWarehouseLocationTotalDisplayed</a>

First included in: InventoryAndWarehouseManagement/InventInventoryValueReportLayoutEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsWarehouseLocationTotalDisplayed attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsWarehouseLocationDisplayed name="IsWarehouseLocationDisplayed">IsWarehouseLocationDisplayed</a>

First included in: InventoryAndWarehouseManagement/InventInventoryValueReportLayoutEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsWarehouseLocationDisplayed attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsBatchNumberTotalDisplayed name="IsBatchNumberTotalDisplayed">IsBatchNumberTotalDisplayed</a>

First included in: InventoryAndWarehouseManagement/InventInventoryValueReportLayoutEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsBatchNumberTotalDisplayed attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsBatchNumberDisplayed name="IsBatchNumberDisplayed">IsBatchNumberDisplayed</a>

First included in: InventoryAndWarehouseManagement/InventInventoryValueReportLayoutEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsBatchNumberDisplayed attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsSerialNumberTotalDisplayed name="IsSerialNumberTotalDisplayed">IsSerialNumberTotalDisplayed</a>

First included in: InventoryAndWarehouseManagement/InventInventoryValueReportLayoutEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsSerialNumberTotalDisplayed attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsSerialNumberDisplayed name="IsSerialNumberDisplayed">IsSerialNumberDisplayed</a>

First included in: InventoryAndWarehouseManagement/InventInventoryValueReportLayoutEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsSerialNumberDisplayed attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsInventoryStatusTotalDisplayed name="IsInventoryStatusTotalDisplayed">IsInventoryStatusTotalDisplayed</a>

First included in: InventoryAndWarehouseManagement/InventInventoryValueReportLayoutEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsInventoryStatusTotalDisplayed attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsInventoryStatusDisplayed name="IsInventoryStatusDisplayed">IsInventoryStatusDisplayed</a>

First included in: InventoryAndWarehouseManagement/InventInventoryValueReportLayoutEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsInventoryStatusDisplayed attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsLicensePlateTotalDisplayed name="IsLicensePlateTotalDisplayed">IsLicensePlateTotalDisplayed</a>

First included in: InventoryAndWarehouseManagement/InventInventoryValueReportLayoutEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsLicensePlateTotalDisplayed attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsLicensePlateDisplayed name="IsLicensePlateDisplayed">IsLicensePlateDisplayed</a>

First included in: InventoryAndWarehouseManagement/InventInventoryValueReportLayoutEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsLicensePlateDisplayed attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsCostResourceIdDisplayed name="IsCostResourceIdDisplayed">IsCostResourceIdDisplayed</a>

First included in: InventoryAndWarehouseManagement/InventInventoryValueReportLayoutEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsCostResourceIdDisplayed attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsCostResourceIdTotalDisplayed name="IsCostResourceIdTotalDisplayed">IsCostResourceIdTotalDisplayed</a>

First included in: InventoryAndWarehouseManagement/InventInventoryValueReportLayoutEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsCostResourceIdTotalDisplayed attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsCostResourceGroupDisplayed name="IsCostResourceGroupDisplayed">IsCostResourceGroupDisplayed</a>

First included in: InventoryAndWarehouseManagement/InventInventoryValueReportLayoutEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsCostResourceGroupDisplayed attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsCostResourceGroupTotalDisplayed name="IsCostResourceGroupTotalDisplayed">IsCostResourceGroupTotalDisplayed</a>

First included in: InventoryAndWarehouseManagement/InventInventoryValueReportLayoutEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsCostResourceGroupTotalDisplayed attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsSubLedgerAndGeneralLedgerReconciled name="IsSubLedgerAndGeneralLedgerReconciled">IsSubLedgerAndGeneralLedgerReconciled</a>

First included in: InventoryAndWarehouseManagement/InventInventoryValueReportLayoutEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsSubLedgerAndGeneralLedgerReconciled attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ReconciledInventoryMainAccountId name="ReconciledInventoryMainAccountId">ReconciledInventoryMainAccountId</a>

First included in: InventoryAndWarehouseManagement/InventInventoryValueReportLayoutEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReconciledInventoryMainAccountId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ReconciledInventoryMainAccountIdDisplayValue name="ReconciledInventoryMainAccountIdDisplayValue">ReconciledInventoryMainAccountIdDisplayValue</a>

First included in: InventoryAndWarehouseManagement/InventInventoryValueReportLayoutEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReconciledInventoryMainAccountIdDisplayValue attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ReconciledWIPMainAccountId name="ReconciledWIPMainAccountId">ReconciledWIPMainAccountId</a>

First included in: InventoryAndWarehouseManagement/InventInventoryValueReportLayoutEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReconciledWIPMainAccountId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ReconciledWIPMainAccountIdDisplayValue name="ReconciledWIPMainAccountIdDisplayValue">ReconciledWIPMainAccountIdDisplayValue</a>

First included in: InventoryAndWarehouseManagement/InventInventoryValueReportLayoutEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReconciledWIPMainAccountIdDisplayValue attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ReconciledDeferredCOGSMainAccountId name="ReconciledDeferredCOGSMainAccountId">ReconciledDeferredCOGSMainAccountId</a>

First included in: InventoryAndWarehouseManagement/InventInventoryValueReportLayoutEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReconciledDeferredCOGSMainAccountId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ReconciledDeferredCOGSMainAccountIdDisplayValue name="ReconciledDeferredCOGSMainAccountIdDisplayValue">ReconciledDeferredCOGSMainAccountIdDisplayValue</a>

First included in: InventoryAndWarehouseManagement/InventInventoryValueReportLayoutEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReconciledDeferredCOGSMainAccountIdDisplayValue attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ReconciledCOGSMainAccountId name="ReconciledCOGSMainAccountId">ReconciledCOGSMainAccountId</a>

First included in: InventoryAndWarehouseManagement/InventInventoryValueReportLayoutEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReconciledCOGSMainAccountId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ReconciledCOGSMainAccountIdDisplayValue name="ReconciledCOGSMainAccountIdDisplayValue">ReconciledCOGSMainAccountIdDisplayValue</a>

First included in: InventoryAndWarehouseManagement/InventInventoryValueReportLayoutEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReconciledCOGSMainAccountIdDisplayValue attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ArePhysicalAndFinancialValuesSummarized name="ArePhysicalAndFinancialValuesSummarized">ArePhysicalAndFinancialValuesSummarized</a>

First included in: InventoryAndWarehouseManagement/InventInventoryValueReportLayoutEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ArePhysicalAndFinancialValuesSummarized attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AreNonePostedSubLedgerValuesIncluded name="AreNonePostedSubLedgerValuesIncluded">AreNonePostedSubLedgerValuesIncluded</a>

First included in: InventoryAndWarehouseManagement/InventInventoryValueReportLayoutEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AreNonePostedSubLedgerValuesIncluded attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsAverageUnitCostDisplayed name="IsAverageUnitCostDisplayed">IsAverageUnitCostDisplayed</a>

First included in: InventoryAndWarehouseManagement/InventInventoryValueReportLayoutEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsAverageUnitCostDisplayed attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsTotalQuantityAndValueDisplayed name="IsTotalQuantityAndValueDisplayed">IsTotalQuantityAndValueDisplayed</a>

First included in: InventoryAndWarehouseManagement/InventInventoryValueReportLayoutEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsTotalQuantityAndValueDisplayed attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsCostResourceTypeLaborDisplayed name="IsCostResourceTypeLaborDisplayed">IsCostResourceTypeLaborDisplayed</a>

First included in: InventoryAndWarehouseManagement/InventInventoryValueReportLayoutEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsCostResourceTypeLaborDisplayed attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsCostResourceTypeIndirectCostDisplayed name="IsCostResourceTypeIndirectCostDisplayed">IsCostResourceTypeIndirectCostDisplayed</a>

First included in: InventoryAndWarehouseManagement/InventInventoryValueReportLayoutEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsCostResourceTypeIndirectCostDisplayed attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsCostResourceTypeDirectOutsourcingDisplayed name="IsCostResourceTypeDirectOutsourcingDisplayed">IsCostResourceTypeDirectOutsourcingDisplayed</a>

First included in: InventoryAndWarehouseManagement/InventInventoryValueReportLayoutEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsCostResourceTypeDirectOutsourcingDisplayed attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ReportDetailLevel name="ReportDetailLevel">ReportDetailLevel</a>

First included in: InventoryAndWarehouseManagement/InventInventoryValueReportLayoutEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReportDetailLevel attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsSubLedgerBeginningBalanceIncluded name="IsSubLedgerBeginningBalanceIncluded">IsSubLedgerBeginningBalanceIncluded</a>

First included in: InventoryAndWarehouseManagement/InventInventoryValueReportLayoutEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsSubLedgerBeginningBalanceIncluded attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_COGSMainAccountIdCombinationRelationshipId name="Relationship_COGSMainAccountIdCombinationRelationshipId">Relationship_COGSMainAccountIdCombinationRelationshipId</a>

First included in: InventoryAndWarehouseManagement/InventInventoryValueReportLayoutEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_COGSMainAccountIdCombinationRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_DeferredCOGSLedgerDimensionCombinationRelationshipId name="Relationship_DeferredCOGSLedgerDimensionCombinationRelationshipId">Relationship_DeferredCOGSLedgerDimensionCombinationRelationshipId</a>

First included in: InventoryAndWarehouseManagement/InventInventoryValueReportLayoutEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_DeferredCOGSLedgerDimensionCombinationRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_InventoryMainAccountIdCombinationRelationshipId name="Relationship_InventoryMainAccountIdCombinationRelationshipId">Relationship_InventoryMainAccountIdCombinationRelationshipId</a>

First included in: InventoryAndWarehouseManagement/InventInventoryValueReportLayoutEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_InventoryMainAccountIdCombinationRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_WIPMainAccountIdCombinationRelationshipId name="Relationship_WIPMainAccountIdCombinationRelationshipId">Relationship_WIPMainAccountIdCombinationRelationshipId</a>

First included in: InventoryAndWarehouseManagement/InventInventoryValueReportLayoutEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_WIPMainAccountIdCombinationRelationshipId attribute are listed below.</summary>

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

### <a href=#BackingTable_InventValueReportRelationshipId name="BackingTable_InventValueReportRelationshipId">BackingTable_InventValueReportRelationshipId</a>

First included in: InventoryAndWarehouseManagement/InventInventoryValueReportLayoutEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_InventValueReportRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/SupplyChain/Inventory/Main/InventValueReport.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/Inventory/Main/InventValueReport.cdm.json/InventValueReport</a></td><td><a href="../../../Tables/SupplyChain/Inventory/Main/InventValueReport.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PrimaryCompanyContextRelationshipId name="Relationship_PrimaryCompanyContextRelationshipId">Relationship_PrimaryCompanyContextRelationshipId</a>

First included in: InventoryAndWarehouseManagement/InventInventoryValueReportLayoutEntity (this entity)  

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
