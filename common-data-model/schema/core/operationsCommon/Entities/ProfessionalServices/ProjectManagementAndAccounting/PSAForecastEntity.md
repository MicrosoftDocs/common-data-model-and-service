---
title: PSAForecastEntity in ProjectManagementAndAccounting - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 7/8/2020
ms.author: nebanfic
---

# Budget updates in ProjectManagementAndAccounting(PSAForecastEntity)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/ProfessionalServices/ProjectManagementAndAccounting/PSAForecastEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Budget updates</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[ActivityNumber](#ActivityNumber)||<a href="PSAForecastEntity.md" target="_blank">ProjectManagementAndAccounting/PSAForecastEntity</a>|
|[AmountMst](#AmountMst)||<a href="PSAForecastEntity.md" target="_blank">ProjectManagementAndAccounting/PSAForecastEntity</a>|
|[CategoryId](#CategoryId)||<a href="PSAForecastEntity.md" target="_blank">ProjectManagementAndAccounting/PSAForecastEntity</a>|
|[costSales](#costSales)||<a href="PSAForecastEntity.md" target="_blank">ProjectManagementAndAccounting/PSAForecastEntity</a>|
|[DefaultDimension](#DefaultDimension)||<a href="PSAForecastEntity.md" target="_blank">ProjectManagementAndAccounting/PSAForecastEntity</a>|
|[Elimination](#Elimination)||<a href="PSAForecastEntity.md" target="_blank">ProjectManagementAndAccounting/PSAForecastEntity</a>|
|[EmplItemId](#EmplItemId)||<a href="PSAForecastEntity.md" target="_blank">ProjectManagementAndAccounting/PSAForecastEntity</a>|
|[LedgerDimension](#LedgerDimension)||<a href="PSAForecastEntity.md" target="_blank">ProjectManagementAndAccounting/PSAForecastEntity</a>|
|[LedgerTransDate](#LedgerTransDate)||<a href="PSAForecastEntity.md" target="_blank">ProjectManagementAndAccounting/PSAForecastEntity</a>|
|[ModelId](#ModelId)||<a href="PSAForecastEntity.md" target="_blank">ProjectManagementAndAccounting/PSAForecastEntity</a>|
|[PaymentDate](#PaymentDate)||<a href="PSAForecastEntity.md" target="_blank">ProjectManagementAndAccounting/PSAForecastEntity</a>|
|[PaymentStatus](#PaymentStatus)||<a href="PSAForecastEntity.md" target="_blank">ProjectManagementAndAccounting/PSAForecastEntity</a>|
|[PostingType](#PostingType)||<a href="PSAForecastEntity.md" target="_blank">ProjectManagementAndAccounting/PSAForecastEntity</a>|
|[ProjFundingSource](#ProjFundingSource)||<a href="PSAForecastEntity.md" target="_blank">ProjectManagementAndAccounting/PSAForecastEntity</a>|
|[ProjId](#ProjId)||<a href="PSAForecastEntity.md" target="_blank">ProjectManagementAndAccounting/PSAForecastEntity</a>|
|[ProjTransDate](#ProjTransDate)||<a href="PSAForecastEntity.md" target="_blank">ProjectManagementAndAccounting/PSAForecastEntity</a>|
|[ProjTransType](#ProjTransType)||<a href="PSAForecastEntity.md" target="_blank">ProjectManagementAndAccounting/PSAForecastEntity</a>|
|[ProjType](#ProjType)||<a href="PSAForecastEntity.md" target="_blank">ProjectManagementAndAccounting/PSAForecastEntity</a>|
|[Qty](#Qty)||<a href="PSAForecastEntity.md" target="_blank">ProjectManagementAndAccounting/PSAForecastEntity</a>|
|[Resource](#Resource)||<a href="PSAForecastEntity.md" target="_blank">ProjectManagementAndAccounting/PSAForecastEntity</a>|
|[ResourceCategory](#ResourceCategory)||<a href="PSAForecastEntity.md" target="_blank">ProjectManagementAndAccounting/PSAForecastEntity</a>|
|[SubscriptionId](#SubscriptionId)||<a href="PSAForecastEntity.md" target="_blank">ProjectManagementAndAccounting/PSAForecastEntity</a>|
|[TransId](#TransId)||<a href="PSAForecastEntity.md" target="_blank">ProjectManagementAndAccounting/PSAForecastEntity</a>|
|[Voucher](#Voucher)||<a href="PSAForecastEntity.md" target="_blank">ProjectManagementAndAccounting/PSAForecastEntity</a>|
|[LedgerDimensionDisplayValue](#LedgerDimensionDisplayValue)||<a href="PSAForecastEntity.md" target="_blank">ProjectManagementAndAccounting/PSAForecastEntity</a>|
|[ProjFundingSource_ContractId](#ProjFundingSource_ContractId)||<a href="PSAForecastEntity.md" target="_blank">ProjectManagementAndAccounting/PSAForecastEntity</a>|
|[ProjFundingSource_FundingSourceId](#ProjFundingSource_FundingSourceId)||<a href="PSAForecastEntity.md" target="_blank">ProjectManagementAndAccounting/PSAForecastEntity</a>|
|[ProjTable_ProjId](#ProjTable_ProjId)||<a href="PSAForecastEntity.md" target="_blank">ProjectManagementAndAccounting/PSAForecastEntity</a>|
|[DefaultDimensionDisplayValue](#DefaultDimensionDisplayValue)||<a href="PSAForecastEntity.md" target="_blank">ProjectManagementAndAccounting/PSAForecastEntity</a>|
|[PLLaborCost](#PLLaborCost)||<a href="PSAForecastEntity.md" target="_blank">ProjectManagementAndAccounting/PSAForecastEntity</a>|
|[PLExpenseCost](#PLExpenseCost)||<a href="PSAForecastEntity.md" target="_blank">ProjectManagementAndAccounting/PSAForecastEntity</a>|
|[PLLaborQty](#PLLaborQty)||<a href="PSAForecastEntity.md" target="_blank">ProjectManagementAndAccounting/PSAForecastEntity</a>|
|[PLMaterialCost](#PLMaterialCost)||<a href="PSAForecastEntity.md" target="_blank">ProjectManagementAndAccounting/PSAForecastEntity</a>|
|[PLCostAccruedLoss](#PLCostAccruedLoss)||<a href="PSAForecastEntity.md" target="_blank">ProjectManagementAndAccounting/PSAForecastEntity</a>|
|[PLTotalCost](#PLTotalCost)||<a href="PSAForecastEntity.md" target="_blank">ProjectManagementAndAccounting/PSAForecastEntity</a>|
|[WIPLaborCost](#WIPLaborCost)||<a href="PSAForecastEntity.md" target="_blank">ProjectManagementAndAccounting/PSAForecastEntity</a>|
|[WIPExpenseCost](#WIPExpenseCost)||<a href="PSAForecastEntity.md" target="_blank">ProjectManagementAndAccounting/PSAForecastEntity</a>|
|[WIPMaterialCost](#WIPMaterialCost)||<a href="PSAForecastEntity.md" target="_blank">ProjectManagementAndAccounting/PSAForecastEntity</a>|
|[WIPCostAccruedLoss](#WIPCostAccruedLoss)||<a href="PSAForecastEntity.md" target="_blank">ProjectManagementAndAccounting/PSAForecastEntity</a>|
|[WIPTotalCost](#WIPTotalCost)||<a href="PSAForecastEntity.md" target="_blank">ProjectManagementAndAccounting/PSAForecastEntity</a>|
|[ConsumedLaborCost](#ConsumedLaborCost)||<a href="PSAForecastEntity.md" target="_blank">ProjectManagementAndAccounting/PSAForecastEntity</a>|
|[ConsumedLaborQty](#ConsumedLaborQty)||<a href="PSAForecastEntity.md" target="_blank">ProjectManagementAndAccounting/PSAForecastEntity</a>|
|[ConsumedExpenseCost](#ConsumedExpenseCost)||<a href="PSAForecastEntity.md" target="_blank">ProjectManagementAndAccounting/PSAForecastEntity</a>|
|[ConsumedMaterialCost](#ConsumedMaterialCost)||<a href="PSAForecastEntity.md" target="_blank">ProjectManagementAndAccounting/PSAForecastEntity</a>|
|[totalConsumption](#totalConsumption)||<a href="PSAForecastEntity.md" target="_blank">ProjectManagementAndAccounting/PSAForecastEntity</a>|
|[PayrollAllocation](#PayrollAllocation)||<a href="PSAForecastEntity.md" target="_blank">ProjectManagementAndAccounting/PSAForecastEntity</a>|
|[LaborInvoicedRevenue](#LaborInvoicedRevenue)||<a href="PSAForecastEntity.md" target="_blank">ProjectManagementAndAccounting/PSAForecastEntity</a>|
|[LaborInvoicedQty](#LaborInvoicedQty)||<a href="PSAForecastEntity.md" target="_blank">ProjectManagementAndAccounting/PSAForecastEntity</a>|
|[ExpenseInvoicedRevenue](#ExpenseInvoicedRevenue)||<a href="PSAForecastEntity.md" target="_blank">ProjectManagementAndAccounting/PSAForecastEntity</a>|
|[MaterialInvoicedRevenue](#MaterialInvoicedRevenue)||<a href="PSAForecastEntity.md" target="_blank">ProjectManagementAndAccounting/PSAForecastEntity</a>|
|[FeeInvoicedRevenue](#FeeInvoicedRevenue)||<a href="PSAForecastEntity.md" target="_blank">ProjectManagementAndAccounting/PSAForecastEntity</a>|
|[OnAccPrePayment](#OnAccPrePayment)||<a href="PSAForecastEntity.md" target="_blank">ProjectManagementAndAccounting/PSAForecastEntity</a>|
|[OnAccDeduction](#OnAccDeduction)||<a href="PSAForecastEntity.md" target="_blank">ProjectManagementAndAccounting/PSAForecastEntity</a>|
|[OnAccMilestone](#OnAccMilestone)||<a href="PSAForecastEntity.md" target="_blank">ProjectManagementAndAccounting/PSAForecastEntity</a>|
|[OnAccBegBal](#OnAccBegBal)||<a href="PSAForecastEntity.md" target="_blank">ProjectManagementAndAccounting/PSAForecastEntity</a>|
|[OnAccTotal](#OnAccTotal)||<a href="PSAForecastEntity.md" target="_blank">ProjectManagementAndAccounting/PSAForecastEntity</a>|
|[PLInvoicedRevenue](#PLInvoicedRevenue)||<a href="PSAForecastEntity.md" target="_blank">ProjectManagementAndAccounting/PSAForecastEntity</a>|
|[totalInvoicedRevenue](#totalInvoicedRevenue)||<a href="PSAForecastEntity.md" target="_blank">ProjectManagementAndAccounting/PSAForecastEntity</a>|
|[PLaccruedRevenueSalesValue](#PLaccruedRevenueSalesValue)||<a href="PSAForecastEntity.md" target="_blank">ProjectManagementAndAccounting/PSAForecastEntity</a>|
|[PLaccruedRevenueSubscription](#PLaccruedRevenueSubscription)||<a href="PSAForecastEntity.md" target="_blank">ProjectManagementAndAccounting/PSAForecastEntity</a>|
|[PLaccruedRevenueProduction](#PLaccruedRevenueProduction)||<a href="PSAForecastEntity.md" target="_blank">ProjectManagementAndAccounting/PSAForecastEntity</a>|
|[PLaccruedRevenueProfit](#PLaccruedRevenueProfit)||<a href="PSAForecastEntity.md" target="_blank">ProjectManagementAndAccounting/PSAForecastEntity</a>|
|[PLAccruedRevenueOnAcc](#PLAccruedRevenueOnAcc)||<a href="PSAForecastEntity.md" target="_blank">ProjectManagementAndAccounting/PSAForecastEntity</a>|
|[PLTotalAccruedRevenue](#PLTotalAccruedRevenue)||<a href="PSAForecastEntity.md" target="_blank">ProjectManagementAndAccounting/PSAForecastEntity</a>|
|[WIPSalesValue](#WIPSalesValue)||<a href="PSAForecastEntity.md" target="_blank">ProjectManagementAndAccounting/PSAForecastEntity</a>|
|[WIPProduction](#WIPProduction)||<a href="PSAForecastEntity.md" target="_blank">ProjectManagementAndAccounting/PSAForecastEntity</a>|
|[WIPProfit](#WIPProfit)||<a href="PSAForecastEntity.md" target="_blank">ProjectManagementAndAccounting/PSAForecastEntity</a>|
|[WIPSubscription](#WIPSubscription)||<a href="PSAForecastEntity.md" target="_blank">ProjectManagementAndAccounting/PSAForecastEntity</a>|
|[WIPInvoicedOnAccount](#WIPInvoicedOnAccount)||<a href="PSAForecastEntity.md" target="_blank">ProjectManagementAndAccounting/PSAForecastEntity</a>|
|[WIPSalesTotal](#WIPSalesTotal)||<a href="PSAForecastEntity.md" target="_blank">ProjectManagementAndAccounting/PSAForecastEntity</a>|
|[GrossWIP](#GrossWIP)||<a href="PSAForecastEntity.md" target="_blank">ProjectManagementAndAccounting/PSAForecastEntity</a>|
|[NetWIP](#NetWIP)||<a href="PSAForecastEntity.md" target="_blank">ProjectManagementAndAccounting/PSAForecastEntity</a>|
|[PLInvoicedRevenueOnAccount](#PLInvoicedRevenueOnAccount)||<a href="PSAForecastEntity.md" target="_blank">ProjectManagementAndAccounting/PSAForecastEntity</a>|
|[ContractId](#ContractId)||<a href="PSAForecastEntity.md" target="_blank">ProjectManagementAndAccounting/PSAForecastEntity</a>|
|[PLLaborCostWithoutNoNeverLedger](#PLLaborCostWithoutNoNeverLedger)||<a href="PSAForecastEntity.md" target="_blank">ProjectManagementAndAccounting/PSAForecastEntity</a>|
|[PLLaborQtyWithoutNoNeverLedger](#PLLaborQtyWithoutNoNeverLedger)||<a href="PSAForecastEntity.md" target="_blank">ProjectManagementAndAccounting/PSAForecastEntity</a>|
|[ConsumedLaborCostWithoutNoNeverLedger](#ConsumedLaborCostWithoutNoNeverLedger)||<a href="PSAForecastEntity.md" target="_blank">ProjectManagementAndAccounting/PSAForecastEntity</a>|
|[ConsumedLaborQtyWithoutNoNeverLedger](#ConsumedLaborQtyWithoutNoNeverLedger)||<a href="PSAForecastEntity.md" target="_blank">ProjectManagementAndAccounting/PSAForecastEntity</a>|
|[PLMaterialCostWithoutNeverLedger](#PLMaterialCostWithoutNeverLedger)||<a href="PSAForecastEntity.md" target="_blank">ProjectManagementAndAccounting/PSAForecastEntity</a>|
|[ConsumedMaterialCostWithoutNeverLedger](#ConsumedMaterialCostWithoutNeverLedger)||<a href="PSAForecastEntity.md" target="_blank">ProjectManagementAndAccounting/PSAForecastEntity</a>|
|[ResourceCompanyId](#ResourceCompanyId)||<a href="PSAForecastEntity.md" target="_blank">ProjectManagementAndAccounting/PSAForecastEntity</a>|
|[ResourceId](#ResourceId)||<a href="PSAForecastEntity.md" target="_blank">ProjectManagementAndAccounting/PSAForecastEntity</a>|
|[PSAIndirectComponent](#PSAIndirectComponent)||<a href="PSAForecastEntity.md" target="_blank">ProjectManagementAndAccounting/PSAForecastEntity</a>|
|[Relationship_DefaultDimensionDimensionSetRelationshipId](#Relationship_DefaultDimensionDimensionSetRelationshipId)||<a href="PSAForecastEntity.md" target="_blank">ProjectManagementAndAccounting/PSAForecastEntity</a>|
|[BackingTable_ProjTransBudgetRelationshipId](#BackingTable_ProjTransBudgetRelationshipId)||<a href="PSAForecastEntity.md" target="_blank">ProjectManagementAndAccounting/PSAForecastEntity</a>|
|[Relationship_PrimaryCompanyContextRelationshipId](#Relationship_PrimaryCompanyContextRelationshipId)||<a href="PSAForecastEntity.md" target="_blank">ProjectManagementAndAccounting/PSAForecastEntity</a>|

### <a href=#ActivityNumber name="ActivityNumber">ActivityNumber</a>

First included in: ProjectManagementAndAccounting/PSAForecastEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ActivityNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AmountMst name="AmountMst">AmountMst</a>

First included in: ProjectManagementAndAccounting/PSAForecastEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AmountMst attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CategoryId name="CategoryId">CategoryId</a>

First included in: ProjectManagementAndAccounting/PSAForecastEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CategoryId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#costSales name="costSales">costSales</a>

First included in: ProjectManagementAndAccounting/PSAForecastEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the costSales attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DefaultDimension name="DefaultDimension">DefaultDimension</a>

First included in: ProjectManagementAndAccounting/PSAForecastEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultDimension attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Elimination name="Elimination">Elimination</a>

First included in: ProjectManagementAndAccounting/PSAForecastEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Elimination attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#EmplItemId name="EmplItemId">EmplItemId</a>

First included in: ProjectManagementAndAccounting/PSAForecastEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EmplItemId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LedgerDimension name="LedgerDimension">LedgerDimension</a>

First included in: ProjectManagementAndAccounting/PSAForecastEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LedgerDimension attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LedgerTransDate name="LedgerTransDate">LedgerTransDate</a>

First included in: ProjectManagementAndAccounting/PSAForecastEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Ledger date</td></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LedgerTransDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Ledger date</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ModelId name="ModelId">ModelId</a>

First included in: ProjectManagementAndAccounting/PSAForecastEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Forecast model</td></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ModelId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Forecast model</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PaymentDate name="PaymentDate">PaymentDate</a>

First included in: ProjectManagementAndAccounting/PSAForecastEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PaymentDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PaymentStatus name="PaymentStatus">PaymentStatus</a>

First included in: ProjectManagementAndAccounting/PSAForecastEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PaymentStatus attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PostingType name="PostingType">PostingType</a>

First included in: ProjectManagementAndAccounting/PSAForecastEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PostingType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProjFundingSource name="ProjFundingSource">ProjFundingSource</a>

First included in: ProjectManagementAndAccounting/PSAForecastEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProjFundingSource attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProjId name="ProjId">ProjId</a>

First included in: ProjectManagementAndAccounting/PSAForecastEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProjId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProjTransDate name="ProjTransDate">ProjTransDate</a>

First included in: ProjectManagementAndAccounting/PSAForecastEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProjTransDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProjTransType name="ProjTransType">ProjTransType</a>

First included in: ProjectManagementAndAccounting/PSAForecastEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProjTransType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProjType name="ProjType">ProjType</a>

First included in: ProjectManagementAndAccounting/PSAForecastEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProjType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Qty name="Qty">Qty</a>

First included in: ProjectManagementAndAccounting/PSAForecastEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Qty attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Resource name="Resource">Resource</a>

First included in: ProjectManagementAndAccounting/PSAForecastEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Resource attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ResourceCategory name="ResourceCategory">ResourceCategory</a>

First included in: ProjectManagementAndAccounting/PSAForecastEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ResourceCategory attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SubscriptionId name="SubscriptionId">SubscriptionId</a>

First included in: ProjectManagementAndAccounting/PSAForecastEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SubscriptionId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TransId name="TransId">TransId</a>

First included in: ProjectManagementAndAccounting/PSAForecastEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TransId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Voucher name="Voucher">Voucher</a>

First included in: ProjectManagementAndAccounting/PSAForecastEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Voucher attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LedgerDimensionDisplayValue name="LedgerDimensionDisplayValue">LedgerDimensionDisplayValue</a>

First included in: ProjectManagementAndAccounting/PSAForecastEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Combination display</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LedgerDimensionDisplayValue attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Combination display</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProjFundingSource_ContractId name="ProjFundingSource_ContractId">ProjFundingSource_ContractId</a>

First included in: ProjectManagementAndAccounting/PSAForecastEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProjFundingSource_ContractId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProjFundingSource_FundingSourceId name="ProjFundingSource_FundingSourceId">ProjFundingSource_FundingSourceId</a>

First included in: ProjectManagementAndAccounting/PSAForecastEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProjFundingSource_FundingSourceId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProjTable_ProjId name="ProjTable_ProjId">ProjTable_ProjId</a>

First included in: ProjectManagementAndAccounting/PSAForecastEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProjTable_ProjId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DefaultDimensionDisplayValue name="DefaultDimensionDisplayValue">DefaultDimensionDisplayValue</a>

First included in: ProjectManagementAndAccounting/PSAForecastEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultDimensionDisplayValue attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PLLaborCost name="PLLaborCost">PLLaborCost</a>

First included in: ProjectManagementAndAccounting/PSAForecastEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PLLaborCost attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PLExpenseCost name="PLExpenseCost">PLExpenseCost</a>

First included in: ProjectManagementAndAccounting/PSAForecastEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PLExpenseCost attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PLLaborQty name="PLLaborQty">PLLaborQty</a>

First included in: ProjectManagementAndAccounting/PSAForecastEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PLLaborQty attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PLMaterialCost name="PLMaterialCost">PLMaterialCost</a>

First included in: ProjectManagementAndAccounting/PSAForecastEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PLMaterialCost attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PLCostAccruedLoss name="PLCostAccruedLoss">PLCostAccruedLoss</a>

First included in: ProjectManagementAndAccounting/PSAForecastEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PLCostAccruedLoss attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PLTotalCost name="PLTotalCost">PLTotalCost</a>

First included in: ProjectManagementAndAccounting/PSAForecastEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Total cost</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PLTotalCost attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Total cost</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WIPLaborCost name="WIPLaborCost">WIPLaborCost</a>

First included in: ProjectManagementAndAccounting/PSAForecastEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WIPLaborCost attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WIPExpenseCost name="WIPExpenseCost">WIPExpenseCost</a>

First included in: ProjectManagementAndAccounting/PSAForecastEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WIPExpenseCost attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WIPMaterialCost name="WIPMaterialCost">WIPMaterialCost</a>

First included in: ProjectManagementAndAccounting/PSAForecastEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WIPMaterialCost attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WIPCostAccruedLoss name="WIPCostAccruedLoss">WIPCostAccruedLoss</a>

First included in: ProjectManagementAndAccounting/PSAForecastEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WIPCostAccruedLoss attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WIPTotalCost name="WIPTotalCost">WIPTotalCost</a>

First included in: ProjectManagementAndAccounting/PSAForecastEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WIPTotalCost attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ConsumedLaborCost name="ConsumedLaborCost">ConsumedLaborCost</a>

First included in: ProjectManagementAndAccounting/PSAForecastEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ConsumedLaborCost attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ConsumedLaborQty name="ConsumedLaborQty">ConsumedLaborQty</a>

First included in: ProjectManagementAndAccounting/PSAForecastEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ConsumedLaborQty attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ConsumedExpenseCost name="ConsumedExpenseCost">ConsumedExpenseCost</a>

First included in: ProjectManagementAndAccounting/PSAForecastEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ConsumedExpenseCost attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ConsumedMaterialCost name="ConsumedMaterialCost">ConsumedMaterialCost</a>

First included in: ProjectManagementAndAccounting/PSAForecastEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ConsumedMaterialCost attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#totalConsumption name="totalConsumption">totalConsumption</a>

First included in: ProjectManagementAndAccounting/PSAForecastEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the totalConsumption attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PayrollAllocation name="PayrollAllocation">PayrollAllocation</a>

First included in: ProjectManagementAndAccounting/PSAForecastEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PayrollAllocation attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LaborInvoicedRevenue name="LaborInvoicedRevenue">LaborInvoicedRevenue</a>

First included in: ProjectManagementAndAccounting/PSAForecastEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LaborInvoicedRevenue attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LaborInvoicedQty name="LaborInvoicedQty">LaborInvoicedQty</a>

First included in: ProjectManagementAndAccounting/PSAForecastEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LaborInvoicedQty attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ExpenseInvoicedRevenue name="ExpenseInvoicedRevenue">ExpenseInvoicedRevenue</a>

First included in: ProjectManagementAndAccounting/PSAForecastEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ExpenseInvoicedRevenue attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MaterialInvoicedRevenue name="MaterialInvoicedRevenue">MaterialInvoicedRevenue</a>

First included in: ProjectManagementAndAccounting/PSAForecastEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MaterialInvoicedRevenue attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FeeInvoicedRevenue name="FeeInvoicedRevenue">FeeInvoicedRevenue</a>

First included in: ProjectManagementAndAccounting/PSAForecastEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FeeInvoicedRevenue attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#OnAccPrePayment name="OnAccPrePayment">OnAccPrePayment</a>

First included in: ProjectManagementAndAccounting/PSAForecastEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OnAccPrePayment attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#OnAccDeduction name="OnAccDeduction">OnAccDeduction</a>

First included in: ProjectManagementAndAccounting/PSAForecastEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OnAccDeduction attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#OnAccMilestone name="OnAccMilestone">OnAccMilestone</a>

First included in: ProjectManagementAndAccounting/PSAForecastEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OnAccMilestone attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#OnAccBegBal name="OnAccBegBal">OnAccBegBal</a>

First included in: ProjectManagementAndAccounting/PSAForecastEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OnAccBegBal attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#OnAccTotal name="OnAccTotal">OnAccTotal</a>

First included in: ProjectManagementAndAccounting/PSAForecastEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OnAccTotal attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PLInvoicedRevenue name="PLInvoicedRevenue">PLInvoicedRevenue</a>

First included in: ProjectManagementAndAccounting/PSAForecastEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PLInvoicedRevenue attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#totalInvoicedRevenue name="totalInvoicedRevenue">totalInvoicedRevenue</a>

First included in: ProjectManagementAndAccounting/PSAForecastEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Total invoiced revenue</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the totalInvoicedRevenue attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Total invoiced revenue</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PLaccruedRevenueSalesValue name="PLaccruedRevenueSalesValue">PLaccruedRevenueSalesValue</a>

First included in: ProjectManagementAndAccounting/PSAForecastEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PLaccruedRevenueSalesValue attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PLaccruedRevenueSubscription name="PLaccruedRevenueSubscription">PLaccruedRevenueSubscription</a>

First included in: ProjectManagementAndAccounting/PSAForecastEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PLaccruedRevenueSubscription attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PLaccruedRevenueProduction name="PLaccruedRevenueProduction">PLaccruedRevenueProduction</a>

First included in: ProjectManagementAndAccounting/PSAForecastEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PLaccruedRevenueProduction attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PLaccruedRevenueProfit name="PLaccruedRevenueProfit">PLaccruedRevenueProfit</a>

First included in: ProjectManagementAndAccounting/PSAForecastEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PLaccruedRevenueProfit attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PLAccruedRevenueOnAcc name="PLAccruedRevenueOnAcc">PLAccruedRevenueOnAcc</a>

First included in: ProjectManagementAndAccounting/PSAForecastEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PLAccruedRevenueOnAcc attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PLTotalAccruedRevenue name="PLTotalAccruedRevenue">PLTotalAccruedRevenue</a>

First included in: ProjectManagementAndAccounting/PSAForecastEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Total accrued revenue</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PLTotalAccruedRevenue attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Total accrued revenue</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WIPSalesValue name="WIPSalesValue">WIPSalesValue</a>

First included in: ProjectManagementAndAccounting/PSAForecastEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WIPSalesValue attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WIPProduction name="WIPProduction">WIPProduction</a>

First included in: ProjectManagementAndAccounting/PSAForecastEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WIPProduction attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WIPProfit name="WIPProfit">WIPProfit</a>

First included in: ProjectManagementAndAccounting/PSAForecastEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WIPProfit attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WIPSubscription name="WIPSubscription">WIPSubscription</a>

First included in: ProjectManagementAndAccounting/PSAForecastEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WIPSubscription attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WIPInvoicedOnAccount name="WIPInvoicedOnAccount">WIPInvoicedOnAccount</a>

First included in: ProjectManagementAndAccounting/PSAForecastEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WIPInvoicedOnAccount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WIPSalesTotal name="WIPSalesTotal">WIPSalesTotal</a>

First included in: ProjectManagementAndAccounting/PSAForecastEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WIPSalesTotal attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#GrossWIP name="GrossWIP">GrossWIP</a>

First included in: ProjectManagementAndAccounting/PSAForecastEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the GrossWIP attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#NetWIP name="NetWIP">NetWIP</a>

First included in: ProjectManagementAndAccounting/PSAForecastEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the NetWIP attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PLInvoicedRevenueOnAccount name="PLInvoicedRevenueOnAccount">PLInvoicedRevenueOnAccount</a>

First included in: ProjectManagementAndAccounting/PSAForecastEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PLInvoicedRevenueOnAccount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ContractId name="ContractId">ContractId</a>

First included in: ProjectManagementAndAccounting/PSAForecastEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ContractId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PLLaborCostWithoutNoNeverLedger name="PLLaborCostWithoutNoNeverLedger">PLLaborCostWithoutNoNeverLedger</a>

First included in: ProjectManagementAndAccounting/PSAForecastEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PLLaborCostWithoutNoNeverLedger attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PLLaborQtyWithoutNoNeverLedger name="PLLaborQtyWithoutNoNeverLedger">PLLaborQtyWithoutNoNeverLedger</a>

First included in: ProjectManagementAndAccounting/PSAForecastEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PLLaborQtyWithoutNoNeverLedger attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ConsumedLaborCostWithoutNoNeverLedger name="ConsumedLaborCostWithoutNoNeverLedger">ConsumedLaborCostWithoutNoNeverLedger</a>

First included in: ProjectManagementAndAccounting/PSAForecastEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ConsumedLaborCostWithoutNoNeverLedger attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ConsumedLaborQtyWithoutNoNeverLedger name="ConsumedLaborQtyWithoutNoNeverLedger">ConsumedLaborQtyWithoutNoNeverLedger</a>

First included in: ProjectManagementAndAccounting/PSAForecastEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ConsumedLaborQtyWithoutNoNeverLedger attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PLMaterialCostWithoutNeverLedger name="PLMaterialCostWithoutNeverLedger">PLMaterialCostWithoutNeverLedger</a>

First included in: ProjectManagementAndAccounting/PSAForecastEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PLMaterialCostWithoutNeverLedger attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ConsumedMaterialCostWithoutNeverLedger name="ConsumedMaterialCostWithoutNeverLedger">ConsumedMaterialCostWithoutNeverLedger</a>

First included in: ProjectManagementAndAccounting/PSAForecastEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ConsumedMaterialCostWithoutNeverLedger attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ResourceCompanyId name="ResourceCompanyId">ResourceCompanyId</a>

First included in: ProjectManagementAndAccounting/PSAForecastEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ResourceCompanyId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ResourceId name="ResourceId">ResourceId</a>

First included in: ProjectManagementAndAccounting/PSAForecastEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ResourceId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PSAIndirectComponent name="PSAIndirectComponent">PSAIndirectComponent</a>

First included in: ProjectManagementAndAccounting/PSAForecastEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PSAIndirectComponent attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_DefaultDimensionDimensionSetRelationshipId name="Relationship_DefaultDimensionDimensionSetRelationshipId">Relationship_DefaultDimensionDimensionSetRelationshipId</a>

First included in: ProjectManagementAndAccounting/PSAForecastEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_DefaultDimensionDimensionSetRelationshipId attribute are listed below.</summary>

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

### <a href=#BackingTable_ProjTransBudgetRelationshipId name="BackingTable_ProjTransBudgetRelationshipId">BackingTable_ProjTransBudgetRelationshipId</a>

First included in: ProjectManagementAndAccounting/PSAForecastEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_ProjTransBudgetRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/ProfessionalServices/ProjectManagementAndAccounting/Transaction/ProjTransBudget.md" target="_blank">/core/operationsCommon/Tables/ProfessionalServices/ProjectManagementAndAccounting/Transaction/ProjTransBudget.cdm.json/ProjTransBudget</a></td><td><a href="../../../Tables/ProfessionalServices/ProjectManagementAndAccounting/Transaction/ProjTransBudget.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PrimaryCompanyContextRelationshipId name="Relationship_PrimaryCompanyContextRelationshipId">Relationship_PrimaryCompanyContextRelationshipId</a>

First included in: ProjectManagementAndAccounting/PSAForecastEntity (this entity)  

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
