---
title: InventItemPriceComparisonStorageEntity - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/29/2020
ms.author: nebanfic
---

# Compare item prices

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/SupplyChain/InventoryAndWarehouseManagement/InventItemPriceComparisonStorageEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Compare item prices</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[ExecutionName](#ExecutionName)||<a href="InventItemPriceComparisonStorageEntity.md" target="_blank">InventoryAndWarehouseManagement/InventItemPriceComparisonStorageEntity</a>|
|[ExecutionTime](#ExecutionTime)||<a href="InventItemPriceComparisonStorageEntity.md" target="_blank">InventoryAndWarehouseManagement/InventItemPriceComparisonStorageEntity</a>|
|[ItemNumber](#ItemNumber)||<a href="InventItemPriceComparisonStorageEntity.md" target="_blank">InventoryAndWarehouseManagement/InventItemPriceComparisonStorageEntity</a>|
|[ProductName](#ProductName)||<a href="InventItemPriceComparisonStorageEntity.md" target="_blank">InventoryAndWarehouseManagement/InventItemPriceComparisonStorageEntity</a>|
|[ProductColorId](#ProductColorId)||<a href="InventItemPriceComparisonStorageEntity.md" target="_blank">InventoryAndWarehouseManagement/InventItemPriceComparisonStorageEntity</a>|
|[ProductSizeId](#ProductSizeId)||<a href="InventItemPriceComparisonStorageEntity.md" target="_blank">InventoryAndWarehouseManagement/InventItemPriceComparisonStorageEntity</a>|
|[ProductStyleId](#ProductStyleId)||<a href="InventItemPriceComparisonStorageEntity.md" target="_blank">InventoryAndWarehouseManagement/InventItemPriceComparisonStorageEntity</a>|
|[ProductVersionId](#ProductVersionId)||<a href="InventItemPriceComparisonStorageEntity.md" target="_blank">InventoryAndWarehouseManagement/InventItemPriceComparisonStorageEntity</a>|
|[ProductConfigurationId](#ProductConfigurationId)||<a href="InventItemPriceComparisonStorageEntity.md" target="_blank">InventoryAndWarehouseManagement/InventItemPriceComparisonStorageEntity</a>|
|[OnHandQuantity](#OnHandQuantity)||<a href="InventItemPriceComparisonStorageEntity.md" target="_blank">InventoryAndWarehouseManagement/InventItemPriceComparisonStorageEntity</a>|
|[OperationalSiteId](#OperationalSiteId)||<a href="InventItemPriceComparisonStorageEntity.md" target="_blank">InventoryAndWarehouseManagement/InventItemPriceComparisonStorageEntity</a>|
|[CostGroupId](#CostGroupId)||<a href="InventItemPriceComparisonStorageEntity.md" target="_blank">InventoryAndWarehouseManagement/InventItemPriceComparisonStorageEntity</a>|
|[CostGroupType](#CostGroupType)||<a href="InventItemPriceComparisonStorageEntity.md" target="_blank">InventoryAndWarehouseManagement/InventItemPriceComparisonStorageEntity</a>|
|[CostLevel](#CostLevel)||<a href="InventItemPriceComparisonStorageEntity.md" target="_blank">InventoryAndWarehouseManagement/InventItemPriceComparisonStorageEntity</a>|
|[DefaultOrderType](#DefaultOrderType)||<a href="InventItemPriceComparisonStorageEntity.md" target="_blank">InventoryAndWarehouseManagement/InventItemPriceComparisonStorageEntity</a>|
|[CompareCostCalculationMethod](#CompareCostCalculationMethod)||<a href="InventItemPriceComparisonStorageEntity.md" target="_blank">InventoryAndWarehouseManagement/InventItemPriceComparisonStorageEntity</a>|
|[CompareFromDate](#CompareFromDate)||<a href="InventItemPriceComparisonStorageEntity.md" target="_blank">InventoryAndWarehouseManagement/InventItemPriceComparisonStorageEntity</a>|
|[ComparePriceCharges](#ComparePriceCharges)||<a href="InventItemPriceComparisonStorageEntity.md" target="_blank">InventoryAndWarehouseManagement/InventItemPriceComparisonStorageEntity</a>|
|[CompareOnhandValue](#CompareOnhandValue)||<a href="InventItemPriceComparisonStorageEntity.md" target="_blank">InventoryAndWarehouseManagement/InventItemPriceComparisonStorageEntity</a>|
|[ComparePrice](#ComparePrice)||<a href="InventItemPriceComparisonStorageEntity.md" target="_blank">InventoryAndWarehouseManagement/InventItemPriceComparisonStorageEntity</a>|
|[ComparePriceIsPriceIncludingCharges](#ComparePriceIsPriceIncludingCharges)||<a href="InventItemPriceComparisonStorageEntity.md" target="_blank">InventoryAndWarehouseManagement/InventItemPriceComparisonStorageEntity</a>|
|[CompareChargesQuantity](#CompareChargesQuantity)||<a href="InventItemPriceComparisonStorageEntity.md" target="_blank">InventoryAndWarehouseManagement/InventItemPriceComparisonStorageEntity</a>|
|[ComparePriceQuantity](#ComparePriceQuantity)||<a href="InventItemPriceComparisonStorageEntity.md" target="_blank">InventoryAndWarehouseManagement/InventItemPriceComparisonStorageEntity</a>|
|[CompareUnitSymbol](#CompareUnitSymbol)||<a href="InventItemPriceComparisonStorageEntity.md" target="_blank">InventoryAndWarehouseManagement/InventItemPriceComparisonStorageEntity</a>|
|[CompareUnitPrice](#CompareUnitPrice)||<a href="InventItemPriceComparisonStorageEntity.md" target="_blank">InventoryAndWarehouseManagement/InventItemPriceComparisonStorageEntity</a>|
|[CompareToCostCalculationMethod](#CompareToCostCalculationMethod)||<a href="InventItemPriceComparisonStorageEntity.md" target="_blank">InventoryAndWarehouseManagement/InventItemPriceComparisonStorageEntity</a>|
|[CompareToFromDate](#CompareToFromDate)||<a href="InventItemPriceComparisonStorageEntity.md" target="_blank">InventoryAndWarehouseManagement/InventItemPriceComparisonStorageEntity</a>|
|[CompareToPriceCharges](#CompareToPriceCharges)||<a href="InventItemPriceComparisonStorageEntity.md" target="_blank">InventoryAndWarehouseManagement/InventItemPriceComparisonStorageEntity</a>|
|[CompareToOnhandValue](#CompareToOnhandValue)||<a href="InventItemPriceComparisonStorageEntity.md" target="_blank">InventoryAndWarehouseManagement/InventItemPriceComparisonStorageEntity</a>|
|[CompareToPrice](#CompareToPrice)||<a href="InventItemPriceComparisonStorageEntity.md" target="_blank">InventoryAndWarehouseManagement/InventItemPriceComparisonStorageEntity</a>|
|[CompareToIsPriceIncludingCharges](#CompareToIsPriceIncludingCharges)||<a href="InventItemPriceComparisonStorageEntity.md" target="_blank">InventoryAndWarehouseManagement/InventItemPriceComparisonStorageEntity</a>|
|[CompareToChargesQuantity](#CompareToChargesQuantity)||<a href="InventItemPriceComparisonStorageEntity.md" target="_blank">InventoryAndWarehouseManagement/InventItemPriceComparisonStorageEntity</a>|
|[CompareToPriceQuantity](#CompareToPriceQuantity)||<a href="InventItemPriceComparisonStorageEntity.md" target="_blank">InventoryAndWarehouseManagement/InventItemPriceComparisonStorageEntity</a>|
|[CompareToUnitSymbol](#CompareToUnitSymbol)||<a href="InventItemPriceComparisonStorageEntity.md" target="_blank">InventoryAndWarehouseManagement/InventItemPriceComparisonStorageEntity</a>|
|[CompareToUnitPrice](#CompareToUnitPrice)||<a href="InventItemPriceComparisonStorageEntity.md" target="_blank">InventoryAndWarehouseManagement/InventItemPriceComparisonStorageEntity</a>|
|[NetChangeUnitPrice](#NetChangeUnitPrice)||<a href="InventItemPriceComparisonStorageEntity.md" target="_blank">InventoryAndWarehouseManagement/InventItemPriceComparisonStorageEntity</a>|
|[NetChangeOnhandValue](#NetChangeOnhandValue)||<a href="InventItemPriceComparisonStorageEntity.md" target="_blank">InventoryAndWarehouseManagement/InventItemPriceComparisonStorageEntity</a>|
|[BackingTable_InventItemPriceCompareStorageDetailsRelationshipId](#BackingTable_InventItemPriceCompareStorageDetailsRelationshipId)||<a href="InventItemPriceComparisonStorageEntity.md" target="_blank">InventoryAndWarehouseManagement/InventItemPriceComparisonStorageEntity</a>|
|[Relationship_PrimaryCompanyContextRelationshipId](#Relationship_PrimaryCompanyContextRelationshipId)||<a href="InventItemPriceComparisonStorageEntity.md" target="_blank">InventoryAndWarehouseManagement/InventItemPriceComparisonStorageEntity</a>|

### <a href=#ExecutionName name="ExecutionName">ExecutionName</a>

First included in: InventoryAndWarehouseManagement/InventItemPriceComparisonStorageEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ExecutionName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ExecutionTime name="ExecutionTime">ExecutionTime</a>

First included in: InventoryAndWarehouseManagement/InventItemPriceComparisonStorageEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ExecutionTime attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ItemNumber name="ItemNumber">ItemNumber</a>

First included in: InventoryAndWarehouseManagement/InventItemPriceComparisonStorageEntity (this entity)  

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

### <a href=#ProductName name="ProductName">ProductName</a>

First included in: InventoryAndWarehouseManagement/InventItemPriceComparisonStorageEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProductName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProductColorId name="ProductColorId">ProductColorId</a>

First included in: InventoryAndWarehouseManagement/InventItemPriceComparisonStorageEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProductColorId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProductSizeId name="ProductSizeId">ProductSizeId</a>

First included in: InventoryAndWarehouseManagement/InventItemPriceComparisonStorageEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProductSizeId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProductStyleId name="ProductStyleId">ProductStyleId</a>

First included in: InventoryAndWarehouseManagement/InventItemPriceComparisonStorageEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProductStyleId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProductVersionId name="ProductVersionId">ProductVersionId</a>

First included in: InventoryAndWarehouseManagement/InventItemPriceComparisonStorageEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProductVersionId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProductConfigurationId name="ProductConfigurationId">ProductConfigurationId</a>

First included in: InventoryAndWarehouseManagement/InventItemPriceComparisonStorageEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProductConfigurationId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#OnHandQuantity name="OnHandQuantity">OnHandQuantity</a>

First included in: InventoryAndWarehouseManagement/InventItemPriceComparisonStorageEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OnHandQuantity attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#OperationalSiteId name="OperationalSiteId">OperationalSiteId</a>

First included in: InventoryAndWarehouseManagement/InventItemPriceComparisonStorageEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OperationalSiteId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CostGroupId name="CostGroupId">CostGroupId</a>

First included in: InventoryAndWarehouseManagement/InventItemPriceComparisonStorageEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CostGroupId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CostGroupType name="CostGroupType">CostGroupType</a>

First included in: InventoryAndWarehouseManagement/InventItemPriceComparisonStorageEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CostGroupType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CostLevel name="CostLevel">CostLevel</a>

First included in: InventoryAndWarehouseManagement/InventItemPriceComparisonStorageEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CostLevel attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DefaultOrderType name="DefaultOrderType">DefaultOrderType</a>

First included in: InventoryAndWarehouseManagement/InventItemPriceComparisonStorageEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultOrderType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CompareCostCalculationMethod name="CompareCostCalculationMethod">CompareCostCalculationMethod</a>

First included in: InventoryAndWarehouseManagement/InventItemPriceComparisonStorageEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CompareCostCalculationMethod attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CompareFromDate name="CompareFromDate">CompareFromDate</a>

First included in: InventoryAndWarehouseManagement/InventItemPriceComparisonStorageEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CompareFromDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ComparePriceCharges name="ComparePriceCharges">ComparePriceCharges</a>

First included in: InventoryAndWarehouseManagement/InventItemPriceComparisonStorageEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ComparePriceCharges attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CompareOnhandValue name="CompareOnhandValue">CompareOnhandValue</a>

First included in: InventoryAndWarehouseManagement/InventItemPriceComparisonStorageEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CompareOnhandValue attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ComparePrice name="ComparePrice">ComparePrice</a>

First included in: InventoryAndWarehouseManagement/InventItemPriceComparisonStorageEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ComparePrice attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ComparePriceIsPriceIncludingCharges name="ComparePriceIsPriceIncludingCharges">ComparePriceIsPriceIncludingCharges</a>

First included in: InventoryAndWarehouseManagement/InventItemPriceComparisonStorageEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ComparePriceIsPriceIncludingCharges attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CompareChargesQuantity name="CompareChargesQuantity">CompareChargesQuantity</a>

First included in: InventoryAndWarehouseManagement/InventItemPriceComparisonStorageEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CompareChargesQuantity attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ComparePriceQuantity name="ComparePriceQuantity">ComparePriceQuantity</a>

First included in: InventoryAndWarehouseManagement/InventItemPriceComparisonStorageEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ComparePriceQuantity attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CompareUnitSymbol name="CompareUnitSymbol">CompareUnitSymbol</a>

First included in: InventoryAndWarehouseManagement/InventItemPriceComparisonStorageEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CompareUnitSymbol attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CompareUnitPrice name="CompareUnitPrice">CompareUnitPrice</a>

First included in: InventoryAndWarehouseManagement/InventItemPriceComparisonStorageEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CompareUnitPrice attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CompareToCostCalculationMethod name="CompareToCostCalculationMethod">CompareToCostCalculationMethod</a>

First included in: InventoryAndWarehouseManagement/InventItemPriceComparisonStorageEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CompareToCostCalculationMethod attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CompareToFromDate name="CompareToFromDate">CompareToFromDate</a>

First included in: InventoryAndWarehouseManagement/InventItemPriceComparisonStorageEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CompareToFromDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CompareToPriceCharges name="CompareToPriceCharges">CompareToPriceCharges</a>

First included in: InventoryAndWarehouseManagement/InventItemPriceComparisonStorageEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CompareToPriceCharges attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CompareToOnhandValue name="CompareToOnhandValue">CompareToOnhandValue</a>

First included in: InventoryAndWarehouseManagement/InventItemPriceComparisonStorageEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CompareToOnhandValue attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CompareToPrice name="CompareToPrice">CompareToPrice</a>

First included in: InventoryAndWarehouseManagement/InventItemPriceComparisonStorageEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CompareToPrice attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CompareToIsPriceIncludingCharges name="CompareToIsPriceIncludingCharges">CompareToIsPriceIncludingCharges</a>

First included in: InventoryAndWarehouseManagement/InventItemPriceComparisonStorageEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CompareToIsPriceIncludingCharges attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CompareToChargesQuantity name="CompareToChargesQuantity">CompareToChargesQuantity</a>

First included in: InventoryAndWarehouseManagement/InventItemPriceComparisonStorageEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CompareToChargesQuantity attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CompareToPriceQuantity name="CompareToPriceQuantity">CompareToPriceQuantity</a>

First included in: InventoryAndWarehouseManagement/InventItemPriceComparisonStorageEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CompareToPriceQuantity attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CompareToUnitSymbol name="CompareToUnitSymbol">CompareToUnitSymbol</a>

First included in: InventoryAndWarehouseManagement/InventItemPriceComparisonStorageEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CompareToUnitSymbol attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CompareToUnitPrice name="CompareToUnitPrice">CompareToUnitPrice</a>

First included in: InventoryAndWarehouseManagement/InventItemPriceComparisonStorageEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CompareToUnitPrice attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#NetChangeUnitPrice name="NetChangeUnitPrice">NetChangeUnitPrice</a>

First included in: InventoryAndWarehouseManagement/InventItemPriceComparisonStorageEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the NetChangeUnitPrice attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#NetChangeOnhandValue name="NetChangeOnhandValue">NetChangeOnhandValue</a>

First included in: InventoryAndWarehouseManagement/InventItemPriceComparisonStorageEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the NetChangeOnhandValue attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BackingTable_InventItemPriceCompareStorageDetailsRelationshipId name="BackingTable_InventItemPriceCompareStorageDetailsRelationshipId">BackingTable_InventItemPriceCompareStorageDetailsRelationshipId</a>

First included in: InventoryAndWarehouseManagement/InventItemPriceComparisonStorageEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_InventItemPriceCompareStorageDetailsRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/SupplyChain/Inventory/WorksheetLine/InventItemPriceCompareStorageDetails.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/Inventory/WorksheetLine/InventItemPriceCompareStorageDetails.cdm.json/InventItemPriceCompareStorageDetails</a></td><td><a href="../../../Tables/SupplyChain/Inventory/WorksheetLine/InventItemPriceCompareStorageDetails.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PrimaryCompanyContextRelationshipId name="Relationship_PrimaryCompanyContextRelationshipId">Relationship_PrimaryCompanyContextRelationshipId</a>

First included in: InventoryAndWarehouseManagement/InventItemPriceComparisonStorageEntity (this entity)  

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
