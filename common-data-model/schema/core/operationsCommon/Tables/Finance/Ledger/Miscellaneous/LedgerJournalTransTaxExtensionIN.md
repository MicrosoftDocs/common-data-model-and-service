---
title: LedgerJournalTransTaxExtensionIN - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 6/30/2020
ms.author: nebanfic
---

# Ledger Journal trans tax extension

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Tables/Finance/Ledger/Miscellaneous/LedgerJournalTransTaxExtensionIN.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[LedgerJournalTransTaxExtensionIN/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Ledger Journal trans tax extension</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="LedgerJournalTransTaxExtensionIN.md" target="_blank">Miscellaneous/LedgerJournalTransTaxExtensionIN</a>|
|[LedgerJournalTrans](#LedgerJournalTrans)||<a href="LedgerJournalTransTaxExtensionIN.md" target="_blank">Miscellaneous/LedgerJournalTransTaxExtensionIN</a>|
|[ServiceEventGroup](#ServiceEventGroup)||<a href="LedgerJournalTransTaxExtensionIN.md" target="_blank">Miscellaneous/LedgerJournalTransTaxExtensionIN</a>|
|[AssessableValueTransactionCurrency](#AssessableValueTransactionCurrency)||<a href="LedgerJournalTransTaxExtensionIN.md" target="_blank">Miscellaneous/LedgerJournalTransTaxExtensionIN</a>|
|[CustomsDuty](#CustomsDuty)||<a href="LedgerJournalTransTaxExtensionIN.md" target="_blank">Miscellaneous/LedgerJournalTransTaxExtensionIN</a>|
|[MaximumRetailPrice](#MaximumRetailPrice)||<a href="LedgerJournalTransTaxExtensionIN.md" target="_blank">Miscellaneous/LedgerJournalTransTaxExtensionIN</a>|
|[TaxSetoffVoucher](#TaxSetoffVoucher)||<a href="LedgerJournalTransTaxExtensionIN.md" target="_blank">Miscellaneous/LedgerJournalTransTaxExtensionIN</a>|
|[TaxWithholdCode](#TaxWithholdCode)||<a href="LedgerJournalTransTaxExtensionIN.md" target="_blank">Miscellaneous/LedgerJournalTransTaxExtensionIN</a>|
|[TCSGroup](#TCSGroup)||<a href="LedgerJournalTransTaxExtensionIN.md" target="_blank">Miscellaneous/LedgerJournalTransTaxExtensionIN</a>|
|[TDSGroup](#TDSGroup)||<a href="LedgerJournalTransTaxExtensionIN.md" target="_blank">Miscellaneous/LedgerJournalTransTaxExtensionIN</a>|
|[ProvisionalAssessment](#ProvisionalAssessment)||<a href="LedgerJournalTransTaxExtensionIN.md" target="_blank">Miscellaneous/LedgerJournalTransTaxExtensionIN</a>|
|[InvoiceIdentification](#InvoiceIdentification)||<a href="LedgerJournalTransTaxExtensionIN.md" target="_blank">Miscellaneous/LedgerJournalTransTaxExtensionIN</a>|
|[OriginalTransactionDate](#OriginalTransactionDate)||<a href="LedgerJournalTransTaxExtensionIN.md" target="_blank">Miscellaneous/LedgerJournalTransTaxExtensionIN</a>|
|[OriginalTransactionID](#OriginalTransactionID)||<a href="LedgerJournalTransTaxExtensionIN.md" target="_blank">Miscellaneous/LedgerJournalTransTaxExtensionIN</a>|
|[RefPurchInvoiceDate](#RefPurchInvoiceDate)||<a href="LedgerJournalTransTaxExtensionIN.md" target="_blank">Miscellaneous/LedgerJournalTransTaxExtensionIN</a>|
|[RefPurchInvoiceId](#RefPurchInvoiceId)||<a href="LedgerJournalTransTaxExtensionIN.md" target="_blank">Miscellaneous/LedgerJournalTransTaxExtensionIN</a>|
|[RefSalesInvoiceDate](#RefSalesInvoiceDate)||<a href="LedgerJournalTransTaxExtensionIN.md" target="_blank">Miscellaneous/LedgerJournalTransTaxExtensionIN</a>|
|[RefSalesInvoiceId](#RefSalesInvoiceId)||<a href="LedgerJournalTransTaxExtensionIN.md" target="_blank">Miscellaneous/LedgerJournalTransTaxExtensionIN</a>|
|[TaxWithholdNatureOfRemittance](#TaxWithholdNatureOfRemittance)||<a href="LedgerJournalTransTaxExtensionIN.md" target="_blank">Miscellaneous/LedgerJournalTransTaxExtensionIN</a>|
|[TaxWithholdCountryRegionToRemittance](#TaxWithholdCountryRegionToRemittance)||<a href="LedgerJournalTransTaxExtensionIN.md" target="_blank">Miscellaneous/LedgerJournalTransTaxExtensionIN</a>|
|[TaxWithholdAcknowledgementNumber](#TaxWithholdAcknowledgementNumber)||<a href="LedgerJournalTransTaxExtensionIN.md" target="_blank">Miscellaneous/LedgerJournalTransTaxExtensionIN</a>|
|[TaxInventVATCommodityCodeId](#TaxInventVATCommodityCodeId)||<a href="LedgerJournalTransTaxExtensionIN.md" target="_blank">Miscellaneous/LedgerJournalTransTaxExtensionIN</a>|
|[TaxInformation_IN](#TaxInformation_IN)||<a href="LedgerJournalTransTaxExtensionIN.md" target="_blank">Miscellaneous/LedgerJournalTransTaxExtensionIN</a>|
|[LedgerJournalInclTax](#LedgerJournalInclTax)||<a href="LedgerJournalTransTaxExtensionIN.md" target="_blank">Miscellaneous/LedgerJournalTransTaxExtensionIN</a>|
|[DirectSettlement](#DirectSettlement)||<a href="LedgerJournalTransTaxExtensionIN.md" target="_blank">Miscellaneous/LedgerJournalTransTaxExtensionIN</a>|
|[CENVATCreditAvailed](#CENVATCreditAvailed)||<a href="LedgerJournalTransTaxExtensionIN.md" target="_blank">Miscellaneous/LedgerJournalTransTaxExtensionIN</a>|
|[ExcludedGSTAmountCur](#ExcludedGSTAmountCur)||<a href="LedgerJournalTransTaxExtensionIN.md" target="_blank">Miscellaneous/LedgerJournalTransTaxExtensionIN</a>|
|[DataAreaId](#DataAreaId)||<a href="LedgerJournalTransTaxExtensionIN.md" target="_blank">Miscellaneous/LedgerJournalTransTaxExtensionIN</a>|
|[Relationship_LedgerJournalTransRelationshipId](#Relationship_LedgerJournalTransRelationshipId)||<a href="LedgerJournalTransTaxExtensionIN.md" target="_blank">Miscellaneous/LedgerJournalTransTaxExtensionIN</a>|
|[Relationship_TaxWithholdGroupHeadingTCS_INRelationshipId](#Relationship_TaxWithholdGroupHeadingTCS_INRelationshipId)||<a href="LedgerJournalTransTaxExtensionIN.md" target="_blank">Miscellaneous/LedgerJournalTransTaxExtensionIN</a>|
|[Relationship_TaxWithholdGroupHeadingTDS_INRelationshipId](#Relationship_TaxWithholdGroupHeadingTDS_INRelationshipId)||<a href="LedgerJournalTransTaxExtensionIN.md" target="_blank">Miscellaneous/LedgerJournalTransTaxExtensionIN</a>|
|[Relationship_TaxWithholdTable_INRelationshipId](#Relationship_TaxWithholdTable_INRelationshipId)||<a href="LedgerJournalTransTaxExtensionIN.md" target="_blank">Miscellaneous/LedgerJournalTransTaxExtensionIN</a>|
|[Relationship_CompanyRelationshipId](#Relationship_CompanyRelationshipId)||<a href="LedgerJournalTransTaxExtensionIN.md" target="_blank">Miscellaneous/LedgerJournalTransTaxExtensionIN</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: Miscellaneous/LedgerJournalTransTaxExtensionIN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[LedgerJournalTransTaxExtensionIN/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#LedgerJournalTrans name="LedgerJournalTrans">LedgerJournalTrans</a>

First included in: Miscellaneous/LedgerJournalTransTaxExtensionIN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LedgerJournalTrans attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#ServiceEventGroup name="ServiceEventGroup">ServiceEventGroup</a>

First included in: Miscellaneous/LedgerJournalTransTaxExtensionIN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ServiceEventGroup attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AssessableValueTransactionCurrency name="AssessableValueTransactionCurrency">AssessableValueTransactionCurrency</a>

First included in: Miscellaneous/LedgerJournalTransTaxExtensionIN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Assessable value</td></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AssessableValueTransactionCurrency attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Assessable value</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#CustomsDuty name="CustomsDuty">CustomsDuty</a>

First included in: Miscellaneous/LedgerJournalTransTaxExtensionIN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CustomsDuty attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#MaximumRetailPrice name="MaximumRetailPrice">MaximumRetailPrice</a>

First included in: Miscellaneous/LedgerJournalTransTaxExtensionIN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Max. retail price</td></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MaximumRetailPrice attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Max. retail price</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#TaxSetoffVoucher name="TaxSetoffVoucher">TaxSetoffVoucher</a>

First included in: Miscellaneous/LedgerJournalTransTaxExtensionIN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Tax setoff voucher</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxSetoffVoucher attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Tax setoff voucher</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TaxWithholdCode name="TaxWithholdCode">TaxWithholdCode</a>

First included in: Miscellaneous/LedgerJournalTransTaxExtensionIN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxWithholdCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.readOnly**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TCSGroup name="TCSGroup">TCSGroup</a>

First included in: Miscellaneous/LedgerJournalTransTaxExtensionIN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>TCS group</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TCSGroup attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>TCS group</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TDSGroup name="TDSGroup">TDSGroup</a>

First included in: Miscellaneous/LedgerJournalTransTaxExtensionIN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>TDS group</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TDSGroup attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>TDS group</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProvisionalAssessment name="ProvisionalAssessment">ProvisionalAssessment</a>

First included in: Miscellaneous/LedgerJournalTransTaxExtensionIN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Provisional assessment</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProvisionalAssessment attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Provisional assessment</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#InvoiceIdentification name="InvoiceIdentification">InvoiceIdentification</a>

First included in: Miscellaneous/LedgerJournalTransTaxExtensionIN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InvoiceIdentification attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#OriginalTransactionDate name="OriginalTransactionDate">OriginalTransactionDate</a>

First included in: Miscellaneous/LedgerJournalTransTaxExtensionIN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Original transaction date</td></tr><tr><td>dataFormat</td><td>date</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OriginalTransactionDate attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Original transaction date</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.date**  
</details>

### <a href=#OriginalTransactionID name="OriginalTransactionID">OriginalTransactionID</a>

First included in: Miscellaneous/LedgerJournalTransTaxExtensionIN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Original transaction id</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OriginalTransactionID attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Original transaction id</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RefPurchInvoiceDate name="RefPurchInvoiceDate">RefPurchInvoiceDate</a>

First included in: Miscellaneous/LedgerJournalTransTaxExtensionIN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Original invoice date</td></tr><tr><td>dataFormat</td><td>date</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RefPurchInvoiceDate attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Original invoice date</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.date**  
</details>

### <a href=#RefPurchInvoiceId name="RefPurchInvoiceId">RefPurchInvoiceId</a>

First included in: Miscellaneous/LedgerJournalTransTaxExtensionIN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Original invoice number</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RefPurchInvoiceId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Original invoice number</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RefSalesInvoiceDate name="RefSalesInvoiceDate">RefSalesInvoiceDate</a>

First included in: Miscellaneous/LedgerJournalTransTaxExtensionIN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Original invoice date</td></tr><tr><td>dataFormat</td><td>date</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RefSalesInvoiceDate attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Original invoice date</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.date**  
</details>

### <a href=#RefSalesInvoiceId name="RefSalesInvoiceId">RefSalesInvoiceId</a>

First included in: Miscellaneous/LedgerJournalTransTaxExtensionIN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Original invoice number</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RefSalesInvoiceId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Original invoice number</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TaxWithholdNatureOfRemittance name="TaxWithholdNatureOfRemittance">TaxWithholdNatureOfRemittance</a>

First included in: Miscellaneous/LedgerJournalTransTaxExtensionIN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxWithholdNatureOfRemittance attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#TaxWithholdCountryRegionToRemittance name="TaxWithholdCountryRegionToRemittance">TaxWithholdCountryRegionToRemittance</a>

First included in: Miscellaneous/LedgerJournalTransTaxExtensionIN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxWithholdCountryRegionToRemittance attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#TaxWithholdAcknowledgementNumber name="TaxWithholdAcknowledgementNumber">TaxWithholdAcknowledgementNumber</a>

First included in: Miscellaneous/LedgerJournalTransTaxExtensionIN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxWithholdAcknowledgementNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TaxInventVATCommodityCodeId name="TaxInventVATCommodityCodeId">TaxInventVATCommodityCodeId</a>

First included in: Miscellaneous/LedgerJournalTransTaxExtensionIN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxInventVATCommodityCodeId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TaxInformation_IN name="TaxInformation_IN">TaxInformation_IN</a>

First included in: Miscellaneous/LedgerJournalTransTaxExtensionIN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxInformation_IN attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#LedgerJournalInclTax name="LedgerJournalInclTax">LedgerJournalInclTax</a>

First included in: Miscellaneous/LedgerJournalTransTaxExtensionIN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LedgerJournalInclTax attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#DirectSettlement name="DirectSettlement">DirectSettlement</a>

First included in: Miscellaneous/LedgerJournalTransTaxExtensionIN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DirectSettlement attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#CENVATCreditAvailed name="CENVATCreditAvailed">CENVATCreditAvailed</a>

First included in: Miscellaneous/LedgerJournalTransTaxExtensionIN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CENVATCreditAvailed attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#ExcludedGSTAmountCur name="ExcludedGSTAmountCur">ExcludedGSTAmountCur</a>

First included in: Miscellaneous/LedgerJournalTransTaxExtensionIN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ExcludedGSTAmountCur attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#DataAreaId name="DataAreaId">DataAreaId</a>

First included in: Miscellaneous/LedgerJournalTransTaxExtensionIN (this entity)  

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

### <a href=#Relationship_LedgerJournalTransRelationshipId name="Relationship_LedgerJournalTransRelationshipId">Relationship_LedgerJournalTransRelationshipId</a>

First included in: Miscellaneous/LedgerJournalTransTaxExtensionIN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_LedgerJournalTransRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../AccountingFoundation/WorksheetLine/LedgerJournalTrans.md" target="_blank">/core/operationsCommon/Tables/Finance/AccountingFoundation/WorksheetLine/LedgerJournalTrans.cdm.json/LedgerJournalTrans</a></td><td><a href="../../AccountingFoundation/WorksheetLine/LedgerJournalTrans.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_TaxWithholdGroupHeadingTCS_INRelationshipId name="Relationship_TaxWithholdGroupHeadingTCS_INRelationshipId">Relationship_TaxWithholdGroupHeadingTCS_INRelationshipId</a>

First included in: Miscellaneous/LedgerJournalTransTaxExtensionIN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_TaxWithholdGroupHeadingTCS_INRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../Tax/Group/TaxWithholdGroupHeading.md" target="_blank">/core/operationsCommon/Tables/Finance/Tax/Group/TaxWithholdGroupHeading.cdm.json/TaxWithholdGroupHeading</a></td><td><a href="../../Tax/Group/TaxWithholdGroupHeading.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_TaxWithholdGroupHeadingTDS_INRelationshipId name="Relationship_TaxWithholdGroupHeadingTDS_INRelationshipId">Relationship_TaxWithholdGroupHeadingTDS_INRelationshipId</a>

First included in: Miscellaneous/LedgerJournalTransTaxExtensionIN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_TaxWithholdGroupHeadingTDS_INRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../Tax/Group/TaxWithholdGroupHeading.md" target="_blank">/core/operationsCommon/Tables/Finance/Tax/Group/TaxWithholdGroupHeading.cdm.json/TaxWithholdGroupHeading</a></td><td><a href="../../Tax/Group/TaxWithholdGroupHeading.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_TaxWithholdTable_INRelationshipId name="Relationship_TaxWithholdTable_INRelationshipId">Relationship_TaxWithholdTable_INRelationshipId</a>

First included in: Miscellaneous/LedgerJournalTransTaxExtensionIN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_TaxWithholdTable_INRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../Tax/Main/TaxWithholdTable.md" target="_blank">/core/operationsCommon/Tables/Finance/Tax/Main/TaxWithholdTable.cdm.json/TaxWithholdTable</a></td><td><a href="../../Tax/Main/TaxWithholdTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_CompanyRelationshipId name="Relationship_CompanyRelationshipId">Relationship_CompanyRelationshipId</a>

First included in: Miscellaneous/LedgerJournalTransTaxExtensionIN (this entity)  

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
