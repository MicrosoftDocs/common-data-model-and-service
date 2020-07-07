---
title: FBTaxTrans_BR in Transaction - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 7/7/2020
ms.author: nebanfic
---

# Tax assessment details in Transaction

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Tables/Finance/FiscalBooksBrazil/Transaction/FBTaxTrans_BR.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[FBTaxTrans_BR/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Tax assessment details</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="FBTaxTrans_BR.md" target="_blank">Transaction/FBTaxTrans_BR</a>|
|[CFOP](#CFOP)||<a href="FBTaxTrans_BR.md" target="_blank">Transaction/FBTaxTrans_BR</a>|
|[Classification](#Classification)||<a href="FBTaxTrans_BR.md" target="_blank">Transaction/FBTaxTrans_BR</a>|
|[FBFiscalDocumentAdjustment_BR](#FBFiscalDocumentAdjustment_BR)||<a href="FBTaxTrans_BR.md" target="_blank">Transaction/FBTaxTrans_BR</a>|
|[FBTaxAssessment_BR](#FBTaxAssessment_BR)||<a href="FBTaxTrans_BR.md" target="_blank">Transaction/FBTaxTrans_BR</a>|
|[FBTaxAssessmentAdjustment_BR](#FBTaxAssessmentAdjustment_BR)||<a href="FBTaxTrans_BR.md" target="_blank">Transaction/FBTaxTrans_BR</a>|
|[FiscalDocument_BR](#FiscalDocument_BR)||<a href="FBTaxTrans_BR.md" target="_blank">Transaction/FBTaxTrans_BR</a>|
|[FiscalDocumentTaxTrans_BR](#FiscalDocumentTaxTrans_BR)||<a href="FBTaxTrans_BR.md" target="_blank">Transaction/FBTaxTrans_BR</a>|
|[RetailFiscalReceiptTaxTrans_BR](#RetailFiscalReceiptTaxTrans_BR)||<a href="FBTaxTrans_BR.md" target="_blank">Transaction/FBTaxTrans_BR</a>|
|[TaxAmount](#TaxAmount)||<a href="FBTaxTrans_BR.md" target="_blank">Transaction/FBTaxTrans_BR</a>|
|[TaxationCode](#TaxationCode)||<a href="FBTaxTrans_BR.md" target="_blank">Transaction/FBTaxTrans_BR</a>|
|[TaxBaseAmount](#TaxBaseAmount)||<a href="FBTaxTrans_BR.md" target="_blank">Transaction/FBTaxTrans_BR</a>|
|[TaxBaseAmountExempt](#TaxBaseAmountExempt)||<a href="FBTaxTrans_BR.md" target="_blank">Transaction/FBTaxTrans_BR</a>|
|[TaxBaseAmountOther](#TaxBaseAmountOther)||<a href="FBTaxTrans_BR.md" target="_blank">Transaction/FBTaxTrans_BR</a>|
|[TaxType](#TaxType)||<a href="FBTaxTrans_BR.md" target="_blank">Transaction/FBTaxTrans_BR</a>|
|[Voucher](#Voucher)||<a href="FBTaxTrans_BR.md" target="_blank">Transaction/FBTaxTrans_BR</a>|
|[VoucherDataArea](#VoucherDataArea)||<a href="FBTaxTrans_BR.md" target="_blank">Transaction/FBTaxTrans_BR</a>|
|[VoucherTransDate](#VoucherTransDate)||<a href="FBTaxTrans_BR.md" target="_blank">Transaction/FBTaxTrans_BR</a>|
|[WithholdingTax](#WithholdingTax)||<a href="FBTaxTrans_BR.md" target="_blank">Transaction/FBTaxTrans_BR</a>|
|[FBNonFiscalOperation_BR](#FBNonFiscalOperation_BR)||<a href="FBTaxTrans_BR.md" target="_blank">Transaction/FBTaxTrans_BR</a>|
|[FBNonFiscalOperationTaxTrans_BR](#FBNonFiscalOperationTaxTrans_BR)||<a href="FBTaxTrans_BR.md" target="_blank">Transaction/FBTaxTrans_BR</a>|
|[FBTaxWithholdTrans_BR](#FBTaxWithholdTrans_BR)||<a href="FBTaxTrans_BR.md" target="_blank">Transaction/FBTaxTrans_BR</a>|
|[FBTaxWithholdTransCreditDetail_BR](#FBTaxWithholdTransCreditDetail_BR)||<a href="FBTaxTrans_BR.md" target="_blank">Transaction/FBTaxTrans_BR</a>|
|[FiscalEstablishmentDataArea](#FiscalEstablishmentDataArea)||<a href="FBTaxTrans_BR.md" target="_blank">Transaction/FBTaxTrans_BR</a>|
|[FiscalEstablishmentId](#FiscalEstablishmentId)||<a href="FBTaxTrans_BR.md" target="_blank">Transaction/FBTaxTrans_BR</a>|
|[LineAmount](#LineAmount)||<a href="FBTaxTrans_BR.md" target="_blank">Transaction/FBTaxTrans_BR</a>|
|[RetailZReportTotalizerTaxTrans_BR](#RetailZReportTotalizerTaxTrans_BR)||<a href="FBTaxTrans_BR.md" target="_blank">Transaction/FBTaxTrans_BR</a>|
|[RevenueSourcePISCOFINS](#RevenueSourcePISCOFINS)||<a href="FBTaxTrans_BR.md" target="_blank">Transaction/FBTaxTrans_BR</a>|
|[TaxValue](#TaxValue)||<a href="FBTaxTrans_BR.md" target="_blank">Transaction/FBTaxTrans_BR</a>|
|[WithholdingTaxAmount](#WithholdingTaxAmount)||<a href="FBTaxTrans_BR.md" target="_blank">Transaction/FBTaxTrans_BR</a>|
|[FBContribCreditControlDetail_BR](#FBContribCreditControlDetail_BR)||<a href="FBTaxTrans_BR.md" target="_blank">Transaction/FBTaxTrans_BR</a>|
|[PisCofinsRevenueClassification](#PisCofinsRevenueClassification)||<a href="FBTaxTrans_BR.md" target="_blank">Transaction/FBTaxTrans_BR</a>|
|[FinancialLedgerDimension](#FinancialLedgerDimension)||<a href="FBTaxTrans_BR.md" target="_blank">Transaction/FBTaxTrans_BR</a>|
|[Relationship_FBFiscalDocumentAdjustment_BRRelationshipId](#Relationship_FBFiscalDocumentAdjustment_BRRelationshipId)||<a href="FBTaxTrans_BR.md" target="_blank">Transaction/FBTaxTrans_BR</a>|
|[Relationship_FBTaxAssessment_BRRelationshipId](#Relationship_FBTaxAssessment_BRRelationshipId)||<a href="FBTaxTrans_BR.md" target="_blank">Transaction/FBTaxTrans_BR</a>|
|[Relationship_FBTaxAssessmentAdjustment_BRRelationshipId](#Relationship_FBTaxAssessmentAdjustment_BRRelationshipId)||<a href="FBTaxTrans_BR.md" target="_blank">Transaction/FBTaxTrans_BR</a>|
|[Relationship_FiscalDocument_BRRelationshipId](#Relationship_FiscalDocument_BRRelationshipId)||<a href="FBTaxTrans_BR.md" target="_blank">Transaction/FBTaxTrans_BR</a>|
|[Relationship_FiscalDocumentTaxTrans_BRRelationshipId](#Relationship_FiscalDocumentTaxTrans_BRRelationshipId)||<a href="FBTaxTrans_BR.md" target="_blank">Transaction/FBTaxTrans_BR</a>|
|[Relationship_DimensionAttributeValueCombinationRelationshipId](#Relationship_DimensionAttributeValueCombinationRelationshipId)||<a href="FBTaxTrans_BR.md" target="_blank">Transaction/FBTaxTrans_BR</a>|
|[Relationship_FBNonFiscalOperation_BRRelationshipId](#Relationship_FBNonFiscalOperation_BRRelationshipId)||<a href="FBTaxTrans_BR.md" target="_blank">Transaction/FBTaxTrans_BR</a>|
|[Relationship_FBNonFiscalOperationTaxTrans_BRRelationshipId](#Relationship_FBNonFiscalOperationTaxTrans_BRRelationshipId)||<a href="FBTaxTrans_BR.md" target="_blank">Transaction/FBTaxTrans_BR</a>|
|[Relationship_FBTaxWithholdTrans_BRRelationshipId](#Relationship_FBTaxWithholdTrans_BRRelationshipId)||<a href="FBTaxTrans_BR.md" target="_blank">Transaction/FBTaxTrans_BR</a>|
|[Relationship_FBTaxWithholdTransCreditDetail_BRRelationshipId](#Relationship_FBTaxWithholdTransCreditDetail_BRRelationshipId)||<a href="FBTaxTrans_BR.md" target="_blank">Transaction/FBTaxTrans_BR</a>|
|[Relationship_FBContribCreditControlDetail_BRRelationshipId](#Relationship_FBContribCreditControlDetail_BRRelationshipId)||<a href="FBTaxTrans_BR.md" target="_blank">Transaction/FBTaxTrans_BR</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: Transaction/FBTaxTrans_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[FBTaxTrans_BR/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#CFOP name="CFOP">CFOP</a>

First included in: Transaction/FBTaxTrans_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CFOP attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Classification name="Classification">Classification</a>

First included in: Transaction/FBTaxTrans_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Classification attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#FBFiscalDocumentAdjustment_BR name="FBFiscalDocumentAdjustment_BR">FBFiscalDocumentAdjustment_BR</a>

First included in: Transaction/FBTaxTrans_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FBFiscalDocumentAdjustment_BR attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#FBTaxAssessment_BR name="FBTaxAssessment_BR">FBTaxAssessment_BR</a>

First included in: Transaction/FBTaxTrans_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FBTaxAssessment_BR attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#FBTaxAssessmentAdjustment_BR name="FBTaxAssessmentAdjustment_BR">FBTaxAssessmentAdjustment_BR</a>

First included in: Transaction/FBTaxTrans_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FBTaxAssessmentAdjustment_BR attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#FiscalDocument_BR name="FiscalDocument_BR">FiscalDocument_BR</a>

First included in: Transaction/FBTaxTrans_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FiscalDocument_BR attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#FiscalDocumentTaxTrans_BR name="FiscalDocumentTaxTrans_BR">FiscalDocumentTaxTrans_BR</a>

First included in: Transaction/FBTaxTrans_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FiscalDocumentTaxTrans_BR attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#RetailFiscalReceiptTaxTrans_BR name="RetailFiscalReceiptTaxTrans_BR">RetailFiscalReceiptTaxTrans_BR</a>

First included in: Transaction/FBTaxTrans_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RetailFiscalReceiptTaxTrans_BR attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#TaxAmount name="TaxAmount">TaxAmount</a>

First included in: Transaction/FBTaxTrans_BR (this entity)  

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

### <a href=#TaxationCode name="TaxationCode">TaxationCode</a>

First included in: Transaction/FBTaxTrans_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxationCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TaxBaseAmount name="TaxBaseAmount">TaxBaseAmount</a>

First included in: Transaction/FBTaxTrans_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Tax base amount</td></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxBaseAmount attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Tax base amount</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#TaxBaseAmountExempt name="TaxBaseAmountExempt">TaxBaseAmountExempt</a>

First included in: Transaction/FBTaxTrans_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Exempt base amount</td></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxBaseAmountExempt attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Exempt base amount</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#TaxBaseAmountOther name="TaxBaseAmountOther">TaxBaseAmountOther</a>

First included in: Transaction/FBTaxTrans_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Other base amount</td></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxBaseAmountOther attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Other base amount</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#TaxType name="TaxType">TaxType</a>

First included in: Transaction/FBTaxTrans_BR (this entity)  

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

### <a href=#Voucher name="Voucher">Voucher</a>

First included in: Transaction/FBTaxTrans_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Voucher attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#VoucherDataArea name="VoucherDataArea">VoucherDataArea</a>

First included in: Transaction/FBTaxTrans_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VoucherDataArea attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#VoucherTransDate name="VoucherTransDate">VoucherTransDate</a>

First included in: Transaction/FBTaxTrans_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VoucherTransDate attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.date**  
</details>

### <a href=#WithholdingTax name="WithholdingTax">WithholdingTax</a>

First included in: Transaction/FBTaxTrans_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Withholding tax</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WithholdingTax attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Withholding tax</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#FBNonFiscalOperation_BR name="FBNonFiscalOperation_BR">FBNonFiscalOperation_BR</a>

First included in: Transaction/FBTaxTrans_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FBNonFiscalOperation_BR attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#FBNonFiscalOperationTaxTrans_BR name="FBNonFiscalOperationTaxTrans_BR">FBNonFiscalOperationTaxTrans_BR</a>

First included in: Transaction/FBTaxTrans_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FBNonFiscalOperationTaxTrans_BR attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#FBTaxWithholdTrans_BR name="FBTaxWithholdTrans_BR">FBTaxWithholdTrans_BR</a>

First included in: Transaction/FBTaxTrans_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FBTaxWithholdTrans_BR attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#FBTaxWithholdTransCreditDetail_BR name="FBTaxWithholdTransCreditDetail_BR">FBTaxWithholdTransCreditDetail_BR</a>

First included in: Transaction/FBTaxTrans_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FBTaxWithholdTransCreditDetail_BR attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#FiscalEstablishmentDataArea name="FiscalEstablishmentDataArea">FiscalEstablishmentDataArea</a>

First included in: Transaction/FBTaxTrans_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FiscalEstablishmentDataArea attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FiscalEstablishmentId name="FiscalEstablishmentId">FiscalEstablishmentId</a>

First included in: Transaction/FBTaxTrans_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FiscalEstablishmentId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LineAmount name="LineAmount">LineAmount</a>

First included in: Transaction/FBTaxTrans_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LineAmount attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#RetailZReportTotalizerTaxTrans_BR name="RetailZReportTotalizerTaxTrans_BR">RetailZReportTotalizerTaxTrans_BR</a>

First included in: Transaction/FBTaxTrans_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>The Z Report totalizer tax transaction</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RetailZReportTotalizerTaxTrans_BR attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>The Z Report totalizer tax transaction</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#RevenueSourcePISCOFINS name="RevenueSourcePISCOFINS">RevenueSourcePISCOFINS</a>

First included in: Transaction/FBTaxTrans_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RevenueSourcePISCOFINS attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TaxValue name="TaxValue">TaxValue</a>

First included in: Transaction/FBTaxTrans_BR (this entity)  

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

### <a href=#WithholdingTaxAmount name="WithholdingTaxAmount">WithholdingTaxAmount</a>

First included in: Transaction/FBTaxTrans_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WithholdingTaxAmount attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#FBContribCreditControlDetail_BR name="FBContribCreditControlDetail_BR">FBContribCreditControlDetail_BR</a>

First included in: Transaction/FBTaxTrans_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FBContribCreditControlDetail_BR attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#PisCofinsRevenueClassification name="PisCofinsRevenueClassification">PisCofinsRevenueClassification</a>

First included in: Transaction/FBTaxTrans_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PisCofinsRevenueClassification attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#FinancialLedgerDimension name="FinancialLedgerDimension">FinancialLedgerDimension</a>

First included in: Transaction/FBTaxTrans_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FinancialLedgerDimension attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#Relationship_FBFiscalDocumentAdjustment_BRRelationshipId name="Relationship_FBFiscalDocumentAdjustment_BRRelationshipId">Relationship_FBFiscalDocumentAdjustment_BRRelationshipId</a>

First included in: Transaction/FBTaxTrans_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_FBFiscalDocumentAdjustment_BRRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="FBFiscalDocumentAdjustment_BR.md" target="_blank">/core/operationsCommon/Tables/Finance/FiscalBooksBrazil/Transaction/FBFiscalDocumentAdjustment_BR.cdm.json/FBFiscalDocumentAdjustment_BR</a></td><td><a href="FBFiscalDocumentAdjustment_BR.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_FBTaxAssessment_BRRelationshipId name="Relationship_FBTaxAssessment_BRRelationshipId">Relationship_FBTaxAssessment_BRRelationshipId</a>

First included in: Transaction/FBTaxTrans_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_FBTaxAssessment_BRRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="FBTaxAssessment_BR.md" target="_blank">/core/operationsCommon/Tables/Finance/FiscalBooksBrazil/Transaction/FBTaxAssessment_BR.cdm.json/FBTaxAssessment_BR</a></td><td><a href="FBTaxAssessment_BR.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_FBTaxAssessmentAdjustment_BRRelationshipId name="Relationship_FBTaxAssessmentAdjustment_BRRelationshipId">Relationship_FBTaxAssessmentAdjustment_BRRelationshipId</a>

First included in: Transaction/FBTaxTrans_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_FBTaxAssessmentAdjustment_BRRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="FBTaxAssessmentAdjustment_BR.md" target="_blank">/core/operationsCommon/Tables/Finance/FiscalBooksBrazil/Transaction/FBTaxAssessmentAdjustment_BR.cdm.json/FBTaxAssessmentAdjustment_BR</a></td><td><a href="FBTaxAssessmentAdjustment_BR.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_FiscalDocument_BRRelationshipId name="Relationship_FiscalDocument_BRRelationshipId">Relationship_FiscalDocument_BRRelationshipId</a>

First included in: Transaction/FBTaxTrans_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_FiscalDocument_BRRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="FiscalDocument_BR.md" target="_blank">/core/operationsCommon/Tables/Finance/FiscalBooksBrazil/Transaction/FiscalDocument_BR.cdm.json/FiscalDocument_BR</a></td><td><a href="FiscalDocument_BR.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_FiscalDocumentTaxTrans_BRRelationshipId name="Relationship_FiscalDocumentTaxTrans_BRRelationshipId">Relationship_FiscalDocumentTaxTrans_BRRelationshipId</a>

First included in: Transaction/FBTaxTrans_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_FiscalDocumentTaxTrans_BRRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="FiscalDocumentTaxTrans_BR.md" target="_blank">/core/operationsCommon/Tables/Finance/FiscalBooksBrazil/Transaction/FiscalDocumentTaxTrans_BR.cdm.json/FiscalDocumentTaxTrans_BR</a></td><td><a href="FiscalDocumentTaxTrans_BR.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_DimensionAttributeValueCombinationRelationshipId name="Relationship_DimensionAttributeValueCombinationRelationshipId">Relationship_DimensionAttributeValueCombinationRelationshipId</a>

First included in: Transaction/FBTaxTrans_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_DimensionAttributeValueCombinationRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../FinancialDimensions/Main/DimensionAttributeValueCombination.md" target="_blank">/core/operationsCommon/Tables/Finance/FinancialDimensions/Main/DimensionAttributeValueCombination.cdm.json/DimensionAttributeValueCombination</a></td><td><a href="../../FinancialDimensions/Main/DimensionAttributeValueCombination.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_FBNonFiscalOperation_BRRelationshipId name="Relationship_FBNonFiscalOperation_BRRelationshipId">Relationship_FBNonFiscalOperation_BRRelationshipId</a>

First included in: Transaction/FBTaxTrans_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_FBNonFiscalOperation_BRRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Miscellaneous/FBNonFiscalOperation_BR.md" target="_blank">/core/operationsCommon/Tables/Finance/FiscalBooksBrazil/Miscellaneous/FBNonFiscalOperation_BR.cdm.json/FBNonFiscalOperation_BR</a></td><td><a href="../Miscellaneous/FBNonFiscalOperation_BR.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_FBNonFiscalOperationTaxTrans_BRRelationshipId name="Relationship_FBNonFiscalOperationTaxTrans_BRRelationshipId">Relationship_FBNonFiscalOperationTaxTrans_BRRelationshipId</a>

First included in: Transaction/FBTaxTrans_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_FBNonFiscalOperationTaxTrans_BRRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Miscellaneous/FBNonFiscalOperationTaxTrans_BR.md" target="_blank">/core/operationsCommon/Tables/Finance/FiscalBooksBrazil/Miscellaneous/FBNonFiscalOperationTaxTrans_BR.cdm.json/FBNonFiscalOperationTaxTrans_BR</a></td><td><a href="../Miscellaneous/FBNonFiscalOperationTaxTrans_BR.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_FBTaxWithholdTrans_BRRelationshipId name="Relationship_FBTaxWithholdTrans_BRRelationshipId">Relationship_FBTaxWithholdTrans_BRRelationshipId</a>

First included in: Transaction/FBTaxTrans_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_FBTaxWithholdTrans_BRRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Miscellaneous/FBTaxWithholdTrans_BR.md" target="_blank">/core/operationsCommon/Tables/Finance/FiscalBooksBrazil/Miscellaneous/FBTaxWithholdTrans_BR.cdm.json/FBTaxWithholdTrans_BR</a></td><td><a href="../Miscellaneous/FBTaxWithholdTrans_BR.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_FBTaxWithholdTransCreditDetail_BRRelationshipId name="Relationship_FBTaxWithholdTransCreditDetail_BRRelationshipId">Relationship_FBTaxWithholdTransCreditDetail_BRRelationshipId</a>

First included in: Transaction/FBTaxTrans_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_FBTaxWithholdTransCreditDetail_BRRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Miscellaneous/FBTaxWithholdTransCreditDetail_BR.md" target="_blank">/core/operationsCommon/Tables/Finance/FiscalBooksBrazil/Miscellaneous/FBTaxWithholdTransCreditDetail_BR.cdm.json/FBTaxWithholdTransCreditDetail_BR</a></td><td><a href="../Miscellaneous/FBTaxWithholdTransCreditDetail_BR.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_FBContribCreditControlDetail_BRRelationshipId name="Relationship_FBContribCreditControlDetail_BRRelationshipId">Relationship_FBContribCreditControlDetail_BRRelationshipId</a>

First included in: Transaction/FBTaxTrans_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_FBContribCreditControlDetail_BRRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Miscellaneous/FBContribCreditControlDetail_BR.md" target="_blank">/core/operationsCommon/Tables/Finance/FiscalBooksBrazil/Miscellaneous/FBContribCreditControlDetail_BR.cdm.json/FBContribCreditControlDetail_BR</a></td><td><a href="../Miscellaneous/FBContribCreditControlDetail_BR.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>
