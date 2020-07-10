---
title: UniqueCertificationTaxWithhold_IT in Miscellaneous - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 7/10/2020
ms.author: nebanfic
---

# Unique Certification - Withhold tax in Miscellaneous(UniqueCertificationTaxWithhold_IT)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Tables/Finance/Tax/Miscellaneous/UniqueCertificationTaxWithhold_IT.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[UniqueCertificationTaxWithhold_IT/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Unique Certification - Withhold tax</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="UniqueCertificationTaxWithhold_IT.md" target="_blank">Miscellaneous/UniqueCertificationTaxWithhold_IT</a>|
|[Anticipation](#Anticipation)||<a href="UniqueCertificationTaxWithhold_IT.md" target="_blank">Miscellaneous/UniqueCertificationTaxWithhold_IT</a>|
|[BankruptcyAmountPaidBefore](#BankruptcyAmountPaidBefore)||<a href="UniqueCertificationTaxWithhold_IT.md" target="_blank">Miscellaneous/UniqueCertificationTaxWithhold_IT</a>|
|[BankruptcyAmountPaidByTrustee](#BankruptcyAmountPaidByTrustee)||<a href="UniqueCertificationTaxWithhold_IT.md" target="_blank">Miscellaneous/UniqueCertificationTaxWithhold_IT</a>|
|[Code](#Code)||<a href="UniqueCertificationTaxWithhold_IT.md" target="_blank">Miscellaneous/UniqueCertificationTaxWithhold_IT</a>|
|[DispossessFiscalCode](#DispossessFiscalCode)||<a href="UniqueCertificationTaxWithhold_IT.md" target="_blank">Miscellaneous/UniqueCertificationTaxWithhold_IT</a>|
|[DistraintFiscalCode](#DistraintFiscalCode)||<a href="UniqueCertificationTaxWithhold_IT.md" target="_blank">Miscellaneous/UniqueCertificationTaxWithhold_IT</a>|
|[ExpensesReimbursed](#ExpensesReimbursed)||<a href="UniqueCertificationTaxWithhold_IT.md" target="_blank">Miscellaneous/UniqueCertificationTaxWithhold_IT</a>|
|[HeaderRefRecId](#HeaderRefRecId)||<a href="UniqueCertificationTaxWithhold_IT.md" target="_blank">Miscellaneous/UniqueCertificationTaxWithhold_IT</a>|
|[IncomesPaidMunicipalAddProvisionalTax](#IncomesPaidMunicipalAddProvisionalTax)||<a href="UniqueCertificationTaxWithhold_IT.md" target="_blank">Miscellaneous/UniqueCertificationTaxWithhold_IT</a>|
|[IncomesPaidMunicipalAddSuspendedTax](#IncomesPaidMunicipalAddSuspendedTax)||<a href="UniqueCertificationTaxWithhold_IT.md" target="_blank">Miscellaneous/UniqueCertificationTaxWithhold_IT</a>|
|[IncomesPaidMunicipalAddTaxTax](#IncomesPaidMunicipalAddTaxTax)||<a href="UniqueCertificationTaxWithhold_IT.md" target="_blank">Miscellaneous/UniqueCertificationTaxWithhold_IT</a>|
|[IncomesPaidRegionalAdditionalSuspended](#IncomesPaidRegionalAdditionalSuspended)||<a href="UniqueCertificationTaxWithhold_IT.md" target="_blank">Miscellaneous/UniqueCertificationTaxWithhold_IT</a>|
|[IncomesPaidRegionalAdditionalTaxTax](#IncomesPaidRegionalAdditionalTaxTax)||<a href="UniqueCertificationTaxWithhold_IT.md" target="_blank">Miscellaneous/UniqueCertificationTaxWithhold_IT</a>|
|[IncomesPaidRegionalAddProvisionalTax](#IncomesPaidRegionalAddProvisionalTax)||<a href="UniqueCertificationTaxWithhold_IT.md" target="_blank">Miscellaneous/UniqueCertificationTaxWithhold_IT</a>|
|[IncomesPaidSuspendedWithhold](#IncomesPaidSuspendedWithhold)||<a href="UniqueCertificationTaxWithhold_IT.md" target="_blank">Miscellaneous/UniqueCertificationTaxWithhold_IT</a>|
|[IncomesPaidTaxableAmount](#IncomesPaidTaxableAmount)||<a href="UniqueCertificationTaxWithhold_IT.md" target="_blank">Miscellaneous/UniqueCertificationTaxWithhold_IT</a>|
|[IncomesPaidWithholdingTax](#IncomesPaidWithholdingTax)||<a href="UniqueCertificationTaxWithhold_IT.md" target="_blank">Miscellaneous/UniqueCertificationTaxWithhold_IT</a>|
|[InvoiceNotTaxableExpenses](#InvoiceNotTaxableExpenses)||<a href="UniqueCertificationTaxWithhold_IT.md" target="_blank">Miscellaneous/UniqueCertificationTaxWithhold_IT</a>|
|[InvoiceNotTaxableExpensesOtherAmount](#InvoiceNotTaxableExpensesOtherAmount)||<a href="UniqueCertificationTaxWithhold_IT.md" target="_blank">Miscellaneous/UniqueCertificationTaxWithhold_IT</a>|
|[LineNum](#LineNum)||<a href="UniqueCertificationTaxWithhold_IT.md" target="_blank">Miscellaneous/UniqueCertificationTaxWithhold_IT</a>|
|[MunicipalAdditionalProvisionalTax](#MunicipalAdditionalProvisionalTax)||<a href="UniqueCertificationTaxWithhold_IT.md" target="_blank">Miscellaneous/UniqueCertificationTaxWithhold_IT</a>|
|[MunicipalAdditionalSuspendedTax](#MunicipalAdditionalSuspendedTax)||<a href="UniqueCertificationTaxWithhold_IT.md" target="_blank">Miscellaneous/UniqueCertificationTaxWithhold_IT</a>|
|[MunicipalAdditionalTaxTax](#MunicipalAdditionalTaxTax)||<a href="UniqueCertificationTaxWithhold_IT.md" target="_blank">Miscellaneous/UniqueCertificationTaxWithhold_IT</a>|
|[OtherSubjectFiscalCode](#OtherSubjectFiscalCode)||<a href="UniqueCertificationTaxWithhold_IT.md" target="_blank">Miscellaneous/UniqueCertificationTaxWithhold_IT</a>|
|[ProvisionalWithholdingTax](#ProvisionalWithholdingTax)||<a href="UniqueCertificationTaxWithhold_IT.md" target="_blank">Miscellaneous/UniqueCertificationTaxWithhold_IT</a>|
|[RefRecId](#RefRecId)||<a href="UniqueCertificationTaxWithhold_IT.md" target="_blank">Miscellaneous/UniqueCertificationTaxWithhold_IT</a>|
|[RegionalAdditionalProvisionalTax](#RegionalAdditionalProvisionalTax)||<a href="UniqueCertificationTaxWithhold_IT.md" target="_blank">Miscellaneous/UniqueCertificationTaxWithhold_IT</a>|
|[RegionalAdditionalSuspended](#RegionalAdditionalSuspended)||<a href="UniqueCertificationTaxWithhold_IT.md" target="_blank">Miscellaneous/UniqueCertificationTaxWithhold_IT</a>|
|[RegionalAdditionalTaxTax](#RegionalAdditionalTaxTax)||<a href="UniqueCertificationTaxWithhold_IT.md" target="_blank">Miscellaneous/UniqueCertificationTaxWithhold_IT</a>|
|[RevenueTypology](#RevenueTypology)||<a href="UniqueCertificationTaxWithhold_IT.md" target="_blank">Miscellaneous/UniqueCertificationTaxWithhold_IT</a>|
|[SelfEmplFiscalCode](#SelfEmplFiscalCode)||<a href="UniqueCertificationTaxWithhold_IT.md" target="_blank">Miscellaneous/UniqueCertificationTaxWithhold_IT</a>|
|[SocialContributionsDue](#SocialContributionsDue)||<a href="UniqueCertificationTaxWithhold_IT.md" target="_blank">Miscellaneous/UniqueCertificationTaxWithhold_IT</a>|
|[SocialContributionsOther](#SocialContributionsOther)||<a href="UniqueCertificationTaxWithhold_IT.md" target="_blank">Miscellaneous/UniqueCertificationTaxWithhold_IT</a>|
|[SocialContributionsOtherAmount](#SocialContributionsOtherAmount)||<a href="UniqueCertificationTaxWithhold_IT.md" target="_blank">Miscellaneous/UniqueCertificationTaxWithhold_IT</a>|
|[SocialContributionsPaid](#SocialContributionsPaid)||<a href="UniqueCertificationTaxWithhold_IT.md" target="_blank">Miscellaneous/UniqueCertificationTaxWithhold_IT</a>|
|[SocialContributionsPaidByThePayer](#SocialContributionsPaidByThePayer)||<a href="UniqueCertificationTaxWithhold_IT.md" target="_blank">Miscellaneous/UniqueCertificationTaxWithhold_IT</a>|
|[SocialContributionsPaidByTheVendor](#SocialContributionsPaidByTheVendor)||<a href="UniqueCertificationTaxWithhold_IT.md" target="_blank">Miscellaneous/UniqueCertificationTaxWithhold_IT</a>|
|[SocialSecCategory](#SocialSecCategory)||<a href="UniqueCertificationTaxWithhold_IT.md" target="_blank">Miscellaneous/UniqueCertificationTaxWithhold_IT</a>|
|[SocialSecCode](#SocialSecCode)||<a href="UniqueCertificationTaxWithhold_IT.md" target="_blank">Miscellaneous/UniqueCertificationTaxWithhold_IT</a>|
|[SocialSecCompanyCode](#SocialSecCompanyCode)||<a href="UniqueCertificationTaxWithhold_IT.md" target="_blank">Miscellaneous/UniqueCertificationTaxWithhold_IT</a>|
|[SocialSecFiscalCode](#SocialSecFiscalCode)||<a href="UniqueCertificationTaxWithhold_IT.md" target="_blank">Miscellaneous/UniqueCertificationTaxWithhold_IT</a>|
|[SocialSecName](#SocialSecName)||<a href="UniqueCertificationTaxWithhold_IT.md" target="_blank">Miscellaneous/UniqueCertificationTaxWithhold_IT</a>|
|[SuspendedWithhold](#SuspendedWithhold)||<a href="UniqueCertificationTaxWithhold_IT.md" target="_blank">Miscellaneous/UniqueCertificationTaxWithhold_IT</a>|
|[TaxableAmount](#TaxableAmount)||<a href="UniqueCertificationTaxWithhold_IT.md" target="_blank">Miscellaneous/UniqueCertificationTaxWithhold_IT</a>|
|[TaxablePrecedingYears](#TaxablePrecedingYears)||<a href="UniqueCertificationTaxWithhold_IT.md" target="_blank">Miscellaneous/UniqueCertificationTaxWithhold_IT</a>|
|[TaxTaxWithholdAmount](#TaxTaxWithholdAmount)||<a href="UniqueCertificationTaxWithhold_IT.md" target="_blank">Miscellaneous/UniqueCertificationTaxWithhold_IT</a>|
|[TaxWithholdCode](#TaxWithholdCode)||<a href="UniqueCertificationTaxWithhold_IT.md" target="_blank">Miscellaneous/UniqueCertificationTaxWithhold_IT</a>|
|[TaxWithholdPrecedingYears](#TaxWithholdPrecedingYears)||<a href="UniqueCertificationTaxWithhold_IT.md" target="_blank">Miscellaneous/UniqueCertificationTaxWithhold_IT</a>|
|[TaxWithholdReimbursed](#TaxWithholdReimbursed)||<a href="UniqueCertificationTaxWithhold_IT.md" target="_blank">Miscellaneous/UniqueCertificationTaxWithhold_IT</a>|
|[TotalGrossAmount](#TotalGrossAmount)||<a href="UniqueCertificationTaxWithhold_IT.md" target="_blank">Miscellaneous/UniqueCertificationTaxWithhold_IT</a>|
|[VendAccount](#VendAccount)||<a href="UniqueCertificationTaxWithhold_IT.md" target="_blank">Miscellaneous/UniqueCertificationTaxWithhold_IT</a>|
|[WithholdingTax](#WithholdingTax)||<a href="UniqueCertificationTaxWithhold_IT.md" target="_blank">Miscellaneous/UniqueCertificationTaxWithhold_IT</a>|
|[Year](#Year)||<a href="UniqueCertificationTaxWithhold_IT.md" target="_blank">Miscellaneous/UniqueCertificationTaxWithhold_IT</a>|
|[CodeRevenueTypology](#CodeRevenueTypology)||<a href="UniqueCertificationTaxWithhold_IT.md" target="_blank">Miscellaneous/UniqueCertificationTaxWithhold_IT</a>|
|[CodeCode](#CodeCode)||<a href="UniqueCertificationTaxWithhold_IT.md" target="_blank">Miscellaneous/UniqueCertificationTaxWithhold_IT</a>|
|[DataAreaId](#DataAreaId)||<a href="UniqueCertificationTaxWithhold_IT.md" target="_blank">Miscellaneous/UniqueCertificationTaxWithhold_IT</a>|
|[Relationship_TaxWithholdTableRelationshipId](#Relationship_TaxWithholdTableRelationshipId)||<a href="UniqueCertificationTaxWithhold_IT.md" target="_blank">Miscellaneous/UniqueCertificationTaxWithhold_IT</a>|
|[Relationship_UniqueCertificationHeaderRelationshipId](#Relationship_UniqueCertificationHeaderRelationshipId)||<a href="UniqueCertificationTaxWithhold_IT.md" target="_blank">Miscellaneous/UniqueCertificationTaxWithhold_IT</a>|
|[Relationship_UniqueCertificationVendorDetailRelationshipId](#Relationship_UniqueCertificationVendorDetailRelationshipId)||<a href="UniqueCertificationTaxWithhold_IT.md" target="_blank">Miscellaneous/UniqueCertificationTaxWithhold_IT</a>|
|[Relationship_VendTableRelationshipId](#Relationship_VendTableRelationshipId)||<a href="UniqueCertificationTaxWithhold_IT.md" target="_blank">Miscellaneous/UniqueCertificationTaxWithhold_IT</a>|
|[Relationship_CompanyRelationshipId](#Relationship_CompanyRelationshipId)||<a href="UniqueCertificationTaxWithhold_IT.md" target="_blank">Miscellaneous/UniqueCertificationTaxWithhold_IT</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: Miscellaneous/UniqueCertificationTaxWithhold_IT (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[UniqueCertificationTaxWithhold_IT/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#Anticipation name="Anticipation">Anticipation</a>

First included in: Miscellaneous/UniqueCertificationTaxWithhold_IT (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Anticipation</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Anticipation attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Anticipation</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#BankruptcyAmountPaidBefore name="BankruptcyAmountPaidBefore">BankruptcyAmountPaidBefore</a>

First included in: Miscellaneous/UniqueCertificationTaxWithhold_IT (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Amount paid before bankruptcy</td></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BankruptcyAmountPaidBefore attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Amount paid before bankruptcy</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#BankruptcyAmountPaidByTrustee name="BankruptcyAmountPaidByTrustee">BankruptcyAmountPaidByTrustee</a>

First included in: Miscellaneous/UniqueCertificationTaxWithhold_IT (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Amount paid by trustee</td></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BankruptcyAmountPaidByTrustee attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Amount paid by trustee</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#Code name="Code">Code</a>

First included in: Miscellaneous/UniqueCertificationTaxWithhold_IT (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Code attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#DispossessFiscalCode name="DispossessFiscalCode">DispossessFiscalCode</a>

First included in: Miscellaneous/UniqueCertificationTaxWithhold_IT (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Dispossess fiscal code</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DispossessFiscalCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Dispossess fiscal code</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DistraintFiscalCode name="DistraintFiscalCode">DistraintFiscalCode</a>

First included in: Miscellaneous/UniqueCertificationTaxWithhold_IT (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Distraint fiscal code</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DistraintFiscalCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Distraint fiscal code</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ExpensesReimbursed name="ExpensesReimbursed">ExpensesReimbursed</a>

First included in: Miscellaneous/UniqueCertificationTaxWithhold_IT (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Expenses reimbursed</td></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ExpensesReimbursed attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Expenses reimbursed</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#HeaderRefRecId name="HeaderRefRecId">HeaderRefRecId</a>

First included in: Miscellaneous/UniqueCertificationTaxWithhold_IT (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the HeaderRefRecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#IncomesPaidMunicipalAddProvisionalTax name="IncomesPaidMunicipalAddProvisionalTax">IncomesPaidMunicipalAddProvisionalTax</a>

First included in: Miscellaneous/UniqueCertificationTaxWithhold_IT (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Municipal additional provisional tax</td></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IncomesPaidMunicipalAddProvisionalTax attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Municipal additional provisional tax</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#IncomesPaidMunicipalAddSuspendedTax name="IncomesPaidMunicipalAddSuspendedTax">IncomesPaidMunicipalAddSuspendedTax</a>

First included in: Miscellaneous/UniqueCertificationTaxWithhold_IT (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Municipal Additional Suspended Tax</td></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IncomesPaidMunicipalAddSuspendedTax attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Municipal Additional Suspended Tax</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#IncomesPaidMunicipalAddTaxTax name="IncomesPaidMunicipalAddTaxTax">IncomesPaidMunicipalAddTaxTax</a>

First included in: Miscellaneous/UniqueCertificationTaxWithhold_IT (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Municipal Additional Tax</td></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IncomesPaidMunicipalAddTaxTax attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Municipal Additional Tax</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#IncomesPaidRegionalAdditionalSuspended name="IncomesPaidRegionalAdditionalSuspended">IncomesPaidRegionalAdditionalSuspended</a>

First included in: Miscellaneous/UniqueCertificationTaxWithhold_IT (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Suspended state addition</td></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IncomesPaidRegionalAdditionalSuspended attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Suspended state addition</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#IncomesPaidRegionalAdditionalTaxTax name="IncomesPaidRegionalAdditionalTaxTax">IncomesPaidRegionalAdditionalTaxTax</a>

First included in: Miscellaneous/UniqueCertificationTaxWithhold_IT (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Regional Additional Tax</td></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IncomesPaidRegionalAdditionalTaxTax attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Regional Additional Tax</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#IncomesPaidRegionalAddProvisionalTax name="IncomesPaidRegionalAddProvisionalTax">IncomesPaidRegionalAddProvisionalTax</a>

First included in: Miscellaneous/UniqueCertificationTaxWithhold_IT (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Regional Additional Provisional Tax</td></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IncomesPaidRegionalAddProvisionalTax attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Regional Additional Provisional Tax</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#IncomesPaidSuspendedWithhold name="IncomesPaidSuspendedWithhold">IncomesPaidSuspendedWithhold</a>

First included in: Miscellaneous/UniqueCertificationTaxWithhold_IT (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Suspended withhold</td></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IncomesPaidSuspendedWithhold attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Suspended withhold</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#IncomesPaidTaxableAmount name="IncomesPaidTaxableAmount">IncomesPaidTaxableAmount</a>

First included in: Miscellaneous/UniqueCertificationTaxWithhold_IT (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Amount origin</td></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IncomesPaidTaxableAmount attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Amount origin</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#IncomesPaidWithholdingTax name="IncomesPaidWithholdingTax">IncomesPaidWithholdingTax</a>

First included in: Miscellaneous/UniqueCertificationTaxWithhold_IT (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Withholding tax</td></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IncomesPaidWithholdingTax attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Withholding tax</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#InvoiceNotTaxableExpenses name="InvoiceNotTaxableExpenses">InvoiceNotTaxableExpenses</a>

First included in: Miscellaneous/UniqueCertificationTaxWithhold_IT (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Base excluded amount</td></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InvoiceNotTaxableExpenses attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Base excluded amount</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#InvoiceNotTaxableExpensesOtherAmount name="InvoiceNotTaxableExpensesOtherAmount">InvoiceNotTaxableExpensesOtherAmount</a>

First included in: Miscellaneous/UniqueCertificationTaxWithhold_IT (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Other amounts not subjected</td></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InvoiceNotTaxableExpensesOtherAmount attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Other amounts not subjected</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#LineNum name="LineNum">LineNum</a>

First included in: Miscellaneous/UniqueCertificationTaxWithhold_IT (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LineNum attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#MunicipalAdditionalProvisionalTax name="MunicipalAdditionalProvisionalTax">MunicipalAdditionalProvisionalTax</a>

First included in: Miscellaneous/UniqueCertificationTaxWithhold_IT (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Municipal additional provisional tax</td></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MunicipalAdditionalProvisionalTax attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Municipal additional provisional tax</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#MunicipalAdditionalSuspendedTax name="MunicipalAdditionalSuspendedTax">MunicipalAdditionalSuspendedTax</a>

First included in: Miscellaneous/UniqueCertificationTaxWithhold_IT (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Municipal Additional Suspended Tax</td></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MunicipalAdditionalSuspendedTax attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Municipal Additional Suspended Tax</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#MunicipalAdditionalTaxTax name="MunicipalAdditionalTaxTax">MunicipalAdditionalTaxTax</a>

First included in: Miscellaneous/UniqueCertificationTaxWithhold_IT (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Municipal Additional Tax</td></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MunicipalAdditionalTaxTax attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Municipal Additional Tax</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#OtherSubjectFiscalCode name="OtherSubjectFiscalCode">OtherSubjectFiscalCode</a>

First included in: Miscellaneous/UniqueCertificationTaxWithhold_IT (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OtherSubjectFiscalCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProvisionalWithholdingTax name="ProvisionalWithholdingTax">ProvisionalWithholdingTax</a>

First included in: Miscellaneous/UniqueCertificationTaxWithhold_IT (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Provisional withholding tax</td></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProvisionalWithholdingTax attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Provisional withholding tax</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#RefRecId name="RefRecId">RefRecId</a>

First included in: Miscellaneous/UniqueCertificationTaxWithhold_IT (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RefRecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#RegionalAdditionalProvisionalTax name="RegionalAdditionalProvisionalTax">RegionalAdditionalProvisionalTax</a>

First included in: Miscellaneous/UniqueCertificationTaxWithhold_IT (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Regional Additional Provisional Tax</td></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RegionalAdditionalProvisionalTax attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Regional Additional Provisional Tax</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#RegionalAdditionalSuspended name="RegionalAdditionalSuspended">RegionalAdditionalSuspended</a>

First included in: Miscellaneous/UniqueCertificationTaxWithhold_IT (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Suspended state addition</td></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RegionalAdditionalSuspended attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Suspended state addition</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#RegionalAdditionalTaxTax name="RegionalAdditionalTaxTax">RegionalAdditionalTaxTax</a>

First included in: Miscellaneous/UniqueCertificationTaxWithhold_IT (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Regional Additional Tax</td></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RegionalAdditionalTaxTax attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Regional Additional Tax</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#RevenueTypology name="RevenueTypology">RevenueTypology</a>

First included in: Miscellaneous/UniqueCertificationTaxWithhold_IT (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RevenueTypology attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#SelfEmplFiscalCode name="SelfEmplFiscalCode">SelfEmplFiscalCode</a>

First included in: Miscellaneous/UniqueCertificationTaxWithhold_IT (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Self-employment fiscal code</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SelfEmplFiscalCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Self-employment fiscal code</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SocialContributionsDue name="SocialContributionsDue">SocialContributionsDue</a>

First included in: Miscellaneous/UniqueCertificationTaxWithhold_IT (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Contributions due</td></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SocialContributionsDue attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Contributions due</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#SocialContributionsOther name="SocialContributionsOther">SocialContributionsOther</a>

First included in: Miscellaneous/UniqueCertificationTaxWithhold_IT (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SocialContributionsOther attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#SocialContributionsOtherAmount name="SocialContributionsOtherAmount">SocialContributionsOtherAmount</a>

First included in: Miscellaneous/UniqueCertificationTaxWithhold_IT (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Other contributions amount</td></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SocialContributionsOtherAmount attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Other contributions amount</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#SocialContributionsPaid name="SocialContributionsPaid">SocialContributionsPaid</a>

First included in: Miscellaneous/UniqueCertificationTaxWithhold_IT (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Contributions paid</td></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SocialContributionsPaid attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Contributions paid</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#SocialContributionsPaidByThePayer name="SocialContributionsPaidByThePayer">SocialContributionsPaidByThePayer</a>

First included in: Miscellaneous/UniqueCertificationTaxWithhold_IT (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Social Contributions Paid By The Payer</td></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SocialContributionsPaidByThePayer attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Social Contributions Paid By The Payer</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#SocialContributionsPaidByTheVendor name="SocialContributionsPaidByTheVendor">SocialContributionsPaidByTheVendor</a>

First included in: Miscellaneous/UniqueCertificationTaxWithhold_IT (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Social Contributions Paid By The Vendor</td></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SocialContributionsPaidByTheVendor attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Social Contributions Paid By The Vendor</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#SocialSecCategory name="SocialSecCategory">SocialSecCategory</a>

First included in: Miscellaneous/UniqueCertificationTaxWithhold_IT (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SocialSecCategory attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SocialSecCode name="SocialSecCode">SocialSecCode</a>

First included in: Miscellaneous/UniqueCertificationTaxWithhold_IT (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SocialSecCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SocialSecCompanyCode name="SocialSecCompanyCode">SocialSecCompanyCode</a>

First included in: Miscellaneous/UniqueCertificationTaxWithhold_IT (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Company code</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SocialSecCompanyCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Company code</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SocialSecFiscalCode name="SocialSecFiscalCode">SocialSecFiscalCode</a>

First included in: Miscellaneous/UniqueCertificationTaxWithhold_IT (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Social security auth. fiscal code</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SocialSecFiscalCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Social security auth. fiscal code</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SocialSecName name="SocialSecName">SocialSecName</a>

First included in: Miscellaneous/UniqueCertificationTaxWithhold_IT (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Social security auth. name</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SocialSecName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Social security auth. name</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SuspendedWithhold name="SuspendedWithhold">SuspendedWithhold</a>

First included in: Miscellaneous/UniqueCertificationTaxWithhold_IT (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Suspended withhold</td></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SuspendedWithhold attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Suspended withhold</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#TaxableAmount name="TaxableAmount">TaxableAmount</a>

First included in: Miscellaneous/UniqueCertificationTaxWithhold_IT (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Amount origin</td></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxableAmount attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Amount origin</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#TaxablePrecedingYears name="TaxablePrecedingYears">TaxablePrecedingYears</a>

First included in: Miscellaneous/UniqueCertificationTaxWithhold_IT (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Taxable preceding years</td></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxablePrecedingYears attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Taxable preceding years</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#TaxTaxWithholdAmount name="TaxTaxWithholdAmount">TaxTaxWithholdAmount</a>

First included in: Miscellaneous/UniqueCertificationTaxWithhold_IT (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Withholding tax amount</td></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxTaxWithholdAmount attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Withholding tax amount</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#TaxWithholdCode name="TaxWithholdCode">TaxWithholdCode</a>

First included in: Miscellaneous/UniqueCertificationTaxWithhold_IT (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxWithholdCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.readOnly**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TaxWithholdPrecedingYears name="TaxWithholdPrecedingYears">TaxWithholdPrecedingYears</a>

First included in: Miscellaneous/UniqueCertificationTaxWithhold_IT (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Tax Withhold Preceding Years</td></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxWithholdPrecedingYears attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Tax Withhold Preceding Years</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#TaxWithholdReimbursed name="TaxWithholdReimbursed">TaxWithholdReimbursed</a>

First included in: Miscellaneous/UniqueCertificationTaxWithhold_IT (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Tax Withhold Reimbursed</td></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxWithholdReimbursed attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Tax Withhold Reimbursed</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#TotalGrossAmount name="TotalGrossAmount">TotalGrossAmount</a>

First included in: Miscellaneous/UniqueCertificationTaxWithhold_IT (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TotalGrossAmount attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#VendAccount name="VendAccount">VendAccount</a>

First included in: Miscellaneous/UniqueCertificationTaxWithhold_IT (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VendAccount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.readOnly**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WithholdingTax name="WithholdingTax">WithholdingTax</a>

First included in: Miscellaneous/UniqueCertificationTaxWithhold_IT (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Withholding tax</td></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WithholdingTax attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Withholding tax</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#Year name="Year">Year</a>

First included in: Miscellaneous/UniqueCertificationTaxWithhold_IT (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Year attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#CodeRevenueTypology name="CodeRevenueTypology">CodeRevenueTypology</a>

First included in: Miscellaneous/UniqueCertificationTaxWithhold_IT (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Revenue typology</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CodeRevenueTypology attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Revenue typology</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CodeCode name="CodeCode">CodeCode</a>

First included in: Miscellaneous/UniqueCertificationTaxWithhold_IT (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Code</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CodeCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Code</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DataAreaId name="DataAreaId">DataAreaId</a>

First included in: Miscellaneous/UniqueCertificationTaxWithhold_IT (this entity)  

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

### <a href=#Relationship_TaxWithholdTableRelationshipId name="Relationship_TaxWithholdTableRelationshipId">Relationship_TaxWithholdTableRelationshipId</a>

First included in: Miscellaneous/UniqueCertificationTaxWithhold_IT (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_TaxWithholdTableRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Main/TaxWithholdTable.md" target="_blank">/core/operationsCommon/Tables/Finance/Tax/Main/TaxWithholdTable.cdm.json/TaxWithholdTable</a></td><td><a href="../Main/TaxWithholdTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_UniqueCertificationHeaderRelationshipId name="Relationship_UniqueCertificationHeaderRelationshipId">Relationship_UniqueCertificationHeaderRelationshipId</a>

First included in: Miscellaneous/UniqueCertificationTaxWithhold_IT (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_UniqueCertificationHeaderRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../APARShared/Miscellaneous/UniqueCertificationHeader_IT.md" target="_blank">/core/operationsCommon/Tables/Finance/APARShared/Miscellaneous/UniqueCertificationHeader_IT.cdm.json/UniqueCertificationHeader_IT</a></td><td><a href="../../APARShared/Miscellaneous/UniqueCertificationHeader_IT.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_UniqueCertificationVendorDetailRelationshipId name="Relationship_UniqueCertificationVendorDetailRelationshipId">Relationship_UniqueCertificationVendorDetailRelationshipId</a>

First included in: Miscellaneous/UniqueCertificationTaxWithhold_IT (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_UniqueCertificationVendorDetailRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../APARShared/Miscellaneous/UniqueCertificationVendorDetail_IT.md" target="_blank">/core/operationsCommon/Tables/Finance/APARShared/Miscellaneous/UniqueCertificationVendorDetail_IT.cdm.json/UniqueCertificationVendorDetail_IT</a></td><td><a href="../../APARShared/Miscellaneous/UniqueCertificationVendorDetail_IT.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_VendTableRelationshipId name="Relationship_VendTableRelationshipId">Relationship_VendTableRelationshipId</a>

First included in: Miscellaneous/UniqueCertificationTaxWithhold_IT (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_VendTableRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../SupplyChain/Vendor/Main/VendTable.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/Vendor/Main/VendTable.cdm.json/VendTable</a></td><td><a href="../../../SupplyChain/Vendor/Main/VendTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_CompanyRelationshipId name="Relationship_CompanyRelationshipId">Relationship_CompanyRelationshipId</a>

First included in: Miscellaneous/UniqueCertificationTaxWithhold_IT (this entity)  

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
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../Ledger/Main/CompanyInfo.md" target="_blank">/core/operationsCommon/Tables/Finance/Ledger/Main/CompanyInfo.cdm.json/CompanyInfo</a></td><td><a href="../../Ledger/Main/CompanyInfo.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>
