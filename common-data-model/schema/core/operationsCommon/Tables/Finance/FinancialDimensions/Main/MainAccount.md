---
title: MainAccount - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/20/2020
ms.author: nebanfic
---

# MainAccount

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Tables/Finance/FinancialDimensions/Main/MainAccount.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[MainAccount/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="MainAccount.md" target="_blank">Main/MainAccount</a>|
|[AccountCategoryRef](#AccountCategoryRef)||<a href="MainAccount.md" target="_blank">Main/MainAccount</a>|
|[AdjustmentMethod_MX](#AdjustmentMethod_MX)||<a href="MainAccount.md" target="_blank">Main/MainAccount</a>|
|[CloseType](#CloseType)||<a href="MainAccount.md" target="_blank">Main/MainAccount</a>|
|[Closing](#Closing)||<a href="MainAccount.md" target="_blank">Main/MainAccount</a>|
|[ConsolidationMainAccount](#ConsolidationMainAccount)||<a href="MainAccount.md" target="_blank">Main/MainAccount</a>|
|[CurrencyCode](#CurrencyCode)||<a href="MainAccount.md" target="_blank">Main/MainAccount</a>|
|[DebitCreditBalanceDemand](#DebitCreditBalanceDemand)||<a href="MainAccount.md" target="_blank">Main/MainAccount</a>|
|[DebitCreditCheck](#DebitCreditCheck)||<a href="MainAccount.md" target="_blank">Main/MainAccount</a>|
|[DebitCreditProposal](#DebitCreditProposal)||<a href="MainAccount.md" target="_blank">Main/MainAccount</a>|
|[ExchangeAdjusted](#ExchangeAdjusted)||<a href="MainAccount.md" target="_blank">Main/MainAccount</a>|
|[ExchangeAdjustmentRateType](#ExchangeAdjustmentRateType)||<a href="MainAccount.md" target="_blank">Main/MainAccount</a>|
|[FinancialReportingExchangeRateType](#FinancialReportingExchangeRateType)||<a href="MainAccount.md" target="_blank">Main/MainAccount</a>|
|[FinancialReportingTranslationType](#FinancialReportingTranslationType)||<a href="MainAccount.md" target="_blank">Main/MainAccount</a>|
|[InflationAdjustment_MX](#InflationAdjustment_MX)||<a href="MainAccount.md" target="_blank">Main/MainAccount</a>|
|[LedgerChartOfAccounts](#LedgerChartOfAccounts)||<a href="MainAccount.md" target="_blank">Main/MainAccount</a>|
|[MainAccountId](#MainAccountId)||<a href="MainAccount.md" target="_blank">Main/MainAccount</a>|
|[MainAccountTemplate](#MainAccountTemplate)||<a href="MainAccount.md" target="_blank">Main/MainAccount</a>|
|[MandatoryPaymentReference](#MandatoryPaymentReference)||<a href="MainAccount.md" target="_blank">Main/MainAccount</a>|
|[Monetary](#Monetary)||<a href="MainAccount.md" target="_blank">Main/MainAccount</a>|
|[Name](#Name)||<a href="MainAccount.md" target="_blank">Main/MainAccount</a>|
|[OffsetLedgerDimension](#OffsetLedgerDimension)||<a href="MainAccount.md" target="_blank">Main/MainAccount</a>|
|[OpeningAccount](#OpeningAccount)||<a href="MainAccount.md" target="_blank">Main/MainAccount</a>|
|[ParentMainAccount](#ParentMainAccount)||<a href="MainAccount.md" target="_blank">Main/MainAccount</a>|
|[PostingType](#PostingType)||<a href="MainAccount.md" target="_blank">Main/MainAccount</a>|
|[RepomoType_MX](#RepomoType_MX)||<a href="MainAccount.md" target="_blank">Main/MainAccount</a>|
|[ReportingAccountType](#ReportingAccountType)||<a href="MainAccount.md" target="_blank">Main/MainAccount</a>|
|[SRUCode](#SRUCode)||<a href="MainAccount.md" target="_blank">Main/MainAccount</a>|
|[TransferYearEndAccount_ES](#TransferYearEndAccount_ES)||<a href="MainAccount.md" target="_blank">Main/MainAccount</a>|
|[Type](#Type)||<a href="MainAccount.md" target="_blank">Main/MainAccount</a>|
|[UnitOfMeasure](#UnitOfMeasure)||<a href="MainAccount.md" target="_blank">Main/MainAccount</a>|
|[UserInfoId](#UserInfoId)||<a href="MainAccount.md" target="_blank">Main/MainAccount</a>|
|[ValidateCurrency](#ValidateCurrency)||<a href="MainAccount.md" target="_blank">Main/MainAccount</a>|
|[ValidatePosting](#ValidatePosting)||<a href="MainAccount.md" target="_blank">Main/MainAccount</a>|
|[ValidateUser](#ValidateUser)||<a href="MainAccount.md" target="_blank">Main/MainAccount</a>|
|[ParentMainAccount_BR](#ParentMainAccount_BR)||<a href="MainAccount.md" target="_blank">Main/MainAccount</a>|
|[ReportingExchangeAdjustmentRateType](#ReportingExchangeAdjustmentRateType)||<a href="MainAccount.md" target="_blank">Main/MainAccount</a>|
|[StandardMainAccount_W](#StandardMainAccount_W)||<a href="MainAccount.md" target="_blank">Main/MainAccount</a>|
|[Relationship_CurrencyRelationshipId](#Relationship_CurrencyRelationshipId)||<a href="MainAccount.md" target="_blank">Main/MainAccount</a>|
|[Relationship_FinancialReportingExchangeRateTypeRelationshipId](#Relationship_FinancialReportingExchangeRateTypeRelationshipId)||<a href="MainAccount.md" target="_blank">Main/MainAccount</a>|
|[Relationship_LedgerChartOfAccountsRelationshipId](#Relationship_LedgerChartOfAccountsRelationshipId)||<a href="MainAccount.md" target="_blank">Main/MainAccount</a>|
|[Relationship_MainAccountCategoryRelationshipId](#Relationship_MainAccountCategoryRelationshipId)||<a href="MainAccount.md" target="_blank">Main/MainAccount</a>|
|[Relationship_OffsetLedgerDimensionRelationshipId](#Relationship_OffsetLedgerDimensionRelationshipId)||<a href="MainAccount.md" target="_blank">Main/MainAccount</a>|
|[Relationship_ExchangeAdjustmentRateTypeRelationshipId](#Relationship_ExchangeAdjustmentRateTypeRelationshipId)||<a href="MainAccount.md" target="_blank">Main/MainAccount</a>|
|[Relationship_ReportingExchangeAdjustmentRateTypeRelationshipId](#Relationship_ReportingExchangeAdjustmentRateTypeRelationshipId)||<a href="MainAccount.md" target="_blank">Main/MainAccount</a>|
|[Relationship_MainAccountTemplateRelationshipId](#Relationship_MainAccountTemplateRelationshipId)||<a href="MainAccount.md" target="_blank">Main/MainAccount</a>|
|[Relationship_StandardMainAccount_WRelationshipId](#Relationship_StandardMainAccount_WRelationshipId)||<a href="MainAccount.md" target="_blank">Main/MainAccount</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: Main/MainAccount (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[MainAccount/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#AccountCategoryRef name="AccountCategoryRef">AccountCategoryRef</a>

First included in: Main/MainAccount (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AccountCategoryRef attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#AdjustmentMethod_MX name="AdjustmentMethod_MX">AdjustmentMethod_MX</a>

First included in: Main/MainAccount (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AdjustmentMethod_MX attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#CloseType name="CloseType">CloseType</a>

First included in: Main/MainAccount (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CloseType attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#Closing name="Closing">Closing</a>

First included in: Main/MainAccount (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Closing attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#ConsolidationMainAccount name="ConsolidationMainAccount">ConsolidationMainAccount</a>

First included in: Main/MainAccount (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ConsolidationMainAccount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CurrencyCode name="CurrencyCode">CurrencyCode</a>

First included in: Main/MainAccount (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CurrencyCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DebitCreditBalanceDemand name="DebitCreditBalanceDemand">DebitCreditBalanceDemand</a>

First included in: Main/MainAccount (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DebitCreditBalanceDemand attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#DebitCreditCheck name="DebitCreditCheck">DebitCreditCheck</a>

First included in: Main/MainAccount (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DebitCreditCheck attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#DebitCreditProposal name="DebitCreditProposal">DebitCreditProposal</a>

First included in: Main/MainAccount (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DebitCreditProposal attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#ExchangeAdjusted name="ExchangeAdjusted">ExchangeAdjusted</a>

First included in: Main/MainAccount (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ExchangeAdjusted attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#ExchangeAdjustmentRateType name="ExchangeAdjustmentRateType">ExchangeAdjustmentRateType</a>

First included in: Main/MainAccount (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ExchangeAdjustmentRateType attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#FinancialReportingExchangeRateType name="FinancialReportingExchangeRateType">FinancialReportingExchangeRateType</a>

First included in: Main/MainAccount (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FinancialReportingExchangeRateType attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#FinancialReportingTranslationType name="FinancialReportingTranslationType">FinancialReportingTranslationType</a>

First included in: Main/MainAccount (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FinancialReportingTranslationType attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#InflationAdjustment_MX name="InflationAdjustment_MX">InflationAdjustment_MX</a>

First included in: Main/MainAccount (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InflationAdjustment_MX attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#LedgerChartOfAccounts name="LedgerChartOfAccounts">LedgerChartOfAccounts</a>

First included in: Main/MainAccount (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LedgerChartOfAccounts attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#MainAccountId name="MainAccountId">MainAccountId</a>

First included in: Main/MainAccount (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MainAccountId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MainAccountTemplate name="MainAccountTemplate">MainAccountTemplate</a>

First included in: Main/MainAccount (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MainAccountTemplate attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#MandatoryPaymentReference name="MandatoryPaymentReference">MandatoryPaymentReference</a>

First included in: Main/MainAccount (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MandatoryPaymentReference attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#Monetary name="Monetary">Monetary</a>

First included in: Main/MainAccount (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Monetary attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#Name name="Name">Name</a>

First included in: Main/MainAccount (this entity)  

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

### <a href=#OffsetLedgerDimension name="OffsetLedgerDimension">OffsetLedgerDimension</a>

First included in: Main/MainAccount (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OffsetLedgerDimension attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#OpeningAccount name="OpeningAccount">OpeningAccount</a>

First included in: Main/MainAccount (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OpeningAccount attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#ParentMainAccount name="ParentMainAccount">ParentMainAccount</a>

First included in: Main/MainAccount (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ParentMainAccount attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#PostingType name="PostingType">PostingType</a>

First included in: Main/MainAccount (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PostingType attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#RepomoType_MX name="RepomoType_MX">RepomoType_MX</a>

First included in: Main/MainAccount (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RepomoType_MX attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#ReportingAccountType name="ReportingAccountType">ReportingAccountType</a>

First included in: Main/MainAccount (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReportingAccountType attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#SRUCode name="SRUCode">SRUCode</a>

First included in: Main/MainAccount (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SRUCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TransferYearEndAccount_ES name="TransferYearEndAccount_ES">TransferYearEndAccount_ES</a>

First included in: Main/MainAccount (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TransferYearEndAccount_ES attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#Type name="Type">Type</a>

First included in: Main/MainAccount (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Type attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#UnitOfMeasure name="UnitOfMeasure">UnitOfMeasure</a>

First included in: Main/MainAccount (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the UnitOfMeasure attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#UserInfoId name="UserInfoId">UserInfoId</a>

First included in: Main/MainAccount (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the UserInfoId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ValidateCurrency name="ValidateCurrency">ValidateCurrency</a>

First included in: Main/MainAccount (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ValidateCurrency attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#ValidatePosting name="ValidatePosting">ValidatePosting</a>

First included in: Main/MainAccount (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ValidatePosting attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#ValidateUser name="ValidateUser">ValidateUser</a>

First included in: Main/MainAccount (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ValidateUser attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#ParentMainAccount_BR name="ParentMainAccount_BR">ParentMainAccount_BR</a>

First included in: Main/MainAccount (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ParentMainAccount_BR attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#ReportingExchangeAdjustmentRateType name="ReportingExchangeAdjustmentRateType">ReportingExchangeAdjustmentRateType</a>

First included in: Main/MainAccount (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReportingExchangeAdjustmentRateType attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#StandardMainAccount_W name="StandardMainAccount_W">StandardMainAccount_W</a>

First included in: Main/MainAccount (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the StandardMainAccount_W attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#Relationship_CurrencyRelationshipId name="Relationship_CurrencyRelationshipId">Relationship_CurrencyRelationshipId</a>

First included in: Main/MainAccount (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_CurrencyRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Common/Currency/Group/Currency.md" target="_blank">/core/operationsCommon/Tables/Common/Currency/Group/Currency.cdm.json/Currency</a></td><td><a href="../../../Common/Currency/Group/Currency.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_FinancialReportingExchangeRateTypeRelationshipId name="Relationship_FinancialReportingExchangeRateTypeRelationshipId">Relationship_FinancialReportingExchangeRateTypeRelationshipId</a>

First included in: Main/MainAccount (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_FinancialReportingExchangeRateTypeRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Common/Currency/Group/ExchangeRateType.md" target="_blank">/core/operationsCommon/Tables/Common/Currency/Group/ExchangeRateType.cdm.json/ExchangeRateType</a></td><td><a href="../../../Common/Currency/Group/ExchangeRateType.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_LedgerChartOfAccountsRelationshipId name="Relationship_LedgerChartOfAccountsRelationshipId">Relationship_LedgerChartOfAccountsRelationshipId</a>

First included in: Main/MainAccount (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_LedgerChartOfAccountsRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../Ledger/Main/LedgerChartOfAccounts.md" target="_blank">/core/operationsCommon/Tables/Finance/Ledger/Main/LedgerChartOfAccounts.cdm.json/LedgerChartOfAccounts</a></td><td><a href="../../Ledger/Main/LedgerChartOfAccounts.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_MainAccountCategoryRelationshipId name="Relationship_MainAccountCategoryRelationshipId">Relationship_MainAccountCategoryRelationshipId</a>

First included in: Main/MainAccount (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_MainAccountCategoryRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../Ledger/Main/MainAccountCategory.md" target="_blank">/core/operationsCommon/Tables/Finance/Ledger/Main/MainAccountCategory.cdm.json/MainAccountCategory</a></td><td><a href="../../Ledger/Main/MainAccountCategory.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_OffsetLedgerDimensionRelationshipId name="Relationship_OffsetLedgerDimensionRelationshipId">Relationship_OffsetLedgerDimensionRelationshipId</a>

First included in: Main/MainAccount (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_OffsetLedgerDimensionRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="DimensionAttributeValueCombination.md" target="_blank">/core/operationsCommon/Tables/Finance/FinancialDimensions/Main/DimensionAttributeValueCombination.cdm.json/DimensionAttributeValueCombination</a></td><td><a href="DimensionAttributeValueCombination.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_ExchangeAdjustmentRateTypeRelationshipId name="Relationship_ExchangeAdjustmentRateTypeRelationshipId">Relationship_ExchangeAdjustmentRateTypeRelationshipId</a>

First included in: Main/MainAccount (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_ExchangeAdjustmentRateTypeRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Common/Currency/Group/ExchangeRateType.md" target="_blank">/core/operationsCommon/Tables/Common/Currency/Group/ExchangeRateType.cdm.json/ExchangeRateType</a></td><td><a href="../../../Common/Currency/Group/ExchangeRateType.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_ReportingExchangeAdjustmentRateTypeRelationshipId name="Relationship_ReportingExchangeAdjustmentRateTypeRelationshipId">Relationship_ReportingExchangeAdjustmentRateTypeRelationshipId</a>

First included in: Main/MainAccount (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_ReportingExchangeAdjustmentRateTypeRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Common/Currency/Group/ExchangeRateType.md" target="_blank">/core/operationsCommon/Tables/Common/Currency/Group/ExchangeRateType.cdm.json/ExchangeRateType</a></td><td><a href="../../../Common/Currency/Group/ExchangeRateType.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_MainAccountTemplateRelationshipId name="Relationship_MainAccountTemplateRelationshipId">Relationship_MainAccountTemplateRelationshipId</a>

First included in: Main/MainAccount (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_MainAccountTemplateRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="MainAccountTemplate.md" target="_blank">/core/operationsCommon/Tables/Finance/FinancialDimensions/Main/MainAccountTemplate.cdm.json/MainAccountTemplate</a></td><td><a href="MainAccountTemplate.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_StandardMainAccount_WRelationshipId name="Relationship_StandardMainAccount_WRelationshipId">Relationship_StandardMainAccount_WRelationshipId</a>

First included in: Main/MainAccount (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_StandardMainAccount_WRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../Ledger/Group/StandardMainAccount_W.md" target="_blank">/core/operationsCommon/Tables/Finance/Ledger/Group/StandardMainAccount_W.cdm.json/StandardMainAccount_W</a></td><td><a href="../../Ledger/Group/StandardMainAccount_W.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>
