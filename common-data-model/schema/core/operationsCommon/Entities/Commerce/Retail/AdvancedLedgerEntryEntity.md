---
title: AdvancedLedgerEntryEntity - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/20/2020
ms.author: nebanfic
---

# AdvancedLedgerEntryEntity

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/Commerce/Retail/AdvancedLedgerEntryEntity.cdm.json" target="_blank">GitHub</a>.  

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
|[LineCurrency](#LineCurrency)||<a href="AdvancedLedgerEntryEntity.md" target="_blank">Retail/AdvancedLedgerEntryEntity</a>|
|[HeaderId](#HeaderId)||<a href="AdvancedLedgerEntryEntity.md" target="_blank">Retail/AdvancedLedgerEntryEntity</a>|
|[Credit](#Credit)||<a href="AdvancedLedgerEntryEntity.md" target="_blank">Retail/AdvancedLedgerEntryEntity</a>|
|[Debit](#Debit)||<a href="AdvancedLedgerEntryEntity.md" target="_blank">Retail/AdvancedLedgerEntryEntity</a>|
|[CostPrice](#CostPrice)||<a href="AdvancedLedgerEntryEntity.md" target="_blank">Retail/AdvancedLedgerEntryEntity</a>|
|[LineJournalizingDefinitionId](#LineJournalizingDefinitionId)||<a href="AdvancedLedgerEntryEntity.md" target="_blank">Retail/AdvancedLedgerEntryEntity</a>|
|[LedgerAccount](#LedgerAccount)||<a href="AdvancedLedgerEntryEntity.md" target="_blank">Retail/AdvancedLedgerEntryEntity</a>|
|[LineNumber](#LineNumber)||<a href="AdvancedLedgerEntryEntity.md" target="_blank">Retail/AdvancedLedgerEntryEntity</a>|
|[ProjectActivityNumber](#ProjectActivityNumber)||<a href="AdvancedLedgerEntryEntity.md" target="_blank">Retail/AdvancedLedgerEntryEntity</a>|
|[ProjectCategory](#ProjectCategory)||<a href="AdvancedLedgerEntryEntity.md" target="_blank">Retail/AdvancedLedgerEntryEntity</a>|
|[ProjectFundingSourceId](#ProjectFundingSourceId)||<a href="AdvancedLedgerEntryEntity.md" target="_blank">Retail/AdvancedLedgerEntryEntity</a>|
|[ProjectID](#ProjectID)||<a href="AdvancedLedgerEntryEntity.md" target="_blank">Retail/AdvancedLedgerEntryEntity</a>|
|[ProjectLineProperty](#ProjectLineProperty)||<a href="AdvancedLedgerEntryEntity.md" target="_blank">Retail/AdvancedLedgerEntryEntity</a>|
|[ProjectSalesCurrency](#ProjectSalesCurrency)||<a href="AdvancedLedgerEntryEntity.md" target="_blank">Retail/AdvancedLedgerEntryEntity</a>|
|[ProjectSalesTaxGroup](#ProjectSalesTaxGroup)||<a href="AdvancedLedgerEntryEntity.md" target="_blank">Retail/AdvancedLedgerEntryEntity</a>|
|[ProjectItemSalesTaxGroup](#ProjectItemSalesTaxGroup)||<a href="AdvancedLedgerEntryEntity.md" target="_blank">Retail/AdvancedLedgerEntryEntity</a>|
|[ProjectTransactionID](#ProjectTransactionID)||<a href="AdvancedLedgerEntryEntity.md" target="_blank">Retail/AdvancedLedgerEntryEntity</a>|
|[Quantity](#Quantity)||<a href="AdvancedLedgerEntryEntity.md" target="_blank">Retail/AdvancedLedgerEntryEntity</a>|
|[ResourceId](#ResourceId)||<a href="AdvancedLedgerEntryEntity.md" target="_blank">Retail/AdvancedLedgerEntryEntity</a>|
|[ResourceCategoryId](#ResourceCategoryId)||<a href="AdvancedLedgerEntryEntity.md" target="_blank">Retail/AdvancedLedgerEntryEntity</a>|
|[SalesPrice](#SalesPrice)||<a href="AdvancedLedgerEntryEntity.md" target="_blank">Retail/AdvancedLedgerEntryEntity</a>|
|[TransactionTextLine](#TransactionTextLine)||<a href="AdvancedLedgerEntryEntity.md" target="_blank">Retail/AdvancedLedgerEntryEntity</a>|
|[HeaderAccountingDate](#HeaderAccountingDate)||<a href="AdvancedLedgerEntryEntity.md" target="_blank">Retail/AdvancedLedgerEntryEntity</a>|
|[FiscalPeriodId](#FiscalPeriodId)||<a href="AdvancedLedgerEntryEntity.md" target="_blank">Retail/AdvancedLedgerEntryEntity</a>|
|[HeaderJournalizingDefinitionId](#HeaderJournalizingDefinitionId)||<a href="AdvancedLedgerEntryEntity.md" target="_blank">Retail/AdvancedLedgerEntryEntity</a>|
|[ReasonId](#ReasonId)||<a href="AdvancedLedgerEntryEntity.md" target="_blank">Retail/AdvancedLedgerEntryEntity</a>|
|[ReversingDate](#ReversingDate)||<a href="AdvancedLedgerEntryEntity.md" target="_blank">Retail/AdvancedLedgerEntryEntity</a>|
|[ReversingEntry](#ReversingEntry)||<a href="AdvancedLedgerEntryEntity.md" target="_blank">Retail/AdvancedLedgerEntryEntity</a>|
|[HeaderCurrency](#HeaderCurrency)||<a href="AdvancedLedgerEntryEntity.md" target="_blank">Retail/AdvancedLedgerEntryEntity</a>|
|[HeaderTransactionNumber](#HeaderTransactionNumber)||<a href="AdvancedLedgerEntryEntity.md" target="_blank">Retail/AdvancedLedgerEntryEntity</a>|
|[HeaderTransactionText](#HeaderTransactionText)||<a href="AdvancedLedgerEntryEntity.md" target="_blank">Retail/AdvancedLedgerEntryEntity</a>|
|[FiscalCalendarYearId](#FiscalCalendarYearId)||<a href="AdvancedLedgerEntryEntity.md" target="_blank">Retail/AdvancedLedgerEntryEntity</a>|
|[FiscalCalendarPeriodName](#FiscalCalendarPeriodName)||<a href="AdvancedLedgerEntryEntity.md" target="_blank">Retail/AdvancedLedgerEntryEntity</a>|
|[FiscalCalendarId](#FiscalCalendarId)||<a href="AdvancedLedgerEntryEntity.md" target="_blank">Retail/AdvancedLedgerEntryEntity</a>|
|[FiscalCalendarYearName](#FiscalCalendarYearName)||<a href="AdvancedLedgerEntryEntity.md" target="_blank">Retail/AdvancedLedgerEntryEntity</a>|
|[FiscalCalendar](#FiscalCalendar)||<a href="AdvancedLedgerEntryEntity.md" target="_blank">Retail/AdvancedLedgerEntryEntity</a>|
|[HeaderPostingDefinition](#HeaderPostingDefinition)||<a href="AdvancedLedgerEntryEntity.md" target="_blank">Retail/AdvancedLedgerEntryEntity</a>|
|[LinePostingDefinition](#LinePostingDefinition)||<a href="AdvancedLedgerEntryEntity.md" target="_blank">Retail/AdvancedLedgerEntryEntity</a>|
|[ProjFundingSourceContract](#ProjFundingSourceContract)||<a href="AdvancedLedgerEntryEntity.md" target="_blank">Retail/AdvancedLedgerEntryEntity</a>|
|[ProjFundingSource](#ProjFundingSource)||<a href="AdvancedLedgerEntryEntity.md" target="_blank">Retail/AdvancedLedgerEntryEntity</a>|
|[LedgerAccountDisplayValue](#LedgerAccountDisplayValue)||<a href="AdvancedLedgerEntryEntity.md" target="_blank">Retail/AdvancedLedgerEntryEntity</a>|
|[HeaderTransactionStatus](#HeaderTransactionStatus)||<a href="AdvancedLedgerEntryEntity.md" target="_blank">Retail/AdvancedLedgerEntryEntity</a>|
|[PSNBankTransactionType](#PSNBankTransactionType)||<a href="AdvancedLedgerEntryEntity.md" target="_blank">Retail/AdvancedLedgerEntryEntity</a>|
|[PSNDoUpdateBank](#PSNDoUpdateBank)||<a href="AdvancedLedgerEntryEntity.md" target="_blank">Retail/AdvancedLedgerEntryEntity</a>|
|[PSNIsCorrection](#PSNIsCorrection)||<a href="AdvancedLedgerEntryEntity.md" target="_blank">Retail/AdvancedLedgerEntryEntity</a>|
|[Relationship_LedgerAccountCombinationRelationshipId](#Relationship_LedgerAccountCombinationRelationshipId)||<a href="AdvancedLedgerEntryEntity.md" target="_blank">Retail/AdvancedLedgerEntryEntity</a>|
|[BackingTable_AdvancedLedgerEntryLineRelationshipId](#BackingTable_AdvancedLedgerEntryLineRelationshipId)||<a href="AdvancedLedgerEntryEntity.md" target="_blank">Retail/AdvancedLedgerEntryEntity</a>|
|[Relationship_PrimaryCompanyContextRelationshipId](#Relationship_PrimaryCompanyContextRelationshipId)||<a href="AdvancedLedgerEntryEntity.md" target="_blank">Retail/AdvancedLedgerEntryEntity</a>|

### <a href=#LineCurrency name="LineCurrency">LineCurrency</a>

First included in: Retail/AdvancedLedgerEntryEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LineCurrency attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#HeaderId name="HeaderId">HeaderId</a>

First included in: Retail/AdvancedLedgerEntryEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the HeaderId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Credit name="Credit">Credit</a>

First included in: Retail/AdvancedLedgerEntryEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Credit attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Debit name="Debit">Debit</a>

First included in: Retail/AdvancedLedgerEntryEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Debit attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CostPrice name="CostPrice">CostPrice</a>

First included in: Retail/AdvancedLedgerEntryEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CostPrice attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LineJournalizingDefinitionId name="LineJournalizingDefinitionId">LineJournalizingDefinitionId</a>

First included in: Retail/AdvancedLedgerEntryEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LineJournalizingDefinitionId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LedgerAccount name="LedgerAccount">LedgerAccount</a>

First included in: Retail/AdvancedLedgerEntryEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LedgerAccount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LineNumber name="LineNumber">LineNumber</a>

First included in: Retail/AdvancedLedgerEntryEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LineNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProjectActivityNumber name="ProjectActivityNumber">ProjectActivityNumber</a>

First included in: Retail/AdvancedLedgerEntryEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProjectActivityNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProjectCategory name="ProjectCategory">ProjectCategory</a>

First included in: Retail/AdvancedLedgerEntryEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProjectCategory attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProjectFundingSourceId name="ProjectFundingSourceId">ProjectFundingSourceId</a>

First included in: Retail/AdvancedLedgerEntryEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProjectFundingSourceId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProjectID name="ProjectID">ProjectID</a>

First included in: Retail/AdvancedLedgerEntryEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProjectID attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProjectLineProperty name="ProjectLineProperty">ProjectLineProperty</a>

First included in: Retail/AdvancedLedgerEntryEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProjectLineProperty attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProjectSalesCurrency name="ProjectSalesCurrency">ProjectSalesCurrency</a>

First included in: Retail/AdvancedLedgerEntryEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProjectSalesCurrency attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProjectSalesTaxGroup name="ProjectSalesTaxGroup">ProjectSalesTaxGroup</a>

First included in: Retail/AdvancedLedgerEntryEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProjectSalesTaxGroup attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProjectItemSalesTaxGroup name="ProjectItemSalesTaxGroup">ProjectItemSalesTaxGroup</a>

First included in: Retail/AdvancedLedgerEntryEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProjectItemSalesTaxGroup attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProjectTransactionID name="ProjectTransactionID">ProjectTransactionID</a>

First included in: Retail/AdvancedLedgerEntryEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProjectTransactionID attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Quantity name="Quantity">Quantity</a>

First included in: Retail/AdvancedLedgerEntryEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Quantity attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ResourceId name="ResourceId">ResourceId</a>

First included in: Retail/AdvancedLedgerEntryEntity (this entity)  

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

### <a href=#ResourceCategoryId name="ResourceCategoryId">ResourceCategoryId</a>

First included in: Retail/AdvancedLedgerEntryEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ResourceCategoryId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SalesPrice name="SalesPrice">SalesPrice</a>

First included in: Retail/AdvancedLedgerEntryEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SalesPrice attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TransactionTextLine name="TransactionTextLine">TransactionTextLine</a>

First included in: Retail/AdvancedLedgerEntryEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TransactionTextLine attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#HeaderAccountingDate name="HeaderAccountingDate">HeaderAccountingDate</a>

First included in: Retail/AdvancedLedgerEntryEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the HeaderAccountingDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FiscalPeriodId name="FiscalPeriodId">FiscalPeriodId</a>

First included in: Retail/AdvancedLedgerEntryEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FiscalPeriodId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#HeaderJournalizingDefinitionId name="HeaderJournalizingDefinitionId">HeaderJournalizingDefinitionId</a>

First included in: Retail/AdvancedLedgerEntryEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the HeaderJournalizingDefinitionId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ReasonId name="ReasonId">ReasonId</a>

First included in: Retail/AdvancedLedgerEntryEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReasonId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ReversingDate name="ReversingDate">ReversingDate</a>

First included in: Retail/AdvancedLedgerEntryEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReversingDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ReversingEntry name="ReversingEntry">ReversingEntry</a>

First included in: Retail/AdvancedLedgerEntryEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReversingEntry attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#HeaderCurrency name="HeaderCurrency">HeaderCurrency</a>

First included in: Retail/AdvancedLedgerEntryEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the HeaderCurrency attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#HeaderTransactionNumber name="HeaderTransactionNumber">HeaderTransactionNumber</a>

First included in: Retail/AdvancedLedgerEntryEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the HeaderTransactionNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#HeaderTransactionText name="HeaderTransactionText">HeaderTransactionText</a>

First included in: Retail/AdvancedLedgerEntryEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the HeaderTransactionText attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FiscalCalendarYearId name="FiscalCalendarYearId">FiscalCalendarYearId</a>

First included in: Retail/AdvancedLedgerEntryEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FiscalCalendarYearId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FiscalCalendarPeriodName name="FiscalCalendarPeriodName">FiscalCalendarPeriodName</a>

First included in: Retail/AdvancedLedgerEntryEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FiscalCalendarPeriodName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FiscalCalendarId name="FiscalCalendarId">FiscalCalendarId</a>

First included in: Retail/AdvancedLedgerEntryEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FiscalCalendarId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FiscalCalendarYearName name="FiscalCalendarYearName">FiscalCalendarYearName</a>

First included in: Retail/AdvancedLedgerEntryEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FiscalCalendarYearName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FiscalCalendar name="FiscalCalendar">FiscalCalendar</a>

First included in: Retail/AdvancedLedgerEntryEntity (this entity)  

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

### <a href=#HeaderPostingDefinition name="HeaderPostingDefinition">HeaderPostingDefinition</a>

First included in: Retail/AdvancedLedgerEntryEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the HeaderPostingDefinition attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LinePostingDefinition name="LinePostingDefinition">LinePostingDefinition</a>

First included in: Retail/AdvancedLedgerEntryEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LinePostingDefinition attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProjFundingSourceContract name="ProjFundingSourceContract">ProjFundingSourceContract</a>

First included in: Retail/AdvancedLedgerEntryEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProjFundingSourceContract attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProjFundingSource name="ProjFundingSource">ProjFundingSource</a>

First included in: Retail/AdvancedLedgerEntryEntity (this entity)  

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

### <a href=#LedgerAccountDisplayValue name="LedgerAccountDisplayValue">LedgerAccountDisplayValue</a>

First included in: Retail/AdvancedLedgerEntryEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LedgerAccountDisplayValue attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#HeaderTransactionStatus name="HeaderTransactionStatus">HeaderTransactionStatus</a>

First included in: Retail/AdvancedLedgerEntryEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the HeaderTransactionStatus attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PSNBankTransactionType name="PSNBankTransactionType">PSNBankTransactionType</a>

First included in: Retail/AdvancedLedgerEntryEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PSNBankTransactionType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PSNDoUpdateBank name="PSNDoUpdateBank">PSNDoUpdateBank</a>

First included in: Retail/AdvancedLedgerEntryEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PSNDoUpdateBank attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PSNIsCorrection name="PSNIsCorrection">PSNIsCorrection</a>

First included in: Retail/AdvancedLedgerEntryEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PSNIsCorrection attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_LedgerAccountCombinationRelationshipId name="Relationship_LedgerAccountCombinationRelationshipId">Relationship_LedgerAccountCombinationRelationshipId</a>

First included in: Retail/AdvancedLedgerEntryEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_LedgerAccountCombinationRelationshipId attribute are listed below.</summary>

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

### <a href=#BackingTable_AdvancedLedgerEntryLineRelationshipId name="BackingTable_AdvancedLedgerEntryLineRelationshipId">BackingTable_AdvancedLedgerEntryLineRelationshipId</a>

First included in: Retail/AdvancedLedgerEntryEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_AdvancedLedgerEntryLineRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/Finance/PublicSector/WorksheetLine/AdvancedLedgerEntryLine.md" target="_blank">/core/operationsCommon/Tables/Finance/PublicSector/WorksheetLine/AdvancedLedgerEntryLine.cdm.json/AdvancedLedgerEntryLine</a></td><td><a href="../../../Tables/Finance/PublicSector/WorksheetLine/AdvancedLedgerEntryLine.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PrimaryCompanyContextRelationshipId name="Relationship_PrimaryCompanyContextRelationshipId">Relationship_PrimaryCompanyContextRelationshipId</a>

First included in: Retail/AdvancedLedgerEntryEntity (this entity)  

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
