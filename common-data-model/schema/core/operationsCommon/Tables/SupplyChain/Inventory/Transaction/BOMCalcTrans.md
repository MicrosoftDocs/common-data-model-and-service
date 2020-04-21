---
title: BOMCalcTrans - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/21/2020
ms.author: nebanfic
---

# BOMCalcTrans

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Tables/SupplyChain/Inventory/Transaction/BOMCalcTrans.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[BOMCalcTrans/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="BOMCalcTrans.md" target="_blank">Transaction/BOMCalcTrans</a>|
|[BOM](#BOM)||<a href="BOMCalcTrans.md" target="_blank">Transaction/BOMCalcTrans</a>|
|[CalcGroupId](#CalcGroupId)||<a href="BOMCalcTrans.md" target="_blank">Transaction/BOMCalcTrans</a>|
|[CalcType](#CalcType)||<a href="BOMCalcTrans.md" target="_blank">Transaction/BOMCalcTrans</a>|
|[ConsistOfPrice](#ConsistOfPrice)||<a href="BOMCalcTrans.md" target="_blank">Transaction/BOMCalcTrans</a>|
|[ConsumptionConstant](#ConsumptionConstant)||<a href="BOMCalcTrans.md" target="_blank">Transaction/BOMCalcTrans</a>|
|[ConsumptionInvent](#ConsumptionInvent)||<a href="BOMCalcTrans.md" target="_blank">Transaction/BOMCalcTrans</a>|
|[ConsumptionVariable](#ConsumptionVariable)||<a href="BOMCalcTrans.md" target="_blank">Transaction/BOMCalcTrans</a>|
|[ConsumpType](#ConsumpType)||<a href="BOMCalcTrans.md" target="_blank">Transaction/BOMCalcTrans</a>|
|[CostGroupId](#CostGroupId)||<a href="BOMCalcTrans.md" target="_blank">Transaction/BOMCalcTrans</a>|
|[CostMarkup](#CostMarkup)||<a href="BOMCalcTrans.md" target="_blank">Transaction/BOMCalcTrans</a>|
|[CostMarkupQty](#CostMarkupQty)||<a href="BOMCalcTrans.md" target="_blank">Transaction/BOMCalcTrans</a>|
|[CostMarkupQtySecCur_RU](#CostMarkupQtySecCur_RU)||<a href="BOMCalcTrans.md" target="_blank">Transaction/BOMCalcTrans</a>|
|[CostMarkupSecCur_RU](#CostMarkupSecCur_RU)||<a href="BOMCalcTrans.md" target="_blank">Transaction/BOMCalcTrans</a>|
|[CostPrice](#CostPrice)||<a href="BOMCalcTrans.md" target="_blank">Transaction/BOMCalcTrans</a>|
|[CostPriceFallBackVersion](#CostPriceFallBackVersion)||<a href="BOMCalcTrans.md" target="_blank">Transaction/BOMCalcTrans</a>|
|[CostPriceModelUsed](#CostPriceModelUsed)||<a href="BOMCalcTrans.md" target="_blank">Transaction/BOMCalcTrans</a>|
|[CostPriceQty](#CostPriceQty)||<a href="BOMCalcTrans.md" target="_blank">Transaction/BOMCalcTrans</a>|
|[CostPriceQtySecCur_RU](#CostPriceQtySecCur_RU)||<a href="BOMCalcTrans.md" target="_blank">Transaction/BOMCalcTrans</a>|
|[CostPriceSecCur_RU](#CostPriceSecCur_RU)||<a href="BOMCalcTrans.md" target="_blank">Transaction/BOMCalcTrans</a>|
|[CostPriceUnit](#CostPriceUnit)||<a href="BOMCalcTrans.md" target="_blank">Transaction/BOMCalcTrans</a>|
|[Infolog](#Infolog)||<a href="BOMCalcTrans.md" target="_blank">Transaction/BOMCalcTrans</a>|
|[InventDimId](#InventDimId)||<a href="BOMCalcTrans.md" target="_blank">Transaction/BOMCalcTrans</a>|
|[InventDimStr](#InventDimStr)||<a href="BOMCalcTrans.md" target="_blank">Transaction/BOMCalcTrans</a>|
|[Level](#Level)||<a href="BOMCalcTrans.md" target="_blank">Transaction/BOMCalcTrans</a>|
|[LineNum](#LineNum)||<a href="BOMCalcTrans.md" target="_blank">Transaction/BOMCalcTrans</a>|
|[NetWeightQty](#NetWeightQty)||<a href="BOMCalcTrans.md" target="_blank">Transaction/BOMCalcTrans</a>|
|[NumOfSeries](#NumOfSeries)||<a href="BOMCalcTrans.md" target="_blank">Transaction/BOMCalcTrans</a>|
|[OprId](#OprId)||<a href="BOMCalcTrans.md" target="_blank">Transaction/BOMCalcTrans</a>|
|[OprNum](#OprNum)||<a href="BOMCalcTrans.md" target="_blank">Transaction/BOMCalcTrans</a>|
|[OprNumNext](#OprNumNext)||<a href="BOMCalcTrans.md" target="_blank">Transaction/BOMCalcTrans</a>|
|[OprPriority](#OprPriority)||<a href="BOMCalcTrans.md" target="_blank">Transaction/BOMCalcTrans</a>|
|[ParentBOMCalcTrans](#ParentBOMCalcTrans)||<a href="BOMCalcTrans.md" target="_blank">Transaction/BOMCalcTrans</a>|
|[PriceCalcId](#PriceCalcId)||<a href="BOMCalcTrans.md" target="_blank">Transaction/BOMCalcTrans</a>|
|[PriceDiscQty](#PriceDiscQty)||<a href="BOMCalcTrans.md" target="_blank">Transaction/BOMCalcTrans</a>|
|[Qty](#Qty)||<a href="BOMCalcTrans.md" target="_blank">Transaction/BOMCalcTrans</a>|
|[Resource](#Resource)||<a href="BOMCalcTrans.md" target="_blank">Transaction/BOMCalcTrans</a>|
|[RouteLevel](#RouteLevel)||<a href="BOMCalcTrans.md" target="_blank">Transaction/BOMCalcTrans</a>|
|[SalesMarkup](#SalesMarkup)||<a href="BOMCalcTrans.md" target="_blank">Transaction/BOMCalcTrans</a>|
|[SalesMarkupQty](#SalesMarkupQty)||<a href="BOMCalcTrans.md" target="_blank">Transaction/BOMCalcTrans</a>|
|[SalesPrice](#SalesPrice)||<a href="BOMCalcTrans.md" target="_blank">Transaction/BOMCalcTrans</a>|
|[SalesPriceFallBackVersion](#SalesPriceFallBackVersion)||<a href="BOMCalcTrans.md" target="_blank">Transaction/BOMCalcTrans</a>|
|[SalesPriceModelUsed](#SalesPriceModelUsed)||<a href="BOMCalcTrans.md" target="_blank">Transaction/BOMCalcTrans</a>|
|[SalesPriceQty](#SalesPriceQty)||<a href="BOMCalcTrans.md" target="_blank">Transaction/BOMCalcTrans</a>|
|[SalesPriceUnit](#SalesPriceUnit)||<a href="BOMCalcTrans.md" target="_blank">Transaction/BOMCalcTrans</a>|
|[TransDate](#TransDate)||<a href="BOMCalcTrans.md" target="_blank">Transaction/BOMCalcTrans</a>|
|[UnitId](#UnitId)||<a href="BOMCalcTrans.md" target="_blank">Transaction/BOMCalcTrans</a>|
|[VendId](#VendId)||<a href="BOMCalcTrans.md" target="_blank">Transaction/BOMCalcTrans</a>|
|[CostCalculationMethod](#CostCalculationMethod)||<a href="BOMCalcTrans.md" target="_blank">Transaction/BOMCalcTrans</a>|
|[DataAreaId](#DataAreaId)||<a href="BOMCalcTrans.md" target="_blank">Transaction/BOMCalcTrans</a>|
|[Relationship_BOMCalcGroupRelationshipId](#Relationship_BOMCalcGroupRelationshipId)||<a href="BOMCalcTrans.md" target="_blank">Transaction/BOMCalcTrans</a>|
|[Relationship_BOMCalcTableRelationshipId](#Relationship_BOMCalcTableRelationshipId)||<a href="BOMCalcTrans.md" target="_blank">Transaction/BOMCalcTrans</a>|
|[Relationship_BOMCostGroupRelationshipId](#Relationship_BOMCostGroupRelationshipId)||<a href="BOMCalcTrans.md" target="_blank">Transaction/BOMCalcTrans</a>|
|[Relationship_ConsistOfBOMCalcTableRelationshipId](#Relationship_ConsistOfBOMCalcTableRelationshipId)||<a href="BOMCalcTrans.md" target="_blank">Transaction/BOMCalcTrans</a>|
|[Relationship_CostPriceFallBackCostingVersionRelationshipId](#Relationship_CostPriceFallBackCostingVersionRelationshipId)||<a href="BOMCalcTrans.md" target="_blank">Transaction/BOMCalcTrans</a>|
|[Relationship_InventDimRelationshipId](#Relationship_InventDimRelationshipId)||<a href="BOMCalcTrans.md" target="_blank">Transaction/BOMCalcTrans</a>|
|[Relationship_InventTableBOMRelationshipId](#Relationship_InventTableBOMRelationshipId)||<a href="BOMCalcTrans.md" target="_blank">Transaction/BOMCalcTrans</a>|
|[Relationship_InventTableItemRelationshipId](#Relationship_InventTableItemRelationshipId)||<a href="BOMCalcTrans.md" target="_blank">Transaction/BOMCalcTrans</a>|
|[Relationship_InventTableProdRelationshipId](#Relationship_InventTableProdRelationshipId)||<a href="BOMCalcTrans.md" target="_blank">Transaction/BOMCalcTrans</a>|
|[Relationship_InventTableServiceRelationshipId](#Relationship_InventTableServiceRelationshipId)||<a href="BOMCalcTrans.md" target="_blank">Transaction/BOMCalcTrans</a>|
|[Relationship_RouteOprTableRelationshipId](#Relationship_RouteOprTableRelationshipId)||<a href="BOMCalcTrans.md" target="_blank">Transaction/BOMCalcTrans</a>|
|[Relationship_SalesPriceFallBackCostingVersionRelationshipId](#Relationship_SalesPriceFallBackCostingVersionRelationshipId)||<a href="BOMCalcTrans.md" target="_blank">Transaction/BOMCalcTrans</a>|
|[Relationship_VendTableRelationshipId](#Relationship_VendTableRelationshipId)||<a href="BOMCalcTrans.md" target="_blank">Transaction/BOMCalcTrans</a>|
|[Relationship_WrkCtrTableProcessRelationshipId](#Relationship_WrkCtrTableProcessRelationshipId)||<a href="BOMCalcTrans.md" target="_blank">Transaction/BOMCalcTrans</a>|
|[Relationship_WrkCtrTableQtyRelationshipId](#Relationship_WrkCtrTableQtyRelationshipId)||<a href="BOMCalcTrans.md" target="_blank">Transaction/BOMCalcTrans</a>|
|[Relationship_WrkCtrTableSetupRelationshipId](#Relationship_WrkCtrTableSetupRelationshipId)||<a href="BOMCalcTrans.md" target="_blank">Transaction/BOMCalcTrans</a>|
|[Relationship_CompanyRelationshipId](#Relationship_CompanyRelationshipId)||<a href="BOMCalcTrans.md" target="_blank">Transaction/BOMCalcTrans</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: Transaction/BOMCalcTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[BOMCalcTrans/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#BOM name="BOM">BOM</a>

First included in: Transaction/BOMCalcTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BOM attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#CalcGroupId name="CalcGroupId">CalcGroupId</a>

First included in: Transaction/BOMCalcTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CalcGroupId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CalcType name="CalcType">CalcType</a>

First included in: Transaction/BOMCalcTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CalcType attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#ConsistOfPrice name="ConsistOfPrice">ConsistOfPrice</a>

First included in: Transaction/BOMCalcTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ConsistOfPrice attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ConsumptionConstant name="ConsumptionConstant">ConsumptionConstant</a>

First included in: Transaction/BOMCalcTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ConsumptionConstant attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#ConsumptionInvent name="ConsumptionInvent">ConsumptionInvent</a>

First included in: Transaction/BOMCalcTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ConsumptionInvent attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.readOnly**  
**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#ConsumptionVariable name="ConsumptionVariable">ConsumptionVariable</a>

First included in: Transaction/BOMCalcTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ConsumptionVariable attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#ConsumpType name="ConsumpType">ConsumpType</a>

First included in: Transaction/BOMCalcTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ConsumpType attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.readOnly**  
**is.dataFormat.integer**  
</details>

### <a href=#CostGroupId name="CostGroupId">CostGroupId</a>

First included in: Transaction/BOMCalcTrans (this entity)  

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

### <a href=#CostMarkup name="CostMarkup">CostMarkup</a>

First included in: Transaction/BOMCalcTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CostMarkup attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#CostMarkupQty name="CostMarkupQty">CostMarkupQty</a>

First included in: Transaction/BOMCalcTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CostMarkupQty attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#CostMarkupQtySecCur_RU name="CostMarkupQtySecCur_RU">CostMarkupQtySecCur_RU</a>

First included in: Transaction/BOMCalcTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CostMarkupQtySecCur_RU attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#CostMarkupSecCur_RU name="CostMarkupSecCur_RU">CostMarkupSecCur_RU</a>

First included in: Transaction/BOMCalcTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CostMarkupSecCur_RU attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#CostPrice name="CostPrice">CostPrice</a>

First included in: Transaction/BOMCalcTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CostPrice attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#CostPriceFallBackVersion name="CostPriceFallBackVersion">CostPriceFallBackVersion</a>

First included in: Transaction/BOMCalcTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CostPriceFallBackVersion attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.readOnly**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CostPriceModelUsed name="CostPriceModelUsed">CostPriceModelUsed</a>

First included in: Transaction/BOMCalcTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CostPriceModelUsed attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#CostPriceQty name="CostPriceQty">CostPriceQty</a>

First included in: Transaction/BOMCalcTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CostPriceQty attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#CostPriceQtySecCur_RU name="CostPriceQtySecCur_RU">CostPriceQtySecCur_RU</a>

First included in: Transaction/BOMCalcTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CostPriceQtySecCur_RU attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#CostPriceSecCur_RU name="CostPriceSecCur_RU">CostPriceSecCur_RU</a>

First included in: Transaction/BOMCalcTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CostPriceSecCur_RU attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#CostPriceUnit name="CostPriceUnit">CostPriceUnit</a>

First included in: Transaction/BOMCalcTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CostPriceUnit attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#Infolog name="Infolog">Infolog</a>

First included in: Transaction/BOMCalcTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>binary</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Infolog attribute are listed below.</summary>

**is.dataFormat.byte**  
**is.dataFormat.array**  
**is.dataFormat.byte**  
**is.dataFormat.array**  
</details>

### <a href=#InventDimId name="InventDimId">InventDimId</a>

First included in: Transaction/BOMCalcTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InventDimId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.readOnly**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InventDimStr name="InventDimStr">InventDimStr</a>

First included in: Transaction/BOMCalcTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InventDimStr attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Level name="Level">Level</a>

First included in: Transaction/BOMCalcTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Level attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#LineNum name="LineNum">LineNum</a>

First included in: Transaction/BOMCalcTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LineNum attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#NetWeightQty name="NetWeightQty">NetWeightQty</a>

First included in: Transaction/BOMCalcTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the NetWeightQty attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#NumOfSeries name="NumOfSeries">NumOfSeries</a>

First included in: Transaction/BOMCalcTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the NumOfSeries attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#OprId name="OprId">OprId</a>

First included in: Transaction/BOMCalcTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OprId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#OprNum name="OprNum">OprNum</a>

First included in: Transaction/BOMCalcTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OprNum attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#OprNumNext name="OprNumNext">OprNumNext</a>

First included in: Transaction/BOMCalcTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OprNumNext attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.readOnly**  
**is.dataFormat.integer**  
</details>

### <a href=#OprPriority name="OprPriority">OprPriority</a>

First included in: Transaction/BOMCalcTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OprPriority attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#ParentBOMCalcTrans name="ParentBOMCalcTrans">ParentBOMCalcTrans</a>

First included in: Transaction/BOMCalcTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ParentBOMCalcTrans attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#PriceCalcId name="PriceCalcId">PriceCalcId</a>

First included in: Transaction/BOMCalcTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PriceCalcId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PriceDiscQty name="PriceDiscQty">PriceDiscQty</a>

First included in: Transaction/BOMCalcTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PriceDiscQty attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#Qty name="Qty">Qty</a>

First included in: Transaction/BOMCalcTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Qty attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#Resource name="Resource">Resource</a>

First included in: Transaction/BOMCalcTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Resource attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RouteLevel name="RouteLevel">RouteLevel</a>

First included in: Transaction/BOMCalcTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RouteLevel attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#SalesMarkup name="SalesMarkup">SalesMarkup</a>

First included in: Transaction/BOMCalcTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SalesMarkup attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#SalesMarkupQty name="SalesMarkupQty">SalesMarkupQty</a>

First included in: Transaction/BOMCalcTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SalesMarkupQty attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#SalesPrice name="SalesPrice">SalesPrice</a>

First included in: Transaction/BOMCalcTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SalesPrice attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#SalesPriceFallBackVersion name="SalesPriceFallBackVersion">SalesPriceFallBackVersion</a>

First included in: Transaction/BOMCalcTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SalesPriceFallBackVersion attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.readOnly**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SalesPriceModelUsed name="SalesPriceModelUsed">SalesPriceModelUsed</a>

First included in: Transaction/BOMCalcTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SalesPriceModelUsed attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#SalesPriceQty name="SalesPriceQty">SalesPriceQty</a>

First included in: Transaction/BOMCalcTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SalesPriceQty attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#SalesPriceUnit name="SalesPriceUnit">SalesPriceUnit</a>

First included in: Transaction/BOMCalcTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SalesPriceUnit attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#TransDate name="TransDate">TransDate</a>

First included in: Transaction/BOMCalcTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TransDate attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.dataFormat.date**  
</details>

### <a href=#UnitId name="UnitId">UnitId</a>

First included in: Transaction/BOMCalcTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the UnitId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#VendId name="VendId">VendId</a>

First included in: Transaction/BOMCalcTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VendId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.readOnly**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CostCalculationMethod name="CostCalculationMethod">CostCalculationMethod</a>

First included in: Transaction/BOMCalcTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CostCalculationMethod attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#DataAreaId name="DataAreaId">DataAreaId</a>

First included in: Transaction/BOMCalcTrans (this entity)  

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

### <a href=#Relationship_BOMCalcGroupRelationshipId name="Relationship_BOMCalcGroupRelationshipId">Relationship_BOMCalcGroupRelationshipId</a>

First included in: Transaction/BOMCalcTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_BOMCalcGroupRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Group/BOMCalcGroup.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/Inventory/Group/BOMCalcGroup.cdm.json/BOMCalcGroup</a></td><td><a href="../Group/BOMCalcGroup.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_BOMCalcTableRelationshipId name="Relationship_BOMCalcTableRelationshipId">Relationship_BOMCalcTableRelationshipId</a>

First included in: Transaction/BOMCalcTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_BOMCalcTableRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="BOMCalcTable.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/Inventory/Transaction/BOMCalcTable.cdm.json/BOMCalcTable</a></td><td><a href="BOMCalcTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_BOMCostGroupRelationshipId name="Relationship_BOMCostGroupRelationshipId">Relationship_BOMCostGroupRelationshipId</a>

First included in: Transaction/BOMCalcTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_BOMCostGroupRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Group/BOMCostGroup.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/Inventory/Group/BOMCostGroup.cdm.json/BOMCostGroup</a></td><td><a href="../Group/BOMCostGroup.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_ConsistOfBOMCalcTableRelationshipId name="Relationship_ConsistOfBOMCalcTableRelationshipId">Relationship_ConsistOfBOMCalcTableRelationshipId</a>

First included in: Transaction/BOMCalcTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_ConsistOfBOMCalcTableRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="BOMCalcTable.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/Inventory/Transaction/BOMCalcTable.cdm.json/BOMCalcTable</a></td><td><a href="BOMCalcTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_CostPriceFallBackCostingVersionRelationshipId name="Relationship_CostPriceFallBackCostingVersionRelationshipId">Relationship_CostPriceFallBackCostingVersionRelationshipId</a>

First included in: Transaction/BOMCalcTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_CostPriceFallBackCostingVersionRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Group/CostingVersion.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/Inventory/Group/CostingVersion.cdm.json/CostingVersion</a></td><td><a href="../Group/CostingVersion.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_InventDimRelationshipId name="Relationship_InventDimRelationshipId">Relationship_InventDimRelationshipId</a>

First included in: Transaction/BOMCalcTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_InventDimRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Main/InventDim.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/Inventory/Main/InventDim.cdm.json/InventDim</a></td><td><a href="../Main/InventDim.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_InventTableBOMRelationshipId name="Relationship_InventTableBOMRelationshipId">Relationship_InventTableBOMRelationshipId</a>

First included in: Transaction/BOMCalcTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_InventTableBOMRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../ProductInformationManagement/Main/InventTable.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/ProductInformationManagement/Main/InventTable.cdm.json/InventTable</a></td><td><a href="../../ProductInformationManagement/Main/InventTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_InventTableItemRelationshipId name="Relationship_InventTableItemRelationshipId">Relationship_InventTableItemRelationshipId</a>

First included in: Transaction/BOMCalcTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_InventTableItemRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../ProductInformationManagement/Main/InventTable.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/ProductInformationManagement/Main/InventTable.cdm.json/InventTable</a></td><td><a href="../../ProductInformationManagement/Main/InventTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_InventTableProdRelationshipId name="Relationship_InventTableProdRelationshipId">Relationship_InventTableProdRelationshipId</a>

First included in: Transaction/BOMCalcTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_InventTableProdRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../ProductInformationManagement/Main/InventTable.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/ProductInformationManagement/Main/InventTable.cdm.json/InventTable</a></td><td><a href="../../ProductInformationManagement/Main/InventTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_InventTableServiceRelationshipId name="Relationship_InventTableServiceRelationshipId">Relationship_InventTableServiceRelationshipId</a>

First included in: Transaction/BOMCalcTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_InventTableServiceRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../ProductInformationManagement/Main/InventTable.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/ProductInformationManagement/Main/InventTable.cdm.json/InventTable</a></td><td><a href="../../ProductInformationManagement/Main/InventTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_RouteOprTableRelationshipId name="Relationship_RouteOprTableRelationshipId">Relationship_RouteOprTableRelationshipId</a>

First included in: Transaction/BOMCalcTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_RouteOprTableRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../ProductionControl/Main/RouteOprTable.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/ProductionControl/Main/RouteOprTable.cdm.json/RouteOprTable</a></td><td><a href="../../ProductionControl/Main/RouteOprTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_SalesPriceFallBackCostingVersionRelationshipId name="Relationship_SalesPriceFallBackCostingVersionRelationshipId">Relationship_SalesPriceFallBackCostingVersionRelationshipId</a>

First included in: Transaction/BOMCalcTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_SalesPriceFallBackCostingVersionRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Group/CostingVersion.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/Inventory/Group/CostingVersion.cdm.json/CostingVersion</a></td><td><a href="../Group/CostingVersion.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_VendTableRelationshipId name="Relationship_VendTableRelationshipId">Relationship_VendTableRelationshipId</a>

First included in: Transaction/BOMCalcTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_VendTableRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../Vendor/Main/VendTable.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/Vendor/Main/VendTable.cdm.json/VendTable</a></td><td><a href="../../Vendor/Main/VendTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_WrkCtrTableProcessRelationshipId name="Relationship_WrkCtrTableProcessRelationshipId">Relationship_WrkCtrTableProcessRelationshipId</a>

First included in: Transaction/BOMCalcTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_WrkCtrTableProcessRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../SalesAndMarketing/Main/WrkCtrTable.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/SalesAndMarketing/Main/WrkCtrTable.cdm.json/WrkCtrTable</a></td><td><a href="../../SalesAndMarketing/Main/WrkCtrTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_WrkCtrTableQtyRelationshipId name="Relationship_WrkCtrTableQtyRelationshipId">Relationship_WrkCtrTableQtyRelationshipId</a>

First included in: Transaction/BOMCalcTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_WrkCtrTableQtyRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../SalesAndMarketing/Main/WrkCtrTable.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/SalesAndMarketing/Main/WrkCtrTable.cdm.json/WrkCtrTable</a></td><td><a href="../../SalesAndMarketing/Main/WrkCtrTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_WrkCtrTableSetupRelationshipId name="Relationship_WrkCtrTableSetupRelationshipId">Relationship_WrkCtrTableSetupRelationshipId</a>

First included in: Transaction/BOMCalcTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_WrkCtrTableSetupRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../SalesAndMarketing/Main/WrkCtrTable.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/SalesAndMarketing/Main/WrkCtrTable.cdm.json/WrkCtrTable</a></td><td><a href="../../SalesAndMarketing/Main/WrkCtrTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_CompanyRelationshipId name="Relationship_CompanyRelationshipId">Relationship_CompanyRelationshipId</a>

First included in: Transaction/BOMCalcTrans (this entity)  

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
