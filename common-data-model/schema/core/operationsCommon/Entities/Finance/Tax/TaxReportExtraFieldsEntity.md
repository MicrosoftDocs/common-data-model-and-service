---
title: TaxReportExtraFieldsEntity - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/29/2020
ms.author: nebanfic
---

# Additional BAS report boxes

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/Finance/Tax/TaxReportExtraFieldsEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Additional BAS report boxes</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[deferredGSTOnImport](#deferredGSTOnImport)||<a href="TaxReportExtraFieldsEntity.md" target="_blank">Tax/TaxReportExtraFieldsEntity</a>|
|[DeferredInstalment](#DeferredInstalment)||<a href="TaxReportExtraFieldsEntity.md" target="_blank">Tax/TaxReportExtraFieldsEntity</a>|
|[ATOFringeBenefit](#ATOFringeBenefit)||<a href="TaxReportExtraFieldsEntity.md" target="_blank">Tax/TaxReportExtraFieldsEntity</a>|
|[fringeCredit](#fringeCredit)||<a href="TaxReportExtraFieldsEntity.md" target="_blank">Tax/TaxReportExtraFieldsEntity</a>|
|[EstimatedTotalFringeBenefits](#EstimatedTotalFringeBenefits)||<a href="TaxReportExtraFieldsEntity.md" target="_blank">Tax/TaxReportExtraFieldsEntity</a>|
|[VariedFringeBenefitsTax](#VariedFringeBenefitsTax)||<a href="TaxReportExtraFieldsEntity.md" target="_blank">Tax/TaxReportExtraFieldsEntity</a>|
|[FromDate](#FromDate)||<a href="TaxReportExtraFieldsEntity.md" target="_blank">Tax/TaxReportExtraFieldsEntity</a>|
|[FuelTaxCredit](#FuelTaxCredit)||<a href="TaxReportExtraFieldsEntity.md" target="_blank">Tax/TaxReportExtraFieldsEntity</a>|
|[FuelTaxCreditOverClaim](#FuelTaxCreditOverClaim)||<a href="TaxReportExtraFieldsEntity.md" target="_blank">Tax/TaxReportExtraFieldsEntity</a>|
|[InstallmentRate](#InstallmentRate)||<a href="TaxReportExtraFieldsEntity.md" target="_blank">Tax/TaxReportExtraFieldsEntity</a>|
|[paygCredit](#paygCredit)||<a href="TaxReportExtraFieldsEntity.md" target="_blank">Tax/TaxReportExtraFieldsEntity</a>|
|[InstallmentIncome](#InstallmentIncome)||<a href="TaxReportExtraFieldsEntity.md" target="_blank">Tax/TaxReportExtraFieldsEntity</a>|
|[NewVariedInstallmentRate](#NewVariedInstallmentRate)||<a href="TaxReportExtraFieldsEntity.md" target="_blank">Tax/TaxReportExtraFieldsEntity</a>|
|[TotalPayroll](#TotalPayroll)||<a href="TaxReportExtraFieldsEntity.md" target="_blank">Tax/TaxReportExtraFieldsEntity</a>|
|[WithheldFromInvestmentWhereNoTFN](#WithheldFromInvestmentWhereNoTFN)||<a href="TaxReportExtraFieldsEntity.md" target="_blank">Tax/TaxReportExtraFieldsEntity</a>|
|[WithheldFromInvoicesWhereNoABN](#WithheldFromInvoicesWhereNoABN)||<a href="TaxReportExtraFieldsEntity.md" target="_blank">Tax/TaxReportExtraFieldsEntity</a>|
|[paygWithheldSalary](#paygWithheldSalary)||<a href="TaxReportExtraFieldsEntity.md" target="_blank">Tax/TaxReportExtraFieldsEntity</a>|
|[DocumentIdentificationNumber](#DocumentIdentificationNumber)||<a href="TaxReportExtraFieldsEntity.md" target="_blank">Tax/TaxReportExtraFieldsEntity</a>|
|[ToDate](#ToDate)||<a href="TaxReportExtraFieldsEntity.md" target="_blank">Tax/TaxReportExtraFieldsEntity</a>|
|[WholesaleCredit](#WholesaleCredit)||<a href="TaxReportExtraFieldsEntity.md" target="_blank">Tax/TaxReportExtraFieldsEntity</a>|
|[FringeReasonForVariation](#FringeReasonForVariation)||<a href="TaxReportExtraFieldsEntity.md" target="_blank">Tax/TaxReportExtraFieldsEntity</a>|
|[PAYGReasonForVariation](#PAYGReasonForVariation)||<a href="TaxReportExtraFieldsEntity.md" target="_blank">Tax/TaxReportExtraFieldsEntity</a>|
|[SettlementPeriod](#SettlementPeriod)||<a href="TaxReportExtraFieldsEntity.md" target="_blank">Tax/TaxReportExtraFieldsEntity</a>|
|[BackingTable_TaxReportExtraFieldsRelationshipId](#BackingTable_TaxReportExtraFieldsRelationshipId)||<a href="TaxReportExtraFieldsEntity.md" target="_blank">Tax/TaxReportExtraFieldsEntity</a>|
|[Relationship_PrimaryCompanyContextRelationshipId](#Relationship_PrimaryCompanyContextRelationshipId)||<a href="TaxReportExtraFieldsEntity.md" target="_blank">Tax/TaxReportExtraFieldsEntity</a>|

### <a href=#deferredGSTOnImport name="deferredGSTOnImport">deferredGSTOnImport</a>

First included in: Tax/TaxReportExtraFieldsEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the deferredGSTOnImport attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DeferredInstalment name="DeferredInstalment">DeferredInstalment</a>

First included in: Tax/TaxReportExtraFieldsEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DeferredInstalment attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ATOFringeBenefit name="ATOFringeBenefit">ATOFringeBenefit</a>

First included in: Tax/TaxReportExtraFieldsEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ATOFringeBenefit attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#fringeCredit name="fringeCredit">fringeCredit</a>

First included in: Tax/TaxReportExtraFieldsEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the fringeCredit attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#EstimatedTotalFringeBenefits name="EstimatedTotalFringeBenefits">EstimatedTotalFringeBenefits</a>

First included in: Tax/TaxReportExtraFieldsEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EstimatedTotalFringeBenefits attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#VariedFringeBenefitsTax name="VariedFringeBenefitsTax">VariedFringeBenefitsTax</a>

First included in: Tax/TaxReportExtraFieldsEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VariedFringeBenefitsTax attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FromDate name="FromDate">FromDate</a>

First included in: Tax/TaxReportExtraFieldsEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FromDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FuelTaxCredit name="FuelTaxCredit">FuelTaxCredit</a>

First included in: Tax/TaxReportExtraFieldsEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FuelTaxCredit attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FuelTaxCreditOverClaim name="FuelTaxCreditOverClaim">FuelTaxCreditOverClaim</a>

First included in: Tax/TaxReportExtraFieldsEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FuelTaxCreditOverClaim attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InstallmentRate name="InstallmentRate">InstallmentRate</a>

First included in: Tax/TaxReportExtraFieldsEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InstallmentRate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#paygCredit name="paygCredit">paygCredit</a>

First included in: Tax/TaxReportExtraFieldsEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the paygCredit attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InstallmentIncome name="InstallmentIncome">InstallmentIncome</a>

First included in: Tax/TaxReportExtraFieldsEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InstallmentIncome attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#NewVariedInstallmentRate name="NewVariedInstallmentRate">NewVariedInstallmentRate</a>

First included in: Tax/TaxReportExtraFieldsEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the NewVariedInstallmentRate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TotalPayroll name="TotalPayroll">TotalPayroll</a>

First included in: Tax/TaxReportExtraFieldsEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TotalPayroll attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WithheldFromInvestmentWhereNoTFN name="WithheldFromInvestmentWhereNoTFN">WithheldFromInvestmentWhereNoTFN</a>

First included in: Tax/TaxReportExtraFieldsEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WithheldFromInvestmentWhereNoTFN attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WithheldFromInvoicesWhereNoABN name="WithheldFromInvoicesWhereNoABN">WithheldFromInvoicesWhereNoABN</a>

First included in: Tax/TaxReportExtraFieldsEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WithheldFromInvoicesWhereNoABN attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#paygWithheldSalary name="paygWithheldSalary">paygWithheldSalary</a>

First included in: Tax/TaxReportExtraFieldsEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the paygWithheldSalary attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DocumentIdentificationNumber name="DocumentIdentificationNumber">DocumentIdentificationNumber</a>

First included in: Tax/TaxReportExtraFieldsEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DocumentIdentificationNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ToDate name="ToDate">ToDate</a>

First included in: Tax/TaxReportExtraFieldsEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ToDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WholesaleCredit name="WholesaleCredit">WholesaleCredit</a>

First included in: Tax/TaxReportExtraFieldsEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WholesaleCredit attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FringeReasonForVariation name="FringeReasonForVariation">FringeReasonForVariation</a>

First included in: Tax/TaxReportExtraFieldsEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FringeReasonForVariation attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PAYGReasonForVariation name="PAYGReasonForVariation">PAYGReasonForVariation</a>

First included in: Tax/TaxReportExtraFieldsEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PAYGReasonForVariation attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SettlementPeriod name="SettlementPeriod">SettlementPeriod</a>

First included in: Tax/TaxReportExtraFieldsEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SettlementPeriod attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BackingTable_TaxReportExtraFieldsRelationshipId name="BackingTable_TaxReportExtraFieldsRelationshipId">BackingTable_TaxReportExtraFieldsRelationshipId</a>

First included in: Tax/TaxReportExtraFieldsEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_TaxReportExtraFieldsRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/Finance/Tax/Transaction/TaxReportExtraFields.md" target="_blank">/core/operationsCommon/Tables/Finance/Tax/Transaction/TaxReportExtraFields.cdm.json/TaxReportExtraFields</a></td><td><a href="../../../Tables/Finance/Tax/Transaction/TaxReportExtraFields.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PrimaryCompanyContextRelationshipId name="Relationship_PrimaryCompanyContextRelationshipId">Relationship_PrimaryCompanyContextRelationshipId</a>

First included in: Tax/TaxReportExtraFieldsEntity (this entity)  

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
