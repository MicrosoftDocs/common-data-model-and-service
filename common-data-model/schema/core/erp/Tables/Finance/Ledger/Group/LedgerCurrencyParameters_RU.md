---
title: LedgerCurrencyParameters_RU - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/17/2020
ms.author: nebanfic
---

# LedgerCurrencyParameters_RU

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/erp/Tables/Finance/Ledger/Group/LedgerCurrencyParameters_RU.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[LedgerCurrencyParameters_RU/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="LedgerCurrencyParameters_RU.md" target="_blank">Group/LedgerCurrencyParameters_RU</a>|
|[CurConvertLossLedgerDimension](#CurConvertLossLedgerDimension)||<a href="LedgerCurrencyParameters_RU.md" target="_blank">Group/LedgerCurrencyParameters_RU</a>|
|[CurConvertProfitLedgerDimension](#CurConvertProfitLedgerDimension)||<a href="LedgerCurrencyParameters_RU.md" target="_blank">Group/LedgerCurrencyParameters_RU</a>|
|[CurrencyCode](#CurrencyCode)||<a href="LedgerCurrencyParameters_RU.md" target="_blank">Group/LedgerCurrencyParameters_RU</a>|
|[CustPostingMode](#CustPostingMode)||<a href="LedgerCurrencyParameters_RU.md" target="_blank">Group/LedgerCurrencyParameters_RU</a>|
|[CustPostingModeTax](#CustPostingModeTax)||<a href="LedgerCurrencyParameters_RU.md" target="_blank">Group/LedgerCurrencyParameters_RU</a>|
|[ExchRateLossTaxVend](#ExchRateLossTaxVend)||<a href="LedgerCurrencyParameters_RU.md" target="_blank">Group/LedgerCurrencyParameters_RU</a>|
|[ExchRateNeg](#ExchRateNeg)||<a href="LedgerCurrencyParameters_RU.md" target="_blank">Group/LedgerCurrencyParameters_RU</a>|
|[ExchRateNonrealLossTaxCust](#ExchRateNonrealLossTaxCust)||<a href="LedgerCurrencyParameters_RU.md" target="_blank">Group/LedgerCurrencyParameters_RU</a>|
|[ExchRateNonrealProfitTaxCust](#ExchRateNonrealProfitTaxCust)||<a href="LedgerCurrencyParameters_RU.md" target="_blank">Group/LedgerCurrencyParameters_RU</a>|
|[ExchRatePos](#ExchRatePos)||<a href="LedgerCurrencyParameters_RU.md" target="_blank">Group/LedgerCurrencyParameters_RU</a>|
|[ExchRateProfitTaxVend](#ExchRateProfitTaxVend)||<a href="LedgerCurrencyParameters_RU.md" target="_blank">Group/LedgerCurrencyParameters_RU</a>|
|[Ledger](#Ledger)||<a href="LedgerCurrencyParameters_RU.md" target="_blank">Group/LedgerCurrencyParameters_RU</a>|
|[RealizedLossCustLedgerDimension](#RealizedLossCustLedgerDimension)||<a href="LedgerCurrencyParameters_RU.md" target="_blank">Group/LedgerCurrencyParameters_RU</a>|
|[RealizedLossEmplLedgerDimension](#RealizedLossEmplLedgerDimension)||<a href="LedgerCurrencyParameters_RU.md" target="_blank">Group/LedgerCurrencyParameters_RU</a>|
|[RealizedLossTaxCustLedgerDimension](#RealizedLossTaxCustLedgerDimension)||<a href="LedgerCurrencyParameters_RU.md" target="_blank">Group/LedgerCurrencyParameters_RU</a>|
|[RealizedLossTaxVendLedgerDimension](#RealizedLossTaxVendLedgerDimension)||<a href="LedgerCurrencyParameters_RU.md" target="_blank">Group/LedgerCurrencyParameters_RU</a>|
|[RealizedLossVendLedgerDimension](#RealizedLossVendLedgerDimension)||<a href="LedgerCurrencyParameters_RU.md" target="_blank">Group/LedgerCurrencyParameters_RU</a>|
|[RealizedProfitCustLedgerDimension](#RealizedProfitCustLedgerDimension)||<a href="LedgerCurrencyParameters_RU.md" target="_blank">Group/LedgerCurrencyParameters_RU</a>|
|[RealizedProfitEmplLedgerDimension](#RealizedProfitEmplLedgerDimension)||<a href="LedgerCurrencyParameters_RU.md" target="_blank">Group/LedgerCurrencyParameters_RU</a>|
|[RealizedProfitTaxCustLedgerDimension](#RealizedProfitTaxCustLedgerDimension)||<a href="LedgerCurrencyParameters_RU.md" target="_blank">Group/LedgerCurrencyParameters_RU</a>|
|[RealizedProfitTaxVendLedgerDimension](#RealizedProfitTaxVendLedgerDimension)||<a href="LedgerCurrencyParameters_RU.md" target="_blank">Group/LedgerCurrencyParameters_RU</a>|
|[RealizedProfitVendLedgerDimension](#RealizedProfitVendLedgerDimension)||<a href="LedgerCurrencyParameters_RU.md" target="_blank">Group/LedgerCurrencyParameters_RU</a>|
|[RTax25ProfitTableConvertLoss](#RTax25ProfitTableConvertLoss)||<a href="LedgerCurrencyParameters_RU.md" target="_blank">Group/LedgerCurrencyParameters_RU</a>|
|[RTax25ProfitTableConvertProfit](#RTax25ProfitTableConvertProfit)||<a href="LedgerCurrencyParameters_RU.md" target="_blank">Group/LedgerCurrencyParameters_RU</a>|
|[RTax25ProfitTableLoss](#RTax25ProfitTableLoss)||<a href="LedgerCurrencyParameters_RU.md" target="_blank">Group/LedgerCurrencyParameters_RU</a>|
|[RTax25ProfitTableLossCust](#RTax25ProfitTableLossCust)||<a href="LedgerCurrencyParameters_RU.md" target="_blank">Group/LedgerCurrencyParameters_RU</a>|
|[RTax25ProfitTableLossCustPrepayment](#RTax25ProfitTableLossCustPrepayment)||<a href="LedgerCurrencyParameters_RU.md" target="_blank">Group/LedgerCurrencyParameters_RU</a>|
|[RTax25ProfitTableLossEmpl](#RTax25ProfitTableLossEmpl)||<a href="LedgerCurrencyParameters_RU.md" target="_blank">Group/LedgerCurrencyParameters_RU</a>|
|[RTax25ProfitTableLossVend](#RTax25ProfitTableLossVend)||<a href="LedgerCurrencyParameters_RU.md" target="_blank">Group/LedgerCurrencyParameters_RU</a>|
|[RTax25ProfitTableLossVendPrepayment](#RTax25ProfitTableLossVendPrepayment)||<a href="LedgerCurrencyParameters_RU.md" target="_blank">Group/LedgerCurrencyParameters_RU</a>|
|[RTax25ProfitTableProfit](#RTax25ProfitTableProfit)||<a href="LedgerCurrencyParameters_RU.md" target="_blank">Group/LedgerCurrencyParameters_RU</a>|
|[RTax25ProfitTableProfitCust](#RTax25ProfitTableProfitCust)||<a href="LedgerCurrencyParameters_RU.md" target="_blank">Group/LedgerCurrencyParameters_RU</a>|
|[RTax25ProfitTableProfitCustPrepayment](#RTax25ProfitTableProfitCustPrepayment)||<a href="LedgerCurrencyParameters_RU.md" target="_blank">Group/LedgerCurrencyParameters_RU</a>|
|[RTax25ProfitTableProfitEmpl](#RTax25ProfitTableProfitEmpl)||<a href="LedgerCurrencyParameters_RU.md" target="_blank">Group/LedgerCurrencyParameters_RU</a>|
|[RTax25ProfitTableProfitVend](#RTax25ProfitTableProfitVend)||<a href="LedgerCurrencyParameters_RU.md" target="_blank">Group/LedgerCurrencyParameters_RU</a>|
|[RTax25ProfitTableProfitVendPrepayment](#RTax25ProfitTableProfitVendPrepayment)||<a href="LedgerCurrencyParameters_RU.md" target="_blank">Group/LedgerCurrencyParameters_RU</a>|
|[TaxAmountDifference](#TaxAmountDifference)||<a href="LedgerCurrencyParameters_RU.md" target="_blank">Group/LedgerCurrencyParameters_RU</a>|
|[TaxAmountDifferenceLoss](#TaxAmountDifferenceLoss)||<a href="LedgerCurrencyParameters_RU.md" target="_blank">Group/LedgerCurrencyParameters_RU</a>|
|[TaxAmountDiffLedgerDimension](#TaxAmountDiffLedgerDimension)||<a href="LedgerCurrencyParameters_RU.md" target="_blank">Group/LedgerCurrencyParameters_RU</a>|
|[TaxAmountDiffLossLedgerDimension](#TaxAmountDiffLossLedgerDimension)||<a href="LedgerCurrencyParameters_RU.md" target="_blank">Group/LedgerCurrencyParameters_RU</a>|
|[TaxAmountDiffProfitLedgerDimension](#TaxAmountDiffProfitLedgerDimension)||<a href="LedgerCurrencyParameters_RU.md" target="_blank">Group/LedgerCurrencyParameters_RU</a>|
|[UnrealizedLossCustLedgerDimension](#UnrealizedLossCustLedgerDimension)||<a href="LedgerCurrencyParameters_RU.md" target="_blank">Group/LedgerCurrencyParameters_RU</a>|
|[UnrealizedLossEmplLedgerDimension](#UnrealizedLossEmplLedgerDimension)||<a href="LedgerCurrencyParameters_RU.md" target="_blank">Group/LedgerCurrencyParameters_RU</a>|
|[UnrealizedLossTaxCustLedgerDimension](#UnrealizedLossTaxCustLedgerDimension)||<a href="LedgerCurrencyParameters_RU.md" target="_blank">Group/LedgerCurrencyParameters_RU</a>|
|[UnrealizedLossVendLedgerDimension](#UnrealizedLossVendLedgerDimension)||<a href="LedgerCurrencyParameters_RU.md" target="_blank">Group/LedgerCurrencyParameters_RU</a>|
|[UnrealizedProfitCustLedgerDimension](#UnrealizedProfitCustLedgerDimension)||<a href="LedgerCurrencyParameters_RU.md" target="_blank">Group/LedgerCurrencyParameters_RU</a>|
|[UnrealizedProfitEmplLedgerDimension](#UnrealizedProfitEmplLedgerDimension)||<a href="LedgerCurrencyParameters_RU.md" target="_blank">Group/LedgerCurrencyParameters_RU</a>|
|[UnrealizedProfitTaxCustLedgerDimension](#UnrealizedProfitTaxCustLedgerDimension)||<a href="LedgerCurrencyParameters_RU.md" target="_blank">Group/LedgerCurrencyParameters_RU</a>|
|[UnrealizedProfitVendLedgerDimension](#UnrealizedProfitVendLedgerDimension)||<a href="LedgerCurrencyParameters_RU.md" target="_blank">Group/LedgerCurrencyParameters_RU</a>|
|[VendPostingMode](#VendPostingMode)||<a href="LedgerCurrencyParameters_RU.md" target="_blank">Group/LedgerCurrencyParameters_RU</a>|
|[VendPostingModeTax](#VendPostingModeTax)||<a href="LedgerCurrencyParameters_RU.md" target="_blank">Group/LedgerCurrencyParameters_RU</a>|
|[DataAreaId](#DataAreaId)||<a href="LedgerCurrencyParameters_RU.md" target="_blank">Group/LedgerCurrencyParameters_RU</a>|
|[Relationship_CurConvertLossLedgerDimensionRelationshipId](#Relationship_CurConvertLossLedgerDimensionRelationshipId)||<a href="LedgerCurrencyParameters_RU.md" target="_blank">Group/LedgerCurrencyParameters_RU</a>|
|[Relationship_CurConvertProfitLedgerDimensionRelationshipId](#Relationship_CurConvertProfitLedgerDimensionRelationshipId)||<a href="LedgerCurrencyParameters_RU.md" target="_blank">Group/LedgerCurrencyParameters_RU</a>|
|[Relationship_CurrencyRelationshipId](#Relationship_CurrencyRelationshipId)||<a href="LedgerCurrencyParameters_RU.md" target="_blank">Group/LedgerCurrencyParameters_RU</a>|
|[Relationship_LedgerRelationshipId](#Relationship_LedgerRelationshipId)||<a href="LedgerCurrencyParameters_RU.md" target="_blank">Group/LedgerCurrencyParameters_RU</a>|
|[Relationship_RealizedLossCustLedgerDimensionRelationshipId](#Relationship_RealizedLossCustLedgerDimensionRelationshipId)||<a href="LedgerCurrencyParameters_RU.md" target="_blank">Group/LedgerCurrencyParameters_RU</a>|
|[Relationship_RealizedLossEmplLedgerDimensionRelationshipId](#Relationship_RealizedLossEmplLedgerDimensionRelationshipId)||<a href="LedgerCurrencyParameters_RU.md" target="_blank">Group/LedgerCurrencyParameters_RU</a>|
|[Relationship_RealizedLossTaxCustLedgerDimensionRelationshipId](#Relationship_RealizedLossTaxCustLedgerDimensionRelationshipId)||<a href="LedgerCurrencyParameters_RU.md" target="_blank">Group/LedgerCurrencyParameters_RU</a>|
|[Relationship_RealizedLossTaxVendLedgerDimensionRelationshipId](#Relationship_RealizedLossTaxVendLedgerDimensionRelationshipId)||<a href="LedgerCurrencyParameters_RU.md" target="_blank">Group/LedgerCurrencyParameters_RU</a>|
|[Relationship_RealizedLossVendLedgerDimensionRelationshipId](#Relationship_RealizedLossVendLedgerDimensionRelationshipId)||<a href="LedgerCurrencyParameters_RU.md" target="_blank">Group/LedgerCurrencyParameters_RU</a>|
|[Relationship_RealizedProfitCustLedgerDimensionRelationshipId](#Relationship_RealizedProfitCustLedgerDimensionRelationshipId)||<a href="LedgerCurrencyParameters_RU.md" target="_blank">Group/LedgerCurrencyParameters_RU</a>|
|[Relationship_RealizedProfitEmplLedgerDimensionRelationshipId](#Relationship_RealizedProfitEmplLedgerDimensionRelationshipId)||<a href="LedgerCurrencyParameters_RU.md" target="_blank">Group/LedgerCurrencyParameters_RU</a>|
|[Relationship_RealizedProfitTaxCustLedgerDimensionRelationshipId](#Relationship_RealizedProfitTaxCustLedgerDimensionRelationshipId)||<a href="LedgerCurrencyParameters_RU.md" target="_blank">Group/LedgerCurrencyParameters_RU</a>|
|[Relationship_RealizedProfitTaxVendLedgerDimensionRelationshipId](#Relationship_RealizedProfitTaxVendLedgerDimensionRelationshipId)||<a href="LedgerCurrencyParameters_RU.md" target="_blank">Group/LedgerCurrencyParameters_RU</a>|
|[Relationship_RealizedProfitVendLedgerDimensionRelationshipId](#Relationship_RealizedProfitVendLedgerDimensionRelationshipId)||<a href="LedgerCurrencyParameters_RU.md" target="_blank">Group/LedgerCurrencyParameters_RU</a>|
|[Relationship_RTax25ProfitTableConvertLossRelationshipId](#Relationship_RTax25ProfitTableConvertLossRelationshipId)||<a href="LedgerCurrencyParameters_RU.md" target="_blank">Group/LedgerCurrencyParameters_RU</a>|
|[Relationship_RTax25ProfitTableConvertProfitRelationshipId](#Relationship_RTax25ProfitTableConvertProfitRelationshipId)||<a href="LedgerCurrencyParameters_RU.md" target="_blank">Group/LedgerCurrencyParameters_RU</a>|
|[Relationship_RTax25ProfitTableLossRelationshipId](#Relationship_RTax25ProfitTableLossRelationshipId)||<a href="LedgerCurrencyParameters_RU.md" target="_blank">Group/LedgerCurrencyParameters_RU</a>|
|[Relationship_RTax25ProfitTableLossCustRelationshipId](#Relationship_RTax25ProfitTableLossCustRelationshipId)||<a href="LedgerCurrencyParameters_RU.md" target="_blank">Group/LedgerCurrencyParameters_RU</a>|
|[Relationship_RTax25ProfitTableLossCustPrepaymentRelationshipId](#Relationship_RTax25ProfitTableLossCustPrepaymentRelationshipId)||<a href="LedgerCurrencyParameters_RU.md" target="_blank">Group/LedgerCurrencyParameters_RU</a>|
|[Relationship_RTax25ProfitTableLossEmplRelationshipId](#Relationship_RTax25ProfitTableLossEmplRelationshipId)||<a href="LedgerCurrencyParameters_RU.md" target="_blank">Group/LedgerCurrencyParameters_RU</a>|
|[Relationship_RTax25ProfitTableLossVendRelationshipId](#Relationship_RTax25ProfitTableLossVendRelationshipId)||<a href="LedgerCurrencyParameters_RU.md" target="_blank">Group/LedgerCurrencyParameters_RU</a>|
|[Relationship_RTax25ProfitTableLossVendPrepaymentRelationshipId](#Relationship_RTax25ProfitTableLossVendPrepaymentRelationshipId)||<a href="LedgerCurrencyParameters_RU.md" target="_blank">Group/LedgerCurrencyParameters_RU</a>|
|[Relationship_RTax25ProfitTableProfitRelationshipId](#Relationship_RTax25ProfitTableProfitRelationshipId)||<a href="LedgerCurrencyParameters_RU.md" target="_blank">Group/LedgerCurrencyParameters_RU</a>|
|[Relationship_RTax25ProfitTableProfitCustRelationshipId](#Relationship_RTax25ProfitTableProfitCustRelationshipId)||<a href="LedgerCurrencyParameters_RU.md" target="_blank">Group/LedgerCurrencyParameters_RU</a>|
|[Relationship_RTax25ProfitTableProfitCustPrepaymentRelationshipId](#Relationship_RTax25ProfitTableProfitCustPrepaymentRelationshipId)||<a href="LedgerCurrencyParameters_RU.md" target="_blank">Group/LedgerCurrencyParameters_RU</a>|
|[Relationship_RTax25ProfitTableProfitEmplRelationshipId](#Relationship_RTax25ProfitTableProfitEmplRelationshipId)||<a href="LedgerCurrencyParameters_RU.md" target="_blank">Group/LedgerCurrencyParameters_RU</a>|
|[Relationship_RTax25ProfitTableProfitVendRelationshipId](#Relationship_RTax25ProfitTableProfitVendRelationshipId)||<a href="LedgerCurrencyParameters_RU.md" target="_blank">Group/LedgerCurrencyParameters_RU</a>|
|[Relationship_RTax25ProfitTableProfitVendPrepaymentRelationshipId](#Relationship_RTax25ProfitTableProfitVendPrepaymentRelationshipId)||<a href="LedgerCurrencyParameters_RU.md" target="_blank">Group/LedgerCurrencyParameters_RU</a>|
|[Relationship_TaxAmountDiffLedgerDimensionRelationshipId](#Relationship_TaxAmountDiffLedgerDimensionRelationshipId)||<a href="LedgerCurrencyParameters_RU.md" target="_blank">Group/LedgerCurrencyParameters_RU</a>|
|[Relationship_TaxAmountDiffLossLedgerDimensionRelationshipId](#Relationship_TaxAmountDiffLossLedgerDimensionRelationshipId)||<a href="LedgerCurrencyParameters_RU.md" target="_blank">Group/LedgerCurrencyParameters_RU</a>|
|[Relationship_TaxAmountDiffProfitLedgerDimensionRelationshipId](#Relationship_TaxAmountDiffProfitLedgerDimensionRelationshipId)||<a href="LedgerCurrencyParameters_RU.md" target="_blank">Group/LedgerCurrencyParameters_RU</a>|
|[Relationship_UnrealizedLossCustLedgerDimensionRelationshipId](#Relationship_UnrealizedLossCustLedgerDimensionRelationshipId)||<a href="LedgerCurrencyParameters_RU.md" target="_blank">Group/LedgerCurrencyParameters_RU</a>|
|[Relationship_UnrealizedLossEmplLedgerDimensionRelationshipId](#Relationship_UnrealizedLossEmplLedgerDimensionRelationshipId)||<a href="LedgerCurrencyParameters_RU.md" target="_blank">Group/LedgerCurrencyParameters_RU</a>|
|[Relationship_UnrealizedLossTaxCustLedgerDimensionRelationshipId](#Relationship_UnrealizedLossTaxCustLedgerDimensionRelationshipId)||<a href="LedgerCurrencyParameters_RU.md" target="_blank">Group/LedgerCurrencyParameters_RU</a>|
|[Relationship_UnrealizedLossVendLedgerDimensionRelationshipId](#Relationship_UnrealizedLossVendLedgerDimensionRelationshipId)||<a href="LedgerCurrencyParameters_RU.md" target="_blank">Group/LedgerCurrencyParameters_RU</a>|
|[Relationship_UnrealizedProfitCustLedgerDimensionRelationshipId](#Relationship_UnrealizedProfitCustLedgerDimensionRelationshipId)||<a href="LedgerCurrencyParameters_RU.md" target="_blank">Group/LedgerCurrencyParameters_RU</a>|
|[Relationship_UnrealizedProfitEmplLedgerDimensionRelationshipId](#Relationship_UnrealizedProfitEmplLedgerDimensionRelationshipId)||<a href="LedgerCurrencyParameters_RU.md" target="_blank">Group/LedgerCurrencyParameters_RU</a>|
|[Relationship_UnrealizedProfitTaxCustLedgerDimensionRelationshipId](#Relationship_UnrealizedProfitTaxCustLedgerDimensionRelationshipId)||<a href="LedgerCurrencyParameters_RU.md" target="_blank">Group/LedgerCurrencyParameters_RU</a>|
|[Relationship_UnrealizedProfitVendLedgerDimensionRelationshipId](#Relationship_UnrealizedProfitVendLedgerDimensionRelationshipId)||<a href="LedgerCurrencyParameters_RU.md" target="_blank">Group/LedgerCurrencyParameters_RU</a>|
|[Relationship_CompanyRelationshipId](#Relationship_CompanyRelationshipId)||<a href="LedgerCurrencyParameters_RU.md" target="_blank">Group/LedgerCurrencyParameters_RU</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: Group/LedgerCurrencyParameters_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[LedgerCurrencyParameters_RU/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#CurConvertLossLedgerDimension name="CurConvertLossLedgerDimension">CurConvertLossLedgerDimension</a>

First included in: Group/LedgerCurrencyParameters_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CurConvertLossLedgerDimension attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#CurConvertProfitLedgerDimension name="CurConvertProfitLedgerDimension">CurConvertProfitLedgerDimension</a>

First included in: Group/LedgerCurrencyParameters_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CurConvertProfitLedgerDimension attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#CurrencyCode name="CurrencyCode">CurrencyCode</a>

First included in: Group/LedgerCurrencyParameters_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CurrencyCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CustPostingMode name="CustPostingMode">CustPostingMode</a>

First included in: Group/LedgerCurrencyParameters_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CustPostingMode attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#CustPostingModeTax name="CustPostingModeTax">CustPostingModeTax</a>

First included in: Group/LedgerCurrencyParameters_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CustPostingModeTax attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#ExchRateLossTaxVend name="ExchRateLossTaxVend">ExchRateLossTaxVend</a>

First included in: Group/LedgerCurrencyParameters_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ExchRateLossTaxVend attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#ExchRateNeg name="ExchRateNeg">ExchRateNeg</a>

First included in: Group/LedgerCurrencyParameters_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ExchRateNeg attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#ExchRateNonrealLossTaxCust name="ExchRateNonrealLossTaxCust">ExchRateNonrealLossTaxCust</a>

First included in: Group/LedgerCurrencyParameters_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ExchRateNonrealLossTaxCust attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#ExchRateNonrealProfitTaxCust name="ExchRateNonrealProfitTaxCust">ExchRateNonrealProfitTaxCust</a>

First included in: Group/LedgerCurrencyParameters_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ExchRateNonrealProfitTaxCust attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#ExchRatePos name="ExchRatePos">ExchRatePos</a>

First included in: Group/LedgerCurrencyParameters_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ExchRatePos attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#ExchRateProfitTaxVend name="ExchRateProfitTaxVend">ExchRateProfitTaxVend</a>

First included in: Group/LedgerCurrencyParameters_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ExchRateProfitTaxVend attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#Ledger name="Ledger">Ledger</a>

First included in: Group/LedgerCurrencyParameters_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Ledger attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#RealizedLossCustLedgerDimension name="RealizedLossCustLedgerDimension">RealizedLossCustLedgerDimension</a>

First included in: Group/LedgerCurrencyParameters_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RealizedLossCustLedgerDimension attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#RealizedLossEmplLedgerDimension name="RealizedLossEmplLedgerDimension">RealizedLossEmplLedgerDimension</a>

First included in: Group/LedgerCurrencyParameters_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RealizedLossEmplLedgerDimension attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#RealizedLossTaxCustLedgerDimension name="RealizedLossTaxCustLedgerDimension">RealizedLossTaxCustLedgerDimension</a>

First included in: Group/LedgerCurrencyParameters_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RealizedLossTaxCustLedgerDimension attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#RealizedLossTaxVendLedgerDimension name="RealizedLossTaxVendLedgerDimension">RealizedLossTaxVendLedgerDimension</a>

First included in: Group/LedgerCurrencyParameters_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RealizedLossTaxVendLedgerDimension attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#RealizedLossVendLedgerDimension name="RealizedLossVendLedgerDimension">RealizedLossVendLedgerDimension</a>

First included in: Group/LedgerCurrencyParameters_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RealizedLossVendLedgerDimension attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#RealizedProfitCustLedgerDimension name="RealizedProfitCustLedgerDimension">RealizedProfitCustLedgerDimension</a>

First included in: Group/LedgerCurrencyParameters_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RealizedProfitCustLedgerDimension attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#RealizedProfitEmplLedgerDimension name="RealizedProfitEmplLedgerDimension">RealizedProfitEmplLedgerDimension</a>

First included in: Group/LedgerCurrencyParameters_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RealizedProfitEmplLedgerDimension attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#RealizedProfitTaxCustLedgerDimension name="RealizedProfitTaxCustLedgerDimension">RealizedProfitTaxCustLedgerDimension</a>

First included in: Group/LedgerCurrencyParameters_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RealizedProfitTaxCustLedgerDimension attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#RealizedProfitTaxVendLedgerDimension name="RealizedProfitTaxVendLedgerDimension">RealizedProfitTaxVendLedgerDimension</a>

First included in: Group/LedgerCurrencyParameters_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RealizedProfitTaxVendLedgerDimension attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#RealizedProfitVendLedgerDimension name="RealizedProfitVendLedgerDimension">RealizedProfitVendLedgerDimension</a>

First included in: Group/LedgerCurrencyParameters_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RealizedProfitVendLedgerDimension attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#RTax25ProfitTableConvertLoss name="RTax25ProfitTableConvertLoss">RTax25ProfitTableConvertLoss</a>

First included in: Group/LedgerCurrencyParameters_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RTax25ProfitTableConvertLoss attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#RTax25ProfitTableConvertProfit name="RTax25ProfitTableConvertProfit">RTax25ProfitTableConvertProfit</a>

First included in: Group/LedgerCurrencyParameters_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RTax25ProfitTableConvertProfit attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#RTax25ProfitTableLoss name="RTax25ProfitTableLoss">RTax25ProfitTableLoss</a>

First included in: Group/LedgerCurrencyParameters_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RTax25ProfitTableLoss attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#RTax25ProfitTableLossCust name="RTax25ProfitTableLossCust">RTax25ProfitTableLossCust</a>

First included in: Group/LedgerCurrencyParameters_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RTax25ProfitTableLossCust attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#RTax25ProfitTableLossCustPrepayment name="RTax25ProfitTableLossCustPrepayment">RTax25ProfitTableLossCustPrepayment</a>

First included in: Group/LedgerCurrencyParameters_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RTax25ProfitTableLossCustPrepayment attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#RTax25ProfitTableLossEmpl name="RTax25ProfitTableLossEmpl">RTax25ProfitTableLossEmpl</a>

First included in: Group/LedgerCurrencyParameters_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RTax25ProfitTableLossEmpl attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#RTax25ProfitTableLossVend name="RTax25ProfitTableLossVend">RTax25ProfitTableLossVend</a>

First included in: Group/LedgerCurrencyParameters_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RTax25ProfitTableLossVend attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#RTax25ProfitTableLossVendPrepayment name="RTax25ProfitTableLossVendPrepayment">RTax25ProfitTableLossVendPrepayment</a>

First included in: Group/LedgerCurrencyParameters_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RTax25ProfitTableLossVendPrepayment attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#RTax25ProfitTableProfit name="RTax25ProfitTableProfit">RTax25ProfitTableProfit</a>

First included in: Group/LedgerCurrencyParameters_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RTax25ProfitTableProfit attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#RTax25ProfitTableProfitCust name="RTax25ProfitTableProfitCust">RTax25ProfitTableProfitCust</a>

First included in: Group/LedgerCurrencyParameters_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RTax25ProfitTableProfitCust attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#RTax25ProfitTableProfitCustPrepayment name="RTax25ProfitTableProfitCustPrepayment">RTax25ProfitTableProfitCustPrepayment</a>

First included in: Group/LedgerCurrencyParameters_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RTax25ProfitTableProfitCustPrepayment attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#RTax25ProfitTableProfitEmpl name="RTax25ProfitTableProfitEmpl">RTax25ProfitTableProfitEmpl</a>

First included in: Group/LedgerCurrencyParameters_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RTax25ProfitTableProfitEmpl attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#RTax25ProfitTableProfitVend name="RTax25ProfitTableProfitVend">RTax25ProfitTableProfitVend</a>

First included in: Group/LedgerCurrencyParameters_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RTax25ProfitTableProfitVend attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#RTax25ProfitTableProfitVendPrepayment name="RTax25ProfitTableProfitVendPrepayment">RTax25ProfitTableProfitVendPrepayment</a>

First included in: Group/LedgerCurrencyParameters_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RTax25ProfitTableProfitVendPrepayment attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#TaxAmountDifference name="TaxAmountDifference">TaxAmountDifference</a>

First included in: Group/LedgerCurrencyParameters_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxAmountDifference attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#TaxAmountDifferenceLoss name="TaxAmountDifferenceLoss">TaxAmountDifferenceLoss</a>

First included in: Group/LedgerCurrencyParameters_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxAmountDifferenceLoss attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#TaxAmountDiffLedgerDimension name="TaxAmountDiffLedgerDimension">TaxAmountDiffLedgerDimension</a>

First included in: Group/LedgerCurrencyParameters_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxAmountDiffLedgerDimension attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#TaxAmountDiffLossLedgerDimension name="TaxAmountDiffLossLedgerDimension">TaxAmountDiffLossLedgerDimension</a>

First included in: Group/LedgerCurrencyParameters_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxAmountDiffLossLedgerDimension attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#TaxAmountDiffProfitLedgerDimension name="TaxAmountDiffProfitLedgerDimension">TaxAmountDiffProfitLedgerDimension</a>

First included in: Group/LedgerCurrencyParameters_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxAmountDiffProfitLedgerDimension attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#UnrealizedLossCustLedgerDimension name="UnrealizedLossCustLedgerDimension">UnrealizedLossCustLedgerDimension</a>

First included in: Group/LedgerCurrencyParameters_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the UnrealizedLossCustLedgerDimension attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#UnrealizedLossEmplLedgerDimension name="UnrealizedLossEmplLedgerDimension">UnrealizedLossEmplLedgerDimension</a>

First included in: Group/LedgerCurrencyParameters_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the UnrealizedLossEmplLedgerDimension attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#UnrealizedLossTaxCustLedgerDimension name="UnrealizedLossTaxCustLedgerDimension">UnrealizedLossTaxCustLedgerDimension</a>

First included in: Group/LedgerCurrencyParameters_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the UnrealizedLossTaxCustLedgerDimension attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#UnrealizedLossVendLedgerDimension name="UnrealizedLossVendLedgerDimension">UnrealizedLossVendLedgerDimension</a>

First included in: Group/LedgerCurrencyParameters_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the UnrealizedLossVendLedgerDimension attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#UnrealizedProfitCustLedgerDimension name="UnrealizedProfitCustLedgerDimension">UnrealizedProfitCustLedgerDimension</a>

First included in: Group/LedgerCurrencyParameters_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the UnrealizedProfitCustLedgerDimension attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#UnrealizedProfitEmplLedgerDimension name="UnrealizedProfitEmplLedgerDimension">UnrealizedProfitEmplLedgerDimension</a>

First included in: Group/LedgerCurrencyParameters_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the UnrealizedProfitEmplLedgerDimension attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#UnrealizedProfitTaxCustLedgerDimension name="UnrealizedProfitTaxCustLedgerDimension">UnrealizedProfitTaxCustLedgerDimension</a>

First included in: Group/LedgerCurrencyParameters_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the UnrealizedProfitTaxCustLedgerDimension attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#UnrealizedProfitVendLedgerDimension name="UnrealizedProfitVendLedgerDimension">UnrealizedProfitVendLedgerDimension</a>

First included in: Group/LedgerCurrencyParameters_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the UnrealizedProfitVendLedgerDimension attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#VendPostingMode name="VendPostingMode">VendPostingMode</a>

First included in: Group/LedgerCurrencyParameters_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VendPostingMode attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#VendPostingModeTax name="VendPostingModeTax">VendPostingModeTax</a>

First included in: Group/LedgerCurrencyParameters_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VendPostingModeTax attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#DataAreaId name="DataAreaId">DataAreaId</a>

First included in: Group/LedgerCurrencyParameters_RU (this entity)  

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

### <a href=#Relationship_CurConvertLossLedgerDimensionRelationshipId name="Relationship_CurConvertLossLedgerDimensionRelationshipId">Relationship_CurConvertLossLedgerDimensionRelationshipId</a>

First included in: Group/LedgerCurrencyParameters_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_CurConvertLossLedgerDimensionRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../FinancialDimensions/Main/DimensionAttributeValueCombination.md" target="_blank">/core/erp/Tables/Finance/FinancialDimensions/Main/DimensionAttributeValueCombination.cdm.json/DimensionAttributeValueCombination</a></td><td><a href="../../FinancialDimensions/Main/DimensionAttributeValueCombination.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_CurConvertProfitLedgerDimensionRelationshipId name="Relationship_CurConvertProfitLedgerDimensionRelationshipId">Relationship_CurConvertProfitLedgerDimensionRelationshipId</a>

First included in: Group/LedgerCurrencyParameters_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_CurConvertProfitLedgerDimensionRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../FinancialDimensions/Main/DimensionAttributeValueCombination.md" target="_blank">/core/erp/Tables/Finance/FinancialDimensions/Main/DimensionAttributeValueCombination.cdm.json/DimensionAttributeValueCombination</a></td><td><a href="../../FinancialDimensions/Main/DimensionAttributeValueCombination.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_CurrencyRelationshipId name="Relationship_CurrencyRelationshipId">Relationship_CurrencyRelationshipId</a>

First included in: Group/LedgerCurrencyParameters_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_CurrencyRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Common/Currency/Group/Currency.md" target="_blank">/core/erp/Tables/Common/Currency/Group/Currency.cdm.json/Currency</a></td><td><a href="../../../Common/Currency/Group/Currency.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_LedgerRelationshipId name="Relationship_LedgerRelationshipId">Relationship_LedgerRelationshipId</a>

First included in: Group/LedgerCurrencyParameters_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_LedgerRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Main/Ledger.md" target="_blank">/core/erp/Tables/Finance/Ledger/Main/Ledger.cdm.json/Ledger</a></td><td><a href="../Main/Ledger.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_RealizedLossCustLedgerDimensionRelationshipId name="Relationship_RealizedLossCustLedgerDimensionRelationshipId">Relationship_RealizedLossCustLedgerDimensionRelationshipId</a>

First included in: Group/LedgerCurrencyParameters_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_RealizedLossCustLedgerDimensionRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../FinancialDimensions/Main/DimensionAttributeValueCombination.md" target="_blank">/core/erp/Tables/Finance/FinancialDimensions/Main/DimensionAttributeValueCombination.cdm.json/DimensionAttributeValueCombination</a></td><td><a href="../../FinancialDimensions/Main/DimensionAttributeValueCombination.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_RealizedLossEmplLedgerDimensionRelationshipId name="Relationship_RealizedLossEmplLedgerDimensionRelationshipId">Relationship_RealizedLossEmplLedgerDimensionRelationshipId</a>

First included in: Group/LedgerCurrencyParameters_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_RealizedLossEmplLedgerDimensionRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../FinancialDimensions/Main/DimensionAttributeValueCombination.md" target="_blank">/core/erp/Tables/Finance/FinancialDimensions/Main/DimensionAttributeValueCombination.cdm.json/DimensionAttributeValueCombination</a></td><td><a href="../../FinancialDimensions/Main/DimensionAttributeValueCombination.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_RealizedLossTaxCustLedgerDimensionRelationshipId name="Relationship_RealizedLossTaxCustLedgerDimensionRelationshipId">Relationship_RealizedLossTaxCustLedgerDimensionRelationshipId</a>

First included in: Group/LedgerCurrencyParameters_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_RealizedLossTaxCustLedgerDimensionRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../FinancialDimensions/Main/DimensionAttributeValueCombination.md" target="_blank">/core/erp/Tables/Finance/FinancialDimensions/Main/DimensionAttributeValueCombination.cdm.json/DimensionAttributeValueCombination</a></td><td><a href="../../FinancialDimensions/Main/DimensionAttributeValueCombination.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_RealizedLossTaxVendLedgerDimensionRelationshipId name="Relationship_RealizedLossTaxVendLedgerDimensionRelationshipId">Relationship_RealizedLossTaxVendLedgerDimensionRelationshipId</a>

First included in: Group/LedgerCurrencyParameters_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_RealizedLossTaxVendLedgerDimensionRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../FinancialDimensions/Main/DimensionAttributeValueCombination.md" target="_blank">/core/erp/Tables/Finance/FinancialDimensions/Main/DimensionAttributeValueCombination.cdm.json/DimensionAttributeValueCombination</a></td><td><a href="../../FinancialDimensions/Main/DimensionAttributeValueCombination.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_RealizedLossVendLedgerDimensionRelationshipId name="Relationship_RealizedLossVendLedgerDimensionRelationshipId">Relationship_RealizedLossVendLedgerDimensionRelationshipId</a>

First included in: Group/LedgerCurrencyParameters_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_RealizedLossVendLedgerDimensionRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../FinancialDimensions/Main/DimensionAttributeValueCombination.md" target="_blank">/core/erp/Tables/Finance/FinancialDimensions/Main/DimensionAttributeValueCombination.cdm.json/DimensionAttributeValueCombination</a></td><td><a href="../../FinancialDimensions/Main/DimensionAttributeValueCombination.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_RealizedProfitCustLedgerDimensionRelationshipId name="Relationship_RealizedProfitCustLedgerDimensionRelationshipId">Relationship_RealizedProfitCustLedgerDimensionRelationshipId</a>

First included in: Group/LedgerCurrencyParameters_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_RealizedProfitCustLedgerDimensionRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../FinancialDimensions/Main/DimensionAttributeValueCombination.md" target="_blank">/core/erp/Tables/Finance/FinancialDimensions/Main/DimensionAttributeValueCombination.cdm.json/DimensionAttributeValueCombination</a></td><td><a href="../../FinancialDimensions/Main/DimensionAttributeValueCombination.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_RealizedProfitEmplLedgerDimensionRelationshipId name="Relationship_RealizedProfitEmplLedgerDimensionRelationshipId">Relationship_RealizedProfitEmplLedgerDimensionRelationshipId</a>

First included in: Group/LedgerCurrencyParameters_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_RealizedProfitEmplLedgerDimensionRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../FinancialDimensions/Main/DimensionAttributeValueCombination.md" target="_blank">/core/erp/Tables/Finance/FinancialDimensions/Main/DimensionAttributeValueCombination.cdm.json/DimensionAttributeValueCombination</a></td><td><a href="../../FinancialDimensions/Main/DimensionAttributeValueCombination.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_RealizedProfitTaxCustLedgerDimensionRelationshipId name="Relationship_RealizedProfitTaxCustLedgerDimensionRelationshipId">Relationship_RealizedProfitTaxCustLedgerDimensionRelationshipId</a>

First included in: Group/LedgerCurrencyParameters_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_RealizedProfitTaxCustLedgerDimensionRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../FinancialDimensions/Main/DimensionAttributeValueCombination.md" target="_blank">/core/erp/Tables/Finance/FinancialDimensions/Main/DimensionAttributeValueCombination.cdm.json/DimensionAttributeValueCombination</a></td><td><a href="../../FinancialDimensions/Main/DimensionAttributeValueCombination.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_RealizedProfitTaxVendLedgerDimensionRelationshipId name="Relationship_RealizedProfitTaxVendLedgerDimensionRelationshipId">Relationship_RealizedProfitTaxVendLedgerDimensionRelationshipId</a>

First included in: Group/LedgerCurrencyParameters_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_RealizedProfitTaxVendLedgerDimensionRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../FinancialDimensions/Main/DimensionAttributeValueCombination.md" target="_blank">/core/erp/Tables/Finance/FinancialDimensions/Main/DimensionAttributeValueCombination.cdm.json/DimensionAttributeValueCombination</a></td><td><a href="../../FinancialDimensions/Main/DimensionAttributeValueCombination.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_RealizedProfitVendLedgerDimensionRelationshipId name="Relationship_RealizedProfitVendLedgerDimensionRelationshipId">Relationship_RealizedProfitVendLedgerDimensionRelationshipId</a>

First included in: Group/LedgerCurrencyParameters_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_RealizedProfitVendLedgerDimensionRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../FinancialDimensions/Main/DimensionAttributeValueCombination.md" target="_blank">/core/erp/Tables/Finance/FinancialDimensions/Main/DimensionAttributeValueCombination.cdm.json/DimensionAttributeValueCombination</a></td><td><a href="../../FinancialDimensions/Main/DimensionAttributeValueCombination.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_RTax25ProfitTableConvertLossRelationshipId name="Relationship_RTax25ProfitTableConvertLossRelationshipId">Relationship_RTax25ProfitTableConvertLossRelationshipId</a>

First included in: Group/LedgerCurrencyParameters_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_RTax25ProfitTableConvertLossRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../RTax25/Group/RTax25ProfitTable.md" target="_blank">/core/erp/Tables/Finance/RTax25/Group/RTax25ProfitTable.cdm.json/RTax25ProfitTable</a></td><td><a href="../../RTax25/Group/RTax25ProfitTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_RTax25ProfitTableConvertProfitRelationshipId name="Relationship_RTax25ProfitTableConvertProfitRelationshipId">Relationship_RTax25ProfitTableConvertProfitRelationshipId</a>

First included in: Group/LedgerCurrencyParameters_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_RTax25ProfitTableConvertProfitRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../RTax25/Group/RTax25ProfitTable.md" target="_blank">/core/erp/Tables/Finance/RTax25/Group/RTax25ProfitTable.cdm.json/RTax25ProfitTable</a></td><td><a href="../../RTax25/Group/RTax25ProfitTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_RTax25ProfitTableLossRelationshipId name="Relationship_RTax25ProfitTableLossRelationshipId">Relationship_RTax25ProfitTableLossRelationshipId</a>

First included in: Group/LedgerCurrencyParameters_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_RTax25ProfitTableLossRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../RTax25/Group/RTax25ProfitTable.md" target="_blank">/core/erp/Tables/Finance/RTax25/Group/RTax25ProfitTable.cdm.json/RTax25ProfitTable</a></td><td><a href="../../RTax25/Group/RTax25ProfitTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_RTax25ProfitTableLossCustRelationshipId name="Relationship_RTax25ProfitTableLossCustRelationshipId">Relationship_RTax25ProfitTableLossCustRelationshipId</a>

First included in: Group/LedgerCurrencyParameters_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_RTax25ProfitTableLossCustRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../RTax25/Group/RTax25ProfitTable.md" target="_blank">/core/erp/Tables/Finance/RTax25/Group/RTax25ProfitTable.cdm.json/RTax25ProfitTable</a></td><td><a href="../../RTax25/Group/RTax25ProfitTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_RTax25ProfitTableLossCustPrepaymentRelationshipId name="Relationship_RTax25ProfitTableLossCustPrepaymentRelationshipId">Relationship_RTax25ProfitTableLossCustPrepaymentRelationshipId</a>

First included in: Group/LedgerCurrencyParameters_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_RTax25ProfitTableLossCustPrepaymentRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../RTax25/Group/RTax25ProfitTable.md" target="_blank">/core/erp/Tables/Finance/RTax25/Group/RTax25ProfitTable.cdm.json/RTax25ProfitTable</a></td><td><a href="../../RTax25/Group/RTax25ProfitTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_RTax25ProfitTableLossEmplRelationshipId name="Relationship_RTax25ProfitTableLossEmplRelationshipId">Relationship_RTax25ProfitTableLossEmplRelationshipId</a>

First included in: Group/LedgerCurrencyParameters_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_RTax25ProfitTableLossEmplRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../RTax25/Group/RTax25ProfitTable.md" target="_blank">/core/erp/Tables/Finance/RTax25/Group/RTax25ProfitTable.cdm.json/RTax25ProfitTable</a></td><td><a href="../../RTax25/Group/RTax25ProfitTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_RTax25ProfitTableLossVendRelationshipId name="Relationship_RTax25ProfitTableLossVendRelationshipId">Relationship_RTax25ProfitTableLossVendRelationshipId</a>

First included in: Group/LedgerCurrencyParameters_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_RTax25ProfitTableLossVendRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../RTax25/Group/RTax25ProfitTable.md" target="_blank">/core/erp/Tables/Finance/RTax25/Group/RTax25ProfitTable.cdm.json/RTax25ProfitTable</a></td><td><a href="../../RTax25/Group/RTax25ProfitTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_RTax25ProfitTableLossVendPrepaymentRelationshipId name="Relationship_RTax25ProfitTableLossVendPrepaymentRelationshipId">Relationship_RTax25ProfitTableLossVendPrepaymentRelationshipId</a>

First included in: Group/LedgerCurrencyParameters_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_RTax25ProfitTableLossVendPrepaymentRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../RTax25/Group/RTax25ProfitTable.md" target="_blank">/core/erp/Tables/Finance/RTax25/Group/RTax25ProfitTable.cdm.json/RTax25ProfitTable</a></td><td><a href="../../RTax25/Group/RTax25ProfitTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_RTax25ProfitTableProfitRelationshipId name="Relationship_RTax25ProfitTableProfitRelationshipId">Relationship_RTax25ProfitTableProfitRelationshipId</a>

First included in: Group/LedgerCurrencyParameters_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_RTax25ProfitTableProfitRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../RTax25/Group/RTax25ProfitTable.md" target="_blank">/core/erp/Tables/Finance/RTax25/Group/RTax25ProfitTable.cdm.json/RTax25ProfitTable</a></td><td><a href="../../RTax25/Group/RTax25ProfitTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_RTax25ProfitTableProfitCustRelationshipId name="Relationship_RTax25ProfitTableProfitCustRelationshipId">Relationship_RTax25ProfitTableProfitCustRelationshipId</a>

First included in: Group/LedgerCurrencyParameters_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_RTax25ProfitTableProfitCustRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../RTax25/Group/RTax25ProfitTable.md" target="_blank">/core/erp/Tables/Finance/RTax25/Group/RTax25ProfitTable.cdm.json/RTax25ProfitTable</a></td><td><a href="../../RTax25/Group/RTax25ProfitTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_RTax25ProfitTableProfitCustPrepaymentRelationshipId name="Relationship_RTax25ProfitTableProfitCustPrepaymentRelationshipId">Relationship_RTax25ProfitTableProfitCustPrepaymentRelationshipId</a>

First included in: Group/LedgerCurrencyParameters_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_RTax25ProfitTableProfitCustPrepaymentRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../RTax25/Group/RTax25ProfitTable.md" target="_blank">/core/erp/Tables/Finance/RTax25/Group/RTax25ProfitTable.cdm.json/RTax25ProfitTable</a></td><td><a href="../../RTax25/Group/RTax25ProfitTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_RTax25ProfitTableProfitEmplRelationshipId name="Relationship_RTax25ProfitTableProfitEmplRelationshipId">Relationship_RTax25ProfitTableProfitEmplRelationshipId</a>

First included in: Group/LedgerCurrencyParameters_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_RTax25ProfitTableProfitEmplRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../RTax25/Group/RTax25ProfitTable.md" target="_blank">/core/erp/Tables/Finance/RTax25/Group/RTax25ProfitTable.cdm.json/RTax25ProfitTable</a></td><td><a href="../../RTax25/Group/RTax25ProfitTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_RTax25ProfitTableProfitVendRelationshipId name="Relationship_RTax25ProfitTableProfitVendRelationshipId">Relationship_RTax25ProfitTableProfitVendRelationshipId</a>

First included in: Group/LedgerCurrencyParameters_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_RTax25ProfitTableProfitVendRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../RTax25/Group/RTax25ProfitTable.md" target="_blank">/core/erp/Tables/Finance/RTax25/Group/RTax25ProfitTable.cdm.json/RTax25ProfitTable</a></td><td><a href="../../RTax25/Group/RTax25ProfitTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_RTax25ProfitTableProfitVendPrepaymentRelationshipId name="Relationship_RTax25ProfitTableProfitVendPrepaymentRelationshipId">Relationship_RTax25ProfitTableProfitVendPrepaymentRelationshipId</a>

First included in: Group/LedgerCurrencyParameters_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_RTax25ProfitTableProfitVendPrepaymentRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../RTax25/Group/RTax25ProfitTable.md" target="_blank">/core/erp/Tables/Finance/RTax25/Group/RTax25ProfitTable.cdm.json/RTax25ProfitTable</a></td><td><a href="../../RTax25/Group/RTax25ProfitTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_TaxAmountDiffLedgerDimensionRelationshipId name="Relationship_TaxAmountDiffLedgerDimensionRelationshipId">Relationship_TaxAmountDiffLedgerDimensionRelationshipId</a>

First included in: Group/LedgerCurrencyParameters_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_TaxAmountDiffLedgerDimensionRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../FinancialDimensions/Main/DimensionAttributeValueCombination.md" target="_blank">/core/erp/Tables/Finance/FinancialDimensions/Main/DimensionAttributeValueCombination.cdm.json/DimensionAttributeValueCombination</a></td><td><a href="../../FinancialDimensions/Main/DimensionAttributeValueCombination.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_TaxAmountDiffLossLedgerDimensionRelationshipId name="Relationship_TaxAmountDiffLossLedgerDimensionRelationshipId">Relationship_TaxAmountDiffLossLedgerDimensionRelationshipId</a>

First included in: Group/LedgerCurrencyParameters_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_TaxAmountDiffLossLedgerDimensionRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../FinancialDimensions/Main/DimensionAttributeValueCombination.md" target="_blank">/core/erp/Tables/Finance/FinancialDimensions/Main/DimensionAttributeValueCombination.cdm.json/DimensionAttributeValueCombination</a></td><td><a href="../../FinancialDimensions/Main/DimensionAttributeValueCombination.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_TaxAmountDiffProfitLedgerDimensionRelationshipId name="Relationship_TaxAmountDiffProfitLedgerDimensionRelationshipId">Relationship_TaxAmountDiffProfitLedgerDimensionRelationshipId</a>

First included in: Group/LedgerCurrencyParameters_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_TaxAmountDiffProfitLedgerDimensionRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../FinancialDimensions/Main/DimensionAttributeValueCombination.md" target="_blank">/core/erp/Tables/Finance/FinancialDimensions/Main/DimensionAttributeValueCombination.cdm.json/DimensionAttributeValueCombination</a></td><td><a href="../../FinancialDimensions/Main/DimensionAttributeValueCombination.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_UnrealizedLossCustLedgerDimensionRelationshipId name="Relationship_UnrealizedLossCustLedgerDimensionRelationshipId">Relationship_UnrealizedLossCustLedgerDimensionRelationshipId</a>

First included in: Group/LedgerCurrencyParameters_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_UnrealizedLossCustLedgerDimensionRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../FinancialDimensions/Main/DimensionAttributeValueCombination.md" target="_blank">/core/erp/Tables/Finance/FinancialDimensions/Main/DimensionAttributeValueCombination.cdm.json/DimensionAttributeValueCombination</a></td><td><a href="../../FinancialDimensions/Main/DimensionAttributeValueCombination.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_UnrealizedLossEmplLedgerDimensionRelationshipId name="Relationship_UnrealizedLossEmplLedgerDimensionRelationshipId">Relationship_UnrealizedLossEmplLedgerDimensionRelationshipId</a>

First included in: Group/LedgerCurrencyParameters_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_UnrealizedLossEmplLedgerDimensionRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../FinancialDimensions/Main/DimensionAttributeValueCombination.md" target="_blank">/core/erp/Tables/Finance/FinancialDimensions/Main/DimensionAttributeValueCombination.cdm.json/DimensionAttributeValueCombination</a></td><td><a href="../../FinancialDimensions/Main/DimensionAttributeValueCombination.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_UnrealizedLossTaxCustLedgerDimensionRelationshipId name="Relationship_UnrealizedLossTaxCustLedgerDimensionRelationshipId">Relationship_UnrealizedLossTaxCustLedgerDimensionRelationshipId</a>

First included in: Group/LedgerCurrencyParameters_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_UnrealizedLossTaxCustLedgerDimensionRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../FinancialDimensions/Main/DimensionAttributeValueCombination.md" target="_blank">/core/erp/Tables/Finance/FinancialDimensions/Main/DimensionAttributeValueCombination.cdm.json/DimensionAttributeValueCombination</a></td><td><a href="../../FinancialDimensions/Main/DimensionAttributeValueCombination.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_UnrealizedLossVendLedgerDimensionRelationshipId name="Relationship_UnrealizedLossVendLedgerDimensionRelationshipId">Relationship_UnrealizedLossVendLedgerDimensionRelationshipId</a>

First included in: Group/LedgerCurrencyParameters_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_UnrealizedLossVendLedgerDimensionRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../FinancialDimensions/Main/DimensionAttributeValueCombination.md" target="_blank">/core/erp/Tables/Finance/FinancialDimensions/Main/DimensionAttributeValueCombination.cdm.json/DimensionAttributeValueCombination</a></td><td><a href="../../FinancialDimensions/Main/DimensionAttributeValueCombination.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_UnrealizedProfitCustLedgerDimensionRelationshipId name="Relationship_UnrealizedProfitCustLedgerDimensionRelationshipId">Relationship_UnrealizedProfitCustLedgerDimensionRelationshipId</a>

First included in: Group/LedgerCurrencyParameters_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_UnrealizedProfitCustLedgerDimensionRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../FinancialDimensions/Main/DimensionAttributeValueCombination.md" target="_blank">/core/erp/Tables/Finance/FinancialDimensions/Main/DimensionAttributeValueCombination.cdm.json/DimensionAttributeValueCombination</a></td><td><a href="../../FinancialDimensions/Main/DimensionAttributeValueCombination.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_UnrealizedProfitEmplLedgerDimensionRelationshipId name="Relationship_UnrealizedProfitEmplLedgerDimensionRelationshipId">Relationship_UnrealizedProfitEmplLedgerDimensionRelationshipId</a>

First included in: Group/LedgerCurrencyParameters_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_UnrealizedProfitEmplLedgerDimensionRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../FinancialDimensions/Main/DimensionAttributeValueCombination.md" target="_blank">/core/erp/Tables/Finance/FinancialDimensions/Main/DimensionAttributeValueCombination.cdm.json/DimensionAttributeValueCombination</a></td><td><a href="../../FinancialDimensions/Main/DimensionAttributeValueCombination.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_UnrealizedProfitTaxCustLedgerDimensionRelationshipId name="Relationship_UnrealizedProfitTaxCustLedgerDimensionRelationshipId">Relationship_UnrealizedProfitTaxCustLedgerDimensionRelationshipId</a>

First included in: Group/LedgerCurrencyParameters_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_UnrealizedProfitTaxCustLedgerDimensionRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../FinancialDimensions/Main/DimensionAttributeValueCombination.md" target="_blank">/core/erp/Tables/Finance/FinancialDimensions/Main/DimensionAttributeValueCombination.cdm.json/DimensionAttributeValueCombination</a></td><td><a href="../../FinancialDimensions/Main/DimensionAttributeValueCombination.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_UnrealizedProfitVendLedgerDimensionRelationshipId name="Relationship_UnrealizedProfitVendLedgerDimensionRelationshipId">Relationship_UnrealizedProfitVendLedgerDimensionRelationshipId</a>

First included in: Group/LedgerCurrencyParameters_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_UnrealizedProfitVendLedgerDimensionRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../FinancialDimensions/Main/DimensionAttributeValueCombination.md" target="_blank">/core/erp/Tables/Finance/FinancialDimensions/Main/DimensionAttributeValueCombination.cdm.json/DimensionAttributeValueCombination</a></td><td><a href="../../FinancialDimensions/Main/DimensionAttributeValueCombination.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_CompanyRelationshipId name="Relationship_CompanyRelationshipId">Relationship_CompanyRelationshipId</a>

First included in: Group/LedgerCurrencyParameters_RU (this entity)  

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
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Main/CompanyInfo.md" target="_blank">/core/erp/Tables/Finance/Ledger/Main/CompanyInfo.cdm.json/CompanyInfo</a></td><td><a href="../Main/CompanyInfo.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>
