---
title: PSAActualEntity - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/20/2020
ms.author: nebanfic
---

# PSAActualEntity

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/ProfessionalServices/ProjectManagementAndAccounting/PSAActualEntity.cdm.json" target="_blank">GitHub</a>.  

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
|[ActivityNumber](#ActivityNumber)||<a href="PSAActualEntity.md" target="_blank">ProjectManagementAndAccounting/PSAActualEntity</a>|
|[AmountMst](#AmountMst)||<a href="PSAActualEntity.md" target="_blank">ProjectManagementAndAccounting/PSAActualEntity</a>|
|[CategoryId](#CategoryId)||<a href="PSAActualEntity.md" target="_blank">ProjectManagementAndAccounting/PSAActualEntity</a>|
|[costSales](#costSales)||<a href="PSAActualEntity.md" target="_blank">ProjectManagementAndAccounting/PSAActualEntity</a>|
|[DefaultDimension](#DefaultDimension)||<a href="PSAActualEntity.md" target="_blank">ProjectManagementAndAccounting/PSAActualEntity</a>|
|[EmplItemId](#EmplItemId)||<a href="PSAActualEntity.md" target="_blank">ProjectManagementAndAccounting/PSAActualEntity</a>|
|[InventTransId](#InventTransId)||<a href="PSAActualEntity.md" target="_blank">ProjectManagementAndAccounting/PSAActualEntity</a>|
|[LedgerDimension](#LedgerDimension)||<a href="PSAActualEntity.md" target="_blank">ProjectManagementAndAccounting/PSAActualEntity</a>|
|[LedgerOrigin](#LedgerOrigin)||<a href="PSAActualEntity.md" target="_blank">ProjectManagementAndAccounting/PSAActualEntity</a>|
|[LedgerTransDate](#LedgerTransDate)||<a href="PSAActualEntity.md" target="_blank">ProjectManagementAndAccounting/PSAActualEntity</a>|
|[PaymentDate](#PaymentDate)||<a href="PSAActualEntity.md" target="_blank">ProjectManagementAndAccounting/PSAActualEntity</a>|
|[PaymentStatus](#PaymentStatus)||<a href="PSAActualEntity.md" target="_blank">ProjectManagementAndAccounting/PSAActualEntity</a>|
|[PostingType](#PostingType)||<a href="PSAActualEntity.md" target="_blank">ProjectManagementAndAccounting/PSAActualEntity</a>|
|[ContractId](#ContractId)||<a href="PSAActualEntity.md" target="_blank">ProjectManagementAndAccounting/PSAActualEntity</a>|
|[ProjId](#ProjId)||<a href="PSAActualEntity.md" target="_blank">ProjectManagementAndAccounting/PSAActualEntity</a>|
|[ProjAdjustRefId](#ProjAdjustRefId)||<a href="PSAActualEntity.md" target="_blank">ProjectManagementAndAccounting/PSAActualEntity</a>|
|[ProjFundingSource](#ProjFundingSource)||<a href="PSAActualEntity.md" target="_blank">ProjectManagementAndAccounting/PSAActualEntity</a>|
|[ProjTransDate](#ProjTransDate)||<a href="PSAActualEntity.md" target="_blank">ProjectManagementAndAccounting/PSAActualEntity</a>|
|[ProjTransType](#ProjTransType)||<a href="PSAActualEntity.md" target="_blank">ProjectManagementAndAccounting/PSAActualEntity</a>|
|[ProjType](#ProjType)||<a href="PSAActualEntity.md" target="_blank">ProjectManagementAndAccounting/PSAActualEntity</a>|
|[Qty](#Qty)||<a href="PSAActualEntity.md" target="_blank">ProjectManagementAndAccounting/PSAActualEntity</a>|
|[SubscriptionId](#SubscriptionId)||<a href="PSAActualEntity.md" target="_blank">ProjectManagementAndAccounting/PSAActualEntity</a>|
|[TransactionOrigin](#TransactionOrigin)||<a href="PSAActualEntity.md" target="_blank">ProjectManagementAndAccounting/PSAActualEntity</a>|
|[TransId](#TransId)||<a href="PSAActualEntity.md" target="_blank">ProjectManagementAndAccounting/PSAActualEntity</a>|
|[Voucher](#Voucher)||<a href="PSAActualEntity.md" target="_blank">ProjectManagementAndAccounting/PSAActualEntity</a>|
|[ResourceLegalEntity](#ResourceLegalEntity)||<a href="PSAActualEntity.md" target="_blank">ProjectManagementAndAccounting/PSAActualEntity</a>|
|[LedgerDimensionDisplayValue](#LedgerDimensionDisplayValue)||<a href="PSAActualEntity.md" target="_blank">ProjectManagementAndAccounting/PSAActualEntity</a>|
|[CompanyInfo_PartyNumber](#CompanyInfo_PartyNumber)||<a href="PSAActualEntity.md" target="_blank">ProjectManagementAndAccounting/PSAActualEntity</a>|
|[CompanyInfo_DataArea](#CompanyInfo_DataArea)||<a href="PSAActualEntity.md" target="_blank">ProjectManagementAndAccounting/PSAActualEntity</a>|
|[ProjFundingSource_ContractId](#ProjFundingSource_ContractId)||<a href="PSAActualEntity.md" target="_blank">ProjectManagementAndAccounting/PSAActualEntity</a>|
|[ProjFundingSource_FundingSourceId](#ProjFundingSource_FundingSourceId)||<a href="PSAActualEntity.md" target="_blank">ProjectManagementAndAccounting/PSAActualEntity</a>|
|[DefaultDimensionDisplayValue](#DefaultDimensionDisplayValue)||<a href="PSAActualEntity.md" target="_blank">ProjectManagementAndAccounting/PSAActualEntity</a>|
|[PLLaborCost](#PLLaborCost)||<a href="PSAActualEntity.md" target="_blank">ProjectManagementAndAccounting/PSAActualEntity</a>|
|[PLExpenseCost](#PLExpenseCost)||<a href="PSAActualEntity.md" target="_blank">ProjectManagementAndAccounting/PSAActualEntity</a>|
|[PLMaterialCost](#PLMaterialCost)||<a href="PSAActualEntity.md" target="_blank">ProjectManagementAndAccounting/PSAActualEntity</a>|
|[PLCostAccruedLoss](#PLCostAccruedLoss)||<a href="PSAActualEntity.md" target="_blank">ProjectManagementAndAccounting/PSAActualEntity</a>|
|[PLTotalCost](#PLTotalCost)||<a href="PSAActualEntity.md" target="_blank">ProjectManagementAndAccounting/PSAActualEntity</a>|
|[WIPLaborCost](#WIPLaborCost)||<a href="PSAActualEntity.md" target="_blank">ProjectManagementAndAccounting/PSAActualEntity</a>|
|[WIPExpenseCost](#WIPExpenseCost)||<a href="PSAActualEntity.md" target="_blank">ProjectManagementAndAccounting/PSAActualEntity</a>|
|[WIPMaterialCost](#WIPMaterialCost)||<a href="PSAActualEntity.md" target="_blank">ProjectManagementAndAccounting/PSAActualEntity</a>|
|[WIPCostAccruedLoss](#WIPCostAccruedLoss)||<a href="PSAActualEntity.md" target="_blank">ProjectManagementAndAccounting/PSAActualEntity</a>|
|[WIPTotalCost](#WIPTotalCost)||<a href="PSAActualEntity.md" target="_blank">ProjectManagementAndAccounting/PSAActualEntity</a>|
|[ConsumedLaborCost](#ConsumedLaborCost)||<a href="PSAActualEntity.md" target="_blank">ProjectManagementAndAccounting/PSAActualEntity</a>|
|[ConsumedLaborQty](#ConsumedLaborQty)||<a href="PSAActualEntity.md" target="_blank">ProjectManagementAndAccounting/PSAActualEntity</a>|
|[ConsumedExpenseCost](#ConsumedExpenseCost)||<a href="PSAActualEntity.md" target="_blank">ProjectManagementAndAccounting/PSAActualEntity</a>|
|[ConsumedMaterialCost](#ConsumedMaterialCost)||<a href="PSAActualEntity.md" target="_blank">ProjectManagementAndAccounting/PSAActualEntity</a>|
|[totalConsumption](#totalConsumption)||<a href="PSAActualEntity.md" target="_blank">ProjectManagementAndAccounting/PSAActualEntity</a>|
|[PayrollAllocation](#PayrollAllocation)||<a href="PSAActualEntity.md" target="_blank">ProjectManagementAndAccounting/PSAActualEntity</a>|
|[LaborInvoicedRevenue](#LaborInvoicedRevenue)||<a href="PSAActualEntity.md" target="_blank">ProjectManagementAndAccounting/PSAActualEntity</a>|
|[LaborInvoicedQty](#LaborInvoicedQty)||<a href="PSAActualEntity.md" target="_blank">ProjectManagementAndAccounting/PSAActualEntity</a>|
|[ExpenseInvoicedRevenue](#ExpenseInvoicedRevenue)||<a href="PSAActualEntity.md" target="_blank">ProjectManagementAndAccounting/PSAActualEntity</a>|
|[MaterialInvoicedRevenue](#MaterialInvoicedRevenue)||<a href="PSAActualEntity.md" target="_blank">ProjectManagementAndAccounting/PSAActualEntity</a>|
|[FeeInvoicedRevenue](#FeeInvoicedRevenue)||<a href="PSAActualEntity.md" target="_blank">ProjectManagementAndAccounting/PSAActualEntity</a>|
|[OnAccPrePayment](#OnAccPrePayment)||<a href="PSAActualEntity.md" target="_blank">ProjectManagementAndAccounting/PSAActualEntity</a>|
|[OnAccDeduction](#OnAccDeduction)||<a href="PSAActualEntity.md" target="_blank">ProjectManagementAndAccounting/PSAActualEntity</a>|
|[OnAccMilestone](#OnAccMilestone)||<a href="PSAActualEntity.md" target="_blank">ProjectManagementAndAccounting/PSAActualEntity</a>|
|[OnAccBegBal](#OnAccBegBal)||<a href="PSAActualEntity.md" target="_blank">ProjectManagementAndAccounting/PSAActualEntity</a>|
|[OnAccTotal](#OnAccTotal)||<a href="PSAActualEntity.md" target="_blank">ProjectManagementAndAccounting/PSAActualEntity</a>|
|[PLInvoicedRevenue](#PLInvoicedRevenue)||<a href="PSAActualEntity.md" target="_blank">ProjectManagementAndAccounting/PSAActualEntity</a>|
|[totalInvoicedRevenue](#totalInvoicedRevenue)||<a href="PSAActualEntity.md" target="_blank">ProjectManagementAndAccounting/PSAActualEntity</a>|
|[PLAccruedRevenueSalesValue](#PLAccruedRevenueSalesValue)||<a href="PSAActualEntity.md" target="_blank">ProjectManagementAndAccounting/PSAActualEntity</a>|
|[PLAccruedRevenueProduction](#PLAccruedRevenueProduction)||<a href="PSAActualEntity.md" target="_blank">ProjectManagementAndAccounting/PSAActualEntity</a>|
|[PLAccruedRevenueProfit](#PLAccruedRevenueProfit)||<a href="PSAActualEntity.md" target="_blank">ProjectManagementAndAccounting/PSAActualEntity</a>|
|[PLAccruedRevenueSubscription](#PLAccruedRevenueSubscription)||<a href="PSAActualEntity.md" target="_blank">ProjectManagementAndAccounting/PSAActualEntity</a>|
|[PLAccruedRevenueOnAcc](#PLAccruedRevenueOnAcc)||<a href="PSAActualEntity.md" target="_blank">ProjectManagementAndAccounting/PSAActualEntity</a>|
|[PLTotalAccruedRevenue](#PLTotalAccruedRevenue)||<a href="PSAActualEntity.md" target="_blank">ProjectManagementAndAccounting/PSAActualEntity</a>|
|[WIPSalesValue](#WIPSalesValue)||<a href="PSAActualEntity.md" target="_blank">ProjectManagementAndAccounting/PSAActualEntity</a>|
|[WIPProduction](#WIPProduction)||<a href="PSAActualEntity.md" target="_blank">ProjectManagementAndAccounting/PSAActualEntity</a>|
|[WIPProfit](#WIPProfit)||<a href="PSAActualEntity.md" target="_blank">ProjectManagementAndAccounting/PSAActualEntity</a>|
|[WIPSubscription](#WIPSubscription)||<a href="PSAActualEntity.md" target="_blank">ProjectManagementAndAccounting/PSAActualEntity</a>|
|[WIPSalesTotal](#WIPSalesTotal)||<a href="PSAActualEntity.md" target="_blank">ProjectManagementAndAccounting/PSAActualEntity</a>|
|[WIPInvoicedOnAccount](#WIPInvoicedOnAccount)||<a href="PSAActualEntity.md" target="_blank">ProjectManagementAndAccounting/PSAActualEntity</a>|
|[PLAccruedRevenueSalesValueLabor](#PLAccruedRevenueSalesValueLabor)||<a href="PSAActualEntity.md" target="_blank">ProjectManagementAndAccounting/PSAActualEntity</a>|
|[PLAccruedRevenueSalesValueExpense](#PLAccruedRevenueSalesValueExpense)||<a href="PSAActualEntity.md" target="_blank">ProjectManagementAndAccounting/PSAActualEntity</a>|
|[PLAccruedRevenueSalesValueMaterial](#PLAccruedRevenueSalesValueMaterial)||<a href="PSAActualEntity.md" target="_blank">ProjectManagementAndAccounting/PSAActualEntity</a>|
|[PLAccruedRevenueSalesValueFee](#PLAccruedRevenueSalesValueFee)||<a href="PSAActualEntity.md" target="_blank">ProjectManagementAndAccounting/PSAActualEntity</a>|
|[GrossWIP](#GrossWIP)||<a href="PSAActualEntity.md" target="_blank">ProjectManagementAndAccounting/PSAActualEntity</a>|
|[NetWIP](#NetWIP)||<a href="PSAActualEntity.md" target="_blank">ProjectManagementAndAccounting/PSAActualEntity</a>|
|[PLInvoicedRevenueOnAccount](#PLInvoicedRevenueOnAccount)||<a href="PSAActualEntity.md" target="_blank">ProjectManagementAndAccounting/PSAActualEntity</a>|
|[PLLaborQty](#PLLaborQty)||<a href="PSAActualEntity.md" target="_blank">ProjectManagementAndAccounting/PSAActualEntity</a>|
|[Resource](#Resource)||<a href="PSAActualEntity.md" target="_blank">ProjectManagementAndAccounting/PSAActualEntity</a>|
|[ResourceCategory](#ResourceCategory)||<a href="PSAActualEntity.md" target="_blank">ProjectManagementAndAccounting/PSAActualEntity</a>|
|[PLLaborQtyWithoutNoNeverLedger](#PLLaborQtyWithoutNoNeverLedger)||<a href="PSAActualEntity.md" target="_blank">ProjectManagementAndAccounting/PSAActualEntity</a>|
|[PLLaborCostWithoutNoNeverLedger](#PLLaborCostWithoutNoNeverLedger)||<a href="PSAActualEntity.md" target="_blank">ProjectManagementAndAccounting/PSAActualEntity</a>|
|[ConsumedLaborCostWithoutNoNeverLedger](#ConsumedLaborCostWithoutNoNeverLedger)||<a href="PSAActualEntity.md" target="_blank">ProjectManagementAndAccounting/PSAActualEntity</a>|
|[ConsumedLaborQtyWithoutNoNeverLedger](#ConsumedLaborQtyWithoutNoNeverLedger)||<a href="PSAActualEntity.md" target="_blank">ProjectManagementAndAccounting/PSAActualEntity</a>|
|[PLMaterialCostWithoutNeverLedger](#PLMaterialCostWithoutNeverLedger)||<a href="PSAActualEntity.md" target="_blank">ProjectManagementAndAccounting/PSAActualEntity</a>|
|[ConsumedMaterialCostWithoutNeverLedger](#ConsumedMaterialCostWithoutNeverLedger)||<a href="PSAActualEntity.md" target="_blank">ProjectManagementAndAccounting/PSAActualEntity</a>|
|[ResourceId](#ResourceId)||<a href="PSAActualEntity.md" target="_blank">ProjectManagementAndAccounting/PSAActualEntity</a>|
|[ResourceCompanyId](#ResourceCompanyId)||<a href="PSAActualEntity.md" target="_blank">ProjectManagementAndAccounting/PSAActualEntity</a>|
|[Relationship_DefaultDimensionDimensionSetRelationshipId](#Relationship_DefaultDimensionDimensionSetRelationshipId)||<a href="PSAActualEntity.md" target="_blank">ProjectManagementAndAccounting/PSAActualEntity</a>|
|[BackingTable_ProjTransPostingRelationshipId](#BackingTable_ProjTransPostingRelationshipId)||<a href="PSAActualEntity.md" target="_blank">ProjectManagementAndAccounting/PSAActualEntity</a>|
|[Relationship_PrimaryCompanyContextRelationshipId](#Relationship_PrimaryCompanyContextRelationshipId)||<a href="PSAActualEntity.md" target="_blank">ProjectManagementAndAccounting/PSAActualEntity</a>|

### <a href=#ActivityNumber name="ActivityNumber">ActivityNumber</a>

First included in: ProjectManagementAndAccounting/PSAActualEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ActivityNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AmountMst name="AmountMst">AmountMst</a>

First included in: ProjectManagementAndAccounting/PSAActualEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AmountMst attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CategoryId name="CategoryId">CategoryId</a>

First included in: ProjectManagementAndAccounting/PSAActualEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CategoryId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#costSales name="costSales">costSales</a>

First included in: ProjectManagementAndAccounting/PSAActualEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the costSales attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DefaultDimension name="DefaultDimension">DefaultDimension</a>

First included in: ProjectManagementAndAccounting/PSAActualEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultDimension attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#EmplItemId name="EmplItemId">EmplItemId</a>

First included in: ProjectManagementAndAccounting/PSAActualEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EmplItemId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InventTransId name="InventTransId">InventTransId</a>

First included in: ProjectManagementAndAccounting/PSAActualEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InventTransId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LedgerDimension name="LedgerDimension">LedgerDimension</a>

First included in: ProjectManagementAndAccounting/PSAActualEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LedgerDimension attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LedgerOrigin name="LedgerOrigin">LedgerOrigin</a>

First included in: ProjectManagementAndAccounting/PSAActualEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LedgerOrigin attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LedgerTransDate name="LedgerTransDate">LedgerTransDate</a>

First included in: ProjectManagementAndAccounting/PSAActualEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LedgerTransDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PaymentDate name="PaymentDate">PaymentDate</a>

First included in: ProjectManagementAndAccounting/PSAActualEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PaymentDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PaymentStatus name="PaymentStatus">PaymentStatus</a>

First included in: ProjectManagementAndAccounting/PSAActualEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PaymentStatus attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PostingType name="PostingType">PostingType</a>

First included in: ProjectManagementAndAccounting/PSAActualEntity (this entity)  

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

### <a href=#ContractId name="ContractId">ContractId</a>

First included in: ProjectManagementAndAccounting/PSAActualEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ContractId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProjId name="ProjId">ProjId</a>

First included in: ProjectManagementAndAccounting/PSAActualEntity (this entity)  

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

### <a href=#ProjAdjustRefId name="ProjAdjustRefId">ProjAdjustRefId</a>

First included in: ProjectManagementAndAccounting/PSAActualEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProjAdjustRefId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProjFundingSource name="ProjFundingSource">ProjFundingSource</a>

First included in: ProjectManagementAndAccounting/PSAActualEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProjFundingSource attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProjTransDate name="ProjTransDate">ProjTransDate</a>

First included in: ProjectManagementAndAccounting/PSAActualEntity (this entity)  

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

First included in: ProjectManagementAndAccounting/PSAActualEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProjTransType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProjType name="ProjType">ProjType</a>

First included in: ProjectManagementAndAccounting/PSAActualEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProjType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Qty name="Qty">Qty</a>

First included in: ProjectManagementAndAccounting/PSAActualEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Qty attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SubscriptionId name="SubscriptionId">SubscriptionId</a>

First included in: ProjectManagementAndAccounting/PSAActualEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SubscriptionId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TransactionOrigin name="TransactionOrigin">TransactionOrigin</a>

First included in: ProjectManagementAndAccounting/PSAActualEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TransactionOrigin attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TransId name="TransId">TransId</a>

First included in: ProjectManagementAndAccounting/PSAActualEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TransId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Voucher name="Voucher">Voucher</a>

First included in: ProjectManagementAndAccounting/PSAActualEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Voucher attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ResourceLegalEntity name="ResourceLegalEntity">ResourceLegalEntity</a>

First included in: ProjectManagementAndAccounting/PSAActualEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ResourceLegalEntity attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LedgerDimensionDisplayValue name="LedgerDimensionDisplayValue">LedgerDimensionDisplayValue</a>

First included in: ProjectManagementAndAccounting/PSAActualEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LedgerDimensionDisplayValue attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CompanyInfo_PartyNumber name="CompanyInfo_PartyNumber">CompanyInfo_PartyNumber</a>

First included in: ProjectManagementAndAccounting/PSAActualEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CompanyInfo_PartyNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CompanyInfo_DataArea name="CompanyInfo_DataArea">CompanyInfo_DataArea</a>

First included in: ProjectManagementAndAccounting/PSAActualEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CompanyInfo_DataArea attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProjFundingSource_ContractId name="ProjFundingSource_ContractId">ProjFundingSource_ContractId</a>

First included in: ProjectManagementAndAccounting/PSAActualEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProjFundingSource_ContractId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProjFundingSource_FundingSourceId name="ProjFundingSource_FundingSourceId">ProjFundingSource_FundingSourceId</a>

First included in: ProjectManagementAndAccounting/PSAActualEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProjFundingSource_FundingSourceId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DefaultDimensionDisplayValue name="DefaultDimensionDisplayValue">DefaultDimensionDisplayValue</a>

First included in: ProjectManagementAndAccounting/PSAActualEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultDimensionDisplayValue attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PLLaborCost name="PLLaborCost">PLLaborCost</a>

First included in: ProjectManagementAndAccounting/PSAActualEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PLLaborCost attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PLExpenseCost name="PLExpenseCost">PLExpenseCost</a>

First included in: ProjectManagementAndAccounting/PSAActualEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PLExpenseCost attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PLMaterialCost name="PLMaterialCost">PLMaterialCost</a>

First included in: ProjectManagementAndAccounting/PSAActualEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PLMaterialCost attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PLCostAccruedLoss name="PLCostAccruedLoss">PLCostAccruedLoss</a>

First included in: ProjectManagementAndAccounting/PSAActualEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PLCostAccruedLoss attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PLTotalCost name="PLTotalCost">PLTotalCost</a>

First included in: ProjectManagementAndAccounting/PSAActualEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PLTotalCost attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WIPLaborCost name="WIPLaborCost">WIPLaborCost</a>

First included in: ProjectManagementAndAccounting/PSAActualEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WIPLaborCost attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WIPExpenseCost name="WIPExpenseCost">WIPExpenseCost</a>

First included in: ProjectManagementAndAccounting/PSAActualEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WIPExpenseCost attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WIPMaterialCost name="WIPMaterialCost">WIPMaterialCost</a>

First included in: ProjectManagementAndAccounting/PSAActualEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WIPMaterialCost attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WIPCostAccruedLoss name="WIPCostAccruedLoss">WIPCostAccruedLoss</a>

First included in: ProjectManagementAndAccounting/PSAActualEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WIPCostAccruedLoss attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WIPTotalCost name="WIPTotalCost">WIPTotalCost</a>

First included in: ProjectManagementAndAccounting/PSAActualEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WIPTotalCost attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ConsumedLaborCost name="ConsumedLaborCost">ConsumedLaborCost</a>

First included in: ProjectManagementAndAccounting/PSAActualEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ConsumedLaborCost attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ConsumedLaborQty name="ConsumedLaborQty">ConsumedLaborQty</a>

First included in: ProjectManagementAndAccounting/PSAActualEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ConsumedLaborQty attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ConsumedExpenseCost name="ConsumedExpenseCost">ConsumedExpenseCost</a>

First included in: ProjectManagementAndAccounting/PSAActualEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ConsumedExpenseCost attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ConsumedMaterialCost name="ConsumedMaterialCost">ConsumedMaterialCost</a>

First included in: ProjectManagementAndAccounting/PSAActualEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ConsumedMaterialCost attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#totalConsumption name="totalConsumption">totalConsumption</a>

First included in: ProjectManagementAndAccounting/PSAActualEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the totalConsumption attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PayrollAllocation name="PayrollAllocation">PayrollAllocation</a>

First included in: ProjectManagementAndAccounting/PSAActualEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PayrollAllocation attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LaborInvoicedRevenue name="LaborInvoicedRevenue">LaborInvoicedRevenue</a>

First included in: ProjectManagementAndAccounting/PSAActualEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LaborInvoicedRevenue attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LaborInvoicedQty name="LaborInvoicedQty">LaborInvoicedQty</a>

First included in: ProjectManagementAndAccounting/PSAActualEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LaborInvoicedQty attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ExpenseInvoicedRevenue name="ExpenseInvoicedRevenue">ExpenseInvoicedRevenue</a>

First included in: ProjectManagementAndAccounting/PSAActualEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ExpenseInvoicedRevenue attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MaterialInvoicedRevenue name="MaterialInvoicedRevenue">MaterialInvoicedRevenue</a>

First included in: ProjectManagementAndAccounting/PSAActualEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MaterialInvoicedRevenue attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FeeInvoicedRevenue name="FeeInvoicedRevenue">FeeInvoicedRevenue</a>

First included in: ProjectManagementAndAccounting/PSAActualEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FeeInvoicedRevenue attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#OnAccPrePayment name="OnAccPrePayment">OnAccPrePayment</a>

First included in: ProjectManagementAndAccounting/PSAActualEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OnAccPrePayment attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#OnAccDeduction name="OnAccDeduction">OnAccDeduction</a>

First included in: ProjectManagementAndAccounting/PSAActualEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OnAccDeduction attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#OnAccMilestone name="OnAccMilestone">OnAccMilestone</a>

First included in: ProjectManagementAndAccounting/PSAActualEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OnAccMilestone attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#OnAccBegBal name="OnAccBegBal">OnAccBegBal</a>

First included in: ProjectManagementAndAccounting/PSAActualEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OnAccBegBal attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#OnAccTotal name="OnAccTotal">OnAccTotal</a>

First included in: ProjectManagementAndAccounting/PSAActualEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OnAccTotal attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PLInvoicedRevenue name="PLInvoicedRevenue">PLInvoicedRevenue</a>

First included in: ProjectManagementAndAccounting/PSAActualEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PLInvoicedRevenue attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#totalInvoicedRevenue name="totalInvoicedRevenue">totalInvoicedRevenue</a>

First included in: ProjectManagementAndAccounting/PSAActualEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the totalInvoicedRevenue attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PLAccruedRevenueSalesValue name="PLAccruedRevenueSalesValue">PLAccruedRevenueSalesValue</a>

First included in: ProjectManagementAndAccounting/PSAActualEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PLAccruedRevenueSalesValue attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PLAccruedRevenueProduction name="PLAccruedRevenueProduction">PLAccruedRevenueProduction</a>

First included in: ProjectManagementAndAccounting/PSAActualEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PLAccruedRevenueProduction attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PLAccruedRevenueProfit name="PLAccruedRevenueProfit">PLAccruedRevenueProfit</a>

First included in: ProjectManagementAndAccounting/PSAActualEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PLAccruedRevenueProfit attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PLAccruedRevenueSubscription name="PLAccruedRevenueSubscription">PLAccruedRevenueSubscription</a>

First included in: ProjectManagementAndAccounting/PSAActualEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PLAccruedRevenueSubscription attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PLAccruedRevenueOnAcc name="PLAccruedRevenueOnAcc">PLAccruedRevenueOnAcc</a>

First included in: ProjectManagementAndAccounting/PSAActualEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PLAccruedRevenueOnAcc attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PLTotalAccruedRevenue name="PLTotalAccruedRevenue">PLTotalAccruedRevenue</a>

First included in: ProjectManagementAndAccounting/PSAActualEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PLTotalAccruedRevenue attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WIPSalesValue name="WIPSalesValue">WIPSalesValue</a>

First included in: ProjectManagementAndAccounting/PSAActualEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WIPSalesValue attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WIPProduction name="WIPProduction">WIPProduction</a>

First included in: ProjectManagementAndAccounting/PSAActualEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WIPProduction attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WIPProfit name="WIPProfit">WIPProfit</a>

First included in: ProjectManagementAndAccounting/PSAActualEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WIPProfit attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WIPSubscription name="WIPSubscription">WIPSubscription</a>

First included in: ProjectManagementAndAccounting/PSAActualEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WIPSubscription attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WIPSalesTotal name="WIPSalesTotal">WIPSalesTotal</a>

First included in: ProjectManagementAndAccounting/PSAActualEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WIPSalesTotal attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WIPInvoicedOnAccount name="WIPInvoicedOnAccount">WIPInvoicedOnAccount</a>

First included in: ProjectManagementAndAccounting/PSAActualEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WIPInvoicedOnAccount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PLAccruedRevenueSalesValueLabor name="PLAccruedRevenueSalesValueLabor">PLAccruedRevenueSalesValueLabor</a>

First included in: ProjectManagementAndAccounting/PSAActualEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PLAccruedRevenueSalesValueLabor attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PLAccruedRevenueSalesValueExpense name="PLAccruedRevenueSalesValueExpense">PLAccruedRevenueSalesValueExpense</a>

First included in: ProjectManagementAndAccounting/PSAActualEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PLAccruedRevenueSalesValueExpense attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PLAccruedRevenueSalesValueMaterial name="PLAccruedRevenueSalesValueMaterial">PLAccruedRevenueSalesValueMaterial</a>

First included in: ProjectManagementAndAccounting/PSAActualEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PLAccruedRevenueSalesValueMaterial attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PLAccruedRevenueSalesValueFee name="PLAccruedRevenueSalesValueFee">PLAccruedRevenueSalesValueFee</a>

First included in: ProjectManagementAndAccounting/PSAActualEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PLAccruedRevenueSalesValueFee attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#GrossWIP name="GrossWIP">GrossWIP</a>

First included in: ProjectManagementAndAccounting/PSAActualEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the GrossWIP attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#NetWIP name="NetWIP">NetWIP</a>

First included in: ProjectManagementAndAccounting/PSAActualEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the NetWIP attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PLInvoicedRevenueOnAccount name="PLInvoicedRevenueOnAccount">PLInvoicedRevenueOnAccount</a>

First included in: ProjectManagementAndAccounting/PSAActualEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PLInvoicedRevenueOnAccount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PLLaborQty name="PLLaborQty">PLLaborQty</a>

First included in: ProjectManagementAndAccounting/PSAActualEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PLLaborQty attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Resource name="Resource">Resource</a>

First included in: ProjectManagementAndAccounting/PSAActualEntity (this entity)  

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

### <a href=#ResourceCategory name="ResourceCategory">ResourceCategory</a>

First included in: ProjectManagementAndAccounting/PSAActualEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ResourceCategory attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PLLaborQtyWithoutNoNeverLedger name="PLLaborQtyWithoutNoNeverLedger">PLLaborQtyWithoutNoNeverLedger</a>

First included in: ProjectManagementAndAccounting/PSAActualEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PLLaborQtyWithoutNoNeverLedger attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PLLaborCostWithoutNoNeverLedger name="PLLaborCostWithoutNoNeverLedger">PLLaborCostWithoutNoNeverLedger</a>

First included in: ProjectManagementAndAccounting/PSAActualEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PLLaborCostWithoutNoNeverLedger attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ConsumedLaborCostWithoutNoNeverLedger name="ConsumedLaborCostWithoutNoNeverLedger">ConsumedLaborCostWithoutNoNeverLedger</a>

First included in: ProjectManagementAndAccounting/PSAActualEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ConsumedLaborCostWithoutNoNeverLedger attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ConsumedLaborQtyWithoutNoNeverLedger name="ConsumedLaborQtyWithoutNoNeverLedger">ConsumedLaborQtyWithoutNoNeverLedger</a>

First included in: ProjectManagementAndAccounting/PSAActualEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ConsumedLaborQtyWithoutNoNeverLedger attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PLMaterialCostWithoutNeverLedger name="PLMaterialCostWithoutNeverLedger">PLMaterialCostWithoutNeverLedger</a>

First included in: ProjectManagementAndAccounting/PSAActualEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PLMaterialCostWithoutNeverLedger attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ConsumedMaterialCostWithoutNeverLedger name="ConsumedMaterialCostWithoutNeverLedger">ConsumedMaterialCostWithoutNeverLedger</a>

First included in: ProjectManagementAndAccounting/PSAActualEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ConsumedMaterialCostWithoutNeverLedger attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ResourceId name="ResourceId">ResourceId</a>

First included in: ProjectManagementAndAccounting/PSAActualEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ResourceId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ResourceCompanyId name="ResourceCompanyId">ResourceCompanyId</a>

First included in: ProjectManagementAndAccounting/PSAActualEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ResourceCompanyId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_DefaultDimensionDimensionSetRelationshipId name="Relationship_DefaultDimensionDimensionSetRelationshipId">Relationship_DefaultDimensionDimensionSetRelationshipId</a>

First included in: ProjectManagementAndAccounting/PSAActualEntity (this entity)  

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

### <a href=#BackingTable_ProjTransPostingRelationshipId name="BackingTable_ProjTransPostingRelationshipId">BackingTable_ProjTransPostingRelationshipId</a>

First included in: ProjectManagementAndAccounting/PSAActualEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_ProjTransPostingRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/ProfessionalServices/ProjectManagementAndAccounting/Transaction/ProjTransPosting.md" target="_blank">/core/operationsCommon/Tables/ProfessionalServices/ProjectManagementAndAccounting/Transaction/ProjTransPosting.cdm.json/ProjTransPosting</a></td><td><a href="../../../Tables/ProfessionalServices/ProjectManagementAndAccounting/Transaction/ProjTransPosting.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PrimaryCompanyContextRelationshipId name="Relationship_PrimaryCompanyContextRelationshipId">Relationship_PrimaryCompanyContextRelationshipId</a>

First included in: ProjectManagementAndAccounting/PSAActualEntity (this entity)  

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
