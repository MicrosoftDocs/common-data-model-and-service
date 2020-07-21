---
title: LedgerFiscalPeriodEntity in GeneralLedger - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 7/21/2020
ms.author: nebanfic
---

# Ledger fiscal calendar period in GeneralLedger(LedgerFiscalPeriodEntity)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/Finance/GeneralLedger/LedgerFiscalPeriodEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Ledger fiscal calendar period</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[FiscalCalendarPeriodRecId](#FiscalCalendarPeriodRecId)||<a href="LedgerFiscalPeriodEntity.md" target="_blank">GeneralLedger/LedgerFiscalPeriodEntity</a>|
|[LedgerRecId](#LedgerRecId)||<a href="LedgerFiscalPeriodEntity.md" target="_blank">GeneralLedger/LedgerFiscalPeriodEntity</a>|
|[PeriodStatus](#PeriodStatus)||<a href="LedgerFiscalPeriodEntity.md" target="_blank">GeneralLedger/LedgerFiscalPeriodEntity</a>|
|[FiscalCalendarYearRecId](#FiscalCalendarYearRecId)||<a href="LedgerFiscalPeriodEntity.md" target="_blank">GeneralLedger/LedgerFiscalPeriodEntity</a>|
|[PeriodName](#PeriodName)||<a href="LedgerFiscalPeriodEntity.md" target="_blank">GeneralLedger/LedgerFiscalPeriodEntity</a>|
|[FiscalCalendarRecId](#FiscalCalendarRecId)||<a href="LedgerFiscalPeriodEntity.md" target="_blank">GeneralLedger/LedgerFiscalPeriodEntity</a>|
|[YearName](#YearName)||<a href="LedgerFiscalPeriodEntity.md" target="_blank">GeneralLedger/LedgerFiscalPeriodEntity</a>|
|[Calendar](#Calendar)||<a href="LedgerFiscalPeriodEntity.md" target="_blank">GeneralLedger/LedgerFiscalPeriodEntity</a>|
|[LedgerName](#LedgerName)||<a href="LedgerFiscalPeriodEntity.md" target="_blank">GeneralLedger/LedgerFiscalPeriodEntity</a>|
|[LedgerFiscalCalendarPeriodRecId](#LedgerFiscalCalendarPeriodRecId)||<a href="LedgerFiscalPeriodEntity.md" target="_blank">GeneralLedger/LedgerFiscalPeriodEntity</a>|
|[LedgerAccessLevel](#LedgerAccessLevel)||<a href="LedgerFiscalPeriodEntity.md" target="_blank">GeneralLedger/LedgerFiscalPeriodEntity</a>|
|[LedgerUserGroupInfo](#LedgerUserGroupInfo)||<a href="LedgerFiscalPeriodEntity.md" target="_blank">GeneralLedger/LedgerFiscalPeriodEntity</a>|
|[TaxAccessLevel](#TaxAccessLevel)||<a href="LedgerFiscalPeriodEntity.md" target="_blank">GeneralLedger/LedgerFiscalPeriodEntity</a>|
|[TaxUserGroupInfo](#TaxUserGroupInfo)||<a href="LedgerFiscalPeriodEntity.md" target="_blank">GeneralLedger/LedgerFiscalPeriodEntity</a>|
|[BankAccessLevel](#BankAccessLevel)||<a href="LedgerFiscalPeriodEntity.md" target="_blank">GeneralLedger/LedgerFiscalPeriodEntity</a>|
|[BankUserGroupInfo](#BankUserGroupInfo)||<a href="LedgerFiscalPeriodEntity.md" target="_blank">GeneralLedger/LedgerFiscalPeriodEntity</a>|
|[CustAccessLevel](#CustAccessLevel)||<a href="LedgerFiscalPeriodEntity.md" target="_blank">GeneralLedger/LedgerFiscalPeriodEntity</a>|
|[CustUserGroupInfo](#CustUserGroupInfo)||<a href="LedgerFiscalPeriodEntity.md" target="_blank">GeneralLedger/LedgerFiscalPeriodEntity</a>|
|[VendAccessLevel](#VendAccessLevel)||<a href="LedgerFiscalPeriodEntity.md" target="_blank">GeneralLedger/LedgerFiscalPeriodEntity</a>|
|[VendUserGroupInfo](#VendUserGroupInfo)||<a href="LedgerFiscalPeriodEntity.md" target="_blank">GeneralLedger/LedgerFiscalPeriodEntity</a>|
|[SalesAccessLevel](#SalesAccessLevel)||<a href="LedgerFiscalPeriodEntity.md" target="_blank">GeneralLedger/LedgerFiscalPeriodEntity</a>|
|[SalesUserGroupInfo](#SalesUserGroupInfo)||<a href="LedgerFiscalPeriodEntity.md" target="_blank">GeneralLedger/LedgerFiscalPeriodEntity</a>|
|[PurchAccessLevel](#PurchAccessLevel)||<a href="LedgerFiscalPeriodEntity.md" target="_blank">GeneralLedger/LedgerFiscalPeriodEntity</a>|
|[PurchUserGroupInfo](#PurchUserGroupInfo)||<a href="LedgerFiscalPeriodEntity.md" target="_blank">GeneralLedger/LedgerFiscalPeriodEntity</a>|
|[InventAccessLevel](#InventAccessLevel)||<a href="LedgerFiscalPeriodEntity.md" target="_blank">GeneralLedger/LedgerFiscalPeriodEntity</a>|
|[InventUserGroupInfo](#InventUserGroupInfo)||<a href="LedgerFiscalPeriodEntity.md" target="_blank">GeneralLedger/LedgerFiscalPeriodEntity</a>|
|[ProdAccessLevel](#ProdAccessLevel)||<a href="LedgerFiscalPeriodEntity.md" target="_blank">GeneralLedger/LedgerFiscalPeriodEntity</a>|
|[ProdUserGroupInfo](#ProdUserGroupInfo)||<a href="LedgerFiscalPeriodEntity.md" target="_blank">GeneralLedger/LedgerFiscalPeriodEntity</a>|
|[ProjectAccessLevel](#ProjectAccessLevel)||<a href="LedgerFiscalPeriodEntity.md" target="_blank">GeneralLedger/LedgerFiscalPeriodEntity</a>|
|[ProjectUserGroupInfo](#ProjectUserGroupInfo)||<a href="LedgerFiscalPeriodEntity.md" target="_blank">GeneralLedger/LedgerFiscalPeriodEntity</a>|
|[FixedAssetsAccessLevel](#FixedAssetsAccessLevel)||<a href="LedgerFiscalPeriodEntity.md" target="_blank">GeneralLedger/LedgerFiscalPeriodEntity</a>|
|[FixedAssetsUserGroupInfo](#FixedAssetsUserGroupInfo)||<a href="LedgerFiscalPeriodEntity.md" target="_blank">GeneralLedger/LedgerFiscalPeriodEntity</a>|
|[PayrollAccessLevel](#PayrollAccessLevel)||<a href="LedgerFiscalPeriodEntity.md" target="_blank">GeneralLedger/LedgerFiscalPeriodEntity</a>|
|[PayrollUserGroupInfo](#PayrollUserGroupInfo)||<a href="LedgerFiscalPeriodEntity.md" target="_blank">GeneralLedger/LedgerFiscalPeriodEntity</a>|
|[ExpenseAccessLevel](#ExpenseAccessLevel)||<a href="LedgerFiscalPeriodEntity.md" target="_blank">GeneralLedger/LedgerFiscalPeriodEntity</a>|
|[ExpenseUserGroupInfo](#ExpenseUserGroupInfo)||<a href="LedgerFiscalPeriodEntity.md" target="_blank">GeneralLedger/LedgerFiscalPeriodEntity</a>|
|[FixedAssets_RUAccessLevel](#FixedAssets_RUAccessLevel)||<a href="LedgerFiscalPeriodEntity.md" target="_blank">GeneralLedger/LedgerFiscalPeriodEntity</a>|
|[FixedAssets_RUUserGroupInfo](#FixedAssets_RUUserGroupInfo)||<a href="LedgerFiscalPeriodEntity.md" target="_blank">GeneralLedger/LedgerFiscalPeriodEntity</a>|
|[RetailAccessLevel](#RetailAccessLevel)||<a href="LedgerFiscalPeriodEntity.md" target="_blank">GeneralLedger/LedgerFiscalPeriodEntity</a>|
|[RetailUserGroupInfo](#RetailUserGroupInfo)||<a href="LedgerFiscalPeriodEntity.md" target="_blank">GeneralLedger/LedgerFiscalPeriodEntity</a>|
|[LegalEntityId](#LegalEntityId)||<a href="LedgerFiscalPeriodEntity.md" target="_blank">GeneralLedger/LedgerFiscalPeriodEntity</a>|
|[BackingTable_LedgerFiscalCalendarPeriodRelationshipId](#BackingTable_LedgerFiscalCalendarPeriodRelationshipId)||<a href="LedgerFiscalPeriodEntity.md" target="_blank">GeneralLedger/LedgerFiscalPeriodEntity</a>|

### <a href=#FiscalCalendarPeriodRecId name="FiscalCalendarPeriodRecId">FiscalCalendarPeriodRecId</a>

First included in: GeneralLedger/LedgerFiscalPeriodEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FiscalCalendarPeriodRecId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LedgerRecId name="LedgerRecId">LedgerRecId</a>

First included in: GeneralLedger/LedgerFiscalPeriodEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LedgerRecId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PeriodStatus name="PeriodStatus">PeriodStatus</a>

First included in: GeneralLedger/LedgerFiscalPeriodEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PeriodStatus attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FiscalCalendarYearRecId name="FiscalCalendarYearRecId">FiscalCalendarYearRecId</a>

First included in: GeneralLedger/LedgerFiscalPeriodEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FiscalCalendarYearRecId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PeriodName name="PeriodName">PeriodName</a>

First included in: GeneralLedger/LedgerFiscalPeriodEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PeriodName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FiscalCalendarRecId name="FiscalCalendarRecId">FiscalCalendarRecId</a>

First included in: GeneralLedger/LedgerFiscalPeriodEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FiscalCalendarRecId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#YearName name="YearName">YearName</a>

First included in: GeneralLedger/LedgerFiscalPeriodEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the YearName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Calendar name="Calendar">Calendar</a>

First included in: GeneralLedger/LedgerFiscalPeriodEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Calendar attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LedgerName name="LedgerName">LedgerName</a>

First included in: GeneralLedger/LedgerFiscalPeriodEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LedgerName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LedgerFiscalCalendarPeriodRecId name="LedgerFiscalCalendarPeriodRecId">LedgerFiscalCalendarPeriodRecId</a>

First included in: GeneralLedger/LedgerFiscalPeriodEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LedgerFiscalCalendarPeriodRecId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LedgerAccessLevel name="LedgerAccessLevel">LedgerAccessLevel</a>

First included in: GeneralLedger/LedgerFiscalPeriodEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LedgerAccessLevel attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LedgerUserGroupInfo name="LedgerUserGroupInfo">LedgerUserGroupInfo</a>

First included in: GeneralLedger/LedgerFiscalPeriodEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LedgerUserGroupInfo attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TaxAccessLevel name="TaxAccessLevel">TaxAccessLevel</a>

First included in: GeneralLedger/LedgerFiscalPeriodEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxAccessLevel attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TaxUserGroupInfo name="TaxUserGroupInfo">TaxUserGroupInfo</a>

First included in: GeneralLedger/LedgerFiscalPeriodEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxUserGroupInfo attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BankAccessLevel name="BankAccessLevel">BankAccessLevel</a>

First included in: GeneralLedger/LedgerFiscalPeriodEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BankAccessLevel attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BankUserGroupInfo name="BankUserGroupInfo">BankUserGroupInfo</a>

First included in: GeneralLedger/LedgerFiscalPeriodEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BankUserGroupInfo attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CustAccessLevel name="CustAccessLevel">CustAccessLevel</a>

First included in: GeneralLedger/LedgerFiscalPeriodEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CustAccessLevel attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CustUserGroupInfo name="CustUserGroupInfo">CustUserGroupInfo</a>

First included in: GeneralLedger/LedgerFiscalPeriodEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CustUserGroupInfo attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#VendAccessLevel name="VendAccessLevel">VendAccessLevel</a>

First included in: GeneralLedger/LedgerFiscalPeriodEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VendAccessLevel attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#VendUserGroupInfo name="VendUserGroupInfo">VendUserGroupInfo</a>

First included in: GeneralLedger/LedgerFiscalPeriodEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VendUserGroupInfo attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SalesAccessLevel name="SalesAccessLevel">SalesAccessLevel</a>

First included in: GeneralLedger/LedgerFiscalPeriodEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SalesAccessLevel attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SalesUserGroupInfo name="SalesUserGroupInfo">SalesUserGroupInfo</a>

First included in: GeneralLedger/LedgerFiscalPeriodEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SalesUserGroupInfo attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PurchAccessLevel name="PurchAccessLevel">PurchAccessLevel</a>

First included in: GeneralLedger/LedgerFiscalPeriodEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PurchAccessLevel attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PurchUserGroupInfo name="PurchUserGroupInfo">PurchUserGroupInfo</a>

First included in: GeneralLedger/LedgerFiscalPeriodEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PurchUserGroupInfo attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InventAccessLevel name="InventAccessLevel">InventAccessLevel</a>

First included in: GeneralLedger/LedgerFiscalPeriodEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InventAccessLevel attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InventUserGroupInfo name="InventUserGroupInfo">InventUserGroupInfo</a>

First included in: GeneralLedger/LedgerFiscalPeriodEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InventUserGroupInfo attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProdAccessLevel name="ProdAccessLevel">ProdAccessLevel</a>

First included in: GeneralLedger/LedgerFiscalPeriodEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProdAccessLevel attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProdUserGroupInfo name="ProdUserGroupInfo">ProdUserGroupInfo</a>

First included in: GeneralLedger/LedgerFiscalPeriodEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProdUserGroupInfo attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProjectAccessLevel name="ProjectAccessLevel">ProjectAccessLevel</a>

First included in: GeneralLedger/LedgerFiscalPeriodEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProjectAccessLevel attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProjectUserGroupInfo name="ProjectUserGroupInfo">ProjectUserGroupInfo</a>

First included in: GeneralLedger/LedgerFiscalPeriodEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProjectUserGroupInfo attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FixedAssetsAccessLevel name="FixedAssetsAccessLevel">FixedAssetsAccessLevel</a>

First included in: GeneralLedger/LedgerFiscalPeriodEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FixedAssetsAccessLevel attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FixedAssetsUserGroupInfo name="FixedAssetsUserGroupInfo">FixedAssetsUserGroupInfo</a>

First included in: GeneralLedger/LedgerFiscalPeriodEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FixedAssetsUserGroupInfo attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PayrollAccessLevel name="PayrollAccessLevel">PayrollAccessLevel</a>

First included in: GeneralLedger/LedgerFiscalPeriodEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PayrollAccessLevel attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PayrollUserGroupInfo name="PayrollUserGroupInfo">PayrollUserGroupInfo</a>

First included in: GeneralLedger/LedgerFiscalPeriodEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PayrollUserGroupInfo attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ExpenseAccessLevel name="ExpenseAccessLevel">ExpenseAccessLevel</a>

First included in: GeneralLedger/LedgerFiscalPeriodEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ExpenseAccessLevel attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ExpenseUserGroupInfo name="ExpenseUserGroupInfo">ExpenseUserGroupInfo</a>

First included in: GeneralLedger/LedgerFiscalPeriodEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ExpenseUserGroupInfo attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FixedAssets_RUAccessLevel name="FixedAssets_RUAccessLevel">FixedAssets_RUAccessLevel</a>

First included in: GeneralLedger/LedgerFiscalPeriodEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FixedAssets_RUAccessLevel attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FixedAssets_RUUserGroupInfo name="FixedAssets_RUUserGroupInfo">FixedAssets_RUUserGroupInfo</a>

First included in: GeneralLedger/LedgerFiscalPeriodEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FixedAssets_RUUserGroupInfo attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RetailAccessLevel name="RetailAccessLevel">RetailAccessLevel</a>

First included in: GeneralLedger/LedgerFiscalPeriodEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RetailAccessLevel attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RetailUserGroupInfo name="RetailUserGroupInfo">RetailUserGroupInfo</a>

First included in: GeneralLedger/LedgerFiscalPeriodEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RetailUserGroupInfo attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LegalEntityId name="LegalEntityId">LegalEntityId</a>

First included in: GeneralLedger/LedgerFiscalPeriodEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LegalEntityId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BackingTable_LedgerFiscalCalendarPeriodRelationshipId name="BackingTable_LedgerFiscalCalendarPeriodRelationshipId">BackingTable_LedgerFiscalCalendarPeriodRelationshipId</a>

First included in: GeneralLedger/LedgerFiscalPeriodEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_LedgerFiscalCalendarPeriodRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/Finance/Ledger/Reference/LedgerFiscalCalendarPeriod.md" target="_blank">/core/operationsCommon/Tables/Finance/Ledger/Reference/LedgerFiscalCalendarPeriod.cdm.json/LedgerFiscalCalendarPeriod</a></td><td><a href="../../../Tables/Finance/Ledger/Reference/LedgerFiscalCalendarPeriod.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>
