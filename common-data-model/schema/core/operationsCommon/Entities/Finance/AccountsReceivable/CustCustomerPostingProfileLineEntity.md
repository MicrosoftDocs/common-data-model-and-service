---
title: CustCustomerPostingProfileLineEntity in AccountsReceivable - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 7/13/2020
ms.author: nebanfic
---

# Customer ledger accounts in AccountsReceivable(CustCustomerPostingProfileLineEntity)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/Finance/AccountsReceivable/CustCustomerPostingProfileLineEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Customer ledger accounts</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[LiabilitiesForDiscountMainAccountId](#LiabilitiesForDiscountMainAccountId)||<a href="CustCustomerPostingProfileLineEntity.md" target="_blank">AccountsReceivable/CustCustomerPostingProfileLineEntity</a>|
|[SummaryMainAccountId](#SummaryMainAccountId)||<a href="CustCustomerPostingProfileLineEntity.md" target="_blank">AccountsReceivable/CustCustomerPostingProfileLineEntity</a>|
|[SalesTaxPrepaymentsMainAccountId](#SalesTaxPrepaymentsMainAccountId)||<a href="CustCustomerPostingProfileLineEntity.md" target="_blank">AccountsReceivable/CustCustomerPostingProfileLineEntity</a>|
|[WriteOffMainAccountId](#WriteOffMainAccountId)||<a href="CustCustomerPostingProfileLineEntity.md" target="_blank">AccountsReceivable/CustCustomerPostingProfileLineEntity</a>|
|[EndorseMainAccountId](#EndorseMainAccountId)||<a href="CustCustomerPostingProfileLineEntity.md" target="_blank">AccountsReceivable/CustCustomerPostingProfileLineEntity</a>|
|[CustInterest](#CustInterest)||<a href="CustCustomerPostingProfileLineEntity.md" target="_blank">AccountsReceivable/CustCustomerPostingProfileLineEntity</a>|
|[PostingProfile](#PostingProfile)||<a href="CustCustomerPostingProfileLineEntity.md" target="_blank">AccountsReceivable/CustCustomerPostingProfileLineEntity</a>|
|[Description](#Description)||<a href="CustCustomerPostingProfileLineEntity.md" target="_blank">AccountsReceivable/CustCustomerPostingProfileLineEntity</a>|
|[AccountCode](#AccountCode)||<a href="CustCustomerPostingProfileLineEntity.md" target="_blank">AccountsReceivable/CustCustomerPostingProfileLineEntity</a>|
|[AccountOrGroupNumber](#AccountOrGroupNumber)||<a href="CustCustomerPostingProfileLineEntity.md" target="_blank">AccountsReceivable/CustCustomerPostingProfileLineEntity</a>|
|[InterestCode](#InterestCode)||<a href="CustCustomerPostingProfileLineEntity.md" target="_blank">AccountsReceivable/CustCustomerPostingProfileLineEntity</a>|
|[CollectionLetterSequence](#CollectionLetterSequence)||<a href="CustCustomerPostingProfileLineEntity.md" target="_blank">AccountsReceivable/CustCustomerPostingProfileLineEntity</a>|
|[LiabilitiesForDiscountMainAccountIdDisplayValue](#LiabilitiesForDiscountMainAccountIdDisplayValue)||<a href="CustCustomerPostingProfileLineEntity.md" target="_blank">AccountsReceivable/CustCustomerPostingProfileLineEntity</a>|
|[SummaryMainAccountIdDisplayValue](#SummaryMainAccountIdDisplayValue)||<a href="CustCustomerPostingProfileLineEntity.md" target="_blank">AccountsReceivable/CustCustomerPostingProfileLineEntity</a>|
|[SalesTaxPrepaymentsMainAccountIdDisplayValue](#SalesTaxPrepaymentsMainAccountIdDisplayValue)||<a href="CustCustomerPostingProfileLineEntity.md" target="_blank">AccountsReceivable/CustCustomerPostingProfileLineEntity</a>|
|[WriteOffMainAccountIdDisplayValue](#WriteOffMainAccountIdDisplayValue)||<a href="CustCustomerPostingProfileLineEntity.md" target="_blank">AccountsReceivable/CustCustomerPostingProfileLineEntity</a>|
|[EndorseMainAccountIdDisplayValue](#EndorseMainAccountIdDisplayValue)||<a href="CustCustomerPostingProfileLineEntity.md" target="_blank">AccountsReceivable/CustCustomerPostingProfileLineEntity</a>|
|[FineAccount](#FineAccount)||<a href="CustCustomerPostingProfileLineEntity.md" target="_blank">AccountsReceivable/CustCustomerPostingProfileLineEntity</a>|
|[FinancialInterestAccount](#FinancialInterestAccount)||<a href="CustCustomerPostingProfileLineEntity.md" target="_blank">AccountsReceivable/CustCustomerPostingProfileLineEntity</a>|
|[TaxTransferAccount](#TaxTransferAccount)||<a href="CustCustomerPostingProfileLineEntity.md" target="_blank">AccountsReceivable/CustCustomerPostingProfileLineEntity</a>|
|[FineAccountDisplayValue](#FineAccountDisplayValue)||<a href="CustCustomerPostingProfileLineEntity.md" target="_blank">AccountsReceivable/CustCustomerPostingProfileLineEntity</a>|
|[FinancialInterestAccountDisplayValue](#FinancialInterestAccountDisplayValue)||<a href="CustCustomerPostingProfileLineEntity.md" target="_blank">AccountsReceivable/CustCustomerPostingProfileLineEntity</a>|
|[TaxTransferAccountDisplayValue](#TaxTransferAccountDisplayValue)||<a href="CustCustomerPostingProfileLineEntity.md" target="_blank">AccountsReceivable/CustCustomerPostingProfileLineEntity</a>|
|[ExportSale](#ExportSale)||<a href="CustCustomerPostingProfileLineEntity.md" target="_blank">AccountsReceivable/CustCustomerPostingProfileLineEntity</a>|
|[ExportSaleDisplayValue](#ExportSaleDisplayValue)||<a href="CustCustomerPostingProfileLineEntity.md" target="_blank">AccountsReceivable/CustCustomerPostingProfileLineEntity</a>|
|[SettleAccount](#SettleAccount)||<a href="CustCustomerPostingProfileLineEntity.md" target="_blank">AccountsReceivable/CustCustomerPostingProfileLineEntity</a>|
|[SettleAccountDisplayValue](#SettleAccountDisplayValue)||<a href="CustCustomerPostingProfileLineEntity.md" target="_blank">AccountsReceivable/CustCustomerPostingProfileLineEntity</a>|
|[HierarchyName](#HierarchyName)||<a href="CustCustomerPostingProfileLineEntity.md" target="_blank">AccountsReceivable/CustCustomerPostingProfileLineEntity</a>|
|[HierarchyType](#HierarchyType)||<a href="CustCustomerPostingProfileLineEntity.md" target="_blank">AccountsReceivable/CustCustomerPostingProfileLineEntity</a>|
|[HierarchyStatus](#HierarchyStatus)||<a href="CustCustomerPostingProfileLineEntity.md" target="_blank">AccountsReceivable/CustCustomerPostingProfileLineEntity</a>|
|[Relationship_LiabilitiesForDiscountLedgerDimensionCombinationRelationshipId](#Relationship_LiabilitiesForDiscountLedgerDimensionCombinationRelationshipId)||<a href="CustCustomerPostingProfileLineEntity.md" target="_blank">AccountsReceivable/CustCustomerPostingProfileLineEntity</a>|
|[Relationship_SummaryLedgerDimensionCombinationRelationshipId](#Relationship_SummaryLedgerDimensionCombinationRelationshipId)||<a href="CustCustomerPostingProfileLineEntity.md" target="_blank">AccountsReceivable/CustCustomerPostingProfileLineEntity</a>|
|[Relationship_VATPrepaymentsLedgerDimensionCombinationRelationshipId](#Relationship_VATPrepaymentsLedgerDimensionCombinationRelationshipId)||<a href="CustCustomerPostingProfileLineEntity.md" target="_blank">AccountsReceivable/CustCustomerPostingProfileLineEntity</a>|
|[Relationship_WriteOffLedgerDimensionCombinationRelationshipId](#Relationship_WriteOffLedgerDimensionCombinationRelationshipId)||<a href="CustCustomerPostingProfileLineEntity.md" target="_blank">AccountsReceivable/CustCustomerPostingProfileLineEntity</a>|
|[Relationship_EndorseLedgerDimensionCombinationRelationshipId](#Relationship_EndorseLedgerDimensionCombinationRelationshipId)||<a href="CustCustomerPostingProfileLineEntity.md" target="_blank">AccountsReceivable/CustCustomerPostingProfileLineEntity</a>|
|[Relationship_HeaderPostingProfileRelationshipId](#Relationship_HeaderPostingProfileRelationshipId)||<a href="CustCustomerPostingProfileLineEntity.md" target="_blank">AccountsReceivable/CustCustomerPostingProfileLineEntity</a>|
|[Relationship_SettleAccountCombinationRelationshipId](#Relationship_SettleAccountCombinationRelationshipId)||<a href="CustCustomerPostingProfileLineEntity.md" target="_blank">AccountsReceivable/CustCustomerPostingProfileLineEntity</a>|
|[BackingTable_CustLedgerAccountsRelationshipId](#BackingTable_CustLedgerAccountsRelationshipId)||<a href="CustCustomerPostingProfileLineEntity.md" target="_blank">AccountsReceivable/CustCustomerPostingProfileLineEntity</a>|
|[Relationship_PrimaryCompanyContextRelationshipId](#Relationship_PrimaryCompanyContextRelationshipId)||<a href="CustCustomerPostingProfileLineEntity.md" target="_blank">AccountsReceivable/CustCustomerPostingProfileLineEntity</a>|

### <a href=#LiabilitiesForDiscountMainAccountId name="LiabilitiesForDiscountMainAccountId">LiabilitiesForDiscountMainAccountId</a>

First included in: AccountsReceivable/CustCustomerPostingProfileLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LiabilitiesForDiscountMainAccountId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SummaryMainAccountId name="SummaryMainAccountId">SummaryMainAccountId</a>

First included in: AccountsReceivable/CustCustomerPostingProfileLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SummaryMainAccountId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SalesTaxPrepaymentsMainAccountId name="SalesTaxPrepaymentsMainAccountId">SalesTaxPrepaymentsMainAccountId</a>

First included in: AccountsReceivable/CustCustomerPostingProfileLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SalesTaxPrepaymentsMainAccountId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WriteOffMainAccountId name="WriteOffMainAccountId">WriteOffMainAccountId</a>

First included in: AccountsReceivable/CustCustomerPostingProfileLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WriteOffMainAccountId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#EndorseMainAccountId name="EndorseMainAccountId">EndorseMainAccountId</a>

First included in: AccountsReceivable/CustCustomerPostingProfileLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EndorseMainAccountId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CustInterest name="CustInterest">CustInterest</a>

First included in: AccountsReceivable/CustCustomerPostingProfileLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CustInterest attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PostingProfile name="PostingProfile">PostingProfile</a>

First included in: AccountsReceivable/CustCustomerPostingProfileLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PostingProfile attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Description name="Description">Description</a>

First included in: AccountsReceivable/CustCustomerPostingProfileLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Description attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AccountCode name="AccountCode">AccountCode</a>

First included in: AccountsReceivable/CustCustomerPostingProfileLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AccountCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AccountOrGroupNumber name="AccountOrGroupNumber">AccountOrGroupNumber</a>

First included in: AccountsReceivable/CustCustomerPostingProfileLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AccountOrGroupNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InterestCode name="InterestCode">InterestCode</a>

First included in: AccountsReceivable/CustCustomerPostingProfileLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InterestCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CollectionLetterSequence name="CollectionLetterSequence">CollectionLetterSequence</a>

First included in: AccountsReceivable/CustCustomerPostingProfileLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CollectionLetterSequence attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LiabilitiesForDiscountMainAccountIdDisplayValue name="LiabilitiesForDiscountMainAccountIdDisplayValue">LiabilitiesForDiscountMainAccountIdDisplayValue</a>

First included in: AccountsReceivable/CustCustomerPostingProfileLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Liabilities for discount account</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LiabilitiesForDiscountMainAccountIdDisplayValue attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Liabilities for discount account</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SummaryMainAccountIdDisplayValue name="SummaryMainAccountIdDisplayValue">SummaryMainAccountIdDisplayValue</a>

First included in: AccountsReceivable/CustCustomerPostingProfileLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Summary account</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SummaryMainAccountIdDisplayValue attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Summary account</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SalesTaxPrepaymentsMainAccountIdDisplayValue name="SalesTaxPrepaymentsMainAccountIdDisplayValue">SalesTaxPrepaymentsMainAccountIdDisplayValue</a>

First included in: AccountsReceivable/CustCustomerPostingProfileLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Sales tax prepayments</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SalesTaxPrepaymentsMainAccountIdDisplayValue attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Sales tax prepayments</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WriteOffMainAccountIdDisplayValue name="WriteOffMainAccountIdDisplayValue">WriteOffMainAccountIdDisplayValue</a>

First included in: AccountsReceivable/CustCustomerPostingProfileLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Write-off account</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WriteOffMainAccountIdDisplayValue attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Write-off account</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#EndorseMainAccountIdDisplayValue name="EndorseMainAccountIdDisplayValue">EndorseMainAccountIdDisplayValue</a>

First included in: AccountsReceivable/CustCustomerPostingProfileLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Endorse account</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EndorseMainAccountIdDisplayValue attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Endorse account</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FineAccount name="FineAccount">FineAccount</a>

First included in: AccountsReceivable/CustCustomerPostingProfileLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FineAccount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FinancialInterestAccount name="FinancialInterestAccount">FinancialInterestAccount</a>

First included in: AccountsReceivable/CustCustomerPostingProfileLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FinancialInterestAccount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TaxTransferAccount name="TaxTransferAccount">TaxTransferAccount</a>

First included in: AccountsReceivable/CustCustomerPostingProfileLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxTransferAccount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FineAccountDisplayValue name="FineAccountDisplayValue">FineAccountDisplayValue</a>

First included in: AccountsReceivable/CustCustomerPostingProfileLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Fine</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FineAccountDisplayValue attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Fine</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FinancialInterestAccountDisplayValue name="FinancialInterestAccountDisplayValue">FinancialInterestAccountDisplayValue</a>

First included in: AccountsReceivable/CustCustomerPostingProfileLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Financial interest</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FinancialInterestAccountDisplayValue attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Financial interest</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TaxTransferAccountDisplayValue name="TaxTransferAccountDisplayValue">TaxTransferAccountDisplayValue</a>

First included in: AccountsReceivable/CustCustomerPostingProfileLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Tax transfer</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxTransferAccountDisplayValue attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Tax transfer</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ExportSale name="ExportSale">ExportSale</a>

First included in: AccountsReceivable/CustCustomerPostingProfileLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ExportSale attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ExportSaleDisplayValue name="ExportSaleDisplayValue">ExportSaleDisplayValue</a>

First included in: AccountsReceivable/CustCustomerPostingProfileLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ExportSaleDisplayValue attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SettleAccount name="SettleAccount">SettleAccount</a>

First included in: AccountsReceivable/CustCustomerPostingProfileLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SettleAccount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SettleAccountDisplayValue name="SettleAccountDisplayValue">SettleAccountDisplayValue</a>

First included in: AccountsReceivable/CustCustomerPostingProfileLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SettleAccountDisplayValue attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#HierarchyName name="HierarchyName">HierarchyName</a>

First included in: AccountsReceivable/CustCustomerPostingProfileLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the HierarchyName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#HierarchyType name="HierarchyType">HierarchyType</a>

First included in: AccountsReceivable/CustCustomerPostingProfileLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the HierarchyType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#HierarchyStatus name="HierarchyStatus">HierarchyStatus</a>

First included in: AccountsReceivable/CustCustomerPostingProfileLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the HierarchyStatus attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_LiabilitiesForDiscountLedgerDimensionCombinationRelationshipId name="Relationship_LiabilitiesForDiscountLedgerDimensionCombinationRelationshipId">Relationship_LiabilitiesForDiscountLedgerDimensionCombinationRelationshipId</a>

First included in: AccountsReceivable/CustCustomerPostingProfileLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_LiabilitiesForDiscountLedgerDimensionCombinationRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_SummaryLedgerDimensionCombinationRelationshipId name="Relationship_SummaryLedgerDimensionCombinationRelationshipId">Relationship_SummaryLedgerDimensionCombinationRelationshipId</a>

First included in: AccountsReceivable/CustCustomerPostingProfileLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_SummaryLedgerDimensionCombinationRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_VATPrepaymentsLedgerDimensionCombinationRelationshipId name="Relationship_VATPrepaymentsLedgerDimensionCombinationRelationshipId">Relationship_VATPrepaymentsLedgerDimensionCombinationRelationshipId</a>

First included in: AccountsReceivable/CustCustomerPostingProfileLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_VATPrepaymentsLedgerDimensionCombinationRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_WriteOffLedgerDimensionCombinationRelationshipId name="Relationship_WriteOffLedgerDimensionCombinationRelationshipId">Relationship_WriteOffLedgerDimensionCombinationRelationshipId</a>

First included in: AccountsReceivable/CustCustomerPostingProfileLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_WriteOffLedgerDimensionCombinationRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_EndorseLedgerDimensionCombinationRelationshipId name="Relationship_EndorseLedgerDimensionCombinationRelationshipId">Relationship_EndorseLedgerDimensionCombinationRelationshipId</a>

First included in: AccountsReceivable/CustCustomerPostingProfileLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_EndorseLedgerDimensionCombinationRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_HeaderPostingProfileRelationshipId name="Relationship_HeaderPostingProfileRelationshipId">Relationship_HeaderPostingProfileRelationshipId</a>

First included in: AccountsReceivable/CustCustomerPostingProfileLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_HeaderPostingProfileRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_SettleAccountCombinationRelationshipId name="Relationship_SettleAccountCombinationRelationshipId">Relationship_SettleAccountCombinationRelationshipId</a>

First included in: AccountsReceivable/CustCustomerPostingProfileLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_SettleAccountCombinationRelationshipId attribute are listed below.</summary>

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

### <a href=#BackingTable_CustLedgerAccountsRelationshipId name="BackingTable_CustLedgerAccountsRelationshipId">BackingTable_CustLedgerAccountsRelationshipId</a>

First included in: AccountsReceivable/CustCustomerPostingProfileLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_CustLedgerAccountsRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/Finance/AccountsReceivable/Group/CustLedgerAccounts.md" target="_blank">/core/operationsCommon/Tables/Finance/AccountsReceivable/Group/CustLedgerAccounts.cdm.json/CustLedgerAccounts</a></td><td><a href="../../../Tables/Finance/AccountsReceivable/Group/CustLedgerAccounts.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PrimaryCompanyContextRelationshipId name="Relationship_PrimaryCompanyContextRelationshipId">Relationship_PrimaryCompanyContextRelationshipId</a>

First included in: AccountsReceivable/CustCustomerPostingProfileLineEntity (this entity)  

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
