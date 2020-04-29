---
title: MainAccountEntity - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/29/2020
ms.author: nebanfic
---

# Main account

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/Finance/GeneralLedger/MainAccountEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Main account</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[MainAccountCategory](#MainAccountCategory)||<a href="MainAccountEntity.md" target="_blank">GeneralLedger/MainAccountEntity</a>|
|[AccountCategoryReference](#AccountCategoryReference)||<a href="MainAccountEntity.md" target="_blank">GeneralLedger/MainAccountEntity</a>|
|[Closing](#Closing)||<a href="MainAccountEntity.md" target="_blank">GeneralLedger/MainAccountEntity</a>|
|[DefaultConsolidationAccount](#DefaultConsolidationAccount)||<a href="MainAccountEntity.md" target="_blank">GeneralLedger/MainAccountEntity</a>|
|[DefaultCurrency](#DefaultCurrency)||<a href="MainAccountEntity.md" target="_blank">GeneralLedger/MainAccountEntity</a>|
|[BalanceControl](#BalanceControl)||<a href="MainAccountEntity.md" target="_blank">GeneralLedger/MainAccountEntity</a>|
|[DebitCreditRequirement](#DebitCreditRequirement)||<a href="MainAccountEntity.md" target="_blank">GeneralLedger/MainAccountEntity</a>|
|[DebitCreditDefault](#DebitCreditDefault)||<a href="MainAccountEntity.md" target="_blank">GeneralLedger/MainAccountEntity</a>|
|[ForeignCurrencyRevaluation](#ForeignCurrencyRevaluation)||<a href="MainAccountEntity.md" target="_blank">GeneralLedger/MainAccountEntity</a>|
|[FinancialReportingExchangeRateTypeRecId](#FinancialReportingExchangeRateTypeRecId)||<a href="MainAccountEntity.md" target="_blank">GeneralLedger/MainAccountEntity</a>|
|[FinancialReportingCurrencyTranslationType](#FinancialReportingCurrencyTranslationType)||<a href="MainAccountEntity.md" target="_blank">GeneralLedger/MainAccountEntity</a>|
|[ChartOfAccountsRecId](#ChartOfAccountsRecId)||<a href="MainAccountEntity.md" target="_blank">GeneralLedger/MainAccountEntity</a>|
|[MainAccountId](#MainAccountId)||<a href="MainAccountEntity.md" target="_blank">GeneralLedger/MainAccountEntity</a>|
|[MandatoryPaymentReference](#MandatoryPaymentReference)||<a href="MainAccountEntity.md" target="_blank">GeneralLedger/MainAccountEntity</a>|
|[Monetary](#Monetary)||<a href="MainAccountEntity.md" target="_blank">GeneralLedger/MainAccountEntity</a>|
|[Name](#Name)||<a href="MainAccountEntity.md" target="_blank">GeneralLedger/MainAccountEntity</a>|
|[OffsetAccount](#OffsetAccount)||<a href="MainAccountEntity.md" target="_blank">GeneralLedger/MainAccountEntity</a>|
|[PostingType](#PostingType)||<a href="MainAccountEntity.md" target="_blank">GeneralLedger/MainAccountEntity</a>|
|[SRUCode](#SRUCode)||<a href="MainAccountEntity.md" target="_blank">GeneralLedger/MainAccountEntity</a>|
|[MainAccountType](#MainAccountType)||<a href="MainAccountEntity.md" target="_blank">GeneralLedger/MainAccountEntity</a>|
|[User](#User)||<a href="MainAccountEntity.md" target="_blank">GeneralLedger/MainAccountEntity</a>|
|[ValidateCurrency](#ValidateCurrency)||<a href="MainAccountEntity.md" target="_blank">GeneralLedger/MainAccountEntity</a>|
|[ValidatePostingType](#ValidatePostingType)||<a href="MainAccountEntity.md" target="_blank">GeneralLedger/MainAccountEntity</a>|
|[ValidateUser](#ValidateUser)||<a href="MainAccountEntity.md" target="_blank">GeneralLedger/MainAccountEntity</a>|
|[OffsetAccountDisplayValue](#OffsetAccountDisplayValue)||<a href="MainAccountEntity.md" target="_blank">GeneralLedger/MainAccountEntity</a>|
|[OpeningAccountId](#OpeningAccountId)||<a href="MainAccountEntity.md" target="_blank">GeneralLedger/MainAccountEntity</a>|
|[ChartOfAccounts](#ChartOfAccounts)||<a href="MainAccountEntity.md" target="_blank">GeneralLedger/MainAccountEntity</a>|
|[ReportingAccountType](#ReportingAccountType)||<a href="MainAccountEntity.md" target="_blank">GeneralLedger/MainAccountEntity</a>|
|[FinancialReportingExchangeRateType](#FinancialReportingExchangeRateType)||<a href="MainAccountEntity.md" target="_blank">GeneralLedger/MainAccountEntity</a>|
|[DoNotAllowManualEntry](#DoNotAllowManualEntry)||<a href="MainAccountEntity.md" target="_blank">GeneralLedger/MainAccountEntity</a>|
|[IsSuspended](#IsSuspended)||<a href="MainAccountEntity.md" target="_blank">GeneralLedger/MainAccountEntity</a>|
|[ActiveFrom](#ActiveFrom)||<a href="MainAccountEntity.md" target="_blank">GeneralLedger/MainAccountEntity</a>|
|[ActiveTo](#ActiveTo)||<a href="MainAccountEntity.md" target="_blank">GeneralLedger/MainAccountEntity</a>|
|[MainAccountRecId](#MainAccountRecId)||<a href="MainAccountEntity.md" target="_blank">GeneralLedger/MainAccountEntity</a>|
|[AccountCategoryDescription](#AccountCategoryDescription)||<a href="MainAccountEntity.md" target="_blank">GeneralLedger/MainAccountEntity</a>|
|[AdjustmentMethod](#AdjustmentMethod)||<a href="MainAccountEntity.md" target="_blank">GeneralLedger/MainAccountEntity</a>|
|[InflationAdjustment](#InflationAdjustment)||<a href="MainAccountEntity.md" target="_blank">GeneralLedger/MainAccountEntity</a>|
|[RepomoType](#RepomoType)||<a href="MainAccountEntity.md" target="_blank">GeneralLedger/MainAccountEntity</a>|
|[ParentMainAccountId](#ParentMainAccountId)||<a href="MainAccountEntity.md" target="_blank">GeneralLedger/MainAccountEntity</a>|
|[AccountCategoryRef](#AccountCategoryRef)||<a href="MainAccountEntity.md" target="_blank">GeneralLedger/MainAccountEntity</a>|
|[ExchangeAdjustmentRateTypeRecId](#ExchangeAdjustmentRateTypeRecId)||<a href="MainAccountEntity.md" target="_blank">GeneralLedger/MainAccountEntity</a>|
|[ExchangeAdjustmentRateType](#ExchangeAdjustmentRateType)||<a href="MainAccountEntity.md" target="_blank">GeneralLedger/MainAccountEntity</a>|
|[ReportingExchangeAdjustmentRateTypeRecId](#ReportingExchangeAdjustmentRateTypeRecId)||<a href="MainAccountEntity.md" target="_blank">GeneralLedger/MainAccountEntity</a>|
|[ReportingExchangeAdjustmentRateType](#ReportingExchangeAdjustmentRateType)||<a href="MainAccountEntity.md" target="_blank">GeneralLedger/MainAccountEntity</a>|
|[Relationship_MainAccountCategoryRelationshipId](#Relationship_MainAccountCategoryRelationshipId)||<a href="MainAccountEntity.md" target="_blank">GeneralLedger/MainAccountEntity</a>|
|[Relationship_OffsetLedgerDimensionDimensionCombinationRelationshipId](#Relationship_OffsetLedgerDimensionDimensionCombinationRelationshipId)||<a href="MainAccountEntity.md" target="_blank">GeneralLedger/MainAccountEntity</a>|
|[Relationship_CurrencyRelationshipId](#Relationship_CurrencyRelationshipId)||<a href="MainAccountEntity.md" target="_blank">GeneralLedger/MainAccountEntity</a>|
|[Relationship_ExchangeAdjustmentRateTypeRelationshipId](#Relationship_ExchangeAdjustmentRateTypeRelationshipId)||<a href="MainAccountEntity.md" target="_blank">GeneralLedger/MainAccountEntity</a>|
|[Relationship_ReportingExchangeAdjustmentRateTypeRelationshipId](#Relationship_ReportingExchangeAdjustmentRateTypeRelationshipId)||<a href="MainAccountEntity.md" target="_blank">GeneralLedger/MainAccountEntity</a>|
|[BackingTable_MainAccountRelationshipId](#BackingTable_MainAccountRelationshipId)||<a href="MainAccountEntity.md" target="_blank">GeneralLedger/MainAccountEntity</a>|

### <a href=#MainAccountCategory name="MainAccountCategory">MainAccountCategory</a>

First included in: GeneralLedger/MainAccountEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MainAccountCategory attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AccountCategoryReference name="AccountCategoryReference">AccountCategoryReference</a>

First included in: GeneralLedger/MainAccountEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AccountCategoryReference attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Closing name="Closing">Closing</a>

First included in: GeneralLedger/MainAccountEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Closing attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DefaultConsolidationAccount name="DefaultConsolidationAccount">DefaultConsolidationAccount</a>

First included in: GeneralLedger/MainAccountEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultConsolidationAccount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DefaultCurrency name="DefaultCurrency">DefaultCurrency</a>

First included in: GeneralLedger/MainAccountEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultCurrency attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BalanceControl name="BalanceControl">BalanceControl</a>

First included in: GeneralLedger/MainAccountEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BalanceControl attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DebitCreditRequirement name="DebitCreditRequirement">DebitCreditRequirement</a>

First included in: GeneralLedger/MainAccountEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DebitCreditRequirement attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DebitCreditDefault name="DebitCreditDefault">DebitCreditDefault</a>

First included in: GeneralLedger/MainAccountEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DebitCreditDefault attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ForeignCurrencyRevaluation name="ForeignCurrencyRevaluation">ForeignCurrencyRevaluation</a>

First included in: GeneralLedger/MainAccountEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ForeignCurrencyRevaluation attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FinancialReportingExchangeRateTypeRecId name="FinancialReportingExchangeRateTypeRecId">FinancialReportingExchangeRateTypeRecId</a>

First included in: GeneralLedger/MainAccountEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FinancialReportingExchangeRateTypeRecId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FinancialReportingCurrencyTranslationType name="FinancialReportingCurrencyTranslationType">FinancialReportingCurrencyTranslationType</a>

First included in: GeneralLedger/MainAccountEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FinancialReportingCurrencyTranslationType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ChartOfAccountsRecId name="ChartOfAccountsRecId">ChartOfAccountsRecId</a>

First included in: GeneralLedger/MainAccountEntity (this entity)  

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

### <a href=#MainAccountId name="MainAccountId">MainAccountId</a>

First included in: GeneralLedger/MainAccountEntity (this entity)  

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

### <a href=#MandatoryPaymentReference name="MandatoryPaymentReference">MandatoryPaymentReference</a>

First included in: GeneralLedger/MainAccountEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MandatoryPaymentReference attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Monetary name="Monetary">Monetary</a>

First included in: GeneralLedger/MainAccountEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Monetary attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Name name="Name">Name</a>

First included in: GeneralLedger/MainAccountEntity (this entity)  

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

### <a href=#OffsetAccount name="OffsetAccount">OffsetAccount</a>

First included in: GeneralLedger/MainAccountEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OffsetAccount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PostingType name="PostingType">PostingType</a>

First included in: GeneralLedger/MainAccountEntity (this entity)  

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

### <a href=#SRUCode name="SRUCode">SRUCode</a>

First included in: GeneralLedger/MainAccountEntity (this entity)  

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

### <a href=#MainAccountType name="MainAccountType">MainAccountType</a>

First included in: GeneralLedger/MainAccountEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MainAccountType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#User name="User">User</a>

First included in: GeneralLedger/MainAccountEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the User attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ValidateCurrency name="ValidateCurrency">ValidateCurrency</a>

First included in: GeneralLedger/MainAccountEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ValidateCurrency attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ValidatePostingType name="ValidatePostingType">ValidatePostingType</a>

First included in: GeneralLedger/MainAccountEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ValidatePostingType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ValidateUser name="ValidateUser">ValidateUser</a>

First included in: GeneralLedger/MainAccountEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ValidateUser attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#OffsetAccountDisplayValue name="OffsetAccountDisplayValue">OffsetAccountDisplayValue</a>

First included in: GeneralLedger/MainAccountEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Offset account</td></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OffsetAccountDisplayValue attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Offset account</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#OpeningAccountId name="OpeningAccountId">OpeningAccountId</a>

First included in: GeneralLedger/MainAccountEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Opening account</td></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OpeningAccountId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Opening account</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ChartOfAccounts name="ChartOfAccounts">ChartOfAccounts</a>

First included in: GeneralLedger/MainAccountEntity (this entity)  

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

### <a href=#ReportingAccountType name="ReportingAccountType">ReportingAccountType</a>

First included in: GeneralLedger/MainAccountEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReportingAccountType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FinancialReportingExchangeRateType name="FinancialReportingExchangeRateType">FinancialReportingExchangeRateType</a>

First included in: GeneralLedger/MainAccountEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Financial reporting exchange rate type</td></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FinancialReportingExchangeRateType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Financial reporting exchange rate type</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DoNotAllowManualEntry name="DoNotAllowManualEntry">DoNotAllowManualEntry</a>

First included in: GeneralLedger/MainAccountEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DoNotAllowManualEntry attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsSuspended name="IsSuspended">IsSuspended</a>

First included in: GeneralLedger/MainAccountEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsSuspended attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ActiveFrom name="ActiveFrom">ActiveFrom</a>

First included in: GeneralLedger/MainAccountEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ActiveFrom attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ActiveTo name="ActiveTo">ActiveTo</a>

First included in: GeneralLedger/MainAccountEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ActiveTo attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MainAccountRecId name="MainAccountRecId">MainAccountRecId</a>

First included in: GeneralLedger/MainAccountEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MainAccountRecId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AccountCategoryDescription name="AccountCategoryDescription">AccountCategoryDescription</a>

First included in: GeneralLedger/MainAccountEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AccountCategoryDescription attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AdjustmentMethod name="AdjustmentMethod">AdjustmentMethod</a>

First included in: GeneralLedger/MainAccountEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AdjustmentMethod attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InflationAdjustment name="InflationAdjustment">InflationAdjustment</a>

First included in: GeneralLedger/MainAccountEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InflationAdjustment attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RepomoType name="RepomoType">RepomoType</a>

First included in: GeneralLedger/MainAccountEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RepomoType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ParentMainAccountId name="ParentMainAccountId">ParentMainAccountId</a>

First included in: GeneralLedger/MainAccountEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Parent account</td></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ParentMainAccountId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Parent account</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AccountCategoryRef name="AccountCategoryRef">AccountCategoryRef</a>

First included in: GeneralLedger/MainAccountEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AccountCategoryRef attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ExchangeAdjustmentRateTypeRecId name="ExchangeAdjustmentRateTypeRecId">ExchangeAdjustmentRateTypeRecId</a>

First included in: GeneralLedger/MainAccountEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ExchangeAdjustmentRateTypeRecId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ExchangeAdjustmentRateType name="ExchangeAdjustmentRateType">ExchangeAdjustmentRateType</a>

First included in: GeneralLedger/MainAccountEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Foreign currency revaluation exchange rate type</td></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ExchangeAdjustmentRateType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Foreign currency revaluation exchange rate type</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ReportingExchangeAdjustmentRateTypeRecId name="ReportingExchangeAdjustmentRateTypeRecId">ReportingExchangeAdjustmentRateTypeRecId</a>

First included in: GeneralLedger/MainAccountEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReportingExchangeAdjustmentRateTypeRecId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ReportingExchangeAdjustmentRateType name="ReportingExchangeAdjustmentRateType">ReportingExchangeAdjustmentRateType</a>

First included in: GeneralLedger/MainAccountEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Foreign currency revaluation reporting currency exchange rate type</td></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReportingExchangeAdjustmentRateType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Foreign currency revaluation reporting currency exchange rate type</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_MainAccountCategoryRelationshipId name="Relationship_MainAccountCategoryRelationshipId">Relationship_MainAccountCategoryRelationshipId</a>

First included in: GeneralLedger/MainAccountEntity (this entity)  

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
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td>empty table</td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_OffsetLedgerDimensionDimensionCombinationRelationshipId name="Relationship_OffsetLedgerDimensionDimensionCombinationRelationshipId">Relationship_OffsetLedgerDimensionDimensionCombinationRelationshipId</a>

First included in: GeneralLedger/MainAccountEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_OffsetLedgerDimensionDimensionCombinationRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_CurrencyRelationshipId name="Relationship_CurrencyRelationshipId">Relationship_CurrencyRelationshipId</a>

First included in: GeneralLedger/MainAccountEntity (this entity)  

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
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td>empty table</td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_ExchangeAdjustmentRateTypeRelationshipId name="Relationship_ExchangeAdjustmentRateTypeRelationshipId">Relationship_ExchangeAdjustmentRateTypeRelationshipId</a>

First included in: GeneralLedger/MainAccountEntity (this entity)  

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
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td>empty table</td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_ReportingExchangeAdjustmentRateTypeRelationshipId name="Relationship_ReportingExchangeAdjustmentRateTypeRelationshipId">Relationship_ReportingExchangeAdjustmentRateTypeRelationshipId</a>

First included in: GeneralLedger/MainAccountEntity (this entity)  

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
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td>empty table</td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BackingTable_MainAccountRelationshipId name="BackingTable_MainAccountRelationshipId">BackingTable_MainAccountRelationshipId</a>

First included in: GeneralLedger/MainAccountEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_MainAccountRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/Finance/FinancialDimensions/Main/MainAccount.md" target="_blank">/core/operationsCommon/Tables/Finance/FinancialDimensions/Main/MainAccount.cdm.json/MainAccount</a></td><td><a href="../../../Tables/Finance/FinancialDimensions/Main/MainAccount.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>
