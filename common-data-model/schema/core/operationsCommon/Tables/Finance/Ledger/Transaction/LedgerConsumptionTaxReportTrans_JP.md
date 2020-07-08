---
title: LedgerConsumptionTaxReportTrans_JP in Transaction - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 7/8/2020
ms.author: nebanfic
---

# Consumption tax report in Transaction(LedgerConsumptionTaxReportTrans_JP)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Tables/Finance/Ledger/Transaction/LedgerConsumptionTaxReportTrans_JP.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[LedgerConsumptionTaxReportTrans_JP/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Consumption tax report</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="LedgerConsumptionTaxReportTrans_JP.md" target="_blank">Transaction/LedgerConsumptionTaxReportTrans_JP</a>|
|[AccountingPersonnel](#AccountingPersonnel)||<a href="LedgerConsumptionTaxReportTrans_JP.md" target="_blank">Transaction/LedgerConsumptionTaxReportTrans_JP</a>|
|[BankAccount](#BankAccount)||<a href="LedgerConsumptionTaxReportTrans_JP.md" target="_blank">Transaction/LedgerConsumptionTaxReportTrans_JP</a>|
|[CalcMethod](#CalcMethod)||<a href="LedgerConsumptionTaxReportTrans_JP.md" target="_blank">Transaction/LedgerConsumptionTaxReportTrans_JP</a>|
|[CashBasisAccounting](#CashBasisAccounting)||<a href="LedgerConsumptionTaxReportTrans_JP.md" target="_blank">Transaction/LedgerConsumptionTaxReportTrans_JP</a>|
|[Comments](#Comments)||<a href="LedgerConsumptionTaxReportTrans_JP.md" target="_blank">Transaction/LedgerConsumptionTaxReportTrans_JP</a>|
|[CompanyRepresentative](#CompanyRepresentative)||<a href="LedgerConsumptionTaxReportTrans_JP.md" target="_blank">Transaction/LedgerConsumptionTaxReportTrans_JP</a>|
|[DeferredPaymentBasis](#DeferredPaymentBasis)||<a href="LedgerConsumptionTaxReportTrans_JP.md" target="_blank">Transaction/LedgerConsumptionTaxReportTrans_JP</a>|
|[DocumentSubmittedLaw30](#DocumentSubmittedLaw30)||<a href="LedgerConsumptionTaxReportTrans_JP.md" target="_blank">Transaction/LedgerConsumptionTaxReportTrans_JP</a>|
|[DocumentSubmittedLaw332](#DocumentSubmittedLaw332)||<a href="LedgerConsumptionTaxReportTrans_JP.md" target="_blank">Transaction/LedgerConsumptionTaxReportTrans_JP</a>|
|[ExceptionalTaxCalcTreatment](#ExceptionalTaxCalcTreatment)||<a href="LedgerConsumptionTaxReportTrans_JP.md" target="_blank">Transaction/LedgerConsumptionTaxReportTrans_JP</a>|
|[FullyDeductible](#FullyDeductible)||<a href="LedgerConsumptionTaxReportTrans_JP.md" target="_blank">Transaction/LedgerConsumptionTaxReportTrans_JP</a>|
|[IndividualMethod](#IndividualMethod)||<a href="LedgerConsumptionTaxReportTrans_JP.md" target="_blank">Transaction/LedgerConsumptionTaxReportTrans_JP</a>|
|[InstallmentBasis](#InstallmentBasis)||<a href="LedgerConsumptionTaxReportTrans_JP.md" target="_blank">Transaction/LedgerConsumptionTaxReportTrans_JP</a>|
|[InterimFrom](#InterimFrom)||<a href="LedgerConsumptionTaxReportTrans_JP.md" target="_blank">Transaction/LedgerConsumptionTaxReportTrans_JP</a>|
|[InterimTo](#InterimTo)||<a href="LedgerConsumptionTaxReportTrans_JP.md" target="_blank">Transaction/LedgerConsumptionTaxReportTrans_JP</a>|
|[LumpsumMethod](#LumpsumMethod)||<a href="LedgerConsumptionTaxReportTrans_JP.md" target="_blank">Transaction/LedgerConsumptionTaxReportTrans_JP</a>|
|[Modified](#Modified)||<a href="LedgerConsumptionTaxReportTrans_JP.md" target="_blank">Transaction/LedgerConsumptionTaxReportTrans_JP</a>|
|[Modified13](#Modified13)||<a href="LedgerConsumptionTaxReportTrans_JP.md" target="_blank">Transaction/LedgerConsumptionTaxReportTrans_JP</a>|
|[Modified24](#Modified24)||<a href="LedgerConsumptionTaxReportTrans_JP.md" target="_blank">Transaction/LedgerConsumptionTaxReportTrans_JP</a>|
|[Modified25](#Modified25)||<a href="LedgerConsumptionTaxReportTrans_JP.md" target="_blank">Transaction/LedgerConsumptionTaxReportTrans_JP</a>|
|[NameOfTaxAccountant](#NameOfTaxAccountant)||<a href="LedgerConsumptionTaxReportTrans_JP.md" target="_blank">Transaction/LedgerConsumptionTaxReportTrans_JP</a>|
|[PercentageOfCompletionBasis](#PercentageOfCompletionBasis)||<a href="LedgerConsumptionTaxReportTrans_JP.md" target="_blank">Transaction/LedgerConsumptionTaxReportTrans_JP</a>|
|[PeriodOfTaxationFrom](#PeriodOfTaxationFrom)||<a href="LedgerConsumptionTaxReportTrans_JP.md" target="_blank">Transaction/LedgerConsumptionTaxReportTrans_JP</a>|
|[PeriodOfTaxationTo](#PeriodOfTaxationTo)||<a href="LedgerConsumptionTaxReportTrans_JP.md" target="_blank">Transaction/LedgerConsumptionTaxReportTrans_JP</a>|
|[ReportItem1](#ReportItem1)||<a href="LedgerConsumptionTaxReportTrans_JP.md" target="_blank">Transaction/LedgerConsumptionTaxReportTrans_JP</a>|
|[ReportItem10](#ReportItem10)||<a href="LedgerConsumptionTaxReportTrans_JP.md" target="_blank">Transaction/LedgerConsumptionTaxReportTrans_JP</a>|
|[ReportItem11](#ReportItem11)||<a href="LedgerConsumptionTaxReportTrans_JP.md" target="_blank">Transaction/LedgerConsumptionTaxReportTrans_JP</a>|
|[ReportItem12](#ReportItem12)||<a href="LedgerConsumptionTaxReportTrans_JP.md" target="_blank">Transaction/LedgerConsumptionTaxReportTrans_JP</a>|
|[ReportItem13](#ReportItem13)||<a href="LedgerConsumptionTaxReportTrans_JP.md" target="_blank">Transaction/LedgerConsumptionTaxReportTrans_JP</a>|
|[ReportItem14](#ReportItem14)||<a href="LedgerConsumptionTaxReportTrans_JP.md" target="_blank">Transaction/LedgerConsumptionTaxReportTrans_JP</a>|
|[ReportItem15](#ReportItem15)||<a href="LedgerConsumptionTaxReportTrans_JP.md" target="_blank">Transaction/LedgerConsumptionTaxReportTrans_JP</a>|
|[ReportItem16](#ReportItem16)||<a href="LedgerConsumptionTaxReportTrans_JP.md" target="_blank">Transaction/LedgerConsumptionTaxReportTrans_JP</a>|
|[ReportItem17](#ReportItem17)||<a href="LedgerConsumptionTaxReportTrans_JP.md" target="_blank">Transaction/LedgerConsumptionTaxReportTrans_JP</a>|
|[ReportItem18](#ReportItem18)||<a href="LedgerConsumptionTaxReportTrans_JP.md" target="_blank">Transaction/LedgerConsumptionTaxReportTrans_JP</a>|
|[ReportItem19](#ReportItem19)||<a href="LedgerConsumptionTaxReportTrans_JP.md" target="_blank">Transaction/LedgerConsumptionTaxReportTrans_JP</a>|
|[ReportItem2](#ReportItem2)||<a href="LedgerConsumptionTaxReportTrans_JP.md" target="_blank">Transaction/LedgerConsumptionTaxReportTrans_JP</a>|
|[ReportItem20](#ReportItem20)||<a href="LedgerConsumptionTaxReportTrans_JP.md" target="_blank">Transaction/LedgerConsumptionTaxReportTrans_JP</a>|
|[ReportItem21](#ReportItem21)||<a href="LedgerConsumptionTaxReportTrans_JP.md" target="_blank">Transaction/LedgerConsumptionTaxReportTrans_JP</a>|
|[ReportItem22](#ReportItem22)||<a href="LedgerConsumptionTaxReportTrans_JP.md" target="_blank">Transaction/LedgerConsumptionTaxReportTrans_JP</a>|
|[ReportItem23](#ReportItem23)||<a href="LedgerConsumptionTaxReportTrans_JP.md" target="_blank">Transaction/LedgerConsumptionTaxReportTrans_JP</a>|
|[ReportItem24](#ReportItem24)||<a href="LedgerConsumptionTaxReportTrans_JP.md" target="_blank">Transaction/LedgerConsumptionTaxReportTrans_JP</a>|
|[ReportItem25](#ReportItem25)||<a href="LedgerConsumptionTaxReportTrans_JP.md" target="_blank">Transaction/LedgerConsumptionTaxReportTrans_JP</a>|
|[ReportItem26](#ReportItem26)||<a href="LedgerConsumptionTaxReportTrans_JP.md" target="_blank">Transaction/LedgerConsumptionTaxReportTrans_JP</a>|
|[ReportItem3](#ReportItem3)||<a href="LedgerConsumptionTaxReportTrans_JP.md" target="_blank">Transaction/LedgerConsumptionTaxReportTrans_JP</a>|
|[ReportItem4](#ReportItem4)||<a href="LedgerConsumptionTaxReportTrans_JP.md" target="_blank">Transaction/LedgerConsumptionTaxReportTrans_JP</a>|
|[ReportItem5](#ReportItem5)||<a href="LedgerConsumptionTaxReportTrans_JP.md" target="_blank">Transaction/LedgerConsumptionTaxReportTrans_JP</a>|
|[ReportItem6](#ReportItem6)||<a href="LedgerConsumptionTaxReportTrans_JP.md" target="_blank">Transaction/LedgerConsumptionTaxReportTrans_JP</a>|
|[ReportItem7](#ReportItem7)||<a href="LedgerConsumptionTaxReportTrans_JP.md" target="_blank">Transaction/LedgerConsumptionTaxReportTrans_JP</a>|
|[ReportItem8](#ReportItem8)||<a href="LedgerConsumptionTaxReportTrans_JP.md" target="_blank">Transaction/LedgerConsumptionTaxReportTrans_JP</a>|
|[ReportItem9](#ReportItem9)||<a href="LedgerConsumptionTaxReportTrans_JP.md" target="_blank">Transaction/LedgerConsumptionTaxReportTrans_JP</a>|
|[TaxableSalesBenchmarkPeriod](#TaxableSalesBenchmarkPeriod)||<a href="LedgerConsumptionTaxReportTrans_JP.md" target="_blank">Transaction/LedgerConsumptionTaxReportTrans_JP</a>|
|[TaxationOfficeName](#TaxationOfficeName)||<a href="LedgerConsumptionTaxReportTrans_JP.md" target="_blank">Transaction/LedgerConsumptionTaxReportTrans_JP</a>|
|[TaxPaymentAmount](#TaxPaymentAmount)||<a href="LedgerConsumptionTaxReportTrans_JP.md" target="_blank">Transaction/LedgerConsumptionTaxReportTrans_JP</a>|
|[TaxRefundAmount](#TaxRefundAmount)||<a href="LedgerConsumptionTaxReportTrans_JP.md" target="_blank">Transaction/LedgerConsumptionTaxReportTrans_JP</a>|
|[TypeOfDeclaration](#TypeOfDeclaration)||<a href="LedgerConsumptionTaxReportTrans_JP.md" target="_blank">Transaction/LedgerConsumptionTaxReportTrans_JP</a>|
|[Version](#Version)||<a href="LedgerConsumptionTaxReportTrans_JP.md" target="_blank">Transaction/LedgerConsumptionTaxReportTrans_JP</a>|
|[TaxValue](#TaxValue)||<a href="LedgerConsumptionTaxReportTrans_JP.md" target="_blank">Transaction/LedgerConsumptionTaxReportTrans_JP</a>|
|[TaxAmount](#TaxAmount)||<a href="LedgerConsumptionTaxReportTrans_JP.md" target="_blank">Transaction/LedgerConsumptionTaxReportTrans_JP</a>|
|[TaxType](#TaxType)||<a href="LedgerConsumptionTaxReportTrans_JP.md" target="_blank">Transaction/LedgerConsumptionTaxReportTrans_JP</a>|
|[RatioOfTaxableSales](#RatioOfTaxableSales)||<a href="LedgerConsumptionTaxReportTrans_JP.md" target="_blank">Transaction/LedgerConsumptionTaxReportTrans_JP</a>|
|[ReportItem4_1](#ReportItem4_1)||<a href="LedgerConsumptionTaxReportTrans_JP.md" target="_blank">Transaction/LedgerConsumptionTaxReportTrans_JP</a>|
|[DataAreaId](#DataAreaId)||<a href="LedgerConsumptionTaxReportTrans_JP.md" target="_blank">Transaction/LedgerConsumptionTaxReportTrans_JP</a>|
|[Relationship_BankAccountRelationshipId](#Relationship_BankAccountRelationshipId)||<a href="LedgerConsumptionTaxReportTrans_JP.md" target="_blank">Transaction/LedgerConsumptionTaxReportTrans_JP</a>|
|[Relationship_CompanyRelationshipId](#Relationship_CompanyRelationshipId)||<a href="LedgerConsumptionTaxReportTrans_JP.md" target="_blank">Transaction/LedgerConsumptionTaxReportTrans_JP</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: Transaction/LedgerConsumptionTaxReportTrans_JP (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[LedgerConsumptionTaxReportTrans_JP/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#AccountingPersonnel name="AccountingPersonnel">AccountingPersonnel</a>

First included in: Transaction/LedgerConsumptionTaxReportTrans_JP (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AccountingPersonnel attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BankAccount name="BankAccount">BankAccount</a>

First included in: Transaction/LedgerConsumptionTaxReportTrans_JP (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Bank information</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BankAccount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Bank information</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CalcMethod name="CalcMethod">CalcMethod</a>

First included in: Transaction/LedgerConsumptionTaxReportTrans_JP (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CalcMethod attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#CashBasisAccounting name="CashBasisAccounting">CashBasisAccounting</a>

First included in: Transaction/LedgerConsumptionTaxReportTrans_JP (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CashBasisAccounting attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#Comments name="Comments">Comments</a>

First included in: Transaction/LedgerConsumptionTaxReportTrans_JP (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Comments attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CompanyRepresentative name="CompanyRepresentative">CompanyRepresentative</a>

First included in: Transaction/LedgerConsumptionTaxReportTrans_JP (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CompanyRepresentative attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DeferredPaymentBasis name="DeferredPaymentBasis">DeferredPaymentBasis</a>

First included in: Transaction/LedgerConsumptionTaxReportTrans_JP (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DeferredPaymentBasis attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#DocumentSubmittedLaw30 name="DocumentSubmittedLaw30">DocumentSubmittedLaw30</a>

First included in: Transaction/LedgerConsumptionTaxReportTrans_JP (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DocumentSubmittedLaw30 attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#DocumentSubmittedLaw332 name="DocumentSubmittedLaw332">DocumentSubmittedLaw332</a>

First included in: Transaction/LedgerConsumptionTaxReportTrans_JP (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DocumentSubmittedLaw332 attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#ExceptionalTaxCalcTreatment name="ExceptionalTaxCalcTreatment">ExceptionalTaxCalcTreatment</a>

First included in: Transaction/LedgerConsumptionTaxReportTrans_JP (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ExceptionalTaxCalcTreatment attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#FullyDeductible name="FullyDeductible">FullyDeductible</a>

First included in: Transaction/LedgerConsumptionTaxReportTrans_JP (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FullyDeductible attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#IndividualMethod name="IndividualMethod">IndividualMethod</a>

First included in: Transaction/LedgerConsumptionTaxReportTrans_JP (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IndividualMethod attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#InstallmentBasis name="InstallmentBasis">InstallmentBasis</a>

First included in: Transaction/LedgerConsumptionTaxReportTrans_JP (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InstallmentBasis attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#InterimFrom name="InterimFrom">InterimFrom</a>

First included in: Transaction/LedgerConsumptionTaxReportTrans_JP (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InterimFrom attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.date**  
</details>

### <a href=#InterimTo name="InterimTo">InterimTo</a>

First included in: Transaction/LedgerConsumptionTaxReportTrans_JP (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InterimTo attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.date**  
</details>

### <a href=#LumpsumMethod name="LumpsumMethod">LumpsumMethod</a>

First included in: Transaction/LedgerConsumptionTaxReportTrans_JP (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LumpsumMethod attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#Modified name="Modified">Modified</a>

First included in: Transaction/LedgerConsumptionTaxReportTrans_JP (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Modified attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#Modified13 name="Modified13">Modified13</a>

First included in: Transaction/LedgerConsumptionTaxReportTrans_JP (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Modified13 attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#Modified24 name="Modified24">Modified24</a>

First included in: Transaction/LedgerConsumptionTaxReportTrans_JP (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Modified24 attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#Modified25 name="Modified25">Modified25</a>

First included in: Transaction/LedgerConsumptionTaxReportTrans_JP (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Modified25 attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#NameOfTaxAccountant name="NameOfTaxAccountant">NameOfTaxAccountant</a>

First included in: Transaction/LedgerConsumptionTaxReportTrans_JP (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the NameOfTaxAccountant attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PercentageOfCompletionBasis name="PercentageOfCompletionBasis">PercentageOfCompletionBasis</a>

First included in: Transaction/LedgerConsumptionTaxReportTrans_JP (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PercentageOfCompletionBasis attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#PeriodOfTaxationFrom name="PeriodOfTaxationFrom">PeriodOfTaxationFrom</a>

First included in: Transaction/LedgerConsumptionTaxReportTrans_JP (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PeriodOfTaxationFrom attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.date**  
</details>

### <a href=#PeriodOfTaxationTo name="PeriodOfTaxationTo">PeriodOfTaxationTo</a>

First included in: Transaction/LedgerConsumptionTaxReportTrans_JP (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PeriodOfTaxationTo attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.date**  
</details>

### <a href=#ReportItem1 name="ReportItem1">ReportItem1</a>

First included in: Transaction/LedgerConsumptionTaxReportTrans_JP (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReportItem1 attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#ReportItem10 name="ReportItem10">ReportItem10</a>

First included in: Transaction/LedgerConsumptionTaxReportTrans_JP (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Item 10</td></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReportItem10 attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Item 10</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#ReportItem11 name="ReportItem11">ReportItem11</a>

First included in: Transaction/LedgerConsumptionTaxReportTrans_JP (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Item 11</td></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReportItem11 attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Item 11</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#ReportItem12 name="ReportItem12">ReportItem12</a>

First included in: Transaction/LedgerConsumptionTaxReportTrans_JP (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Item 12</td></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReportItem12 attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Item 12</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#ReportItem13 name="ReportItem13">ReportItem13</a>

First included in: Transaction/LedgerConsumptionTaxReportTrans_JP (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Item 13</td></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReportItem13 attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Item 13</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#ReportItem14 name="ReportItem14">ReportItem14</a>

First included in: Transaction/LedgerConsumptionTaxReportTrans_JP (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Item 14</td></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReportItem14 attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Item 14</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#ReportItem15 name="ReportItem15">ReportItem15</a>

First included in: Transaction/LedgerConsumptionTaxReportTrans_JP (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Item 15</td></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReportItem15 attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Item 15</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#ReportItem16 name="ReportItem16">ReportItem16</a>

First included in: Transaction/LedgerConsumptionTaxReportTrans_JP (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Item 16</td></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReportItem16 attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Item 16</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#ReportItem17 name="ReportItem17">ReportItem17</a>

First included in: Transaction/LedgerConsumptionTaxReportTrans_JP (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Item 17</td></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReportItem17 attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Item 17</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#ReportItem18 name="ReportItem18">ReportItem18</a>

First included in: Transaction/LedgerConsumptionTaxReportTrans_JP (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Item 18</td></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReportItem18 attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Item 18</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#ReportItem19 name="ReportItem19">ReportItem19</a>

First included in: Transaction/LedgerConsumptionTaxReportTrans_JP (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Item 19</td></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReportItem19 attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Item 19</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#ReportItem2 name="ReportItem2">ReportItem2</a>

First included in: Transaction/LedgerConsumptionTaxReportTrans_JP (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Item 2</td></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReportItem2 attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Item 2</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#ReportItem20 name="ReportItem20">ReportItem20</a>

First included in: Transaction/LedgerConsumptionTaxReportTrans_JP (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Item 20</td></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReportItem20 attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Item 20</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#ReportItem21 name="ReportItem21">ReportItem21</a>

First included in: Transaction/LedgerConsumptionTaxReportTrans_JP (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Item 21</td></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReportItem21 attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Item 21</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#ReportItem22 name="ReportItem22">ReportItem22</a>

First included in: Transaction/LedgerConsumptionTaxReportTrans_JP (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Item 22</td></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReportItem22 attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Item 22</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#ReportItem23 name="ReportItem23">ReportItem23</a>

First included in: Transaction/LedgerConsumptionTaxReportTrans_JP (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Item 23</td></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReportItem23 attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Item 23</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#ReportItem24 name="ReportItem24">ReportItem24</a>

First included in: Transaction/LedgerConsumptionTaxReportTrans_JP (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Item 24</td></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReportItem24 attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Item 24</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#ReportItem25 name="ReportItem25">ReportItem25</a>

First included in: Transaction/LedgerConsumptionTaxReportTrans_JP (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Item 25</td></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReportItem25 attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Item 25</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#ReportItem26 name="ReportItem26">ReportItem26</a>

First included in: Transaction/LedgerConsumptionTaxReportTrans_JP (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Item 26</td></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReportItem26 attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Item 26</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#ReportItem3 name="ReportItem3">ReportItem3</a>

First included in: Transaction/LedgerConsumptionTaxReportTrans_JP (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Item 3</td></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReportItem3 attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Item 3</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#ReportItem4 name="ReportItem4">ReportItem4</a>

First included in: Transaction/LedgerConsumptionTaxReportTrans_JP (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Item 4</td></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReportItem4 attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Item 4</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#ReportItem5 name="ReportItem5">ReportItem5</a>

First included in: Transaction/LedgerConsumptionTaxReportTrans_JP (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Item 5</td></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReportItem5 attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Item 5</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#ReportItem6 name="ReportItem6">ReportItem6</a>

First included in: Transaction/LedgerConsumptionTaxReportTrans_JP (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Item 6</td></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReportItem6 attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Item 6</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#ReportItem7 name="ReportItem7">ReportItem7</a>

First included in: Transaction/LedgerConsumptionTaxReportTrans_JP (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Item 7</td></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReportItem7 attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Item 7</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#ReportItem8 name="ReportItem8">ReportItem8</a>

First included in: Transaction/LedgerConsumptionTaxReportTrans_JP (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Item 8</td></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReportItem8 attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Item 8</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#ReportItem9 name="ReportItem9">ReportItem9</a>

First included in: Transaction/LedgerConsumptionTaxReportTrans_JP (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Item 9</td></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReportItem9 attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Item 9</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#TaxableSalesBenchmarkPeriod name="TaxableSalesBenchmarkPeriod">TaxableSalesBenchmarkPeriod</a>

First included in: Transaction/LedgerConsumptionTaxReportTrans_JP (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxableSalesBenchmarkPeriod attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#TaxationOfficeName name="TaxationOfficeName">TaxationOfficeName</a>

First included in: Transaction/LedgerConsumptionTaxReportTrans_JP (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxationOfficeName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TaxPaymentAmount name="TaxPaymentAmount">TaxPaymentAmount</a>

First included in: Transaction/LedgerConsumptionTaxReportTrans_JP (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxPaymentAmount attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#TaxRefundAmount name="TaxRefundAmount">TaxRefundAmount</a>

First included in: Transaction/LedgerConsumptionTaxReportTrans_JP (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxRefundAmount attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#TypeOfDeclaration name="TypeOfDeclaration">TypeOfDeclaration</a>

First included in: Transaction/LedgerConsumptionTaxReportTrans_JP (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TypeOfDeclaration attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#Version name="Version">Version</a>

First included in: Transaction/LedgerConsumptionTaxReportTrans_JP (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Version attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#TaxValue name="TaxValue">TaxValue</a>

First included in: Transaction/LedgerConsumptionTaxReportTrans_JP (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxValue attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#TaxAmount name="TaxAmount">TaxAmount</a>

First included in: Transaction/LedgerConsumptionTaxReportTrans_JP (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxAmount attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#TaxType name="TaxType">TaxType</a>

First included in: Transaction/LedgerConsumptionTaxReportTrans_JP (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxType attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#RatioOfTaxableSales name="RatioOfTaxableSales">RatioOfTaxableSales</a>

First included in: Transaction/LedgerConsumptionTaxReportTrans_JP (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RatioOfTaxableSales attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#ReportItem4_1 name="ReportItem4_1">ReportItem4_1</a>

First included in: Transaction/LedgerConsumptionTaxReportTrans_JP (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Item 4</td></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReportItem4_1 attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Item 4</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#DataAreaId name="DataAreaId">DataAreaId</a>

First included in: Transaction/LedgerConsumptionTaxReportTrans_JP (this entity)  

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

### <a href=#Relationship_BankAccountRelationshipId name="Relationship_BankAccountRelationshipId">Relationship_BankAccountRelationshipId</a>

First included in: Transaction/LedgerConsumptionTaxReportTrans_JP (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_BankAccountRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../Bank/Main/BankAccountTable.md" target="_blank">/core/operationsCommon/Tables/Finance/Bank/Main/BankAccountTable.cdm.json/BankAccountTable</a></td><td><a href="../../Bank/Main/BankAccountTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_CompanyRelationshipId name="Relationship_CompanyRelationshipId">Relationship_CompanyRelationshipId</a>

First included in: Transaction/LedgerConsumptionTaxReportTrans_JP (this entity)  

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
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Main/CompanyInfo.md" target="_blank">/core/operationsCommon/Tables/Finance/Ledger/Main/CompanyInfo.cdm.json/CompanyInfo</a></td><td><a href="../Main/CompanyInfo.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>
