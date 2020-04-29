---
title: ProjBeginningBalanceCostSaleEntity - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/29/2020
ms.author: nebanfic
---

# Project journal lines for cost/sale beginning balances

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/ProfessionalServices/ProjectManagementAndAccounting/ProjBeginningBalanceCostSaleEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Project journal lines for cost/sale beginning balances</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[ActivityNumber](#ActivityNumber)||<a href="ProjBeginningBalanceCostSaleEntity.md" target="_blank">ProjectManagementAndAccounting/ProjBeginningBalanceCostSaleEntity</a>|
|[CostPrice](#CostPrice)||<a href="ProjBeginningBalanceCostSaleEntity.md" target="_blank">ProjectManagementAndAccounting/ProjBeginningBalanceCostSaleEntity</a>|
|[DefaultDimension](#DefaultDimension)||<a href="ProjBeginningBalanceCostSaleEntity.md" target="_blank">ProjectManagementAndAccounting/ProjBeginningBalanceCostSaleEntity</a>|
|[ItemId](#ItemId)||<a href="ProjBeginningBalanceCostSaleEntity.md" target="_blank">ProjectManagementAndAccounting/ProjBeginningBalanceCostSaleEntity</a>|
|[LineNumber](#LineNumber)||<a href="ProjBeginningBalanceCostSaleEntity.md" target="_blank">ProjectManagementAndAccounting/ProjBeginningBalanceCostSaleEntity</a>|
|[LinePropertyId](#LinePropertyId)||<a href="ProjBeginningBalanceCostSaleEntity.md" target="_blank">ProjectManagementAndAccounting/ProjBeginningBalanceCostSaleEntity</a>|
|[CanAccrueRevenue](#CanAccrueRevenue)||<a href="ProjBeginningBalanceCostSaleEntity.md" target="_blank">ProjectManagementAndAccounting/ProjBeginningBalanceCostSaleEntity</a>|
|[CategoryId](#CategoryId)||<a href="ProjBeginningBalanceCostSaleEntity.md" target="_blank">ProjectManagementAndAccounting/ProjBeginningBalanceCostSaleEntity</a>|
|[ProjFundingSource](#ProjFundingSource)||<a href="ProjBeginningBalanceCostSaleEntity.md" target="_blank">ProjectManagementAndAccounting/ProjBeginningBalanceCostSaleEntity</a>|
|[ProjectId](#ProjectId)||<a href="ProjBeginningBalanceCostSaleEntity.md" target="_blank">ProjectManagementAndAccounting/ProjBeginningBalanceCostSaleEntity</a>|
|[CostStatus](#CostStatus)||<a href="ProjBeginningBalanceCostSaleEntity.md" target="_blank">ProjectManagementAndAccounting/ProjBeginningBalanceCostSaleEntity</a>|
|[SalesCurrency](#SalesCurrency)||<a href="ProjBeginningBalanceCostSaleEntity.md" target="_blank">ProjectManagementAndAccounting/ProjBeginningBalanceCostSaleEntity</a>|
|[SalesTaxGroup](#SalesTaxGroup)||<a href="ProjBeginningBalanceCostSaleEntity.md" target="_blank">ProjectManagementAndAccounting/ProjBeginningBalanceCostSaleEntity</a>|
|[ItemSalesTaxGroup](#ItemSalesTaxGroup)||<a href="ProjBeginningBalanceCostSaleEntity.md" target="_blank">ProjectManagementAndAccounting/ProjBeginningBalanceCostSaleEntity</a>|
|[ProjectDate](#ProjectDate)||<a href="ProjBeginningBalanceCostSaleEntity.md" target="_blank">ProjectManagementAndAccounting/ProjBeginningBalanceCostSaleEntity</a>|
|[TransactionStatus](#TransactionStatus)||<a href="ProjBeginningBalanceCostSaleEntity.md" target="_blank">ProjectManagementAndAccounting/ProjBeginningBalanceCostSaleEntity</a>|
|[TransactionType](#TransactionType)||<a href="ProjBeginningBalanceCostSaleEntity.md" target="_blank">ProjectManagementAndAccounting/ProjBeginningBalanceCostSaleEntity</a>|
|[Quantity](#Quantity)||<a href="ProjBeginningBalanceCostSaleEntity.md" target="_blank">ProjectManagementAndAccounting/ProjBeginningBalanceCostSaleEntity</a>|
|[SalesPrice](#SalesPrice)||<a href="ProjBeginningBalanceCostSaleEntity.md" target="_blank">ProjectManagementAndAccounting/ProjBeginningBalanceCostSaleEntity</a>|
|[VoucherDate](#VoucherDate)||<a href="ProjBeginningBalanceCostSaleEntity.md" target="_blank">ProjectManagementAndAccounting/ProjBeginningBalanceCostSaleEntity</a>|
|[Description](#Description)||<a href="ProjBeginningBalanceCostSaleEntity.md" target="_blank">ProjectManagementAndAccounting/ProjBeginningBalanceCostSaleEntity</a>|
|[Voucher](#Voucher)||<a href="ProjBeginningBalanceCostSaleEntity.md" target="_blank">ProjectManagementAndAccounting/ProjBeginningBalanceCostSaleEntity</a>|
|[ResourceRecId](#ResourceRecId)||<a href="ProjBeginningBalanceCostSaleEntity.md" target="_blank">ProjectManagementAndAccounting/ProjBeginningBalanceCostSaleEntity</a>|
|[ResourceCategoryRecId](#ResourceCategoryRecId)||<a href="ProjBeginningBalanceCostSaleEntity.md" target="_blank">ProjectManagementAndAccounting/ProjBeginningBalanceCostSaleEntity</a>|
|[FundingSourceId](#FundingSourceId)||<a href="ProjBeginningBalanceCostSaleEntity.md" target="_blank">ProjectManagementAndAccounting/ProjBeginningBalanceCostSaleEntity</a>|
|[JournalId](#JournalId)||<a href="ProjBeginningBalanceCostSaleEntity.md" target="_blank">ProjectManagementAndAccounting/ProjBeginningBalanceCostSaleEntity</a>|
|[DefaultDimensionDisplayValue](#DefaultDimensionDisplayValue)||<a href="ProjBeginningBalanceCostSaleEntity.md" target="_blank">ProjectManagementAndAccounting/ProjBeginningBalanceCostSaleEntity</a>|
|[JournalDescription](#JournalDescription)||<a href="ProjBeginningBalanceCostSaleEntity.md" target="_blank">ProjectManagementAndAccounting/ProjBeginningBalanceCostSaleEntity</a>|
|[JournalDetailSummary](#JournalDetailSummary)||<a href="ProjBeginningBalanceCostSaleEntity.md" target="_blank">ProjectManagementAndAccounting/ProjBeginningBalanceCostSaleEntity</a>|
|[JournalName](#JournalName)||<a href="ProjBeginningBalanceCostSaleEntity.md" target="_blank">ProjectManagementAndAccounting/ProjBeginningBalanceCostSaleEntity</a>|
|[JournalType](#JournalType)||<a href="ProjBeginningBalanceCostSaleEntity.md" target="_blank">ProjectManagementAndAccounting/ProjBeginningBalanceCostSaleEntity</a>|
|[VoucherChange](#VoucherChange)||<a href="ProjBeginningBalanceCostSaleEntity.md" target="_blank">ProjectManagementAndAccounting/ProjBeginningBalanceCostSaleEntity</a>|
|[VoucherDraw](#VoucherDraw)||<a href="ProjBeginningBalanceCostSaleEntity.md" target="_blank">ProjectManagementAndAccounting/ProjBeginningBalanceCostSaleEntity</a>|
|[VoucherNumberSequenceTable](#VoucherNumberSequenceTable)||<a href="ProjBeginningBalanceCostSaleEntity.md" target="_blank">ProjectManagementAndAccounting/ProjBeginningBalanceCostSaleEntity</a>|
|[ContractId](#ContractId)||<a href="ProjBeginningBalanceCostSaleEntity.md" target="_blank">ProjectManagementAndAccounting/ProjBeginningBalanceCostSaleEntity</a>|
|[Resource](#Resource)||<a href="ProjBeginningBalanceCostSaleEntity.md" target="_blank">ProjectManagementAndAccounting/ProjBeginningBalanceCostSaleEntity</a>|
|[SalesAmount](#SalesAmount)||<a href="ProjBeginningBalanceCostSaleEntity.md" target="_blank">ProjectManagementAndAccounting/ProjBeginningBalanceCostSaleEntity</a>|
|[CostAmount](#CostAmount)||<a href="ProjBeginningBalanceCostSaleEntity.md" target="_blank">ProjectManagementAndAccounting/ProjBeginningBalanceCostSaleEntity</a>|
|[Relationship_DefaultDimensionDimensionSetRelationshipId](#Relationship_DefaultDimensionDimensionSetRelationshipId)||<a href="ProjBeginningBalanceCostSaleEntity.md" target="_blank">ProjectManagementAndAccounting/ProjBeginningBalanceCostSaleEntity</a>|
|[Relationship_ProjectRelationshipId](#Relationship_ProjectRelationshipId)||<a href="ProjBeginningBalanceCostSaleEntity.md" target="_blank">ProjectManagementAndAccounting/ProjBeginningBalanceCostSaleEntity</a>|
|[Relationship_ProjJournalTableEntityRelationshipId](#Relationship_ProjJournalTableEntityRelationshipId)||<a href="ProjBeginningBalanceCostSaleEntity.md" target="_blank">ProjectManagementAndAccounting/ProjBeginningBalanceCostSaleEntity</a>|
|[BackingTable_ProjBegBalJournalTrans_CostSalesRelationshipId](#BackingTable_ProjBegBalJournalTrans_CostSalesRelationshipId)||<a href="ProjBeginningBalanceCostSaleEntity.md" target="_blank">ProjectManagementAndAccounting/ProjBeginningBalanceCostSaleEntity</a>|
|[Relationship_PrimaryCompanyContextRelationshipId](#Relationship_PrimaryCompanyContextRelationshipId)||<a href="ProjBeginningBalanceCostSaleEntity.md" target="_blank">ProjectManagementAndAccounting/ProjBeginningBalanceCostSaleEntity</a>|

### <a href=#ActivityNumber name="ActivityNumber">ActivityNumber</a>

First included in: ProjectManagementAndAccounting/ProjBeginningBalanceCostSaleEntity (this entity)  

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

### <a href=#CostPrice name="CostPrice">CostPrice</a>

First included in: ProjectManagementAndAccounting/ProjBeginningBalanceCostSaleEntity (this entity)  

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

### <a href=#DefaultDimension name="DefaultDimension">DefaultDimension</a>

First included in: ProjectManagementAndAccounting/ProjBeginningBalanceCostSaleEntity (this entity)  

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

### <a href=#ItemId name="ItemId">ItemId</a>

First included in: ProjectManagementAndAccounting/ProjBeginningBalanceCostSaleEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ItemId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LineNumber name="LineNumber">LineNumber</a>

First included in: ProjectManagementAndAccounting/ProjBeginningBalanceCostSaleEntity (this entity)  

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

### <a href=#LinePropertyId name="LinePropertyId">LinePropertyId</a>

First included in: ProjectManagementAndAccounting/ProjBeginningBalanceCostSaleEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LinePropertyId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CanAccrueRevenue name="CanAccrueRevenue">CanAccrueRevenue</a>

First included in: ProjectManagementAndAccounting/ProjBeginningBalanceCostSaleEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CanAccrueRevenue attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CategoryId name="CategoryId">CategoryId</a>

First included in: ProjectManagementAndAccounting/ProjBeginningBalanceCostSaleEntity (this entity)  

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

### <a href=#ProjFundingSource name="ProjFundingSource">ProjFundingSource</a>

First included in: ProjectManagementAndAccounting/ProjBeginningBalanceCostSaleEntity (this entity)  

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

### <a href=#ProjectId name="ProjectId">ProjectId</a>

First included in: ProjectManagementAndAccounting/ProjBeginningBalanceCostSaleEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProjectId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CostStatus name="CostStatus">CostStatus</a>

First included in: ProjectManagementAndAccounting/ProjBeginningBalanceCostSaleEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CostStatus attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SalesCurrency name="SalesCurrency">SalesCurrency</a>

First included in: ProjectManagementAndAccounting/ProjBeginningBalanceCostSaleEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SalesCurrency attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SalesTaxGroup name="SalesTaxGroup">SalesTaxGroup</a>

First included in: ProjectManagementAndAccounting/ProjBeginningBalanceCostSaleEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SalesTaxGroup attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ItemSalesTaxGroup name="ItemSalesTaxGroup">ItemSalesTaxGroup</a>

First included in: ProjectManagementAndAccounting/ProjBeginningBalanceCostSaleEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ItemSalesTaxGroup attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProjectDate name="ProjectDate">ProjectDate</a>

First included in: ProjectManagementAndAccounting/ProjBeginningBalanceCostSaleEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProjectDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TransactionStatus name="TransactionStatus">TransactionStatus</a>

First included in: ProjectManagementAndAccounting/ProjBeginningBalanceCostSaleEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TransactionStatus attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TransactionType name="TransactionType">TransactionType</a>

First included in: ProjectManagementAndAccounting/ProjBeginningBalanceCostSaleEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TransactionType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Quantity name="Quantity">Quantity</a>

First included in: ProjectManagementAndAccounting/ProjBeginningBalanceCostSaleEntity (this entity)  

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

### <a href=#SalesPrice name="SalesPrice">SalesPrice</a>

First included in: ProjectManagementAndAccounting/ProjBeginningBalanceCostSaleEntity (this entity)  

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

### <a href=#VoucherDate name="VoucherDate">VoucherDate</a>

First included in: ProjectManagementAndAccounting/ProjBeginningBalanceCostSaleEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VoucherDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Description name="Description">Description</a>

First included in: ProjectManagementAndAccounting/ProjBeginningBalanceCostSaleEntity (this entity)  

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

### <a href=#Voucher name="Voucher">Voucher</a>

First included in: ProjectManagementAndAccounting/ProjBeginningBalanceCostSaleEntity (this entity)  

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

### <a href=#ResourceRecId name="ResourceRecId">ResourceRecId</a>

First included in: ProjectManagementAndAccounting/ProjBeginningBalanceCostSaleEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ResourceRecId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ResourceCategoryRecId name="ResourceCategoryRecId">ResourceCategoryRecId</a>

First included in: ProjectManagementAndAccounting/ProjBeginningBalanceCostSaleEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ResourceCategoryRecId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FundingSourceId name="FundingSourceId">FundingSourceId</a>

First included in: ProjectManagementAndAccounting/ProjBeginningBalanceCostSaleEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FundingSourceId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#JournalId name="JournalId">JournalId</a>

First included in: ProjectManagementAndAccounting/ProjBeginningBalanceCostSaleEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the JournalId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DefaultDimensionDisplayValue name="DefaultDimensionDisplayValue">DefaultDimensionDisplayValue</a>

First included in: ProjectManagementAndAccounting/ProjBeginningBalanceCostSaleEntity (this entity)  

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

### <a href=#JournalDescription name="JournalDescription">JournalDescription</a>

First included in: ProjectManagementAndAccounting/ProjBeginningBalanceCostSaleEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the JournalDescription attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#JournalDetailSummary name="JournalDetailSummary">JournalDetailSummary</a>

First included in: ProjectManagementAndAccounting/ProjBeginningBalanceCostSaleEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the JournalDetailSummary attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#JournalName name="JournalName">JournalName</a>

First included in: ProjectManagementAndAccounting/ProjBeginningBalanceCostSaleEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Journal name</td></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the JournalName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Journal name</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#JournalType name="JournalType">JournalType</a>

First included in: ProjectManagementAndAccounting/ProjBeginningBalanceCostSaleEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the JournalType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#VoucherChange name="VoucherChange">VoucherChange</a>

First included in: ProjectManagementAndAccounting/ProjBeginningBalanceCostSaleEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VoucherChange attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#VoucherDraw name="VoucherDraw">VoucherDraw</a>

First included in: ProjectManagementAndAccounting/ProjBeginningBalanceCostSaleEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VoucherDraw attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#VoucherNumberSequenceTable name="VoucherNumberSequenceTable">VoucherNumberSequenceTable</a>

First included in: ProjectManagementAndAccounting/ProjBeginningBalanceCostSaleEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VoucherNumberSequenceTable attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ContractId name="ContractId">ContractId</a>

First included in: ProjectManagementAndAccounting/ProjBeginningBalanceCostSaleEntity (this entity)  

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

### <a href=#Resource name="Resource">Resource</a>

First included in: ProjectManagementAndAccounting/ProjBeginningBalanceCostSaleEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Resource ID</td></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Resource attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Resource ID</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SalesAmount name="SalesAmount">SalesAmount</a>

First included in: ProjectManagementAndAccounting/ProjBeginningBalanceCostSaleEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SalesAmount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CostAmount name="CostAmount">CostAmount</a>

First included in: ProjectManagementAndAccounting/ProjBeginningBalanceCostSaleEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CostAmount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_DefaultDimensionDimensionSetRelationshipId name="Relationship_DefaultDimensionDimensionSetRelationshipId">Relationship_DefaultDimensionDimensionSetRelationshipId</a>

First included in: ProjectManagementAndAccounting/ProjBeginningBalanceCostSaleEntity (this entity)  

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

### <a href=#Relationship_ProjectRelationshipId name="Relationship_ProjectRelationshipId">Relationship_ProjectRelationshipId</a>

First included in: ProjectManagementAndAccounting/ProjBeginningBalanceCostSaleEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_ProjectRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_ProjJournalTableEntityRelationshipId name="Relationship_ProjJournalTableEntityRelationshipId">Relationship_ProjJournalTableEntityRelationshipId</a>

First included in: ProjectManagementAndAccounting/ProjBeginningBalanceCostSaleEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_ProjJournalTableEntityRelationshipId attribute are listed below.</summary>

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

### <a href=#BackingTable_ProjBegBalJournalTrans_CostSalesRelationshipId name="BackingTable_ProjBegBalJournalTrans_CostSalesRelationshipId">BackingTable_ProjBegBalJournalTrans_CostSalesRelationshipId</a>

First included in: ProjectManagementAndAccounting/ProjBeginningBalanceCostSaleEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_ProjBegBalJournalTrans_CostSalesRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/ProfessionalServices/ProjectManagementAndAccounting/WorksheetLine/ProjBegBalJournalTrans_CostSales.md" target="_blank">/core/operationsCommon/Tables/ProfessionalServices/ProjectManagementAndAccounting/WorksheetLine/ProjBegBalJournalTrans_CostSales.cdm.json/ProjBegBalJournalTrans_CostSales</a></td><td><a href="../../../Tables/ProfessionalServices/ProjectManagementAndAccounting/WorksheetLine/ProjBegBalJournalTrans_CostSales.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PrimaryCompanyContextRelationshipId name="Relationship_PrimaryCompanyContextRelationshipId">Relationship_PrimaryCompanyContextRelationshipId</a>

First included in: ProjectManagementAndAccounting/ProjBeginningBalanceCostSaleEntity (this entity)  

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
