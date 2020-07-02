---
title: LedgerCurrencyParametersV2Entity - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 6/30/2020
ms.author: nebanfic
---

# Ledger Currency Parameters Entity V2

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/Finance/GeneralLedger/LedgerCurrencyParametersV2Entity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Ledger Currency Parameters Entity V2</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[CurConvertLossLedgerDimension](#CurConvertLossLedgerDimension)||<a href="LedgerCurrencyParametersV2Entity.md" target="_blank">GeneralLedger/LedgerCurrencyParametersV2Entity</a>|
|[CurConvertProfitLedgerDimension](#CurConvertProfitLedgerDimension)||<a href="LedgerCurrencyParametersV2Entity.md" target="_blank">GeneralLedger/LedgerCurrencyParametersV2Entity</a>|
|[CurrencyCode](#CurrencyCode)||<a href="LedgerCurrencyParametersV2Entity.md" target="_blank">GeneralLedger/LedgerCurrencyParametersV2Entity</a>|
|[CustPostingMode](#CustPostingMode)||<a href="LedgerCurrencyParametersV2Entity.md" target="_blank">GeneralLedger/LedgerCurrencyParametersV2Entity</a>|
|[CustPostingModeTax](#CustPostingModeTax)||<a href="LedgerCurrencyParametersV2Entity.md" target="_blank">GeneralLedger/LedgerCurrencyParametersV2Entity</a>|
|[ExchRateLossTaxVend](#ExchRateLossTaxVend)||<a href="LedgerCurrencyParametersV2Entity.md" target="_blank">GeneralLedger/LedgerCurrencyParametersV2Entity</a>|
|[ExchRateNeg](#ExchRateNeg)||<a href="LedgerCurrencyParametersV2Entity.md" target="_blank">GeneralLedger/LedgerCurrencyParametersV2Entity</a>|
|[ExchRateNonrealLossTaxCust](#ExchRateNonrealLossTaxCust)||<a href="LedgerCurrencyParametersV2Entity.md" target="_blank">GeneralLedger/LedgerCurrencyParametersV2Entity</a>|
|[ExchRateNonrealProfitTaxCust](#ExchRateNonrealProfitTaxCust)||<a href="LedgerCurrencyParametersV2Entity.md" target="_blank">GeneralLedger/LedgerCurrencyParametersV2Entity</a>|
|[ExchRatePos](#ExchRatePos)||<a href="LedgerCurrencyParametersV2Entity.md" target="_blank">GeneralLedger/LedgerCurrencyParametersV2Entity</a>|
|[ExchRateProfitTaxVend](#ExchRateProfitTaxVend)||<a href="LedgerCurrencyParametersV2Entity.md" target="_blank">GeneralLedger/LedgerCurrencyParametersV2Entity</a>|
|[Ledger](#Ledger)||<a href="LedgerCurrencyParametersV2Entity.md" target="_blank">GeneralLedger/LedgerCurrencyParametersV2Entity</a>|
|[RealizedLossCustLedgerDimension](#RealizedLossCustLedgerDimension)||<a href="LedgerCurrencyParametersV2Entity.md" target="_blank">GeneralLedger/LedgerCurrencyParametersV2Entity</a>|
|[RealizedLossEmplLedgerDimension](#RealizedLossEmplLedgerDimension)||<a href="LedgerCurrencyParametersV2Entity.md" target="_blank">GeneralLedger/LedgerCurrencyParametersV2Entity</a>|
|[RealizedLossVendLedgerDimension](#RealizedLossVendLedgerDimension)||<a href="LedgerCurrencyParametersV2Entity.md" target="_blank">GeneralLedger/LedgerCurrencyParametersV2Entity</a>|
|[RealizedProfitCustLedgerDimension](#RealizedProfitCustLedgerDimension)||<a href="LedgerCurrencyParametersV2Entity.md" target="_blank">GeneralLedger/LedgerCurrencyParametersV2Entity</a>|
|[RealizedProfitEmplLedgerDimension](#RealizedProfitEmplLedgerDimension)||<a href="LedgerCurrencyParametersV2Entity.md" target="_blank">GeneralLedger/LedgerCurrencyParametersV2Entity</a>|
|[RealizedProfitVendLedgerDimension](#RealizedProfitVendLedgerDimension)||<a href="LedgerCurrencyParametersV2Entity.md" target="_blank">GeneralLedger/LedgerCurrencyParametersV2Entity</a>|
|[RTax25ProfitTableConvertLoss](#RTax25ProfitTableConvertLoss)||<a href="LedgerCurrencyParametersV2Entity.md" target="_blank">GeneralLedger/LedgerCurrencyParametersV2Entity</a>|
|[RTax25ProfitTableConvertProfit](#RTax25ProfitTableConvertProfit)||<a href="LedgerCurrencyParametersV2Entity.md" target="_blank">GeneralLedger/LedgerCurrencyParametersV2Entity</a>|
|[RTax25ProfitTableLoss](#RTax25ProfitTableLoss)||<a href="LedgerCurrencyParametersV2Entity.md" target="_blank">GeneralLedger/LedgerCurrencyParametersV2Entity</a>|
|[RTax25ProfitTableLossCust](#RTax25ProfitTableLossCust)||<a href="LedgerCurrencyParametersV2Entity.md" target="_blank">GeneralLedger/LedgerCurrencyParametersV2Entity</a>|
|[RTax25ProfitTableLossCustPrepayment](#RTax25ProfitTableLossCustPrepayment)||<a href="LedgerCurrencyParametersV2Entity.md" target="_blank">GeneralLedger/LedgerCurrencyParametersV2Entity</a>|
|[RTax25ProfitTableLossEmpl](#RTax25ProfitTableLossEmpl)||<a href="LedgerCurrencyParametersV2Entity.md" target="_blank">GeneralLedger/LedgerCurrencyParametersV2Entity</a>|
|[RTax25ProfitTableLossVend](#RTax25ProfitTableLossVend)||<a href="LedgerCurrencyParametersV2Entity.md" target="_blank">GeneralLedger/LedgerCurrencyParametersV2Entity</a>|
|[RTax25ProfitTableLossVendPrepayment](#RTax25ProfitTableLossVendPrepayment)||<a href="LedgerCurrencyParametersV2Entity.md" target="_blank">GeneralLedger/LedgerCurrencyParametersV2Entity</a>|
|[RTax25ProfitTableProfit](#RTax25ProfitTableProfit)||<a href="LedgerCurrencyParametersV2Entity.md" target="_blank">GeneralLedger/LedgerCurrencyParametersV2Entity</a>|
|[RTax25ProfitTableProfitCust](#RTax25ProfitTableProfitCust)||<a href="LedgerCurrencyParametersV2Entity.md" target="_blank">GeneralLedger/LedgerCurrencyParametersV2Entity</a>|
|[RTax25ProfitTableProfitCustPrepayment](#RTax25ProfitTableProfitCustPrepayment)||<a href="LedgerCurrencyParametersV2Entity.md" target="_blank">GeneralLedger/LedgerCurrencyParametersV2Entity</a>|
|[RTax25ProfitTableProfitEmpl](#RTax25ProfitTableProfitEmpl)||<a href="LedgerCurrencyParametersV2Entity.md" target="_blank">GeneralLedger/LedgerCurrencyParametersV2Entity</a>|
|[RTax25ProfitTableProfitVend](#RTax25ProfitTableProfitVend)||<a href="LedgerCurrencyParametersV2Entity.md" target="_blank">GeneralLedger/LedgerCurrencyParametersV2Entity</a>|
|[RTax25ProfitTableProfitVendPrepayment](#RTax25ProfitTableProfitVendPrepayment)||<a href="LedgerCurrencyParametersV2Entity.md" target="_blank">GeneralLedger/LedgerCurrencyParametersV2Entity</a>|
|[TaxAmountDifference](#TaxAmountDifference)||<a href="LedgerCurrencyParametersV2Entity.md" target="_blank">GeneralLedger/LedgerCurrencyParametersV2Entity</a>|
|[TaxAmountDifferenceLoss](#TaxAmountDifferenceLoss)||<a href="LedgerCurrencyParametersV2Entity.md" target="_blank">GeneralLedger/LedgerCurrencyParametersV2Entity</a>|
|[TaxAmountDiffLedgerDimension](#TaxAmountDiffLedgerDimension)||<a href="LedgerCurrencyParametersV2Entity.md" target="_blank">GeneralLedger/LedgerCurrencyParametersV2Entity</a>|
|[TaxAmountDiffLossLedgerDimension](#TaxAmountDiffLossLedgerDimension)||<a href="LedgerCurrencyParametersV2Entity.md" target="_blank">GeneralLedger/LedgerCurrencyParametersV2Entity</a>|
|[TaxAmountDiffProfitLedgerDimension](#TaxAmountDiffProfitLedgerDimension)||<a href="LedgerCurrencyParametersV2Entity.md" target="_blank">GeneralLedger/LedgerCurrencyParametersV2Entity</a>|
|[UnrealizedLossCustLedgerDimension](#UnrealizedLossCustLedgerDimension)||<a href="LedgerCurrencyParametersV2Entity.md" target="_blank">GeneralLedger/LedgerCurrencyParametersV2Entity</a>|
|[UnrealizedLossEmplLedgerDimension](#UnrealizedLossEmplLedgerDimension)||<a href="LedgerCurrencyParametersV2Entity.md" target="_blank">GeneralLedger/LedgerCurrencyParametersV2Entity</a>|
|[UnrealizedLossVendLedgerDimension](#UnrealizedLossVendLedgerDimension)||<a href="LedgerCurrencyParametersV2Entity.md" target="_blank">GeneralLedger/LedgerCurrencyParametersV2Entity</a>|
|[UnrealizedProfitCustLedgerDimension](#UnrealizedProfitCustLedgerDimension)||<a href="LedgerCurrencyParametersV2Entity.md" target="_blank">GeneralLedger/LedgerCurrencyParametersV2Entity</a>|
|[UnrealizedProfitEmplLedgerDimension](#UnrealizedProfitEmplLedgerDimension)||<a href="LedgerCurrencyParametersV2Entity.md" target="_blank">GeneralLedger/LedgerCurrencyParametersV2Entity</a>|
|[UnrealizedProfitVendLedgerDimension](#UnrealizedProfitVendLedgerDimension)||<a href="LedgerCurrencyParametersV2Entity.md" target="_blank">GeneralLedger/LedgerCurrencyParametersV2Entity</a>|
|[VendPostingMode](#VendPostingMode)||<a href="LedgerCurrencyParametersV2Entity.md" target="_blank">GeneralLedger/LedgerCurrencyParametersV2Entity</a>|
|[VendPostingModeTax](#VendPostingModeTax)||<a href="LedgerCurrencyParametersV2Entity.md" target="_blank">GeneralLedger/LedgerCurrencyParametersV2Entity</a>|
|[Ledger_Name](#Ledger_Name)||<a href="LedgerCurrencyParametersV2Entity.md" target="_blank">GeneralLedger/LedgerCurrencyParametersV2Entity</a>|
|[ConvertLossExpenseCode](#ConvertLossExpenseCode)||<a href="LedgerCurrencyParametersV2Entity.md" target="_blank">GeneralLedger/LedgerCurrencyParametersV2Entity</a>|
|[ConvertProfitIncomeCode](#ConvertProfitIncomeCode)||<a href="LedgerCurrencyParametersV2Entity.md" target="_blank">GeneralLedger/LedgerCurrencyParametersV2Entity</a>|
|[LossGeneralExpenseCode](#LossGeneralExpenseCode)||<a href="LedgerCurrencyParametersV2Entity.md" target="_blank">GeneralLedger/LedgerCurrencyParametersV2Entity</a>|
|[LossCustExpenseCode](#LossCustExpenseCode)||<a href="LedgerCurrencyParametersV2Entity.md" target="_blank">GeneralLedger/LedgerCurrencyParametersV2Entity</a>|
|[LossCustPrepaymentExpenseCode](#LossCustPrepaymentExpenseCode)||<a href="LedgerCurrencyParametersV2Entity.md" target="_blank">GeneralLedger/LedgerCurrencyParametersV2Entity</a>|
|[LossEmplExpenseCode](#LossEmplExpenseCode)||<a href="LedgerCurrencyParametersV2Entity.md" target="_blank">GeneralLedger/LedgerCurrencyParametersV2Entity</a>|
|[LossVendExpenseCode](#LossVendExpenseCode)||<a href="LedgerCurrencyParametersV2Entity.md" target="_blank">GeneralLedger/LedgerCurrencyParametersV2Entity</a>|
|[LossVendPrepaymentExpenseCode](#LossVendPrepaymentExpenseCode)||<a href="LedgerCurrencyParametersV2Entity.md" target="_blank">GeneralLedger/LedgerCurrencyParametersV2Entity</a>|
|[ProfitGeneralIncomeCode](#ProfitGeneralIncomeCode)||<a href="LedgerCurrencyParametersV2Entity.md" target="_blank">GeneralLedger/LedgerCurrencyParametersV2Entity</a>|
|[ProfitCustIncomeCode](#ProfitCustIncomeCode)||<a href="LedgerCurrencyParametersV2Entity.md" target="_blank">GeneralLedger/LedgerCurrencyParametersV2Entity</a>|
|[ProfitCustPrepaymentIncomeCode](#ProfitCustPrepaymentIncomeCode)||<a href="LedgerCurrencyParametersV2Entity.md" target="_blank">GeneralLedger/LedgerCurrencyParametersV2Entity</a>|
|[ProfitEmplIncomeCode](#ProfitEmplIncomeCode)||<a href="LedgerCurrencyParametersV2Entity.md" target="_blank">GeneralLedger/LedgerCurrencyParametersV2Entity</a>|
|[ProfitVendIncomeCode](#ProfitVendIncomeCode)||<a href="LedgerCurrencyParametersV2Entity.md" target="_blank">GeneralLedger/LedgerCurrencyParametersV2Entity</a>|
|[ProfitVendPrepaymentIncomeCode](#ProfitVendPrepaymentIncomeCode)||<a href="LedgerCurrencyParametersV2Entity.md" target="_blank">GeneralLedger/LedgerCurrencyParametersV2Entity</a>|
|[CurConvertLossLedgerDimensionDisplayValue](#CurConvertLossLedgerDimensionDisplayValue)||<a href="LedgerCurrencyParametersV2Entity.md" target="_blank">GeneralLedger/LedgerCurrencyParametersV2Entity</a>|
|[CurConvertProfitLedgerDimensionDisplayValue](#CurConvertProfitLedgerDimensionDisplayValue)||<a href="LedgerCurrencyParametersV2Entity.md" target="_blank">GeneralLedger/LedgerCurrencyParametersV2Entity</a>|
|[RealizedLossCustLedgerDimensionDisplayValue](#RealizedLossCustLedgerDimensionDisplayValue)||<a href="LedgerCurrencyParametersV2Entity.md" target="_blank">GeneralLedger/LedgerCurrencyParametersV2Entity</a>|
|[RealizedLossEmplLedgerDimensionDisplayValue](#RealizedLossEmplLedgerDimensionDisplayValue)||<a href="LedgerCurrencyParametersV2Entity.md" target="_blank">GeneralLedger/LedgerCurrencyParametersV2Entity</a>|
|[RealizedLossVendLedgerDimensionDisplayValue](#RealizedLossVendLedgerDimensionDisplayValue)||<a href="LedgerCurrencyParametersV2Entity.md" target="_blank">GeneralLedger/LedgerCurrencyParametersV2Entity</a>|
|[RealizedProfitCustLedgerDimensionDisplayValue](#RealizedProfitCustLedgerDimensionDisplayValue)||<a href="LedgerCurrencyParametersV2Entity.md" target="_blank">GeneralLedger/LedgerCurrencyParametersV2Entity</a>|
|[RealizedProfitEmplLedgerDimensionDisplayValue](#RealizedProfitEmplLedgerDimensionDisplayValue)||<a href="LedgerCurrencyParametersV2Entity.md" target="_blank">GeneralLedger/LedgerCurrencyParametersV2Entity</a>|
|[RealizedProfitVendLedgerDimensionDisplayValue](#RealizedProfitVendLedgerDimensionDisplayValue)||<a href="LedgerCurrencyParametersV2Entity.md" target="_blank">GeneralLedger/LedgerCurrencyParametersV2Entity</a>|
|[TaxAmountDiffLedgerDimensionDisplayValue](#TaxAmountDiffLedgerDimensionDisplayValue)||<a href="LedgerCurrencyParametersV2Entity.md" target="_blank">GeneralLedger/LedgerCurrencyParametersV2Entity</a>|
|[TaxAmountDiffLossLedgerDimensionDisplayValue](#TaxAmountDiffLossLedgerDimensionDisplayValue)||<a href="LedgerCurrencyParametersV2Entity.md" target="_blank">GeneralLedger/LedgerCurrencyParametersV2Entity</a>|
|[TaxAmountDiffProfitLedgerDimensionDisplayValue](#TaxAmountDiffProfitLedgerDimensionDisplayValue)||<a href="LedgerCurrencyParametersV2Entity.md" target="_blank">GeneralLedger/LedgerCurrencyParametersV2Entity</a>|
|[UnrealizedLossCustLedgerDimensionDisplayValue](#UnrealizedLossCustLedgerDimensionDisplayValue)||<a href="LedgerCurrencyParametersV2Entity.md" target="_blank">GeneralLedger/LedgerCurrencyParametersV2Entity</a>|
|[UnrealizedLossEmplLedgerDimensionDisplayValue](#UnrealizedLossEmplLedgerDimensionDisplayValue)||<a href="LedgerCurrencyParametersV2Entity.md" target="_blank">GeneralLedger/LedgerCurrencyParametersV2Entity</a>|
|[UnrealizedLossVendLedgerDimensionDisplayValue](#UnrealizedLossVendLedgerDimensionDisplayValue)||<a href="LedgerCurrencyParametersV2Entity.md" target="_blank">GeneralLedger/LedgerCurrencyParametersV2Entity</a>|
|[UnrealizedProfitCustLedgerDimensionDisplayValue](#UnrealizedProfitCustLedgerDimensionDisplayValue)||<a href="LedgerCurrencyParametersV2Entity.md" target="_blank">GeneralLedger/LedgerCurrencyParametersV2Entity</a>|
|[UnrealizedProfitEmplLedgerDimensionDisplayValue](#UnrealizedProfitEmplLedgerDimensionDisplayValue)||<a href="LedgerCurrencyParametersV2Entity.md" target="_blank">GeneralLedger/LedgerCurrencyParametersV2Entity</a>|
|[UnrealizedProfitVendLedgerDimensionDisplayValue](#UnrealizedProfitVendLedgerDimensionDisplayValue)||<a href="LedgerCurrencyParametersV2Entity.md" target="_blank">GeneralLedger/LedgerCurrencyParametersV2Entity</a>|
|[Relationship_CurConvertLossLedgerDimensionCombinationRelationshipId](#Relationship_CurConvertLossLedgerDimensionCombinationRelationshipId)||<a href="LedgerCurrencyParametersV2Entity.md" target="_blank">GeneralLedger/LedgerCurrencyParametersV2Entity</a>|
|[Relationship_CurConvertProfitLedgerDimensionCombinationRelationshipId](#Relationship_CurConvertProfitLedgerDimensionCombinationRelationshipId)||<a href="LedgerCurrencyParametersV2Entity.md" target="_blank">GeneralLedger/LedgerCurrencyParametersV2Entity</a>|
|[Relationship_RealizedLossCustLedgerDimensionCombinationRelationshipId](#Relationship_RealizedLossCustLedgerDimensionCombinationRelationshipId)||<a href="LedgerCurrencyParametersV2Entity.md" target="_blank">GeneralLedger/LedgerCurrencyParametersV2Entity</a>|
|[Relationship_RealizedLossEmplLedgerDimensionCombinationRelationshipId](#Relationship_RealizedLossEmplLedgerDimensionCombinationRelationshipId)||<a href="LedgerCurrencyParametersV2Entity.md" target="_blank">GeneralLedger/LedgerCurrencyParametersV2Entity</a>|
|[Relationship_RealizedLossVendLedgerDimensionCombinationRelationshipId](#Relationship_RealizedLossVendLedgerDimensionCombinationRelationshipId)||<a href="LedgerCurrencyParametersV2Entity.md" target="_blank">GeneralLedger/LedgerCurrencyParametersV2Entity</a>|
|[Relationship_RealizedProfitCustLedgerDimensionCombinationRelationshipId](#Relationship_RealizedProfitCustLedgerDimensionCombinationRelationshipId)||<a href="LedgerCurrencyParametersV2Entity.md" target="_blank">GeneralLedger/LedgerCurrencyParametersV2Entity</a>|
|[Relationship_RealizedProfitEmplLedgerDimensionCombinationRelationshipId](#Relationship_RealizedProfitEmplLedgerDimensionCombinationRelationshipId)||<a href="LedgerCurrencyParametersV2Entity.md" target="_blank">GeneralLedger/LedgerCurrencyParametersV2Entity</a>|
|[Relationship_RealizedProfitVendLedgerDimensionCombinationRelationshipId](#Relationship_RealizedProfitVendLedgerDimensionCombinationRelationshipId)||<a href="LedgerCurrencyParametersV2Entity.md" target="_blank">GeneralLedger/LedgerCurrencyParametersV2Entity</a>|
|[Relationship_TaxAmountDiffLedgerDimensionCombinationRelationshipId](#Relationship_TaxAmountDiffLedgerDimensionCombinationRelationshipId)||<a href="LedgerCurrencyParametersV2Entity.md" target="_blank">GeneralLedger/LedgerCurrencyParametersV2Entity</a>|
|[Relationship_TaxAmountDiffLossLedgerDimensionCombinationRelationshipId](#Relationship_TaxAmountDiffLossLedgerDimensionCombinationRelationshipId)||<a href="LedgerCurrencyParametersV2Entity.md" target="_blank">GeneralLedger/LedgerCurrencyParametersV2Entity</a>|
|[Relationship_TaxAmountDiffProfitLedgerDimensionCombinationRelationshipId](#Relationship_TaxAmountDiffProfitLedgerDimensionCombinationRelationshipId)||<a href="LedgerCurrencyParametersV2Entity.md" target="_blank">GeneralLedger/LedgerCurrencyParametersV2Entity</a>|
|[Relationship_UnrealizedLossCustLedgerDimensionCombinationRelationshipId](#Relationship_UnrealizedLossCustLedgerDimensionCombinationRelationshipId)||<a href="LedgerCurrencyParametersV2Entity.md" target="_blank">GeneralLedger/LedgerCurrencyParametersV2Entity</a>|
|[Relationship_UnrealizedLossEmplLedgerDimensionCombinationRelationshipId](#Relationship_UnrealizedLossEmplLedgerDimensionCombinationRelationshipId)||<a href="LedgerCurrencyParametersV2Entity.md" target="_blank">GeneralLedger/LedgerCurrencyParametersV2Entity</a>|
|[Relationship_UnrealizedLossVendLedgerDimensionCombinationRelationshipId](#Relationship_UnrealizedLossVendLedgerDimensionCombinationRelationshipId)||<a href="LedgerCurrencyParametersV2Entity.md" target="_blank">GeneralLedger/LedgerCurrencyParametersV2Entity</a>|
|[Relationship_UnrealizedProfitCustLedgerDimensionCombinationRelationshipId](#Relationship_UnrealizedProfitCustLedgerDimensionCombinationRelationshipId)||<a href="LedgerCurrencyParametersV2Entity.md" target="_blank">GeneralLedger/LedgerCurrencyParametersV2Entity</a>|
|[Relationship_UnrealizedProfitEmplLedgerDimensionCombinationRelationshipId](#Relationship_UnrealizedProfitEmplLedgerDimensionCombinationRelationshipId)||<a href="LedgerCurrencyParametersV2Entity.md" target="_blank">GeneralLedger/LedgerCurrencyParametersV2Entity</a>|
|[Relationship_UnrealizedProfitVendLedgerDimensionCombinationRelationshipId](#Relationship_UnrealizedProfitVendLedgerDimensionCombinationRelationshipId)||<a href="LedgerCurrencyParametersV2Entity.md" target="_blank">GeneralLedger/LedgerCurrencyParametersV2Entity</a>|
|[BackingTable_LedgerCurrencyParameters_RURelationshipId](#BackingTable_LedgerCurrencyParameters_RURelationshipId)||<a href="LedgerCurrencyParametersV2Entity.md" target="_blank">GeneralLedger/LedgerCurrencyParametersV2Entity</a>|
|[Relationship_PrimaryCompanyContextRelationshipId](#Relationship_PrimaryCompanyContextRelationshipId)||<a href="LedgerCurrencyParametersV2Entity.md" target="_blank">GeneralLedger/LedgerCurrencyParametersV2Entity</a>|

### <a href=#CurConvertLossLedgerDimension name="CurConvertLossLedgerDimension">CurConvertLossLedgerDimension</a>

First included in: GeneralLedger/LedgerCurrencyParametersV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CurConvertLossLedgerDimension attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CurConvertProfitLedgerDimension name="CurConvertProfitLedgerDimension">CurConvertProfitLedgerDimension</a>

First included in: GeneralLedger/LedgerCurrencyParametersV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CurConvertProfitLedgerDimension attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CurrencyCode name="CurrencyCode">CurrencyCode</a>

First included in: GeneralLedger/LedgerCurrencyParametersV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CurrencyCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CustPostingMode name="CustPostingMode">CustPostingMode</a>

First included in: GeneralLedger/LedgerCurrencyParametersV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CustPostingMode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CustPostingModeTax name="CustPostingModeTax">CustPostingModeTax</a>

First included in: GeneralLedger/LedgerCurrencyParametersV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CustPostingModeTax attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ExchRateLossTaxVend name="ExchRateLossTaxVend">ExchRateLossTaxVend</a>

First included in: GeneralLedger/LedgerCurrencyParametersV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ExchRateLossTaxVend attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ExchRateNeg name="ExchRateNeg">ExchRateNeg</a>

First included in: GeneralLedger/LedgerCurrencyParametersV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ExchRateNeg attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ExchRateNonrealLossTaxCust name="ExchRateNonrealLossTaxCust">ExchRateNonrealLossTaxCust</a>

First included in: GeneralLedger/LedgerCurrencyParametersV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ExchRateNonrealLossTaxCust attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ExchRateNonrealProfitTaxCust name="ExchRateNonrealProfitTaxCust">ExchRateNonrealProfitTaxCust</a>

First included in: GeneralLedger/LedgerCurrencyParametersV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ExchRateNonrealProfitTaxCust attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ExchRatePos name="ExchRatePos">ExchRatePos</a>

First included in: GeneralLedger/LedgerCurrencyParametersV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ExchRatePos attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ExchRateProfitTaxVend name="ExchRateProfitTaxVend">ExchRateProfitTaxVend</a>

First included in: GeneralLedger/LedgerCurrencyParametersV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ExchRateProfitTaxVend attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Ledger name="Ledger">Ledger</a>

First included in: GeneralLedger/LedgerCurrencyParametersV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Ledger attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RealizedLossCustLedgerDimension name="RealizedLossCustLedgerDimension">RealizedLossCustLedgerDimension</a>

First included in: GeneralLedger/LedgerCurrencyParametersV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RealizedLossCustLedgerDimension attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RealizedLossEmplLedgerDimension name="RealizedLossEmplLedgerDimension">RealizedLossEmplLedgerDimension</a>

First included in: GeneralLedger/LedgerCurrencyParametersV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RealizedLossEmplLedgerDimension attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RealizedLossVendLedgerDimension name="RealizedLossVendLedgerDimension">RealizedLossVendLedgerDimension</a>

First included in: GeneralLedger/LedgerCurrencyParametersV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RealizedLossVendLedgerDimension attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RealizedProfitCustLedgerDimension name="RealizedProfitCustLedgerDimension">RealizedProfitCustLedgerDimension</a>

First included in: GeneralLedger/LedgerCurrencyParametersV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RealizedProfitCustLedgerDimension attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RealizedProfitEmplLedgerDimension name="RealizedProfitEmplLedgerDimension">RealizedProfitEmplLedgerDimension</a>

First included in: GeneralLedger/LedgerCurrencyParametersV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RealizedProfitEmplLedgerDimension attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RealizedProfitVendLedgerDimension name="RealizedProfitVendLedgerDimension">RealizedProfitVendLedgerDimension</a>

First included in: GeneralLedger/LedgerCurrencyParametersV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RealizedProfitVendLedgerDimension attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RTax25ProfitTableConvertLoss name="RTax25ProfitTableConvertLoss">RTax25ProfitTableConvertLoss</a>

First included in: GeneralLedger/LedgerCurrencyParametersV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RTax25ProfitTableConvertLoss attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RTax25ProfitTableConvertProfit name="RTax25ProfitTableConvertProfit">RTax25ProfitTableConvertProfit</a>

First included in: GeneralLedger/LedgerCurrencyParametersV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RTax25ProfitTableConvertProfit attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RTax25ProfitTableLoss name="RTax25ProfitTableLoss">RTax25ProfitTableLoss</a>

First included in: GeneralLedger/LedgerCurrencyParametersV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RTax25ProfitTableLoss attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RTax25ProfitTableLossCust name="RTax25ProfitTableLossCust">RTax25ProfitTableLossCust</a>

First included in: GeneralLedger/LedgerCurrencyParametersV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RTax25ProfitTableLossCust attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RTax25ProfitTableLossCustPrepayment name="RTax25ProfitTableLossCustPrepayment">RTax25ProfitTableLossCustPrepayment</a>

First included in: GeneralLedger/LedgerCurrencyParametersV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RTax25ProfitTableLossCustPrepayment attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RTax25ProfitTableLossEmpl name="RTax25ProfitTableLossEmpl">RTax25ProfitTableLossEmpl</a>

First included in: GeneralLedger/LedgerCurrencyParametersV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RTax25ProfitTableLossEmpl attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RTax25ProfitTableLossVend name="RTax25ProfitTableLossVend">RTax25ProfitTableLossVend</a>

First included in: GeneralLedger/LedgerCurrencyParametersV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RTax25ProfitTableLossVend attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RTax25ProfitTableLossVendPrepayment name="RTax25ProfitTableLossVendPrepayment">RTax25ProfitTableLossVendPrepayment</a>

First included in: GeneralLedger/LedgerCurrencyParametersV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RTax25ProfitTableLossVendPrepayment attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RTax25ProfitTableProfit name="RTax25ProfitTableProfit">RTax25ProfitTableProfit</a>

First included in: GeneralLedger/LedgerCurrencyParametersV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RTax25ProfitTableProfit attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RTax25ProfitTableProfitCust name="RTax25ProfitTableProfitCust">RTax25ProfitTableProfitCust</a>

First included in: GeneralLedger/LedgerCurrencyParametersV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RTax25ProfitTableProfitCust attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RTax25ProfitTableProfitCustPrepayment name="RTax25ProfitTableProfitCustPrepayment">RTax25ProfitTableProfitCustPrepayment</a>

First included in: GeneralLedger/LedgerCurrencyParametersV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RTax25ProfitTableProfitCustPrepayment attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RTax25ProfitTableProfitEmpl name="RTax25ProfitTableProfitEmpl">RTax25ProfitTableProfitEmpl</a>

First included in: GeneralLedger/LedgerCurrencyParametersV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RTax25ProfitTableProfitEmpl attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RTax25ProfitTableProfitVend name="RTax25ProfitTableProfitVend">RTax25ProfitTableProfitVend</a>

First included in: GeneralLedger/LedgerCurrencyParametersV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RTax25ProfitTableProfitVend attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RTax25ProfitTableProfitVendPrepayment name="RTax25ProfitTableProfitVendPrepayment">RTax25ProfitTableProfitVendPrepayment</a>

First included in: GeneralLedger/LedgerCurrencyParametersV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RTax25ProfitTableProfitVendPrepayment attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TaxAmountDifference name="TaxAmountDifference">TaxAmountDifference</a>

First included in: GeneralLedger/LedgerCurrencyParametersV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Amount difference in tax accounting</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxAmountDifference attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Amount difference in tax accounting</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TaxAmountDifferenceLoss name="TaxAmountDifferenceLoss">TaxAmountDifferenceLoss</a>

First included in: GeneralLedger/LedgerCurrencyParametersV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Take VAT into account for expenses</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxAmountDifferenceLoss attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Take VAT into account for expenses</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TaxAmountDiffLedgerDimension name="TaxAmountDiffLedgerDimension">TaxAmountDiffLedgerDimension</a>

First included in: GeneralLedger/LedgerCurrencyParametersV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxAmountDiffLedgerDimension attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TaxAmountDiffLossLedgerDimension name="TaxAmountDiffLossLedgerDimension">TaxAmountDiffLossLedgerDimension</a>

First included in: GeneralLedger/LedgerCurrencyParametersV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxAmountDiffLossLedgerDimension attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TaxAmountDiffProfitLedgerDimension name="TaxAmountDiffProfitLedgerDimension">TaxAmountDiffProfitLedgerDimension</a>

First included in: GeneralLedger/LedgerCurrencyParametersV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxAmountDiffProfitLedgerDimension attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#UnrealizedLossCustLedgerDimension name="UnrealizedLossCustLedgerDimension">UnrealizedLossCustLedgerDimension</a>

First included in: GeneralLedger/LedgerCurrencyParametersV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the UnrealizedLossCustLedgerDimension attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#UnrealizedLossEmplLedgerDimension name="UnrealizedLossEmplLedgerDimension">UnrealizedLossEmplLedgerDimension</a>

First included in: GeneralLedger/LedgerCurrencyParametersV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the UnrealizedLossEmplLedgerDimension attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#UnrealizedLossVendLedgerDimension name="UnrealizedLossVendLedgerDimension">UnrealizedLossVendLedgerDimension</a>

First included in: GeneralLedger/LedgerCurrencyParametersV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the UnrealizedLossVendLedgerDimension attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#UnrealizedProfitCustLedgerDimension name="UnrealizedProfitCustLedgerDimension">UnrealizedProfitCustLedgerDimension</a>

First included in: GeneralLedger/LedgerCurrencyParametersV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the UnrealizedProfitCustLedgerDimension attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#UnrealizedProfitEmplLedgerDimension name="UnrealizedProfitEmplLedgerDimension">UnrealizedProfitEmplLedgerDimension</a>

First included in: GeneralLedger/LedgerCurrencyParametersV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the UnrealizedProfitEmplLedgerDimension attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#UnrealizedProfitVendLedgerDimension name="UnrealizedProfitVendLedgerDimension">UnrealizedProfitVendLedgerDimension</a>

First included in: GeneralLedger/LedgerCurrencyParametersV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the UnrealizedProfitVendLedgerDimension attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#VendPostingMode name="VendPostingMode">VendPostingMode</a>

First included in: GeneralLedger/LedgerCurrencyParametersV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VendPostingMode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#VendPostingModeTax name="VendPostingModeTax">VendPostingModeTax</a>

First included in: GeneralLedger/LedgerCurrencyParametersV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VendPostingModeTax attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Ledger_Name name="Ledger_Name">Ledger_Name</a>

First included in: GeneralLedger/LedgerCurrencyParametersV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Ledger_Name attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ConvertLossExpenseCode name="ConvertLossExpenseCode">ConvertLossExpenseCode</a>

First included in: GeneralLedger/LedgerCurrencyParametersV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Purchases/Vendors tax dimension expense code for currency conversion</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ConvertLossExpenseCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Purchases/Vendors tax dimension expense code for currency conversion</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ConvertProfitIncomeCode name="ConvertProfitIncomeCode">ConvertProfitIncomeCode</a>

First included in: GeneralLedger/LedgerCurrencyParametersV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Purchases/Vendors tax dimension income code for currency conversion</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ConvertProfitIncomeCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Purchases/Vendors tax dimension income code for currency conversion</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LossGeneralExpenseCode name="LossGeneralExpenseCode">LossGeneralExpenseCode</a>

First included in: GeneralLedger/LedgerCurrencyParametersV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Expense code</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LossGeneralExpenseCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Expense code</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LossCustExpenseCode name="LossCustExpenseCode">LossCustExpenseCode</a>

First included in: GeneralLedger/LedgerCurrencyParametersV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Sales/customers tax dimension expense code</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LossCustExpenseCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Sales/customers tax dimension expense code</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LossCustPrepaymentExpenseCode name="LossCustPrepaymentExpenseCode">LossCustPrepaymentExpenseCode</a>

First included in: GeneralLedger/LedgerCurrencyParametersV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Sales/customers tax dimension expense code for prepayments</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LossCustPrepaymentExpenseCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Sales/customers tax dimension expense code for prepayments</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LossEmplExpenseCode name="LossEmplExpenseCode">LossEmplExpenseCode</a>

First included in: GeneralLedger/LedgerCurrencyParametersV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Purchases/Advance holders tax dimension expense code</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LossEmplExpenseCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Purchases/Advance holders tax dimension expense code</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LossVendExpenseCode name="LossVendExpenseCode">LossVendExpenseCode</a>

First included in: GeneralLedger/LedgerCurrencyParametersV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Purchases/Vendors tax dimension expense code</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LossVendExpenseCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Purchases/Vendors tax dimension expense code</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LossVendPrepaymentExpenseCode name="LossVendPrepaymentExpenseCode">LossVendPrepaymentExpenseCode</a>

First included in: GeneralLedger/LedgerCurrencyParametersV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Purchases/Vendors tax dimension expense code for prepayments</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LossVendPrepaymentExpenseCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Purchases/Vendors tax dimension expense code for prepayments</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProfitGeneralIncomeCode name="ProfitGeneralIncomeCode">ProfitGeneralIncomeCode</a>

First included in: GeneralLedger/LedgerCurrencyParametersV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Income code</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProfitGeneralIncomeCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Income code</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProfitCustIncomeCode name="ProfitCustIncomeCode">ProfitCustIncomeCode</a>

First included in: GeneralLedger/LedgerCurrencyParametersV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Sales/customers tax dimension income code</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProfitCustIncomeCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Sales/customers tax dimension income code</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProfitCustPrepaymentIncomeCode name="ProfitCustPrepaymentIncomeCode">ProfitCustPrepaymentIncomeCode</a>

First included in: GeneralLedger/LedgerCurrencyParametersV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Sales/customers tax dimension income code for prepayments</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProfitCustPrepaymentIncomeCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Sales/customers tax dimension income code for prepayments</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProfitEmplIncomeCode name="ProfitEmplIncomeCode">ProfitEmplIncomeCode</a>

First included in: GeneralLedger/LedgerCurrencyParametersV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Purchases/Advance holders  tax dimension income code</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProfitEmplIncomeCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Purchases/Advance holders  tax dimension income code</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProfitVendIncomeCode name="ProfitVendIncomeCode">ProfitVendIncomeCode</a>

First included in: GeneralLedger/LedgerCurrencyParametersV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Purchases/Vendors  tax dimension income code</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProfitVendIncomeCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Purchases/Vendors  tax dimension income code</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProfitVendPrepaymentIncomeCode name="ProfitVendPrepaymentIncomeCode">ProfitVendPrepaymentIncomeCode</a>

First included in: GeneralLedger/LedgerCurrencyParametersV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Purchases/Vendors tax dimension income code for prepayments</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProfitVendPrepaymentIncomeCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Purchases/Vendors tax dimension income code for prepayments</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CurConvertLossLedgerDimensionDisplayValue name="CurConvertLossLedgerDimensionDisplayValue">CurConvertLossLedgerDimensionDisplayValue</a>

First included in: GeneralLedger/LedgerCurrencyParametersV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Conversion loss</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CurConvertLossLedgerDimensionDisplayValue attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Conversion loss</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CurConvertProfitLedgerDimensionDisplayValue name="CurConvertProfitLedgerDimensionDisplayValue">CurConvertProfitLedgerDimensionDisplayValue</a>

First included in: GeneralLedger/LedgerCurrencyParametersV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Conversion gain</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CurConvertProfitLedgerDimensionDisplayValue attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Conversion gain</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RealizedLossCustLedgerDimensionDisplayValue name="RealizedLossCustLedgerDimensionDisplayValue">RealizedLossCustLedgerDimensionDisplayValue</a>

First included in: GeneralLedger/LedgerCurrencyParametersV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Sales/customers Realized loss Main account</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RealizedLossCustLedgerDimensionDisplayValue attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Sales/customers Realized loss Main account</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RealizedLossEmplLedgerDimensionDisplayValue name="RealizedLossEmplLedgerDimensionDisplayValue">RealizedLossEmplLedgerDimensionDisplayValue</a>

First included in: GeneralLedger/LedgerCurrencyParametersV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Purchases/Advance holders Realized loss Main account</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RealizedLossEmplLedgerDimensionDisplayValue attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Purchases/Advance holders Realized loss Main account</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RealizedLossVendLedgerDimensionDisplayValue name="RealizedLossVendLedgerDimensionDisplayValue">RealizedLossVendLedgerDimensionDisplayValue</a>

First included in: GeneralLedger/LedgerCurrencyParametersV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Purchases/Vendors Realized loss Main account</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RealizedLossVendLedgerDimensionDisplayValue attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Purchases/Vendors Realized loss Main account</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RealizedProfitCustLedgerDimensionDisplayValue name="RealizedProfitCustLedgerDimensionDisplayValue">RealizedProfitCustLedgerDimensionDisplayValue</a>

First included in: GeneralLedger/LedgerCurrencyParametersV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Sales/customers Realized gain Main account</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RealizedProfitCustLedgerDimensionDisplayValue attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Sales/customers Realized gain Main account</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RealizedProfitEmplLedgerDimensionDisplayValue name="RealizedProfitEmplLedgerDimensionDisplayValue">RealizedProfitEmplLedgerDimensionDisplayValue</a>

First included in: GeneralLedger/LedgerCurrencyParametersV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Purchases/Advance holders Realized gain Main account</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RealizedProfitEmplLedgerDimensionDisplayValue attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Purchases/Advance holders Realized gain Main account</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RealizedProfitVendLedgerDimensionDisplayValue name="RealizedProfitVendLedgerDimensionDisplayValue">RealizedProfitVendLedgerDimensionDisplayValue</a>

First included in: GeneralLedger/LedgerCurrencyParametersV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Purchases/Vendors Realized gain Main account</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RealizedProfitVendLedgerDimensionDisplayValue attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Purchases/Vendors Realized gain Main account</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TaxAmountDiffLedgerDimensionDisplayValue name="TaxAmountDiffLedgerDimensionDisplayValue">TaxAmountDiffLedgerDimensionDisplayValue</a>

First included in: GeneralLedger/LedgerCurrencyParametersV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Offset ledger account</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxAmountDiffLedgerDimensionDisplayValue attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Offset ledger account</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TaxAmountDiffLossLedgerDimensionDisplayValue name="TaxAmountDiffLossLedgerDimensionDisplayValue">TaxAmountDiffLossLedgerDimensionDisplayValue</a>

First included in: GeneralLedger/LedgerCurrencyParametersV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Amount difference - loss</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxAmountDiffLossLedgerDimensionDisplayValue attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Amount difference - loss</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TaxAmountDiffProfitLedgerDimensionDisplayValue name="TaxAmountDiffProfitLedgerDimensionDisplayValue">TaxAmountDiffProfitLedgerDimensionDisplayValue</a>

First included in: GeneralLedger/LedgerCurrencyParametersV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Amount difference - gain</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxAmountDiffProfitLedgerDimensionDisplayValue attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Amount difference - gain</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#UnrealizedLossCustLedgerDimensionDisplayValue name="UnrealizedLossCustLedgerDimensionDisplayValue">UnrealizedLossCustLedgerDimensionDisplayValue</a>

First included in: GeneralLedger/LedgerCurrencyParametersV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Sales/customers Unrealized loss Main account</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the UnrealizedLossCustLedgerDimensionDisplayValue attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Sales/customers Unrealized loss Main account</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#UnrealizedLossEmplLedgerDimensionDisplayValue name="UnrealizedLossEmplLedgerDimensionDisplayValue">UnrealizedLossEmplLedgerDimensionDisplayValue</a>

First included in: GeneralLedger/LedgerCurrencyParametersV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Purchases/Advance holders Unrealized loss Main account</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the UnrealizedLossEmplLedgerDimensionDisplayValue attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Purchases/Advance holders Unrealized loss Main account</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#UnrealizedLossVendLedgerDimensionDisplayValue name="UnrealizedLossVendLedgerDimensionDisplayValue">UnrealizedLossVendLedgerDimensionDisplayValue</a>

First included in: GeneralLedger/LedgerCurrencyParametersV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Purchases/Vendors Unrealized loss Main account</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the UnrealizedLossVendLedgerDimensionDisplayValue attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Purchases/Vendors Unrealized loss Main account</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#UnrealizedProfitCustLedgerDimensionDisplayValue name="UnrealizedProfitCustLedgerDimensionDisplayValue">UnrealizedProfitCustLedgerDimensionDisplayValue</a>

First included in: GeneralLedger/LedgerCurrencyParametersV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Purchases/Vendors Unrealized gain Main account</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the UnrealizedProfitCustLedgerDimensionDisplayValue attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Purchases/Vendors Unrealized gain Main account</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#UnrealizedProfitEmplLedgerDimensionDisplayValue name="UnrealizedProfitEmplLedgerDimensionDisplayValue">UnrealizedProfitEmplLedgerDimensionDisplayValue</a>

First included in: GeneralLedger/LedgerCurrencyParametersV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Purchases/Advance holders Unrealized gain Main account</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the UnrealizedProfitEmplLedgerDimensionDisplayValue attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Purchases/Advance holders Unrealized gain Main account</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#UnrealizedProfitVendLedgerDimensionDisplayValue name="UnrealizedProfitVendLedgerDimensionDisplayValue">UnrealizedProfitVendLedgerDimensionDisplayValue</a>

First included in: GeneralLedger/LedgerCurrencyParametersV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Purchases/Vendors Unrealized gain Main account</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the UnrealizedProfitVendLedgerDimensionDisplayValue attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Purchases/Vendors Unrealized gain Main account</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_CurConvertLossLedgerDimensionCombinationRelationshipId name="Relationship_CurConvertLossLedgerDimensionCombinationRelationshipId">Relationship_CurConvertLossLedgerDimensionCombinationRelationshipId</a>

First included in: GeneralLedger/LedgerCurrencyParametersV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_CurConvertLossLedgerDimensionCombinationRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_CurConvertProfitLedgerDimensionCombinationRelationshipId name="Relationship_CurConvertProfitLedgerDimensionCombinationRelationshipId">Relationship_CurConvertProfitLedgerDimensionCombinationRelationshipId</a>

First included in: GeneralLedger/LedgerCurrencyParametersV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_CurConvertProfitLedgerDimensionCombinationRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_RealizedLossCustLedgerDimensionCombinationRelationshipId name="Relationship_RealizedLossCustLedgerDimensionCombinationRelationshipId">Relationship_RealizedLossCustLedgerDimensionCombinationRelationshipId</a>

First included in: GeneralLedger/LedgerCurrencyParametersV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_RealizedLossCustLedgerDimensionCombinationRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_RealizedLossEmplLedgerDimensionCombinationRelationshipId name="Relationship_RealizedLossEmplLedgerDimensionCombinationRelationshipId">Relationship_RealizedLossEmplLedgerDimensionCombinationRelationshipId</a>

First included in: GeneralLedger/LedgerCurrencyParametersV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_RealizedLossEmplLedgerDimensionCombinationRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_RealizedLossVendLedgerDimensionCombinationRelationshipId name="Relationship_RealizedLossVendLedgerDimensionCombinationRelationshipId">Relationship_RealizedLossVendLedgerDimensionCombinationRelationshipId</a>

First included in: GeneralLedger/LedgerCurrencyParametersV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_RealizedLossVendLedgerDimensionCombinationRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_RealizedProfitCustLedgerDimensionCombinationRelationshipId name="Relationship_RealizedProfitCustLedgerDimensionCombinationRelationshipId">Relationship_RealizedProfitCustLedgerDimensionCombinationRelationshipId</a>

First included in: GeneralLedger/LedgerCurrencyParametersV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_RealizedProfitCustLedgerDimensionCombinationRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_RealizedProfitEmplLedgerDimensionCombinationRelationshipId name="Relationship_RealizedProfitEmplLedgerDimensionCombinationRelationshipId">Relationship_RealizedProfitEmplLedgerDimensionCombinationRelationshipId</a>

First included in: GeneralLedger/LedgerCurrencyParametersV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_RealizedProfitEmplLedgerDimensionCombinationRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_RealizedProfitVendLedgerDimensionCombinationRelationshipId name="Relationship_RealizedProfitVendLedgerDimensionCombinationRelationshipId">Relationship_RealizedProfitVendLedgerDimensionCombinationRelationshipId</a>

First included in: GeneralLedger/LedgerCurrencyParametersV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_RealizedProfitVendLedgerDimensionCombinationRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_TaxAmountDiffLedgerDimensionCombinationRelationshipId name="Relationship_TaxAmountDiffLedgerDimensionCombinationRelationshipId">Relationship_TaxAmountDiffLedgerDimensionCombinationRelationshipId</a>

First included in: GeneralLedger/LedgerCurrencyParametersV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_TaxAmountDiffLedgerDimensionCombinationRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_TaxAmountDiffLossLedgerDimensionCombinationRelationshipId name="Relationship_TaxAmountDiffLossLedgerDimensionCombinationRelationshipId">Relationship_TaxAmountDiffLossLedgerDimensionCombinationRelationshipId</a>

First included in: GeneralLedger/LedgerCurrencyParametersV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_TaxAmountDiffLossLedgerDimensionCombinationRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_TaxAmountDiffProfitLedgerDimensionCombinationRelationshipId name="Relationship_TaxAmountDiffProfitLedgerDimensionCombinationRelationshipId">Relationship_TaxAmountDiffProfitLedgerDimensionCombinationRelationshipId</a>

First included in: GeneralLedger/LedgerCurrencyParametersV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_TaxAmountDiffProfitLedgerDimensionCombinationRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_UnrealizedLossCustLedgerDimensionCombinationRelationshipId name="Relationship_UnrealizedLossCustLedgerDimensionCombinationRelationshipId">Relationship_UnrealizedLossCustLedgerDimensionCombinationRelationshipId</a>

First included in: GeneralLedger/LedgerCurrencyParametersV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_UnrealizedLossCustLedgerDimensionCombinationRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_UnrealizedLossEmplLedgerDimensionCombinationRelationshipId name="Relationship_UnrealizedLossEmplLedgerDimensionCombinationRelationshipId">Relationship_UnrealizedLossEmplLedgerDimensionCombinationRelationshipId</a>

First included in: GeneralLedger/LedgerCurrencyParametersV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_UnrealizedLossEmplLedgerDimensionCombinationRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_UnrealizedLossVendLedgerDimensionCombinationRelationshipId name="Relationship_UnrealizedLossVendLedgerDimensionCombinationRelationshipId">Relationship_UnrealizedLossVendLedgerDimensionCombinationRelationshipId</a>

First included in: GeneralLedger/LedgerCurrencyParametersV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_UnrealizedLossVendLedgerDimensionCombinationRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_UnrealizedProfitCustLedgerDimensionCombinationRelationshipId name="Relationship_UnrealizedProfitCustLedgerDimensionCombinationRelationshipId">Relationship_UnrealizedProfitCustLedgerDimensionCombinationRelationshipId</a>

First included in: GeneralLedger/LedgerCurrencyParametersV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_UnrealizedProfitCustLedgerDimensionCombinationRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_UnrealizedProfitEmplLedgerDimensionCombinationRelationshipId name="Relationship_UnrealizedProfitEmplLedgerDimensionCombinationRelationshipId">Relationship_UnrealizedProfitEmplLedgerDimensionCombinationRelationshipId</a>

First included in: GeneralLedger/LedgerCurrencyParametersV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_UnrealizedProfitEmplLedgerDimensionCombinationRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_UnrealizedProfitVendLedgerDimensionCombinationRelationshipId name="Relationship_UnrealizedProfitVendLedgerDimensionCombinationRelationshipId">Relationship_UnrealizedProfitVendLedgerDimensionCombinationRelationshipId</a>

First included in: GeneralLedger/LedgerCurrencyParametersV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_UnrealizedProfitVendLedgerDimensionCombinationRelationshipId attribute are listed below.</summary>

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

### <a href=#BackingTable_LedgerCurrencyParameters_RURelationshipId name="BackingTable_LedgerCurrencyParameters_RURelationshipId">BackingTable_LedgerCurrencyParameters_RURelationshipId</a>

First included in: GeneralLedger/LedgerCurrencyParametersV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_LedgerCurrencyParameters_RURelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/Finance/Ledger/Group/LedgerCurrencyParameters_RU.md" target="_blank">/core/operationsCommon/Tables/Finance/Ledger/Group/LedgerCurrencyParameters_RU.cdm.json/LedgerCurrencyParameters_RU</a></td><td><a href="../../../Tables/Finance/Ledger/Group/LedgerCurrencyParameters_RU.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PrimaryCompanyContextRelationshipId name="Relationship_PrimaryCompanyContextRelationshipId">Relationship_PrimaryCompanyContextRelationshipId</a>

First included in: GeneralLedger/LedgerCurrencyParametersV2Entity (this entity)  

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
