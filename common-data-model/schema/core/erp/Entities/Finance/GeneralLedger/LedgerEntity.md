---
title: LedgerEntity - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/17/2020
ms.author: nebanfic
---

# LedgerEntity

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/erp/Entities/Finance/GeneralLedger/LedgerEntity.cdm.json" target="_blank">GitHub</a>.  

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
|[AccountingCurrency](#AccountingCurrency)||<a href="LedgerEntity.md" target="_blank">GeneralLedger/LedgerEntity</a>|
|[ReportingCurrency](#ReportingCurrency)||<a href="LedgerEntity.md" target="_blank">GeneralLedger/LedgerEntity</a>|
|[Description](#Description)||<a href="LedgerEntity.md" target="_blank">GeneralLedger/LedgerEntity</a>|
|[FiscalCalendar](#FiscalCalendar)||<a href="LedgerEntity.md" target="_blank">GeneralLedger/LedgerEntity</a>|
|[FiscalCalendarRecId](#FiscalCalendarRecId)||<a href="LedgerEntity.md" target="_blank">GeneralLedger/LedgerEntity</a>|
|[ExchangeRateType](#ExchangeRateType)||<a href="LedgerEntity.md" target="_blank">GeneralLedger/LedgerEntity</a>|
|[ExchangeRateTypeRecId](#ExchangeRateTypeRecId)||<a href="LedgerEntity.md" target="_blank">GeneralLedger/LedgerEntity</a>|
|[BudgetExchangeRateType](#BudgetExchangeRateType)||<a href="LedgerEntity.md" target="_blank">GeneralLedger/LedgerEntity</a>|
|[BudgetExchangeRateTypeRecId](#BudgetExchangeRateTypeRecId)||<a href="LedgerEntity.md" target="_blank">GeneralLedger/LedgerEntity</a>|
|[IsBudgetControlEnabled](#IsBudgetControlEnabled)||<a href="LedgerEntity.md" target="_blank">GeneralLedger/LedgerEntity</a>|
|[ChartOfAccounts](#ChartOfAccounts)||<a href="LedgerEntity.md" target="_blank">GeneralLedger/LedgerEntity</a>|
|[ChartOfAccountsRecId](#ChartOfAccountsRecId)||<a href="LedgerEntity.md" target="_blank">GeneralLedger/LedgerEntity</a>|
|[Name](#Name)||<a href="LedgerEntity.md" target="_blank">GeneralLedger/LedgerEntity</a>|
|[PrimaryForLegalEntityRecId](#PrimaryForLegalEntityRecId)||<a href="LedgerEntity.md" target="_blank">GeneralLedger/LedgerEntity</a>|
|[LegalEntityId](#LegalEntityId)||<a href="LedgerEntity.md" target="_blank">GeneralLedger/LedgerEntity</a>|
|[BalancingFinancialDimensionRecId](#BalancingFinancialDimensionRecId)||<a href="LedgerEntity.md" target="_blank">GeneralLedger/LedgerEntity</a>|
|[BalancingFinancialDimension](#BalancingFinancialDimension)||<a href="LedgerEntity.md" target="_blank">GeneralLedger/LedgerEntity</a>|
|[AccountStructureName1](#AccountStructureName1)||<a href="LedgerEntity.md" target="_blank">GeneralLedger/LedgerEntity</a>|
|[AccountStructureName2](#AccountStructureName2)||<a href="LedgerEntity.md" target="_blank">GeneralLedger/LedgerEntity</a>|
|[AccountStructureName3](#AccountStructureName3)||<a href="LedgerEntity.md" target="_blank">GeneralLedger/LedgerEntity</a>|
|[AccountStructureName4](#AccountStructureName4)||<a href="LedgerEntity.md" target="_blank">GeneralLedger/LedgerEntity</a>|
|[AccountStructureName5](#AccountStructureName5)||<a href="LedgerEntity.md" target="_blank">GeneralLedger/LedgerEntity</a>|
|[AccountStructureName6](#AccountStructureName6)||<a href="LedgerEntity.md" target="_blank">GeneralLedger/LedgerEntity</a>|
|[AccountStructureName7](#AccountStructureName7)||<a href="LedgerEntity.md" target="_blank">GeneralLedger/LedgerEntity</a>|
|[AccountStructureName8](#AccountStructureName8)||<a href="LedgerEntity.md" target="_blank">GeneralLedger/LedgerEntity</a>|
|[AccountStructureName9](#AccountStructureName9)||<a href="LedgerEntity.md" target="_blank">GeneralLedger/LedgerEntity</a>|
|[AccountStructureName10](#AccountStructureName10)||<a href="LedgerEntity.md" target="_blank">GeneralLedger/LedgerEntity</a>|
|[AccountStructureName11](#AccountStructureName11)||<a href="LedgerEntity.md" target="_blank">GeneralLedger/LedgerEntity</a>|
|[AccountStructureName12](#AccountStructureName12)||<a href="LedgerEntity.md" target="_blank">GeneralLedger/LedgerEntity</a>|
|[AccountStructureName13](#AccountStructureName13)||<a href="LedgerEntity.md" target="_blank">GeneralLedger/LedgerEntity</a>|
|[AccountStructureName14](#AccountStructureName14)||<a href="LedgerEntity.md" target="_blank">GeneralLedger/LedgerEntity</a>|
|[AccountStructureName15](#AccountStructureName15)||<a href="LedgerEntity.md" target="_blank">GeneralLedger/LedgerEntity</a>|
|[AccountStructureName16](#AccountStructureName16)||<a href="LedgerEntity.md" target="_blank">GeneralLedger/LedgerEntity</a>|
|[AccountStructureName17](#AccountStructureName17)||<a href="LedgerEntity.md" target="_blank">GeneralLedger/LedgerEntity</a>|
|[AccountStructureName18](#AccountStructureName18)||<a href="LedgerEntity.md" target="_blank">GeneralLedger/LedgerEntity</a>|
|[AccountStructureName19](#AccountStructureName19)||<a href="LedgerEntity.md" target="_blank">GeneralLedger/LedgerEntity</a>|
|[AccountStructureName20](#AccountStructureName20)||<a href="LedgerEntity.md" target="_blank">GeneralLedger/LedgerEntity</a>|
|[LedgerRecId](#LedgerRecId)||<a href="LedgerEntity.md" target="_blank">GeneralLedger/LedgerEntity</a>|
|[MainAccountIdRealizedGain](#MainAccountIdRealizedGain)||<a href="LedgerEntity.md" target="_blank">GeneralLedger/LedgerEntity</a>|
|[MainAccountIdRealizedLoss](#MainAccountIdRealizedLoss)||<a href="LedgerEntity.md" target="_blank">GeneralLedger/LedgerEntity</a>|
|[MainAccountIdUnrealizedGain](#MainAccountIdUnrealizedGain)||<a href="LedgerEntity.md" target="_blank">GeneralLedger/LedgerEntity</a>|
|[MainAccountIdUnrealizedLoss](#MainAccountIdUnrealizedLoss)||<a href="LedgerEntity.md" target="_blank">GeneralLedger/LedgerEntity</a>|
|[MainAccountIdFinancialGain](#MainAccountIdFinancialGain)||<a href="LedgerEntity.md" target="_blank">GeneralLedger/LedgerEntity</a>|
|[MainAccountIdFinancialLoss](#MainAccountIdFinancialLoss)||<a href="LedgerEntity.md" target="_blank">GeneralLedger/LedgerEntity</a>|
|[ReportingCurrencyExchangeRateType](#ReportingCurrencyExchangeRateType)||<a href="LedgerEntity.md" target="_blank">GeneralLedger/LedgerEntity</a>|
|[ReportingCurrencyExchangeRateTypeRecId](#ReportingCurrencyExchangeRateTypeRecId)||<a href="LedgerEntity.md" target="_blank">GeneralLedger/LedgerEntity</a>|
|[Relationship_AccountingCurrencyRelationshipId](#Relationship_AccountingCurrencyRelationshipId)||<a href="LedgerEntity.md" target="_blank">GeneralLedger/LedgerEntity</a>|
|[Relationship_ReportingCurrencyRelationshipId](#Relationship_ReportingCurrencyRelationshipId)||<a href="LedgerEntity.md" target="_blank">GeneralLedger/LedgerEntity</a>|
|[Relationship_InterunitDimensionAttributeRelationshipId](#Relationship_InterunitDimensionAttributeRelationshipId)||<a href="LedgerEntity.md" target="_blank">GeneralLedger/LedgerEntity</a>|
|[BackingTable_LedgerRelationshipId](#BackingTable_LedgerRelationshipId)||<a href="LedgerEntity.md" target="_blank">GeneralLedger/LedgerEntity</a>|

### <a href=#AccountingCurrency name="AccountingCurrency">AccountingCurrency</a>

First included in: GeneralLedger/LedgerEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AccountingCurrency attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ReportingCurrency name="ReportingCurrency">ReportingCurrency</a>

First included in: GeneralLedger/LedgerEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReportingCurrency attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Description name="Description">Description</a>

First included in: GeneralLedger/LedgerEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Description attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FiscalCalendar name="FiscalCalendar">FiscalCalendar</a>

First included in: GeneralLedger/LedgerEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FiscalCalendar attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FiscalCalendarRecId name="FiscalCalendarRecId">FiscalCalendarRecId</a>

First included in: GeneralLedger/LedgerEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FiscalCalendarRecId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ExchangeRateType name="ExchangeRateType">ExchangeRateType</a>

First included in: GeneralLedger/LedgerEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ExchangeRateType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ExchangeRateTypeRecId name="ExchangeRateTypeRecId">ExchangeRateTypeRecId</a>

First included in: GeneralLedger/LedgerEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ExchangeRateTypeRecId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BudgetExchangeRateType name="BudgetExchangeRateType">BudgetExchangeRateType</a>

First included in: GeneralLedger/LedgerEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BudgetExchangeRateType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BudgetExchangeRateTypeRecId name="BudgetExchangeRateTypeRecId">BudgetExchangeRateTypeRecId</a>

First included in: GeneralLedger/LedgerEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BudgetExchangeRateTypeRecId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsBudgetControlEnabled name="IsBudgetControlEnabled">IsBudgetControlEnabled</a>

First included in: GeneralLedger/LedgerEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsBudgetControlEnabled attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ChartOfAccounts name="ChartOfAccounts">ChartOfAccounts</a>

First included in: GeneralLedger/LedgerEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ChartOfAccounts attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ChartOfAccountsRecId name="ChartOfAccountsRecId">ChartOfAccountsRecId</a>

First included in: GeneralLedger/LedgerEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ChartOfAccountsRecId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Name name="Name">Name</a>

First included in: GeneralLedger/LedgerEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Name attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PrimaryForLegalEntityRecId name="PrimaryForLegalEntityRecId">PrimaryForLegalEntityRecId</a>

First included in: GeneralLedger/LedgerEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrimaryForLegalEntityRecId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LegalEntityId name="LegalEntityId">LegalEntityId</a>

First included in: GeneralLedger/LedgerEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LegalEntityId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BalancingFinancialDimensionRecId name="BalancingFinancialDimensionRecId">BalancingFinancialDimensionRecId</a>

First included in: GeneralLedger/LedgerEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BalancingFinancialDimensionRecId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BalancingFinancialDimension name="BalancingFinancialDimension">BalancingFinancialDimension</a>

First included in: GeneralLedger/LedgerEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BalancingFinancialDimension attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AccountStructureName1 name="AccountStructureName1">AccountStructureName1</a>

First included in: GeneralLedger/LedgerEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AccountStructureName1 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AccountStructureName2 name="AccountStructureName2">AccountStructureName2</a>

First included in: GeneralLedger/LedgerEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AccountStructureName2 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AccountStructureName3 name="AccountStructureName3">AccountStructureName3</a>

First included in: GeneralLedger/LedgerEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AccountStructureName3 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AccountStructureName4 name="AccountStructureName4">AccountStructureName4</a>

First included in: GeneralLedger/LedgerEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AccountStructureName4 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AccountStructureName5 name="AccountStructureName5">AccountStructureName5</a>

First included in: GeneralLedger/LedgerEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AccountStructureName5 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AccountStructureName6 name="AccountStructureName6">AccountStructureName6</a>

First included in: GeneralLedger/LedgerEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AccountStructureName6 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AccountStructureName7 name="AccountStructureName7">AccountStructureName7</a>

First included in: GeneralLedger/LedgerEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AccountStructureName7 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AccountStructureName8 name="AccountStructureName8">AccountStructureName8</a>

First included in: GeneralLedger/LedgerEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AccountStructureName8 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AccountStructureName9 name="AccountStructureName9">AccountStructureName9</a>

First included in: GeneralLedger/LedgerEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AccountStructureName9 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AccountStructureName10 name="AccountStructureName10">AccountStructureName10</a>

First included in: GeneralLedger/LedgerEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AccountStructureName10 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AccountStructureName11 name="AccountStructureName11">AccountStructureName11</a>

First included in: GeneralLedger/LedgerEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AccountStructureName11 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AccountStructureName12 name="AccountStructureName12">AccountStructureName12</a>

First included in: GeneralLedger/LedgerEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AccountStructureName12 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AccountStructureName13 name="AccountStructureName13">AccountStructureName13</a>

First included in: GeneralLedger/LedgerEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AccountStructureName13 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AccountStructureName14 name="AccountStructureName14">AccountStructureName14</a>

First included in: GeneralLedger/LedgerEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AccountStructureName14 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AccountStructureName15 name="AccountStructureName15">AccountStructureName15</a>

First included in: GeneralLedger/LedgerEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AccountStructureName15 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AccountStructureName16 name="AccountStructureName16">AccountStructureName16</a>

First included in: GeneralLedger/LedgerEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AccountStructureName16 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AccountStructureName17 name="AccountStructureName17">AccountStructureName17</a>

First included in: GeneralLedger/LedgerEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AccountStructureName17 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AccountStructureName18 name="AccountStructureName18">AccountStructureName18</a>

First included in: GeneralLedger/LedgerEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AccountStructureName18 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AccountStructureName19 name="AccountStructureName19">AccountStructureName19</a>

First included in: GeneralLedger/LedgerEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AccountStructureName19 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AccountStructureName20 name="AccountStructureName20">AccountStructureName20</a>

First included in: GeneralLedger/LedgerEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AccountStructureName20 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LedgerRecId name="LedgerRecId">LedgerRecId</a>

First included in: GeneralLedger/LedgerEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LedgerRecId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MainAccountIdRealizedGain name="MainAccountIdRealizedGain">MainAccountIdRealizedGain</a>

First included in: GeneralLedger/LedgerEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MainAccountIdRealizedGain attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MainAccountIdRealizedLoss name="MainAccountIdRealizedLoss">MainAccountIdRealizedLoss</a>

First included in: GeneralLedger/LedgerEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MainAccountIdRealizedLoss attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MainAccountIdUnrealizedGain name="MainAccountIdUnrealizedGain">MainAccountIdUnrealizedGain</a>

First included in: GeneralLedger/LedgerEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MainAccountIdUnrealizedGain attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MainAccountIdUnrealizedLoss name="MainAccountIdUnrealizedLoss">MainAccountIdUnrealizedLoss</a>

First included in: GeneralLedger/LedgerEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MainAccountIdUnrealizedLoss attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MainAccountIdFinancialGain name="MainAccountIdFinancialGain">MainAccountIdFinancialGain</a>

First included in: GeneralLedger/LedgerEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MainAccountIdFinancialGain attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MainAccountIdFinancialLoss name="MainAccountIdFinancialLoss">MainAccountIdFinancialLoss</a>

First included in: GeneralLedger/LedgerEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MainAccountIdFinancialLoss attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ReportingCurrencyExchangeRateType name="ReportingCurrencyExchangeRateType">ReportingCurrencyExchangeRateType</a>

First included in: GeneralLedger/LedgerEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReportingCurrencyExchangeRateType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ReportingCurrencyExchangeRateTypeRecId name="ReportingCurrencyExchangeRateTypeRecId">ReportingCurrencyExchangeRateTypeRecId</a>

First included in: GeneralLedger/LedgerEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReportingCurrencyExchangeRateTypeRecId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_AccountingCurrencyRelationshipId name="Relationship_AccountingCurrencyRelationshipId">Relationship_AccountingCurrencyRelationshipId</a>

First included in: GeneralLedger/LedgerEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_AccountingCurrencyRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_ReportingCurrencyRelationshipId name="Relationship_ReportingCurrencyRelationshipId">Relationship_ReportingCurrencyRelationshipId</a>

First included in: GeneralLedger/LedgerEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_ReportingCurrencyRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_InterunitDimensionAttributeRelationshipId name="Relationship_InterunitDimensionAttributeRelationshipId">Relationship_InterunitDimensionAttributeRelationshipId</a>

First included in: GeneralLedger/LedgerEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_InterunitDimensionAttributeRelationshipId attribute are listed below.</summary>

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

### <a href=#BackingTable_LedgerRelationshipId name="BackingTable_LedgerRelationshipId">BackingTable_LedgerRelationshipId</a>

First included in: GeneralLedger/LedgerEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_LedgerRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/Finance/Ledger/Main/Ledger.md" target="_blank">/core/erp/Tables/Finance/Ledger/Main/Ledger.cdm.json/Ledger</a></td><td><a href="../../../Tables/Finance/Ledger/Main/Ledger.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>
