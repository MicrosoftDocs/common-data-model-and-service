---
title: ProjControlPeriodTableColumn in Transaction - Common Data Model | Microsoft Docs
description: undefined
author: llawwaii

ms.reviewer: deonhe
ms.topic: article
ms.date: 8/7/2020
ms.author: weiluo
---

# Control period estimate in Transaction(ProjControlPeriodTableColumn)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Tables/ProfessionalServices/ProjectManagementAndAccounting/Transaction/ProjControlPeriodTableColumn.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[ProjControlPeriodTableColumn/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.1"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Control period estimate</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="ProjControlPeriodTableColumn.md" target="_blank">Transaction/ProjControlPeriodTableColumn</a>|
|[ConsumCostHourRate](#ConsumCostHourRate)||<a href="ProjControlPeriodTableColumn.md" target="_blank">Transaction/ProjControlPeriodTableColumn</a>|
|[ConsumExpCapital](#ConsumExpCapital)||<a href="ProjControlPeriodTableColumn.md" target="_blank">Transaction/ProjControlPeriodTableColumn</a>|
|[ConsumExpConsum](#ConsumExpConsum)||<a href="ProjControlPeriodTableColumn.md" target="_blank">Transaction/ProjControlPeriodTableColumn</a>|
|[ConsumExpNotCapital](#ConsumExpNotCapital)||<a href="ProjControlPeriodTableColumn.md" target="_blank">Transaction/ProjControlPeriodTableColumn</a>|
|[ConsumHourCapital](#ConsumHourCapital)||<a href="ProjControlPeriodTableColumn.md" target="_blank">Transaction/ProjControlPeriodTableColumn</a>|
|[ConsumHourConsum](#ConsumHourConsum)||<a href="ProjControlPeriodTableColumn.md" target="_blank">Transaction/ProjControlPeriodTableColumn</a>|
|[ConsumHourNotCapital](#ConsumHourNotCapital)||<a href="ProjControlPeriodTableColumn.md" target="_blank">Transaction/ProjControlPeriodTableColumn</a>|
|[ConsumItemCapital](#ConsumItemCapital)||<a href="ProjControlPeriodTableColumn.md" target="_blank">Transaction/ProjControlPeriodTableColumn</a>|
|[ConsumItemConsum](#ConsumItemConsum)||<a href="ProjControlPeriodTableColumn.md" target="_blank">Transaction/ProjControlPeriodTableColumn</a>|
|[ConsumItemConsumNeverLedger](#ConsumItemConsumNeverLedger)||<a href="ProjControlPeriodTableColumn.md" target="_blank">Transaction/ProjControlPeriodTableColumn</a>|
|[ConsumItemNotCapital](#ConsumItemNotCapital)||<a href="ProjControlPeriodTableColumn.md" target="_blank">Transaction/ProjControlPeriodTableColumn</a>|
|[ConsumTotalCapital](#ConsumTotalCapital)||<a href="ProjControlPeriodTableColumn.md" target="_blank">Transaction/ProjControlPeriodTableColumn</a>|
|[ConsumTotalConsum](#ConsumTotalConsum)||<a href="ProjControlPeriodTableColumn.md" target="_blank">Transaction/ProjControlPeriodTableColumn</a>|
|[ConsumTotalNotCapital](#ConsumTotalNotCapital)||<a href="ProjControlPeriodTableColumn.md" target="_blank">Transaction/ProjControlPeriodTableColumn</a>|
|[ControlId](#ControlId)||<a href="ProjControlPeriodTableColumn.md" target="_blank">Transaction/ProjControlPeriodTableColumn</a>|
|[EstimateColumn](#EstimateColumn)||<a href="ProjControlPeriodTableColumn.md" target="_blank">Transaction/ProjControlPeriodTableColumn</a>|
|[GeneralHourCostHourRate](#GeneralHourCostHourRate)||<a href="ProjControlPeriodTableColumn.md" target="_blank">Transaction/ProjControlPeriodTableColumn</a>|
|[GeneralHourGrossMarginHourRate](#GeneralHourGrossMarginHourRate)||<a href="ProjControlPeriodTableColumn.md" target="_blank">Transaction/ProjControlPeriodTableColumn</a>|
|[GeneralHourQtyCapitalized](#GeneralHourQtyCapitalized)||<a href="ProjControlPeriodTableColumn.md" target="_blank">Transaction/ProjControlPeriodTableColumn</a>|
|[GeneralHourRevenue](#GeneralHourRevenue)||<a href="ProjControlPeriodTableColumn.md" target="_blank">Transaction/ProjControlPeriodTableColumn</a>|
|[GeneralHoursQty](#GeneralHoursQty)||<a href="ProjControlPeriodTableColumn.md" target="_blank">Transaction/ProjControlPeriodTableColumn</a>|
|[GeneralHourValuaddedHourRate](#GeneralHourValuaddedHourRate)||<a href="ProjControlPeriodTableColumn.md" target="_blank">Transaction/ProjControlPeriodTableColumn</a>|
|[PeriodFrom](#PeriodFrom)||<a href="ProjControlPeriodTableColumn.md" target="_blank">Transaction/ProjControlPeriodTableColumn</a>|
|[PLAccRevAccOnAcc](#PLAccRevAccOnAcc)||<a href="ProjControlPeriodTableColumn.md" target="_blank">Transaction/ProjControlPeriodTableColumn</a>|
|[PLAccRevProduction](#PLAccRevProduction)||<a href="ProjControlPeriodTableColumn.md" target="_blank">Transaction/ProjControlPeriodTableColumn</a>|
|[PLAccRevProfit](#PLAccRevProfit)||<a href="ProjControlPeriodTableColumn.md" target="_blank">Transaction/ProjControlPeriodTableColumn</a>|
|[PLAccRevSalesValue](#PLAccRevSalesValue)||<a href="ProjControlPeriodTableColumn.md" target="_blank">Transaction/ProjControlPeriodTableColumn</a>|
|[PLAccRevTotalAccRev](#PLAccRevTotalAccRev)||<a href="ProjControlPeriodTableColumn.md" target="_blank">Transaction/ProjControlPeriodTableColumn</a>|
|[PLCostAccCost](#PLCostAccCost)||<a href="ProjControlPeriodTableColumn.md" target="_blank">Transaction/ProjControlPeriodTableColumn</a>|
|[PLCostExpenses](#PLCostExpenses)||<a href="ProjControlPeriodTableColumn.md" target="_blank">Transaction/ProjControlPeriodTableColumn</a>|
|[PLCostHour](#PLCostHour)||<a href="ProjControlPeriodTableColumn.md" target="_blank">Transaction/ProjControlPeriodTableColumn</a>|
|[PLCostItem](#PLCostItem)||<a href="ProjControlPeriodTableColumn.md" target="_blank">Transaction/ProjControlPeriodTableColumn</a>|
|[PLCostTotalCost](#PLCostTotalCost)||<a href="ProjControlPeriodTableColumn.md" target="_blank">Transaction/ProjControlPeriodTableColumn</a>|
|[PLInvRevInvoiceOnAcc](#PLInvRevInvoiceOnAcc)||<a href="ProjControlPeriodTableColumn.md" target="_blank">Transaction/ProjControlPeriodTableColumn</a>|
|[PLTotalGrossMargin](#PLTotalGrossMargin)||<a href="ProjControlPeriodTableColumn.md" target="_blank">Transaction/ProjControlPeriodTableColumn</a>|
|[PLTotalRevenue](#PLTotalRevenue)||<a href="ProjControlPeriodTableColumn.md" target="_blank">Transaction/ProjControlPeriodTableColumn</a>|
|[PLTotalValueAddedAmount](#PLTotalValueAddedAmount)||<a href="ProjControlPeriodTableColumn.md" target="_blank">Transaction/ProjControlPeriodTableColumn</a>|
|[ProjId](#ProjId)||<a href="ProjControlPeriodTableColumn.md" target="_blank">Transaction/ProjControlPeriodTableColumn</a>|
|[Version](#Version)||<a href="ProjControlPeriodTableColumn.md" target="_blank">Transaction/ProjControlPeriodTableColumn</a>|
|[WIPCostpriceAccruedCost](#WIPCostpriceAccruedCost)||<a href="ProjControlPeriodTableColumn.md" target="_blank">Transaction/ProjControlPeriodTableColumn</a>|
|[WIPCostpriceExp](#WIPCostpriceExp)||<a href="ProjControlPeriodTableColumn.md" target="_blank">Transaction/ProjControlPeriodTableColumn</a>|
|[WIPCostpriceHour](#WIPCostpriceHour)||<a href="ProjControlPeriodTableColumn.md" target="_blank">Transaction/ProjControlPeriodTableColumn</a>|
|[WIPCostpriceItem](#WIPCostpriceItem)||<a href="ProjControlPeriodTableColumn.md" target="_blank">Transaction/ProjControlPeriodTableColumn</a>|
|[WIPCostpriceTotal](#WIPCostpriceTotal)||<a href="ProjControlPeriodTableColumn.md" target="_blank">Transaction/ProjControlPeriodTableColumn</a>|
|[WIPInvoiceOnAcc](#WIPInvoiceOnAcc)||<a href="ProjControlPeriodTableColumn.md" target="_blank">Transaction/ProjControlPeriodTableColumn</a>|
|[WIPSalespriceProduction](#WIPSalespriceProduction)||<a href="ProjControlPeriodTableColumn.md" target="_blank">Transaction/ProjControlPeriodTableColumn</a>|
|[WIPSalesPriceProfit](#WIPSalesPriceProfit)||<a href="ProjControlPeriodTableColumn.md" target="_blank">Transaction/ProjControlPeriodTableColumn</a>|
|[WIPSalesPriceSalesValue](#WIPSalesPriceSalesValue)||<a href="ProjControlPeriodTableColumn.md" target="_blank">Transaction/ProjControlPeriodTableColumn</a>|
|[WIPSalespriceTotal](#WIPSalespriceTotal)||<a href="ProjControlPeriodTableColumn.md" target="_blank">Transaction/ProjControlPeriodTableColumn</a>|
|[WIPTotalGrossWIP](#WIPTotalGrossWIP)||<a href="ProjControlPeriodTableColumn.md" target="_blank">Transaction/ProjControlPeriodTableColumn</a>|
|[WIPTotalNetWIP](#WIPTotalNetWIP)||<a href="ProjControlPeriodTableColumn.md" target="_blank">Transaction/ProjControlPeriodTableColumn</a>|
|[DataAreaId](#DataAreaId)||<a href="ProjControlPeriodTableColumn.md" target="_blank">Transaction/ProjControlPeriodTableColumn</a>|
|[Relationship_ProjControlPeriodTableRelationshipId](#Relationship_ProjControlPeriodTableRelationshipId)||<a href="ProjControlPeriodTableColumn.md" target="_blank">Transaction/ProjControlPeriodTableColumn</a>|
|[Relationship_CompanyRelationshipId](#Relationship_CompanyRelationshipId)||<a href="ProjControlPeriodTableColumn.md" target="_blank">Transaction/ProjControlPeriodTableColumn</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: Transaction/ProjControlPeriodTableColumn (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[ProjControlPeriodTableColumn/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#ConsumCostHourRate name="ConsumCostHourRate">ConsumCostHourRate</a>

First included in: Transaction/ProjControlPeriodTableColumn (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ConsumCostHourRate attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#ConsumExpCapital name="ConsumExpCapital">ConsumExpCapital</a>

First included in: Transaction/ProjControlPeriodTableColumn (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ConsumExpCapital attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.readOnly**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#ConsumExpConsum name="ConsumExpConsum">ConsumExpConsum</a>

First included in: Transaction/ProjControlPeriodTableColumn (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ConsumExpConsum attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.readOnly**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#ConsumExpNotCapital name="ConsumExpNotCapital">ConsumExpNotCapital</a>

First included in: Transaction/ProjControlPeriodTableColumn (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ConsumExpNotCapital attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.readOnly**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#ConsumHourCapital name="ConsumHourCapital">ConsumHourCapital</a>

First included in: Transaction/ProjControlPeriodTableColumn (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ConsumHourCapital attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.readOnly**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#ConsumHourConsum name="ConsumHourConsum">ConsumHourConsum</a>

First included in: Transaction/ProjControlPeriodTableColumn (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ConsumHourConsum attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.readOnly**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#ConsumHourNotCapital name="ConsumHourNotCapital">ConsumHourNotCapital</a>

First included in: Transaction/ProjControlPeriodTableColumn (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ConsumHourNotCapital attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.readOnly**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#ConsumItemCapital name="ConsumItemCapital">ConsumItemCapital</a>

First included in: Transaction/ProjControlPeriodTableColumn (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ConsumItemCapital attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.readOnly**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#ConsumItemConsum name="ConsumItemConsum">ConsumItemConsum</a>

First included in: Transaction/ProjControlPeriodTableColumn (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ConsumItemConsum attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.readOnly**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#ConsumItemConsumNeverLedger name="ConsumItemConsumNeverLedger">ConsumItemConsumNeverLedger</a>

First included in: Transaction/ProjControlPeriodTableColumn (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ConsumItemConsumNeverLedger attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.readOnly**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#ConsumItemNotCapital name="ConsumItemNotCapital">ConsumItemNotCapital</a>

First included in: Transaction/ProjControlPeriodTableColumn (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ConsumItemNotCapital attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.readOnly**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#ConsumTotalCapital name="ConsumTotalCapital">ConsumTotalCapital</a>

First included in: Transaction/ProjControlPeriodTableColumn (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ConsumTotalCapital attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#ConsumTotalConsum name="ConsumTotalConsum">ConsumTotalConsum</a>

First included in: Transaction/ProjControlPeriodTableColumn (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ConsumTotalConsum attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.readOnly**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#ConsumTotalNotCapital name="ConsumTotalNotCapital">ConsumTotalNotCapital</a>

First included in: Transaction/ProjControlPeriodTableColumn (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ConsumTotalNotCapital attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.readOnly**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#ControlId name="ControlId">ControlId</a>

First included in: Transaction/ProjControlPeriodTableColumn (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ControlId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.readOnly**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#EstimateColumn name="EstimateColumn">EstimateColumn</a>

First included in: Transaction/ProjControlPeriodTableColumn (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EstimateColumn attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.readOnly**  
**is.dataFormat.integer**  
</details>

### <a href=#GeneralHourCostHourRate name="GeneralHourCostHourRate">GeneralHourCostHourRate</a>

First included in: Transaction/ProjControlPeriodTableColumn (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the GeneralHourCostHourRate attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#GeneralHourGrossMarginHourRate name="GeneralHourGrossMarginHourRate">GeneralHourGrossMarginHourRate</a>

First included in: Transaction/ProjControlPeriodTableColumn (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the GeneralHourGrossMarginHourRate attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#GeneralHourQtyCapitalized name="GeneralHourQtyCapitalized">GeneralHourQtyCapitalized</a>

First included in: Transaction/ProjControlPeriodTableColumn (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Hour - quantity</td></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the GeneralHourQtyCapitalized attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Hour - quantity</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#GeneralHourRevenue name="GeneralHourRevenue">GeneralHourRevenue</a>

First included in: Transaction/ProjControlPeriodTableColumn (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the GeneralHourRevenue attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#GeneralHoursQty name="GeneralHoursQty">GeneralHoursQty</a>

First included in: Transaction/ProjControlPeriodTableColumn (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Hour - quantity</td></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the GeneralHoursQty attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.readOnly**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Hour - quantity</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#GeneralHourValuaddedHourRate name="GeneralHourValuaddedHourRate">GeneralHourValuaddedHourRate</a>

First included in: Transaction/ProjControlPeriodTableColumn (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the GeneralHourValuaddedHourRate attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#PeriodFrom name="PeriodFrom">PeriodFrom</a>

First included in: Transaction/ProjControlPeriodTableColumn (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PeriodFrom attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.readOnly**  
**is.dataFormat.date**  
</details>

### <a href=#PLAccRevAccOnAcc name="PLAccRevAccOnAcc">PLAccRevAccOnAcc</a>

First included in: Transaction/ProjControlPeriodTableColumn (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Accrued revenue - on-account</td></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PLAccRevAccOnAcc attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.readOnly**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Accrued revenue - on-account</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#PLAccRevProduction name="PLAccRevProduction">PLAccRevProduction</a>

First included in: Transaction/ProjControlPeriodTableColumn (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PLAccRevProduction attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.readOnly**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#PLAccRevProfit name="PLAccRevProfit">PLAccRevProfit</a>

First included in: Transaction/ProjControlPeriodTableColumn (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PLAccRevProfit attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#PLAccRevSalesValue name="PLAccRevSalesValue">PLAccRevSalesValue</a>

First included in: Transaction/ProjControlPeriodTableColumn (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PLAccRevSalesValue attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#PLAccRevTotalAccRev name="PLAccRevTotalAccRev">PLAccRevTotalAccRev</a>

First included in: Transaction/ProjControlPeriodTableColumn (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PLAccRevTotalAccRev attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#PLCostAccCost name="PLCostAccCost">PLCostAccCost</a>

First included in: Transaction/ProjControlPeriodTableColumn (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PLCostAccCost attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#PLCostExpenses name="PLCostExpenses">PLCostExpenses</a>

First included in: Transaction/ProjControlPeriodTableColumn (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PLCostExpenses attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#PLCostHour name="PLCostHour">PLCostHour</a>

First included in: Transaction/ProjControlPeriodTableColumn (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Cost - hour</td></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PLCostHour attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.readOnly**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Cost - hour</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#PLCostItem name="PLCostItem">PLCostItem</a>

First included in: Transaction/ProjControlPeriodTableColumn (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PLCostItem attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#PLCostTotalCost name="PLCostTotalCost">PLCostTotalCost</a>

First included in: Transaction/ProjControlPeriodTableColumn (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PLCostTotalCost attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#PLInvRevInvoiceOnAcc name="PLInvRevInvoiceOnAcc">PLInvRevInvoiceOnAcc</a>

First included in: Transaction/ProjControlPeriodTableColumn (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Invoiced revenue - on-account</td></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PLInvRevInvoiceOnAcc attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.readOnly**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Invoiced revenue - on-account</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#PLTotalGrossMargin name="PLTotalGrossMargin">PLTotalGrossMargin</a>

First included in: Transaction/ProjControlPeriodTableColumn (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PLTotalGrossMargin attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#PLTotalRevenue name="PLTotalRevenue">PLTotalRevenue</a>

First included in: Transaction/ProjControlPeriodTableColumn (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PLTotalRevenue attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#PLTotalValueAddedAmount name="PLTotalValueAddedAmount">PLTotalValueAddedAmount</a>

First included in: Transaction/ProjControlPeriodTableColumn (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PLTotalValueAddedAmount attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#ProjId name="ProjId">ProjId</a>

First included in: Transaction/ProjControlPeriodTableColumn (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProjId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.readOnly**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Version name="Version">Version</a>

First included in: Transaction/ProjControlPeriodTableColumn (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Version attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.readOnly**  
**is.dataFormat.integer**  
</details>

### <a href=#WIPCostpriceAccruedCost name="WIPCostpriceAccruedCost">WIPCostpriceAccruedCost</a>

First included in: Transaction/ProjControlPeriodTableColumn (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>WIP - accrued loss</td></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WIPCostpriceAccruedCost attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>WIP - accrued loss</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#WIPCostpriceExp name="WIPCostpriceExp">WIPCostpriceExp</a>

First included in: Transaction/ProjControlPeriodTableColumn (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>WIP - cost value - expense</td></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WIPCostpriceExp attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>WIP - cost value - expense</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#WIPCostpriceHour name="WIPCostpriceHour">WIPCostpriceHour</a>

First included in: Transaction/ProjControlPeriodTableColumn (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>WIP - cost value - hour</td></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WIPCostpriceHour attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>WIP - cost value - hour</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#WIPCostpriceItem name="WIPCostpriceItem">WIPCostpriceItem</a>

First included in: Transaction/ProjControlPeriodTableColumn (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>WIP - cost value - item</td></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WIPCostpriceItem attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>WIP - cost value - item</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#WIPCostpriceTotal name="WIPCostpriceTotal">WIPCostpriceTotal</a>

First included in: Transaction/ProjControlPeriodTableColumn (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WIPCostpriceTotal attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#WIPInvoiceOnAcc name="WIPInvoiceOnAcc">WIPInvoiceOnAcc</a>

First included in: Transaction/ProjControlPeriodTableColumn (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WIPInvoiceOnAcc attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.readOnly**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#WIPSalespriceProduction name="WIPSalespriceProduction">WIPSalespriceProduction</a>

First included in: Transaction/ProjControlPeriodTableColumn (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>WIP - production</td></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WIPSalespriceProduction attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>WIP - production</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#WIPSalesPriceProfit name="WIPSalesPriceProfit">WIPSalesPriceProfit</a>

First included in: Transaction/ProjControlPeriodTableColumn (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>WIP - profit</td></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WIPSalesPriceProfit attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>WIP - profit</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#WIPSalesPriceSalesValue name="WIPSalesPriceSalesValue">WIPSalesPriceSalesValue</a>

First included in: Transaction/ProjControlPeriodTableColumn (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>WIP - sales value</td></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WIPSalesPriceSalesValue attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>WIP - sales value</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#WIPSalespriceTotal name="WIPSalespriceTotal">WIPSalespriceTotal</a>

First included in: Transaction/ProjControlPeriodTableColumn (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Total WIP sales</td></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WIPSalespriceTotal attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.readOnly**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Total WIP sales</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#WIPTotalGrossWIP name="WIPTotalGrossWIP">WIPTotalGrossWIP</a>

First included in: Transaction/ProjControlPeriodTableColumn (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WIPTotalGrossWIP attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#WIPTotalNetWIP name="WIPTotalNetWIP">WIPTotalNetWIP</a>

First included in: Transaction/ProjControlPeriodTableColumn (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WIPTotalNetWIP attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#DataAreaId name="DataAreaId">DataAreaId</a>

First included in: Transaction/ProjControlPeriodTableColumn (this entity)  

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

### <a href=#Relationship_ProjControlPeriodTableRelationshipId name="Relationship_ProjControlPeriodTableRelationshipId">Relationship_ProjControlPeriodTableRelationshipId</a>

First included in: Transaction/ProjControlPeriodTableColumn (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_ProjControlPeriodTableRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="ProjControlPeriodTable.md" target="_blank">/core/operationsCommon/Tables/ProfessionalServices/ProjectManagementAndAccounting/Transaction/ProjControlPeriodTable.cdm.json/ProjControlPeriodTable</a></td><td><a href="ProjControlPeriodTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_CompanyRelationshipId name="Relationship_CompanyRelationshipId">Relationship_CompanyRelationshipId</a>

First included in: Transaction/ProjControlPeriodTableColumn (this entity)  

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
