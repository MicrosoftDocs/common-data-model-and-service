---
title: FBTaxAssessmentAdjustment_BR in Transaction - Common Data Model | Microsoft Docs
description: undefined
author: llawwaii
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: reference
ms.date: 8/7/2020
ms.author: weiluo
---

# General tax adjust/benefit/incentive in Transaction(FBTaxAssessmentAdjustment_BR)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Tables/Finance/FiscalBooksBrazil/Transaction/FBTaxAssessmentAdjustment_BR.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[FBTaxAssessmentAdjustment_BR/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.1"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>General tax adjust/benefit/incentive</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="FBTaxAssessmentAdjustment_BR.md" target="_blank">Transaction/FBTaxAssessmentAdjustment_BR</a>|
|[CancelTransDate](#CancelTransDate)||<a href="FBTaxAssessmentAdjustment_BR.md" target="_blank">Transaction/FBTaxAssessmentAdjustment_BR</a>|
|[CancelVoucher](#CancelVoucher)||<a href="FBTaxAssessmentAdjustment_BR.md" target="_blank">Transaction/FBTaxAssessmentAdjustment_BR</a>|
|[ComplementaryDescription](#ComplementaryDescription)||<a href="FBTaxAssessmentAdjustment_BR.md" target="_blank">Transaction/FBTaxAssessmentAdjustment_BR</a>|
|[ComplementaryDescriptionPISCOFINS](#ComplementaryDescriptionPISCOFINS)||<a href="FBTaxAssessmentAdjustment_BR.md" target="_blank">Transaction/FBTaxAssessmentAdjustment_BR</a>|
|[ContribAssessmentPeriod](#ContribAssessmentPeriod)||<a href="FBTaxAssessmentAdjustment_BR.md" target="_blank">Transaction/FBTaxAssessmentAdjustment_BR</a>|
|[ContribCreditBaseSource](#ContribCreditBaseSource)||<a href="FBTaxAssessmentAdjustment_BR.md" target="_blank">Transaction/FBTaxAssessmentAdjustment_BR</a>|
|[ContribTransferredCreditPercentage](#ContribTransferredCreditPercentage)||<a href="FBTaxAssessmentAdjustment_BR.md" target="_blank">Transaction/FBTaxAssessmentAdjustment_BR</a>|
|[CreatePayment](#CreatePayment)||<a href="FBTaxAssessmentAdjustment_BR.md" target="_blank">Transaction/FBTaxAssessmentAdjustment_BR</a>|
|[DeductionCNPJ](#DeductionCNPJ)||<a href="FBTaxAssessmentAdjustment_BR.md" target="_blank">Transaction/FBTaxAssessmentAdjustment_BR</a>|
|[FBContribCreditType_BR](#FBContribCreditType_BR)||<a href="FBTaxAssessmentAdjustment_BR.md" target="_blank">Transaction/FBTaxAssessmentAdjustment_BR</a>|
|[FBGeneralAdjustmentCode_BR](#FBGeneralAdjustmentCode_BR)||<a href="FBTaxAssessmentAdjustment_BR.md" target="_blank">Transaction/FBTaxAssessmentAdjustment_BR</a>|
|[FBTaxAssessment_BR](#FBTaxAssessment_BR)||<a href="FBTaxAssessmentAdjustment_BR.md" target="_blank">Transaction/FBTaxAssessmentAdjustment_BR</a>|
|[FiscalDocumentTaxTrans_BR](#FiscalDocumentTaxTrans_BR)||<a href="FBTaxAssessmentAdjustment_BR.md" target="_blank">Transaction/FBTaxAssessmentAdjustment_BR</a>|
|[FiscalEstablishmentId](#FiscalEstablishmentId)||<a href="FBTaxAssessmentAdjustment_BR.md" target="_blank">Transaction/FBTaxAssessmentAdjustment_BR</a>|
|[IsCancelled](#IsCancelled)||<a href="FBTaxAssessmentAdjustment_BR.md" target="_blank">Transaction/FBTaxAssessmentAdjustment_BR</a>|
|[IsTaxDifference](#IsTaxDifference)||<a href="FBTaxAssessmentAdjustment_BR.md" target="_blank">Transaction/FBTaxAssessmentAdjustment_BR</a>|
|[State](#State)||<a href="FBTaxAssessmentAdjustment_BR.md" target="_blank">Transaction/FBTaxAssessmentAdjustment_BR</a>|
|[TaxAmount](#TaxAmount)||<a href="FBTaxAssessmentAdjustment_BR.md" target="_blank">Transaction/FBTaxAssessmentAdjustment_BR</a>|
|[TaxAdjustmentProcessNum](#TaxAdjustmentProcessNum)||<a href="FBTaxAssessmentAdjustment_BR.md" target="_blank">Transaction/FBTaxAssessmentAdjustment_BR</a>|
|[TaxAdjustmentSourceType](#TaxAdjustmentSourceType)||<a href="FBTaxAssessmentAdjustment_BR.md" target="_blank">Transaction/FBTaxAssessmentAdjustment_BR</a>|
|[TaxationCode](#TaxationCode)||<a href="FBTaxAssessmentAdjustment_BR.md" target="_blank">Transaction/FBTaxAssessmentAdjustment_BR</a>|
|[TaxBaseAmount](#TaxBaseAmount)||<a href="FBTaxAssessmentAdjustment_BR.md" target="_blank">Transaction/FBTaxAssessmentAdjustment_BR</a>|
|[TaxType_BR](#TaxType_BR)||<a href="FBTaxAssessmentAdjustment_BR.md" target="_blank">Transaction/FBTaxAssessmentAdjustment_BR</a>|
|[TaxValue](#TaxValue)||<a href="FBTaxAssessmentAdjustment_BR.md" target="_blank">Transaction/FBTaxAssessmentAdjustment_BR</a>|
|[TransDate](#TransDate)||<a href="FBTaxAssessmentAdjustment_BR.md" target="_blank">Transaction/FBTaxAssessmentAdjustment_BR</a>|
|[Voucher](#Voucher)||<a href="FBTaxAssessmentAdjustment_BR.md" target="_blank">Transaction/FBTaxAssessmentAdjustment_BR</a>|
|[VoucherDataArea](#VoucherDataArea)||<a href="FBTaxAssessmentAdjustment_BR.md" target="_blank">Transaction/FBTaxAssessmentAdjustment_BR</a>|
|[IsPovertyFund](#IsPovertyFund)||<a href="FBTaxAssessmentAdjustment_BR.md" target="_blank">Transaction/FBTaxAssessmentAdjustment_BR</a>|
|[FBEconomicActivityCode_BR](#FBEconomicActivityCode_BR)||<a href="FBTaxAssessmentAdjustment_BR.md" target="_blank">Transaction/FBTaxAssessmentAdjustment_BR</a>|
|[ReceiptNumber](#ReceiptNumber)||<a href="FBTaxAssessmentAdjustment_BR.md" target="_blank">Transaction/FBTaxAssessmentAdjustment_BR</a>|
|[BaseAdjMainAccount](#BaseAdjMainAccount)||<a href="FBTaxAssessmentAdjustment_BR.md" target="_blank">Transaction/FBTaxAssessmentAdjustment_BR</a>|
|[LedgerJournalTrans](#LedgerJournalTrans)||<a href="FBTaxAssessmentAdjustment_BR.md" target="_blank">Transaction/FBTaxAssessmentAdjustment_BR</a>|
|[Relationship_FBContribCreditType_BRRelationshipId](#Relationship_FBContribCreditType_BRRelationshipId)||<a href="FBTaxAssessmentAdjustment_BR.md" target="_blank">Transaction/FBTaxAssessmentAdjustment_BR</a>|
|[Relationship_FBGeneralAdjustmentCode_BRRelationshipId](#Relationship_FBGeneralAdjustmentCode_BRRelationshipId)||<a href="FBTaxAssessmentAdjustment_BR.md" target="_blank">Transaction/FBTaxAssessmentAdjustment_BR</a>|
|[Relationship_FBTaxAssessment_BRRelationshipId](#Relationship_FBTaxAssessment_BRRelationshipId)||<a href="FBTaxAssessmentAdjustment_BR.md" target="_blank">Transaction/FBTaxAssessmentAdjustment_BR</a>|
|[Relationship_FiscalDocumentTaxTrans_BRRelationshipId](#Relationship_FiscalDocumentTaxTrans_BRRelationshipId)||<a href="FBTaxAssessmentAdjustment_BR.md" target="_blank">Transaction/FBTaxAssessmentAdjustment_BR</a>|
|[Relationship_FBEconomicActivityCode_BRRelationshipId](#Relationship_FBEconomicActivityCode_BRRelationshipId)||<a href="FBTaxAssessmentAdjustment_BR.md" target="_blank">Transaction/FBTaxAssessmentAdjustment_BR</a>|
|[Relationship_MainAccountRelationshipId](#Relationship_MainAccountRelationshipId)||<a href="FBTaxAssessmentAdjustment_BR.md" target="_blank">Transaction/FBTaxAssessmentAdjustment_BR</a>|
|[Relationship_LedgerJournalTransRelationshipId](#Relationship_LedgerJournalTransRelationshipId)||<a href="FBTaxAssessmentAdjustment_BR.md" target="_blank">Transaction/FBTaxAssessmentAdjustment_BR</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: Transaction/FBTaxAssessmentAdjustment_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[FBTaxAssessmentAdjustment_BR/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#CancelTransDate name="CancelTransDate">CancelTransDate</a>

First included in: Transaction/FBTaxAssessmentAdjustment_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CancelTransDate attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.readOnly**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.date**  
</details>

### <a href=#CancelVoucher name="CancelVoucher">CancelVoucher</a>

First included in: Transaction/FBTaxAssessmentAdjustment_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CancelVoucher attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.readOnly**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ComplementaryDescription name="ComplementaryDescription">ComplementaryDescription</a>

First included in: Transaction/FBTaxAssessmentAdjustment_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ComplementaryDescription attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ComplementaryDescriptionPISCOFINS name="ComplementaryDescriptionPISCOFINS">ComplementaryDescriptionPISCOFINS</a>

First included in: Transaction/FBTaxAssessmentAdjustment_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ComplementaryDescriptionPISCOFINS attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ContribAssessmentPeriod name="ContribAssessmentPeriod">ContribAssessmentPeriod</a>

First included in: Transaction/FBTaxAssessmentAdjustment_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ContribAssessmentPeriod attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.date**  
</details>

### <a href=#ContribCreditBaseSource name="ContribCreditBaseSource">ContribCreditBaseSource</a>

First included in: Transaction/FBTaxAssessmentAdjustment_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Credit base source</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ContribCreditBaseSource attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Credit base source</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#ContribTransferredCreditPercentage name="ContribTransferredCreditPercentage">ContribTransferredCreditPercentage</a>

First included in: Transaction/FBTaxAssessmentAdjustment_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Transferred credit percentage</td></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ContribTransferredCreditPercentage attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Transferred credit percentage</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#CreatePayment name="CreatePayment">CreatePayment</a>

First included in: Transaction/FBTaxAssessmentAdjustment_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CreatePayment attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#DeductionCNPJ name="DeductionCNPJ">DeductionCNPJ</a>

First included in: Transaction/FBTaxAssessmentAdjustment_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DeductionCNPJ attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FBContribCreditType_BR name="FBContribCreditType_BR">FBContribCreditType_BR</a>

First included in: Transaction/FBTaxAssessmentAdjustment_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Credit type</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FBContribCreditType_BR attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Credit type</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#FBGeneralAdjustmentCode_BR name="FBGeneralAdjustmentCode_BR">FBGeneralAdjustmentCode_BR</a>

First included in: Transaction/FBTaxAssessmentAdjustment_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FBGeneralAdjustmentCode_BR attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#FBTaxAssessment_BR name="FBTaxAssessment_BR">FBTaxAssessment_BR</a>

First included in: Transaction/FBTaxAssessmentAdjustment_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FBTaxAssessment_BR attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#FiscalDocumentTaxTrans_BR name="FiscalDocumentTaxTrans_BR">FiscalDocumentTaxTrans_BR</a>

First included in: Transaction/FBTaxAssessmentAdjustment_BR (this entity)  

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

### <a href=#FiscalEstablishmentId name="FiscalEstablishmentId">FiscalEstablishmentId</a>

First included in: Transaction/FBTaxAssessmentAdjustment_BR (this entity)  

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

### <a href=#IsCancelled name="IsCancelled">IsCancelled</a>

First included in: Transaction/FBTaxAssessmentAdjustment_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Cancelled</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsCancelled attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.readOnly**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Cancelled</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#IsTaxDifference name="IsTaxDifference">IsTaxDifference</a>

First included in: Transaction/FBTaxAssessmentAdjustment_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Tax difference</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsTaxDifference attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Tax difference</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#State name="State">State</a>

First included in: Transaction/FBTaxAssessmentAdjustment_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the State attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.readOnly**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TaxAmount name="TaxAmount">TaxAmount</a>

First included in: Transaction/FBTaxAssessmentAdjustment_BR (this entity)  

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

### <a href=#TaxAdjustmentProcessNum name="TaxAdjustmentProcessNum">TaxAdjustmentProcessNum</a>

First included in: Transaction/FBTaxAssessmentAdjustment_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxAdjustmentProcessNum attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TaxAdjustmentSourceType name="TaxAdjustmentSourceType">TaxAdjustmentSourceType</a>

First included in: Transaction/FBTaxAssessmentAdjustment_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxAdjustmentSourceType attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#TaxationCode name="TaxationCode">TaxationCode</a>

First included in: Transaction/FBTaxAssessmentAdjustment_BR (this entity)  

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

First included in: Transaction/FBTaxAssessmentAdjustment_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Base amount</td></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxBaseAmount attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Base amount</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#TaxType_BR name="TaxType_BR">TaxType_BR</a>

First included in: Transaction/FBTaxAssessmentAdjustment_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxType_BR attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.readOnly**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#TaxValue name="TaxValue">TaxValue</a>

First included in: Transaction/FBTaxAssessmentAdjustment_BR (this entity)  

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

### <a href=#TransDate name="TransDate">TransDate</a>

First included in: Transaction/FBTaxAssessmentAdjustment_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TransDate attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.date**  
</details>

### <a href=#Voucher name="Voucher">Voucher</a>

First included in: Transaction/FBTaxAssessmentAdjustment_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Voucher attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.readOnly**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#VoucherDataArea name="VoucherDataArea">VoucherDataArea</a>

First included in: Transaction/FBTaxAssessmentAdjustment_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VoucherDataArea attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.readOnly**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsPovertyFund name="IsPovertyFund">IsPovertyFund</a>

First included in: Transaction/FBTaxAssessmentAdjustment_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>FCP</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsPovertyFund attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>FCP</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#FBEconomicActivityCode_BR name="FBEconomicActivityCode_BR">FBEconomicActivityCode_BR</a>

First included in: Transaction/FBTaxAssessmentAdjustment_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Economic activity code</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FBEconomicActivityCode_BR attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Economic activity code</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#ReceiptNumber name="ReceiptNumber">ReceiptNumber</a>

First included in: Transaction/FBTaxAssessmentAdjustment_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReceiptNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BaseAdjMainAccount name="BaseAdjMainAccount">BaseAdjMainAccount</a>

First included in: Transaction/FBTaxAssessmentAdjustment_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BaseAdjMainAccount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LedgerJournalTrans name="LedgerJournalTrans">LedgerJournalTrans</a>

First included in: Transaction/FBTaxAssessmentAdjustment_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LedgerJournalTrans attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#Relationship_FBContribCreditType_BRRelationshipId name="Relationship_FBContribCreditType_BRRelationshipId">Relationship_FBContribCreditType_BRRelationshipId</a>

First included in: Transaction/FBTaxAssessmentAdjustment_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_FBContribCreditType_BRRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Miscellaneous/FBContribCreditType_BR.md" target="_blank">/core/operationsCommon/Tables/Finance/FiscalBooksBrazil/Miscellaneous/FBContribCreditType_BR.cdm.json/FBContribCreditType_BR</a></td><td><a href="../Miscellaneous/FBContribCreditType_BR.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_FBGeneralAdjustmentCode_BRRelationshipId name="Relationship_FBGeneralAdjustmentCode_BRRelationshipId">Relationship_FBGeneralAdjustmentCode_BRRelationshipId</a>

First included in: Transaction/FBTaxAssessmentAdjustment_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_FBGeneralAdjustmentCode_BRRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Main/FBGeneralAdjustmentCode_BR.md" target="_blank">/core/operationsCommon/Tables/Finance/FiscalBooksBrazil/Main/FBGeneralAdjustmentCode_BR.cdm.json/FBGeneralAdjustmentCode_BR</a></td><td><a href="../Main/FBGeneralAdjustmentCode_BR.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_FBTaxAssessment_BRRelationshipId name="Relationship_FBTaxAssessment_BRRelationshipId">Relationship_FBTaxAssessment_BRRelationshipId</a>

First included in: Transaction/FBTaxAssessmentAdjustment_BR (this entity)  

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

### <a href=#Relationship_FiscalDocumentTaxTrans_BRRelationshipId name="Relationship_FiscalDocumentTaxTrans_BRRelationshipId">Relationship_FiscalDocumentTaxTrans_BRRelationshipId</a>

First included in: Transaction/FBTaxAssessmentAdjustment_BR (this entity)  

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

### <a href=#Relationship_FBEconomicActivityCode_BRRelationshipId name="Relationship_FBEconomicActivityCode_BRRelationshipId">Relationship_FBEconomicActivityCode_BRRelationshipId</a>

First included in: Transaction/FBTaxAssessmentAdjustment_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_FBEconomicActivityCode_BRRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Miscellaneous/FBEconomicActivityCode_BR.md" target="_blank">/core/operationsCommon/Tables/Finance/FiscalBooksBrazil/Miscellaneous/FBEconomicActivityCode_BR.cdm.json/FBEconomicActivityCode_BR</a></td><td><a href="../Miscellaneous/FBEconomicActivityCode_BR.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_MainAccountRelationshipId name="Relationship_MainAccountRelationshipId">Relationship_MainAccountRelationshipId</a>

First included in: Transaction/FBTaxAssessmentAdjustment_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_MainAccountRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../FinancialDimensions/Main/MainAccount.md" target="_blank">/core/operationsCommon/Tables/Finance/FinancialDimensions/Main/MainAccount.cdm.json/MainAccount</a></td><td><a href="../../FinancialDimensions/Main/MainAccount.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_LedgerJournalTransRelationshipId name="Relationship_LedgerJournalTransRelationshipId">Relationship_LedgerJournalTransRelationshipId</a>

First included in: Transaction/FBTaxAssessmentAdjustment_BR (this entity)  

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
