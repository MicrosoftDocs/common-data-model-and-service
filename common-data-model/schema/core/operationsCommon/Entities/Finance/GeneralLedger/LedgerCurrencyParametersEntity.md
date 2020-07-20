---
title: LedgerCurrencyParametersEntity in GeneralLedger - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 7/20/2020
ms.author: nebanfic
---

# Ledger currency parameters in GeneralLedger(LedgerCurrencyParametersEntity)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/Finance/GeneralLedger/LedgerCurrencyParametersEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Ledger currency parameters</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[ConversionLoss](#ConversionLoss)||<a href="LedgerCurrencyParametersEntity.md" target="_blank">GeneralLedger/LedgerCurrencyParametersEntity</a>|
|[ConversionGain](#ConversionGain)||<a href="LedgerCurrencyParametersEntity.md" target="_blank">GeneralLedger/LedgerCurrencyParametersEntity</a>|
|[Currency](#Currency)||<a href="LedgerCurrencyParametersEntity.md" target="_blank">GeneralLedger/LedgerCurrencyParametersEntity</a>|
|[CustPrimaryPostingLedger](#CustPrimaryPostingLedger)||<a href="LedgerCurrencyParametersEntity.md" target="_blank">GeneralLedger/LedgerCurrencyParametersEntity</a>|
|[CustTaxPrimaryPostingLedger](#CustTaxPrimaryPostingLedger)||<a href="LedgerCurrencyParametersEntity.md" target="_blank">GeneralLedger/LedgerCurrencyParametersEntity</a>|
|[VendRealizedLossSalesTaxes](#VendRealizedLossSalesTaxes)||<a href="LedgerCurrencyParametersEntity.md" target="_blank">GeneralLedger/LedgerCurrencyParametersEntity</a>|
|[CustRealizedGainSalesTaxes](#CustRealizedGainSalesTaxes)||<a href="LedgerCurrencyParametersEntity.md" target="_blank">GeneralLedger/LedgerCurrencyParametersEntity</a>|
|[CustRealizedLossSalesTaxes](#CustRealizedLossSalesTaxes)||<a href="LedgerCurrencyParametersEntity.md" target="_blank">GeneralLedger/LedgerCurrencyParametersEntity</a>|
|[VendRealizedGainSalesTaxes](#VendRealizedGainSalesTaxes)||<a href="LedgerCurrencyParametersEntity.md" target="_blank">GeneralLedger/LedgerCurrencyParametersEntity</a>|
|[Reference](#Reference)||<a href="LedgerCurrencyParametersEntity.md" target="_blank">GeneralLedger/LedgerCurrencyParametersEntity</a>|
|[RealizedLoss](#RealizedLoss)||<a href="LedgerCurrencyParametersEntity.md" target="_blank">GeneralLedger/LedgerCurrencyParametersEntity</a>|
|[MainAccount](#MainAccount)||<a href="LedgerCurrencyParametersEntity.md" target="_blank">GeneralLedger/LedgerCurrencyParametersEntity</a>|
|[MainAccount1](#MainAccount1)||<a href="LedgerCurrencyParametersEntity.md" target="_blank">GeneralLedger/LedgerCurrencyParametersEntity</a>|
|[MainAccount2](#MainAccount2)||<a href="LedgerCurrencyParametersEntity.md" target="_blank">GeneralLedger/LedgerCurrencyParametersEntity</a>|
|[RealizedLoss1](#RealizedLoss1)||<a href="LedgerCurrencyParametersEntity.md" target="_blank">GeneralLedger/LedgerCurrencyParametersEntity</a>|
|[RealizedGain](#RealizedGain)||<a href="LedgerCurrencyParametersEntity.md" target="_blank">GeneralLedger/LedgerCurrencyParametersEntity</a>|
|[MainAccount3](#MainAccount3)||<a href="LedgerCurrencyParametersEntity.md" target="_blank">GeneralLedger/LedgerCurrencyParametersEntity</a>|
|[MainAccount4](#MainAccount4)||<a href="LedgerCurrencyParametersEntity.md" target="_blank">GeneralLedger/LedgerCurrencyParametersEntity</a>|
|[MainAccount5](#MainAccount5)||<a href="LedgerCurrencyParametersEntity.md" target="_blank">GeneralLedger/LedgerCurrencyParametersEntity</a>|
|[RealizedGain1](#RealizedGain1)||<a href="LedgerCurrencyParametersEntity.md" target="_blank">GeneralLedger/LedgerCurrencyParametersEntity</a>|
|[RTax25ProfitTableConvertLoss](#RTax25ProfitTableConvertLoss)||<a href="LedgerCurrencyParametersEntity.md" target="_blank">GeneralLedger/LedgerCurrencyParametersEntity</a>|
|[RTax25ProfitTableConvertProfit](#RTax25ProfitTableConvertProfit)||<a href="LedgerCurrencyParametersEntity.md" target="_blank">GeneralLedger/LedgerCurrencyParametersEntity</a>|
|[ExpenseCode](#ExpenseCode)||<a href="LedgerCurrencyParametersEntity.md" target="_blank">GeneralLedger/LedgerCurrencyParametersEntity</a>|
|[ExpenseCode1](#ExpenseCode1)||<a href="LedgerCurrencyParametersEntity.md" target="_blank">GeneralLedger/LedgerCurrencyParametersEntity</a>|
|[ExpenseCode2](#ExpenseCode2)||<a href="LedgerCurrencyParametersEntity.md" target="_blank">GeneralLedger/LedgerCurrencyParametersEntity</a>|
|[ExpenseCode3](#ExpenseCode3)||<a href="LedgerCurrencyParametersEntity.md" target="_blank">GeneralLedger/LedgerCurrencyParametersEntity</a>|
|[ExpenseCode4](#ExpenseCode4)||<a href="LedgerCurrencyParametersEntity.md" target="_blank">GeneralLedger/LedgerCurrencyParametersEntity</a>|
|[ExpenseCode5](#ExpenseCode5)||<a href="LedgerCurrencyParametersEntity.md" target="_blank">GeneralLedger/LedgerCurrencyParametersEntity</a>|
|[RevenueCode](#RevenueCode)||<a href="LedgerCurrencyParametersEntity.md" target="_blank">GeneralLedger/LedgerCurrencyParametersEntity</a>|
|[RevenueCode1](#RevenueCode1)||<a href="LedgerCurrencyParametersEntity.md" target="_blank">GeneralLedger/LedgerCurrencyParametersEntity</a>|
|[RevenueCode2](#RevenueCode2)||<a href="LedgerCurrencyParametersEntity.md" target="_blank">GeneralLedger/LedgerCurrencyParametersEntity</a>|
|[RevenueCode3](#RevenueCode3)||<a href="LedgerCurrencyParametersEntity.md" target="_blank">GeneralLedger/LedgerCurrencyParametersEntity</a>|
|[RevenueCode4](#RevenueCode4)||<a href="LedgerCurrencyParametersEntity.md" target="_blank">GeneralLedger/LedgerCurrencyParametersEntity</a>|
|[RevenueCode5](#RevenueCode5)||<a href="LedgerCurrencyParametersEntity.md" target="_blank">GeneralLedger/LedgerCurrencyParametersEntity</a>|
|[AmountDifferenceInTaxAccounting](#AmountDifferenceInTaxAccounting)||<a href="LedgerCurrencyParametersEntity.md" target="_blank">GeneralLedger/LedgerCurrencyParametersEntity</a>|
|[TakeVATIntoAccountForExpenses](#TakeVATIntoAccountForExpenses)||<a href="LedgerCurrencyParametersEntity.md" target="_blank">GeneralLedger/LedgerCurrencyParametersEntity</a>|
|[OffsetLedgerAccount](#OffsetLedgerAccount)||<a href="LedgerCurrencyParametersEntity.md" target="_blank">GeneralLedger/LedgerCurrencyParametersEntity</a>|
|[TaxAmountDiffLossLedgerDimension](#TaxAmountDiffLossLedgerDimension)||<a href="LedgerCurrencyParametersEntity.md" target="_blank">GeneralLedger/LedgerCurrencyParametersEntity</a>|
|[TaxAmountDiffProfitLedgerDimension](#TaxAmountDiffProfitLedgerDimension)||<a href="LedgerCurrencyParametersEntity.md" target="_blank">GeneralLedger/LedgerCurrencyParametersEntity</a>|
|[UnrealizedLoss](#UnrealizedLoss)||<a href="LedgerCurrencyParametersEntity.md" target="_blank">GeneralLedger/LedgerCurrencyParametersEntity</a>|
|[MainAccount6](#MainAccount6)||<a href="LedgerCurrencyParametersEntity.md" target="_blank">GeneralLedger/LedgerCurrencyParametersEntity</a>|
|[MainAccount7](#MainAccount7)||<a href="LedgerCurrencyParametersEntity.md" target="_blank">GeneralLedger/LedgerCurrencyParametersEntity</a>|
|[UnrealizedLoss1](#UnrealizedLoss1)||<a href="LedgerCurrencyParametersEntity.md" target="_blank">GeneralLedger/LedgerCurrencyParametersEntity</a>|
|[UnrealizedGain](#UnrealizedGain)||<a href="LedgerCurrencyParametersEntity.md" target="_blank">GeneralLedger/LedgerCurrencyParametersEntity</a>|
|[MainAccount8](#MainAccount8)||<a href="LedgerCurrencyParametersEntity.md" target="_blank">GeneralLedger/LedgerCurrencyParametersEntity</a>|
|[MainAccount9](#MainAccount9)||<a href="LedgerCurrencyParametersEntity.md" target="_blank">GeneralLedger/LedgerCurrencyParametersEntity</a>|
|[UnrealizedGain1](#UnrealizedGain1)||<a href="LedgerCurrencyParametersEntity.md" target="_blank">GeneralLedger/LedgerCurrencyParametersEntity</a>|
|[VendPrimaryPostingLedger](#VendPrimaryPostingLedger)||<a href="LedgerCurrencyParametersEntity.md" target="_blank">GeneralLedger/LedgerCurrencyParametersEntity</a>|
|[VendTaxPrimaryPostingLedger](#VendTaxPrimaryPostingLedger)||<a href="LedgerCurrencyParametersEntity.md" target="_blank">GeneralLedger/LedgerCurrencyParametersEntity</a>|
|[Ledger_Name](#Ledger_Name)||<a href="LedgerCurrencyParametersEntity.md" target="_blank">GeneralLedger/LedgerCurrencyParametersEntity</a>|
|[VendTaxDimensionConversionExpenseCode](#VendTaxDimensionConversionExpenseCode)||<a href="LedgerCurrencyParametersEntity.md" target="_blank">GeneralLedger/LedgerCurrencyParametersEntity</a>|
|[VendTaxDimensionConversionRevenueCode](#VendTaxDimensionConversionRevenueCode)||<a href="LedgerCurrencyParametersEntity.md" target="_blank">GeneralLedger/LedgerCurrencyParametersEntity</a>|
|[GeneralTaxDimensionExpenseCode](#GeneralTaxDimensionExpenseCode)||<a href="LedgerCurrencyParametersEntity.md" target="_blank">GeneralLedger/LedgerCurrencyParametersEntity</a>|
|[CustTaxDimensionExpenseCode](#CustTaxDimensionExpenseCode)||<a href="LedgerCurrencyParametersEntity.md" target="_blank">GeneralLedger/LedgerCurrencyParametersEntity</a>|
|[CustTaxDimensionPrepaymentsExpenseCode](#CustTaxDimensionPrepaymentsExpenseCode)||<a href="LedgerCurrencyParametersEntity.md" target="_blank">GeneralLedger/LedgerCurrencyParametersEntity</a>|
|[EmplTaxDimensionExpenseCode](#EmplTaxDimensionExpenseCode)||<a href="LedgerCurrencyParametersEntity.md" target="_blank">GeneralLedger/LedgerCurrencyParametersEntity</a>|
|[VendTaxDImensionExpenseCode](#VendTaxDImensionExpenseCode)||<a href="LedgerCurrencyParametersEntity.md" target="_blank">GeneralLedger/LedgerCurrencyParametersEntity</a>|
|[VendTaxDimensionPrepaymentsExpenseCode](#VendTaxDimensionPrepaymentsExpenseCode)||<a href="LedgerCurrencyParametersEntity.md" target="_blank">GeneralLedger/LedgerCurrencyParametersEntity</a>|
|[GeneralTaxDimensionRevenueCode](#GeneralTaxDimensionRevenueCode)||<a href="LedgerCurrencyParametersEntity.md" target="_blank">GeneralLedger/LedgerCurrencyParametersEntity</a>|
|[CustTaxDimensionRevenueCode](#CustTaxDimensionRevenueCode)||<a href="LedgerCurrencyParametersEntity.md" target="_blank">GeneralLedger/LedgerCurrencyParametersEntity</a>|
|[CustTaxDimensionPrepaymentsRevenueCode](#CustTaxDimensionPrepaymentsRevenueCode)||<a href="LedgerCurrencyParametersEntity.md" target="_blank">GeneralLedger/LedgerCurrencyParametersEntity</a>|
|[EmplTaxDimensionRevenueCode](#EmplTaxDimensionRevenueCode)||<a href="LedgerCurrencyParametersEntity.md" target="_blank">GeneralLedger/LedgerCurrencyParametersEntity</a>|
|[VendTaxDimensionRevenueCode](#VendTaxDimensionRevenueCode)||<a href="LedgerCurrencyParametersEntity.md" target="_blank">GeneralLedger/LedgerCurrencyParametersEntity</a>|
|[VendTaxDimensionPrepaymentsRevenueCode](#VendTaxDimensionPrepaymentsRevenueCode)||<a href="LedgerCurrencyParametersEntity.md" target="_blank">GeneralLedger/LedgerCurrencyParametersEntity</a>|
|[VendConversionLoss](#VendConversionLoss)||<a href="LedgerCurrencyParametersEntity.md" target="_blank">GeneralLedger/LedgerCurrencyParametersEntity</a>|
|[VendConversionGain](#VendConversionGain)||<a href="LedgerCurrencyParametersEntity.md" target="_blank">GeneralLedger/LedgerCurrencyParametersEntity</a>|
|[CustRealizedLossMainAccount](#CustRealizedLossMainAccount)||<a href="LedgerCurrencyParametersEntity.md" target="_blank">GeneralLedger/LedgerCurrencyParametersEntity</a>|
|[EmplRealizedLossMainAccount](#EmplRealizedLossMainAccount)||<a href="LedgerCurrencyParametersEntity.md" target="_blank">GeneralLedger/LedgerCurrencyParametersEntity</a>|
|[CustRealizedLossTaxPostingAccount](#CustRealizedLossTaxPostingAccount)||<a href="LedgerCurrencyParametersEntity.md" target="_blank">GeneralLedger/LedgerCurrencyParametersEntity</a>|
|[VendRelizedLossTaxPostingAccount](#VendRelizedLossTaxPostingAccount)||<a href="LedgerCurrencyParametersEntity.md" target="_blank">GeneralLedger/LedgerCurrencyParametersEntity</a>|
|[VendRealizedLossMainAccount](#VendRealizedLossMainAccount)||<a href="LedgerCurrencyParametersEntity.md" target="_blank">GeneralLedger/LedgerCurrencyParametersEntity</a>|
|[CustRealizedGainMainAccount](#CustRealizedGainMainAccount)||<a href="LedgerCurrencyParametersEntity.md" target="_blank">GeneralLedger/LedgerCurrencyParametersEntity</a>|
|[EmplRealizedGain](#EmplRealizedGain)||<a href="LedgerCurrencyParametersEntity.md" target="_blank">GeneralLedger/LedgerCurrencyParametersEntity</a>|
|[CustRealizedGainTaxPostingAccount](#CustRealizedGainTaxPostingAccount)||<a href="LedgerCurrencyParametersEntity.md" target="_blank">GeneralLedger/LedgerCurrencyParametersEntity</a>|
|[VendRelizedGainTaxPostingAccount](#VendRelizedGainTaxPostingAccount)||<a href="LedgerCurrencyParametersEntity.md" target="_blank">GeneralLedger/LedgerCurrencyParametersEntity</a>|
|[VendRealizedGainMainAccount](#VendRealizedGainMainAccount)||<a href="LedgerCurrencyParametersEntity.md" target="_blank">GeneralLedger/LedgerCurrencyParametersEntity</a>|
|[CustUnrealizedLossMainAccount](#CustUnrealizedLossMainAccount)||<a href="LedgerCurrencyParametersEntity.md" target="_blank">GeneralLedger/LedgerCurrencyParametersEntity</a>|
|[EmplUnrealizedLossMainAccount](#EmplUnrealizedLossMainAccount)||<a href="LedgerCurrencyParametersEntity.md" target="_blank">GeneralLedger/LedgerCurrencyParametersEntity</a>|
|[VendUnrealizedLossMainAccount](#VendUnrealizedLossMainAccount)||<a href="LedgerCurrencyParametersEntity.md" target="_blank">GeneralLedger/LedgerCurrencyParametersEntity</a>|
|[CustUnrealizedGainMainAccount](#CustUnrealizedGainMainAccount)||<a href="LedgerCurrencyParametersEntity.md" target="_blank">GeneralLedger/LedgerCurrencyParametersEntity</a>|
|[EmplUnrealizedGainMainAccount](#EmplUnrealizedGainMainAccount)||<a href="LedgerCurrencyParametersEntity.md" target="_blank">GeneralLedger/LedgerCurrencyParametersEntity</a>|
|[VendUnrealizedGainMainAccount](#VendUnrealizedGainMainAccount)||<a href="LedgerCurrencyParametersEntity.md" target="_blank">GeneralLedger/LedgerCurrencyParametersEntity</a>|
|[Relationship_ConversionLossCombinationRelationshipId](#Relationship_ConversionLossCombinationRelationshipId)||<a href="LedgerCurrencyParametersEntity.md" target="_blank">GeneralLedger/LedgerCurrencyParametersEntity</a>|
|[Relationship_ConversionGainCombinationRelationshipId](#Relationship_ConversionGainCombinationRelationshipId)||<a href="LedgerCurrencyParametersEntity.md" target="_blank">GeneralLedger/LedgerCurrencyParametersEntity</a>|
|[Relationship_RealizedLossCombinationRelationshipId](#Relationship_RealizedLossCombinationRelationshipId)||<a href="LedgerCurrencyParametersEntity.md" target="_blank">GeneralLedger/LedgerCurrencyParametersEntity</a>|
|[Relationship_MainAccountCombinationRelationshipId](#Relationship_MainAccountCombinationRelationshipId)||<a href="LedgerCurrencyParametersEntity.md" target="_blank">GeneralLedger/LedgerCurrencyParametersEntity</a>|
|[Relationship_MainAccount1CombinationRelationshipId](#Relationship_MainAccount1CombinationRelationshipId)||<a href="LedgerCurrencyParametersEntity.md" target="_blank">GeneralLedger/LedgerCurrencyParametersEntity</a>|
|[Relationship_MainAccount2CombinationRelationshipId](#Relationship_MainAccount2CombinationRelationshipId)||<a href="LedgerCurrencyParametersEntity.md" target="_blank">GeneralLedger/LedgerCurrencyParametersEntity</a>|
|[Relationship_RealizedLoss1CombinationRelationshipId](#Relationship_RealizedLoss1CombinationRelationshipId)||<a href="LedgerCurrencyParametersEntity.md" target="_blank">GeneralLedger/LedgerCurrencyParametersEntity</a>|
|[Relationship_RealizedGainCombinationRelationshipId](#Relationship_RealizedGainCombinationRelationshipId)||<a href="LedgerCurrencyParametersEntity.md" target="_blank">GeneralLedger/LedgerCurrencyParametersEntity</a>|
|[Relationship_MainAccount3CombinationRelationshipId](#Relationship_MainAccount3CombinationRelationshipId)||<a href="LedgerCurrencyParametersEntity.md" target="_blank">GeneralLedger/LedgerCurrencyParametersEntity</a>|
|[Relationship_MainAccount4CombinationRelationshipId](#Relationship_MainAccount4CombinationRelationshipId)||<a href="LedgerCurrencyParametersEntity.md" target="_blank">GeneralLedger/LedgerCurrencyParametersEntity</a>|
|[Relationship_MainAccount5CombinationRelationshipId](#Relationship_MainAccount5CombinationRelationshipId)||<a href="LedgerCurrencyParametersEntity.md" target="_blank">GeneralLedger/LedgerCurrencyParametersEntity</a>|
|[Relationship_RealizedGain1CombinationRelationshipId](#Relationship_RealizedGain1CombinationRelationshipId)||<a href="LedgerCurrencyParametersEntity.md" target="_blank">GeneralLedger/LedgerCurrencyParametersEntity</a>|
|[Relationship_OffsetLedgerAccountCombinationRelationshipId](#Relationship_OffsetLedgerAccountCombinationRelationshipId)||<a href="LedgerCurrencyParametersEntity.md" target="_blank">GeneralLedger/LedgerCurrencyParametersEntity</a>|
|[Relationship_TaxAmountDiffLossLedgerDimensionCombinationRelationshipId](#Relationship_TaxAmountDiffLossLedgerDimensionCombinationRelationshipId)||<a href="LedgerCurrencyParametersEntity.md" target="_blank">GeneralLedger/LedgerCurrencyParametersEntity</a>|
|[Relationship_TaxAmountDiffProfitLedgerDimensionCombinationRelationshipId](#Relationship_TaxAmountDiffProfitLedgerDimensionCombinationRelationshipId)||<a href="LedgerCurrencyParametersEntity.md" target="_blank">GeneralLedger/LedgerCurrencyParametersEntity</a>|
|[Relationship_UnrealizedLossCombinationRelationshipId](#Relationship_UnrealizedLossCombinationRelationshipId)||<a href="LedgerCurrencyParametersEntity.md" target="_blank">GeneralLedger/LedgerCurrencyParametersEntity</a>|
|[Relationship_MainAccount6CombinationRelationshipId](#Relationship_MainAccount6CombinationRelationshipId)||<a href="LedgerCurrencyParametersEntity.md" target="_blank">GeneralLedger/LedgerCurrencyParametersEntity</a>|
|[Relationship_MainAccount7CombinationRelationshipId](#Relationship_MainAccount7CombinationRelationshipId)||<a href="LedgerCurrencyParametersEntity.md" target="_blank">GeneralLedger/LedgerCurrencyParametersEntity</a>|
|[Relationship_UnrealizedLoss1CombinationRelationshipId](#Relationship_UnrealizedLoss1CombinationRelationshipId)||<a href="LedgerCurrencyParametersEntity.md" target="_blank">GeneralLedger/LedgerCurrencyParametersEntity</a>|
|[Relationship_UnrealizedGainCombinationRelationshipId](#Relationship_UnrealizedGainCombinationRelationshipId)||<a href="LedgerCurrencyParametersEntity.md" target="_blank">GeneralLedger/LedgerCurrencyParametersEntity</a>|
|[Relationship_MainAccount8CombinationRelationshipId](#Relationship_MainAccount8CombinationRelationshipId)||<a href="LedgerCurrencyParametersEntity.md" target="_blank">GeneralLedger/LedgerCurrencyParametersEntity</a>|
|[Relationship_MainAccount9CombinationRelationshipId](#Relationship_MainAccount9CombinationRelationshipId)||<a href="LedgerCurrencyParametersEntity.md" target="_blank">GeneralLedger/LedgerCurrencyParametersEntity</a>|
|[Relationship_UnrealizedGain1CombinationRelationshipId](#Relationship_UnrealizedGain1CombinationRelationshipId)||<a href="LedgerCurrencyParametersEntity.md" target="_blank">GeneralLedger/LedgerCurrencyParametersEntity</a>|
|[BackingTable_LedgerCurrencyParameters_RURelationshipId](#BackingTable_LedgerCurrencyParameters_RURelationshipId)||<a href="LedgerCurrencyParametersEntity.md" target="_blank">GeneralLedger/LedgerCurrencyParametersEntity</a>|
|[Relationship_PrimaryCompanyContextRelationshipId](#Relationship_PrimaryCompanyContextRelationshipId)||<a href="LedgerCurrencyParametersEntity.md" target="_blank">GeneralLedger/LedgerCurrencyParametersEntity</a>|

### <a href=#ConversionLoss name="ConversionLoss">ConversionLoss</a>

First included in: GeneralLedger/LedgerCurrencyParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ConversionLoss attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ConversionGain name="ConversionGain">ConversionGain</a>

First included in: GeneralLedger/LedgerCurrencyParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ConversionGain attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Currency name="Currency">Currency</a>

First included in: GeneralLedger/LedgerCurrencyParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Currency attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CustPrimaryPostingLedger name="CustPrimaryPostingLedger">CustPrimaryPostingLedger</a>

First included in: GeneralLedger/LedgerCurrencyParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CustPrimaryPostingLedger attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CustTaxPrimaryPostingLedger name="CustTaxPrimaryPostingLedger">CustTaxPrimaryPostingLedger</a>

First included in: GeneralLedger/LedgerCurrencyParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CustTaxPrimaryPostingLedger attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#VendRealizedLossSalesTaxes name="VendRealizedLossSalesTaxes">VendRealizedLossSalesTaxes</a>

First included in: GeneralLedger/LedgerCurrencyParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VendRealizedLossSalesTaxes attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CustRealizedGainSalesTaxes name="CustRealizedGainSalesTaxes">CustRealizedGainSalesTaxes</a>

First included in: GeneralLedger/LedgerCurrencyParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CustRealizedGainSalesTaxes attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CustRealizedLossSalesTaxes name="CustRealizedLossSalesTaxes">CustRealizedLossSalesTaxes</a>

First included in: GeneralLedger/LedgerCurrencyParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CustRealizedLossSalesTaxes attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#VendRealizedGainSalesTaxes name="VendRealizedGainSalesTaxes">VendRealizedGainSalesTaxes</a>

First included in: GeneralLedger/LedgerCurrencyParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VendRealizedGainSalesTaxes attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Reference name="Reference">Reference</a>

First included in: GeneralLedger/LedgerCurrencyParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Reference attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RealizedLoss name="RealizedLoss">RealizedLoss</a>

First included in: GeneralLedger/LedgerCurrencyParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RealizedLoss attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MainAccount name="MainAccount">MainAccount</a>

First included in: GeneralLedger/LedgerCurrencyParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MainAccount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MainAccount1 name="MainAccount1">MainAccount1</a>

First included in: GeneralLedger/LedgerCurrencyParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MainAccount1 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MainAccount2 name="MainAccount2">MainAccount2</a>

First included in: GeneralLedger/LedgerCurrencyParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MainAccount2 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RealizedLoss1 name="RealizedLoss1">RealizedLoss1</a>

First included in: GeneralLedger/LedgerCurrencyParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RealizedLoss1 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RealizedGain name="RealizedGain">RealizedGain</a>

First included in: GeneralLedger/LedgerCurrencyParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RealizedGain attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MainAccount3 name="MainAccount3">MainAccount3</a>

First included in: GeneralLedger/LedgerCurrencyParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MainAccount3 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MainAccount4 name="MainAccount4">MainAccount4</a>

First included in: GeneralLedger/LedgerCurrencyParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MainAccount4 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MainAccount5 name="MainAccount5">MainAccount5</a>

First included in: GeneralLedger/LedgerCurrencyParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MainAccount5 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RealizedGain1 name="RealizedGain1">RealizedGain1</a>

First included in: GeneralLedger/LedgerCurrencyParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RealizedGain1 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RTax25ProfitTableConvertLoss name="RTax25ProfitTableConvertLoss">RTax25ProfitTableConvertLoss</a>

First included in: GeneralLedger/LedgerCurrencyParametersEntity (this entity)  

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

First included in: GeneralLedger/LedgerCurrencyParametersEntity (this entity)  

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

### <a href=#ExpenseCode name="ExpenseCode">ExpenseCode</a>

First included in: GeneralLedger/LedgerCurrencyParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ExpenseCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ExpenseCode1 name="ExpenseCode1">ExpenseCode1</a>

First included in: GeneralLedger/LedgerCurrencyParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ExpenseCode1 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ExpenseCode2 name="ExpenseCode2">ExpenseCode2</a>

First included in: GeneralLedger/LedgerCurrencyParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ExpenseCode2 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ExpenseCode3 name="ExpenseCode3">ExpenseCode3</a>

First included in: GeneralLedger/LedgerCurrencyParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ExpenseCode3 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ExpenseCode4 name="ExpenseCode4">ExpenseCode4</a>

First included in: GeneralLedger/LedgerCurrencyParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ExpenseCode4 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ExpenseCode5 name="ExpenseCode5">ExpenseCode5</a>

First included in: GeneralLedger/LedgerCurrencyParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ExpenseCode5 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RevenueCode name="RevenueCode">RevenueCode</a>

First included in: GeneralLedger/LedgerCurrencyParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RevenueCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RevenueCode1 name="RevenueCode1">RevenueCode1</a>

First included in: GeneralLedger/LedgerCurrencyParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RevenueCode1 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RevenueCode2 name="RevenueCode2">RevenueCode2</a>

First included in: GeneralLedger/LedgerCurrencyParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RevenueCode2 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RevenueCode3 name="RevenueCode3">RevenueCode3</a>

First included in: GeneralLedger/LedgerCurrencyParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RevenueCode3 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RevenueCode4 name="RevenueCode4">RevenueCode4</a>

First included in: GeneralLedger/LedgerCurrencyParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RevenueCode4 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RevenueCode5 name="RevenueCode5">RevenueCode5</a>

First included in: GeneralLedger/LedgerCurrencyParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RevenueCode5 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AmountDifferenceInTaxAccounting name="AmountDifferenceInTaxAccounting">AmountDifferenceInTaxAccounting</a>

First included in: GeneralLedger/LedgerCurrencyParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AmountDifferenceInTaxAccounting attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TakeVATIntoAccountForExpenses name="TakeVATIntoAccountForExpenses">TakeVATIntoAccountForExpenses</a>

First included in: GeneralLedger/LedgerCurrencyParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TakeVATIntoAccountForExpenses attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#OffsetLedgerAccount name="OffsetLedgerAccount">OffsetLedgerAccount</a>

First included in: GeneralLedger/LedgerCurrencyParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OffsetLedgerAccount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TaxAmountDiffLossLedgerDimension name="TaxAmountDiffLossLedgerDimension">TaxAmountDiffLossLedgerDimension</a>

First included in: GeneralLedger/LedgerCurrencyParametersEntity (this entity)  

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

First included in: GeneralLedger/LedgerCurrencyParametersEntity (this entity)  

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

### <a href=#UnrealizedLoss name="UnrealizedLoss">UnrealizedLoss</a>

First included in: GeneralLedger/LedgerCurrencyParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the UnrealizedLoss attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MainAccount6 name="MainAccount6">MainAccount6</a>

First included in: GeneralLedger/LedgerCurrencyParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MainAccount6 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MainAccount7 name="MainAccount7">MainAccount7</a>

First included in: GeneralLedger/LedgerCurrencyParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MainAccount7 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#UnrealizedLoss1 name="UnrealizedLoss1">UnrealizedLoss1</a>

First included in: GeneralLedger/LedgerCurrencyParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the UnrealizedLoss1 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#UnrealizedGain name="UnrealizedGain">UnrealizedGain</a>

First included in: GeneralLedger/LedgerCurrencyParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the UnrealizedGain attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MainAccount8 name="MainAccount8">MainAccount8</a>

First included in: GeneralLedger/LedgerCurrencyParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MainAccount8 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MainAccount9 name="MainAccount9">MainAccount9</a>

First included in: GeneralLedger/LedgerCurrencyParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MainAccount9 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#UnrealizedGain1 name="UnrealizedGain1">UnrealizedGain1</a>

First included in: GeneralLedger/LedgerCurrencyParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the UnrealizedGain1 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#VendPrimaryPostingLedger name="VendPrimaryPostingLedger">VendPrimaryPostingLedger</a>

First included in: GeneralLedger/LedgerCurrencyParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VendPrimaryPostingLedger attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#VendTaxPrimaryPostingLedger name="VendTaxPrimaryPostingLedger">VendTaxPrimaryPostingLedger</a>

First included in: GeneralLedger/LedgerCurrencyParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VendTaxPrimaryPostingLedger attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Ledger_Name name="Ledger_Name">Ledger_Name</a>

First included in: GeneralLedger/LedgerCurrencyParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Ledger_Name attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#VendTaxDimensionConversionExpenseCode name="VendTaxDimensionConversionExpenseCode">VendTaxDimensionConversionExpenseCode</a>

First included in: GeneralLedger/LedgerCurrencyParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VendTaxDimensionConversionExpenseCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#VendTaxDimensionConversionRevenueCode name="VendTaxDimensionConversionRevenueCode">VendTaxDimensionConversionRevenueCode</a>

First included in: GeneralLedger/LedgerCurrencyParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VendTaxDimensionConversionRevenueCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#GeneralTaxDimensionExpenseCode name="GeneralTaxDimensionExpenseCode">GeneralTaxDimensionExpenseCode</a>

First included in: GeneralLedger/LedgerCurrencyParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the GeneralTaxDimensionExpenseCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CustTaxDimensionExpenseCode name="CustTaxDimensionExpenseCode">CustTaxDimensionExpenseCode</a>

First included in: GeneralLedger/LedgerCurrencyParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CustTaxDimensionExpenseCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CustTaxDimensionPrepaymentsExpenseCode name="CustTaxDimensionPrepaymentsExpenseCode">CustTaxDimensionPrepaymentsExpenseCode</a>

First included in: GeneralLedger/LedgerCurrencyParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CustTaxDimensionPrepaymentsExpenseCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#EmplTaxDimensionExpenseCode name="EmplTaxDimensionExpenseCode">EmplTaxDimensionExpenseCode</a>

First included in: GeneralLedger/LedgerCurrencyParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EmplTaxDimensionExpenseCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#VendTaxDImensionExpenseCode name="VendTaxDImensionExpenseCode">VendTaxDImensionExpenseCode</a>

First included in: GeneralLedger/LedgerCurrencyParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VendTaxDImensionExpenseCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#VendTaxDimensionPrepaymentsExpenseCode name="VendTaxDimensionPrepaymentsExpenseCode">VendTaxDimensionPrepaymentsExpenseCode</a>

First included in: GeneralLedger/LedgerCurrencyParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VendTaxDimensionPrepaymentsExpenseCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#GeneralTaxDimensionRevenueCode name="GeneralTaxDimensionRevenueCode">GeneralTaxDimensionRevenueCode</a>

First included in: GeneralLedger/LedgerCurrencyParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the GeneralTaxDimensionRevenueCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CustTaxDimensionRevenueCode name="CustTaxDimensionRevenueCode">CustTaxDimensionRevenueCode</a>

First included in: GeneralLedger/LedgerCurrencyParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CustTaxDimensionRevenueCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CustTaxDimensionPrepaymentsRevenueCode name="CustTaxDimensionPrepaymentsRevenueCode">CustTaxDimensionPrepaymentsRevenueCode</a>

First included in: GeneralLedger/LedgerCurrencyParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CustTaxDimensionPrepaymentsRevenueCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#EmplTaxDimensionRevenueCode name="EmplTaxDimensionRevenueCode">EmplTaxDimensionRevenueCode</a>

First included in: GeneralLedger/LedgerCurrencyParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EmplTaxDimensionRevenueCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#VendTaxDimensionRevenueCode name="VendTaxDimensionRevenueCode">VendTaxDimensionRevenueCode</a>

First included in: GeneralLedger/LedgerCurrencyParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VendTaxDimensionRevenueCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#VendTaxDimensionPrepaymentsRevenueCode name="VendTaxDimensionPrepaymentsRevenueCode">VendTaxDimensionPrepaymentsRevenueCode</a>

First included in: GeneralLedger/LedgerCurrencyParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VendTaxDimensionPrepaymentsRevenueCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#VendConversionLoss name="VendConversionLoss">VendConversionLoss</a>

First included in: GeneralLedger/LedgerCurrencyParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VendConversionLoss attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#VendConversionGain name="VendConversionGain">VendConversionGain</a>

First included in: GeneralLedger/LedgerCurrencyParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VendConversionGain attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CustRealizedLossMainAccount name="CustRealizedLossMainAccount">CustRealizedLossMainAccount</a>

First included in: GeneralLedger/LedgerCurrencyParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CustRealizedLossMainAccount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#EmplRealizedLossMainAccount name="EmplRealizedLossMainAccount">EmplRealizedLossMainAccount</a>

First included in: GeneralLedger/LedgerCurrencyParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EmplRealizedLossMainAccount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CustRealizedLossTaxPostingAccount name="CustRealizedLossTaxPostingAccount">CustRealizedLossTaxPostingAccount</a>

First included in: GeneralLedger/LedgerCurrencyParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CustRealizedLossTaxPostingAccount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#VendRelizedLossTaxPostingAccount name="VendRelizedLossTaxPostingAccount">VendRelizedLossTaxPostingAccount</a>

First included in: GeneralLedger/LedgerCurrencyParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VendRelizedLossTaxPostingAccount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#VendRealizedLossMainAccount name="VendRealizedLossMainAccount">VendRealizedLossMainAccount</a>

First included in: GeneralLedger/LedgerCurrencyParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VendRealizedLossMainAccount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CustRealizedGainMainAccount name="CustRealizedGainMainAccount">CustRealizedGainMainAccount</a>

First included in: GeneralLedger/LedgerCurrencyParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CustRealizedGainMainAccount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#EmplRealizedGain name="EmplRealizedGain">EmplRealizedGain</a>

First included in: GeneralLedger/LedgerCurrencyParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EmplRealizedGain attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CustRealizedGainTaxPostingAccount name="CustRealizedGainTaxPostingAccount">CustRealizedGainTaxPostingAccount</a>

First included in: GeneralLedger/LedgerCurrencyParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CustRealizedGainTaxPostingAccount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#VendRelizedGainTaxPostingAccount name="VendRelizedGainTaxPostingAccount">VendRelizedGainTaxPostingAccount</a>

First included in: GeneralLedger/LedgerCurrencyParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VendRelizedGainTaxPostingAccount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#VendRealizedGainMainAccount name="VendRealizedGainMainAccount">VendRealizedGainMainAccount</a>

First included in: GeneralLedger/LedgerCurrencyParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VendRealizedGainMainAccount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CustUnrealizedLossMainAccount name="CustUnrealizedLossMainAccount">CustUnrealizedLossMainAccount</a>

First included in: GeneralLedger/LedgerCurrencyParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CustUnrealizedLossMainAccount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#EmplUnrealizedLossMainAccount name="EmplUnrealizedLossMainAccount">EmplUnrealizedLossMainAccount</a>

First included in: GeneralLedger/LedgerCurrencyParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EmplUnrealizedLossMainAccount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#VendUnrealizedLossMainAccount name="VendUnrealizedLossMainAccount">VendUnrealizedLossMainAccount</a>

First included in: GeneralLedger/LedgerCurrencyParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VendUnrealizedLossMainAccount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CustUnrealizedGainMainAccount name="CustUnrealizedGainMainAccount">CustUnrealizedGainMainAccount</a>

First included in: GeneralLedger/LedgerCurrencyParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CustUnrealizedGainMainAccount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#EmplUnrealizedGainMainAccount name="EmplUnrealizedGainMainAccount">EmplUnrealizedGainMainAccount</a>

First included in: GeneralLedger/LedgerCurrencyParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EmplUnrealizedGainMainAccount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#VendUnrealizedGainMainAccount name="VendUnrealizedGainMainAccount">VendUnrealizedGainMainAccount</a>

First included in: GeneralLedger/LedgerCurrencyParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VendUnrealizedGainMainAccount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_ConversionLossCombinationRelationshipId name="Relationship_ConversionLossCombinationRelationshipId">Relationship_ConversionLossCombinationRelationshipId</a>

First included in: GeneralLedger/LedgerCurrencyParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_ConversionLossCombinationRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_ConversionGainCombinationRelationshipId name="Relationship_ConversionGainCombinationRelationshipId">Relationship_ConversionGainCombinationRelationshipId</a>

First included in: GeneralLedger/LedgerCurrencyParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_ConversionGainCombinationRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_RealizedLossCombinationRelationshipId name="Relationship_RealizedLossCombinationRelationshipId">Relationship_RealizedLossCombinationRelationshipId</a>

First included in: GeneralLedger/LedgerCurrencyParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_RealizedLossCombinationRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_MainAccountCombinationRelationshipId name="Relationship_MainAccountCombinationRelationshipId">Relationship_MainAccountCombinationRelationshipId</a>

First included in: GeneralLedger/LedgerCurrencyParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_MainAccountCombinationRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_MainAccount1CombinationRelationshipId name="Relationship_MainAccount1CombinationRelationshipId">Relationship_MainAccount1CombinationRelationshipId</a>

First included in: GeneralLedger/LedgerCurrencyParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_MainAccount1CombinationRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_MainAccount2CombinationRelationshipId name="Relationship_MainAccount2CombinationRelationshipId">Relationship_MainAccount2CombinationRelationshipId</a>

First included in: GeneralLedger/LedgerCurrencyParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_MainAccount2CombinationRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_RealizedLoss1CombinationRelationshipId name="Relationship_RealizedLoss1CombinationRelationshipId">Relationship_RealizedLoss1CombinationRelationshipId</a>

First included in: GeneralLedger/LedgerCurrencyParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_RealizedLoss1CombinationRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_RealizedGainCombinationRelationshipId name="Relationship_RealizedGainCombinationRelationshipId">Relationship_RealizedGainCombinationRelationshipId</a>

First included in: GeneralLedger/LedgerCurrencyParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_RealizedGainCombinationRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_MainAccount3CombinationRelationshipId name="Relationship_MainAccount3CombinationRelationshipId">Relationship_MainAccount3CombinationRelationshipId</a>

First included in: GeneralLedger/LedgerCurrencyParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_MainAccount3CombinationRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_MainAccount4CombinationRelationshipId name="Relationship_MainAccount4CombinationRelationshipId">Relationship_MainAccount4CombinationRelationshipId</a>

First included in: GeneralLedger/LedgerCurrencyParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_MainAccount4CombinationRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_MainAccount5CombinationRelationshipId name="Relationship_MainAccount5CombinationRelationshipId">Relationship_MainAccount5CombinationRelationshipId</a>

First included in: GeneralLedger/LedgerCurrencyParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_MainAccount5CombinationRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_RealizedGain1CombinationRelationshipId name="Relationship_RealizedGain1CombinationRelationshipId">Relationship_RealizedGain1CombinationRelationshipId</a>

First included in: GeneralLedger/LedgerCurrencyParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_RealizedGain1CombinationRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_OffsetLedgerAccountCombinationRelationshipId name="Relationship_OffsetLedgerAccountCombinationRelationshipId">Relationship_OffsetLedgerAccountCombinationRelationshipId</a>

First included in: GeneralLedger/LedgerCurrencyParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_OffsetLedgerAccountCombinationRelationshipId attribute are listed below.</summary>

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

First included in: GeneralLedger/LedgerCurrencyParametersEntity (this entity)  

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

First included in: GeneralLedger/LedgerCurrencyParametersEntity (this entity)  

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

### <a href=#Relationship_UnrealizedLossCombinationRelationshipId name="Relationship_UnrealizedLossCombinationRelationshipId">Relationship_UnrealizedLossCombinationRelationshipId</a>

First included in: GeneralLedger/LedgerCurrencyParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_UnrealizedLossCombinationRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_MainAccount6CombinationRelationshipId name="Relationship_MainAccount6CombinationRelationshipId">Relationship_MainAccount6CombinationRelationshipId</a>

First included in: GeneralLedger/LedgerCurrencyParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_MainAccount6CombinationRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_MainAccount7CombinationRelationshipId name="Relationship_MainAccount7CombinationRelationshipId">Relationship_MainAccount7CombinationRelationshipId</a>

First included in: GeneralLedger/LedgerCurrencyParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_MainAccount7CombinationRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_UnrealizedLoss1CombinationRelationshipId name="Relationship_UnrealizedLoss1CombinationRelationshipId">Relationship_UnrealizedLoss1CombinationRelationshipId</a>

First included in: GeneralLedger/LedgerCurrencyParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_UnrealizedLoss1CombinationRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_UnrealizedGainCombinationRelationshipId name="Relationship_UnrealizedGainCombinationRelationshipId">Relationship_UnrealizedGainCombinationRelationshipId</a>

First included in: GeneralLedger/LedgerCurrencyParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_UnrealizedGainCombinationRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_MainAccount8CombinationRelationshipId name="Relationship_MainAccount8CombinationRelationshipId">Relationship_MainAccount8CombinationRelationshipId</a>

First included in: GeneralLedger/LedgerCurrencyParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_MainAccount8CombinationRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_MainAccount9CombinationRelationshipId name="Relationship_MainAccount9CombinationRelationshipId">Relationship_MainAccount9CombinationRelationshipId</a>

First included in: GeneralLedger/LedgerCurrencyParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_MainAccount9CombinationRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_UnrealizedGain1CombinationRelationshipId name="Relationship_UnrealizedGain1CombinationRelationshipId">Relationship_UnrealizedGain1CombinationRelationshipId</a>

First included in: GeneralLedger/LedgerCurrencyParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_UnrealizedGain1CombinationRelationshipId attribute are listed below.</summary>

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

First included in: GeneralLedger/LedgerCurrencyParametersEntity (this entity)  

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

First included in: GeneralLedger/LedgerCurrencyParametersEntity (this entity)  

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
