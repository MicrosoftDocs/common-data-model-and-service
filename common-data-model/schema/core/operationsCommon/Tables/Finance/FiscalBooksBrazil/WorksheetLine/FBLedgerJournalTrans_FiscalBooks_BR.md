---
title: FBLedgerJournalTrans_FiscalBooks_BR in WorksheetLine - Common Data Model | Microsoft Docs
description: undefined
author: llawwaii
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: reference
ms.date: 8/7/2020
ms.author: weiluo
---

# Fiscal books journal lines in WorksheetLine(FBLedgerJournalTrans_FiscalBooks_BR)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Tables/Finance/FiscalBooksBrazil/WorksheetLine/FBLedgerJournalTrans_FiscalBooks_BR.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[FBLedgerJournalTrans_FiscalBooks_BR/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.1"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Fiscal books journal lines</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="FBLedgerJournalTrans_FiscalBooks_BR.md" target="_blank">WorksheetLine/FBLedgerJournalTrans_FiscalBooks_BR</a>|
|[AdjustmentType](#AdjustmentType)||<a href="FBLedgerJournalTrans_FiscalBooks_BR.md" target="_blank">WorksheetLine/FBLedgerJournalTrans_FiscalBooks_BR</a>|
|[ComplementaryDescription](#ComplementaryDescription)||<a href="FBLedgerJournalTrans_FiscalBooks_BR.md" target="_blank">WorksheetLine/FBLedgerJournalTrans_FiscalBooks_BR</a>|
|[ContribAssessmentPeriod](#ContribAssessmentPeriod)||<a href="FBLedgerJournalTrans_FiscalBooks_BR.md" target="_blank">WorksheetLine/FBLedgerJournalTrans_FiscalBooks_BR</a>|
|[ContribCreditBaseSource](#ContribCreditBaseSource)||<a href="FBLedgerJournalTrans_FiscalBooks_BR.md" target="_blank">WorksheetLine/FBLedgerJournalTrans_FiscalBooks_BR</a>|
|[ContribTransferredCreditPercentage](#ContribTransferredCreditPercentage)||<a href="FBLedgerJournalTrans_FiscalBooks_BR.md" target="_blank">WorksheetLine/FBLedgerJournalTrans_FiscalBooks_BR</a>|
|[DeductionCNPJ](#DeductionCNPJ)||<a href="FBLedgerJournalTrans_FiscalBooks_BR.md" target="_blank">WorksheetLine/FBLedgerJournalTrans_FiscalBooks_BR</a>|
|[FBContribCreditType_BR](#FBContribCreditType_BR)||<a href="FBLedgerJournalTrans_FiscalBooks_BR.md" target="_blank">WorksheetLine/FBLedgerJournalTrans_FiscalBooks_BR</a>|
|[FiscalDocumentAdjustmentCodeICMS](#FiscalDocumentAdjustmentCodeICMS)||<a href="FBLedgerJournalTrans_FiscalBooks_BR.md" target="_blank">WorksheetLine/FBLedgerJournalTrans_FiscalBooks_BR</a>|
|[FiscalDocumentLine_BR](#FiscalDocumentLine_BR)||<a href="FBLedgerJournalTrans_FiscalBooks_BR.md" target="_blank">WorksheetLine/FBLedgerJournalTrans_FiscalBooks_BR</a>|
|[FiscalDocumentTaxTrans_BR](#FiscalDocumentTaxTrans_BR)||<a href="FBLedgerJournalTrans_FiscalBooks_BR.md" target="_blank">WorksheetLine/FBLedgerJournalTrans_FiscalBooks_BR</a>|
|[FiscalDocument_BR](#FiscalDocument_BR)||<a href="FBLedgerJournalTrans_FiscalBooks_BR.md" target="_blank">WorksheetLine/FBLedgerJournalTrans_FiscalBooks_BR</a>|
|[FiscalEstablishment_BR](#FiscalEstablishment_BR)||<a href="FBLedgerJournalTrans_FiscalBooks_BR.md" target="_blank">WorksheetLine/FBLedgerJournalTrans_FiscalBooks_BR</a>|
|[GeneralAdjustmentCode](#GeneralAdjustmentCode)||<a href="FBLedgerJournalTrans_FiscalBooks_BR.md" target="_blank">WorksheetLine/FBLedgerJournalTrans_FiscalBooks_BR</a>|
|[LedgerJournalTrans](#LedgerJournalTrans)||<a href="FBLedgerJournalTrans_FiscalBooks_BR.md" target="_blank">WorksheetLine/FBLedgerJournalTrans_FiscalBooks_BR</a>|
|[ObservationCodeTable](#ObservationCodeTable)||<a href="FBLedgerJournalTrans_FiscalBooks_BR.md" target="_blank">WorksheetLine/FBLedgerJournalTrans_FiscalBooks_BR</a>|
|[State](#State)||<a href="FBLedgerJournalTrans_FiscalBooks_BR.md" target="_blank">WorksheetLine/FBLedgerJournalTrans_FiscalBooks_BR</a>|
|[TaxAmount](#TaxAmount)||<a href="FBLedgerJournalTrans_FiscalBooks_BR.md" target="_blank">WorksheetLine/FBLedgerJournalTrans_FiscalBooks_BR</a>|
|[TaxAmountOther](#TaxAmountOther)||<a href="FBLedgerJournalTrans_FiscalBooks_BR.md" target="_blank">WorksheetLine/FBLedgerJournalTrans_FiscalBooks_BR</a>|
|[TaxAdjustmentProcessNum](#TaxAdjustmentProcessNum)||<a href="FBLedgerJournalTrans_FiscalBooks_BR.md" target="_blank">WorksheetLine/FBLedgerJournalTrans_FiscalBooks_BR</a>|
|[TaxAdjustmentSourceType](#TaxAdjustmentSourceType)||<a href="FBLedgerJournalTrans_FiscalBooks_BR.md" target="_blank">WorksheetLine/FBLedgerJournalTrans_FiscalBooks_BR</a>|
|[TaxationCode](#TaxationCode)||<a href="FBLedgerJournalTrans_FiscalBooks_BR.md" target="_blank">WorksheetLine/FBLedgerJournalTrans_FiscalBooks_BR</a>|
|[TaxBaseAmount](#TaxBaseAmount)||<a href="FBLedgerJournalTrans_FiscalBooks_BR.md" target="_blank">WorksheetLine/FBLedgerJournalTrans_FiscalBooks_BR</a>|
|[TaxType](#TaxType)||<a href="FBLedgerJournalTrans_FiscalBooks_BR.md" target="_blank">WorksheetLine/FBLedgerJournalTrans_FiscalBooks_BR</a>|
|[TaxValue](#TaxValue)||<a href="FBLedgerJournalTrans_FiscalBooks_BR.md" target="_blank">WorksheetLine/FBLedgerJournalTrans_FiscalBooks_BR</a>|
|[DataAreaId](#DataAreaId)||<a href="FBLedgerJournalTrans_FiscalBooks_BR.md" target="_blank">WorksheetLine/FBLedgerJournalTrans_FiscalBooks_BR</a>|
|[Relationship_FBContribCreditType_BRRelationshipId](#Relationship_FBContribCreditType_BRRelationshipId)||<a href="FBLedgerJournalTrans_FiscalBooks_BR.md" target="_blank">WorksheetLine/FBLedgerJournalTrans_FiscalBooks_BR</a>|
|[Relationship_FBFiscalDocumentAdjustmentCodeICMSRelationshipId](#Relationship_FBFiscalDocumentAdjustmentCodeICMSRelationshipId)||<a href="FBLedgerJournalTrans_FiscalBooks_BR.md" target="_blank">WorksheetLine/FBLedgerJournalTrans_FiscalBooks_BR</a>|
|[Relationship_FBGeneralAdjustmentCodeRelationshipId](#Relationship_FBGeneralAdjustmentCodeRelationshipId)||<a href="FBLedgerJournalTrans_FiscalBooks_BR.md" target="_blank">WorksheetLine/FBLedgerJournalTrans_FiscalBooks_BR</a>|
|[Relationship_FiscalDocumentRelationshipId](#Relationship_FiscalDocumentRelationshipId)||<a href="FBLedgerJournalTrans_FiscalBooks_BR.md" target="_blank">WorksheetLine/FBLedgerJournalTrans_FiscalBooks_BR</a>|
|[Relationship_FiscalDocumentLine_BRRelationshipId](#Relationship_FiscalDocumentLine_BRRelationshipId)||<a href="FBLedgerJournalTrans_FiscalBooks_BR.md" target="_blank">WorksheetLine/FBLedgerJournalTrans_FiscalBooks_BR</a>|
|[Relationship_FiscalDocumentTaxTrans_BRRelationshipId](#Relationship_FiscalDocumentTaxTrans_BRRelationshipId)||<a href="FBLedgerJournalTrans_FiscalBooks_BR.md" target="_blank">WorksheetLine/FBLedgerJournalTrans_FiscalBooks_BR</a>|
|[Relationship_FiscalEstablishmentRelationshipId](#Relationship_FiscalEstablishmentRelationshipId)||<a href="FBLedgerJournalTrans_FiscalBooks_BR.md" target="_blank">WorksheetLine/FBLedgerJournalTrans_FiscalBooks_BR</a>|
|[Relationship_LedgerJournalTransRelationshipId](#Relationship_LedgerJournalTransRelationshipId)||<a href="FBLedgerJournalTrans_FiscalBooks_BR.md" target="_blank">WorksheetLine/FBLedgerJournalTrans_FiscalBooks_BR</a>|
|[Relationship_ObservationCodeTableRelationshipId](#Relationship_ObservationCodeTableRelationshipId)||<a href="FBLedgerJournalTrans_FiscalBooks_BR.md" target="_blank">WorksheetLine/FBLedgerJournalTrans_FiscalBooks_BR</a>|
|[Relationship_CompanyRelationshipId](#Relationship_CompanyRelationshipId)||<a href="FBLedgerJournalTrans_FiscalBooks_BR.md" target="_blank">WorksheetLine/FBLedgerJournalTrans_FiscalBooks_BR</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: WorksheetLine/FBLedgerJournalTrans_FiscalBooks_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[FBLedgerJournalTrans_FiscalBooks_BR/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#AdjustmentType name="AdjustmentType">AdjustmentType</a>

First included in: WorksheetLine/FBLedgerJournalTrans_FiscalBooks_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AdjustmentType attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#ComplementaryDescription name="ComplementaryDescription">ComplementaryDescription</a>

First included in: WorksheetLine/FBLedgerJournalTrans_FiscalBooks_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Complementary description</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ComplementaryDescription attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Complementary description</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ContribAssessmentPeriod name="ContribAssessmentPeriod">ContribAssessmentPeriod</a>

First included in: WorksheetLine/FBLedgerJournalTrans_FiscalBooks_BR (this entity)  

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

First included in: WorksheetLine/FBLedgerJournalTrans_FiscalBooks_BR (this entity)  

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

First included in: WorksheetLine/FBLedgerJournalTrans_FiscalBooks_BR (this entity)  

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

### <a href=#DeductionCNPJ name="DeductionCNPJ">DeductionCNPJ</a>

First included in: WorksheetLine/FBLedgerJournalTrans_FiscalBooks_BR (this entity)  

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

First included in: WorksheetLine/FBLedgerJournalTrans_FiscalBooks_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FBContribCreditType_BR attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#FiscalDocumentAdjustmentCodeICMS name="FiscalDocumentAdjustmentCodeICMS">FiscalDocumentAdjustmentCodeICMS</a>

First included in: WorksheetLine/FBLedgerJournalTrans_FiscalBooks_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FiscalDocumentAdjustmentCodeICMS attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#FiscalDocumentLine_BR name="FiscalDocumentLine_BR">FiscalDocumentLine_BR</a>

First included in: WorksheetLine/FBLedgerJournalTrans_FiscalBooks_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FiscalDocumentLine_BR attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.readOnly**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#FiscalDocumentTaxTrans_BR name="FiscalDocumentTaxTrans_BR">FiscalDocumentTaxTrans_BR</a>

First included in: WorksheetLine/FBLedgerJournalTrans_FiscalBooks_BR (this entity)  

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

### <a href=#FiscalDocument_BR name="FiscalDocument_BR">FiscalDocument_BR</a>

First included in: WorksheetLine/FBLedgerJournalTrans_FiscalBooks_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FiscalDocument_BR attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.readOnly**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#FiscalEstablishment_BR name="FiscalEstablishment_BR">FiscalEstablishment_BR</a>

First included in: WorksheetLine/FBLedgerJournalTrans_FiscalBooks_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FiscalEstablishment_BR attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#GeneralAdjustmentCode name="GeneralAdjustmentCode">GeneralAdjustmentCode</a>

First included in: WorksheetLine/FBLedgerJournalTrans_FiscalBooks_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the GeneralAdjustmentCode attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#LedgerJournalTrans name="LedgerJournalTrans">LedgerJournalTrans</a>

First included in: WorksheetLine/FBLedgerJournalTrans_FiscalBooks_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LedgerJournalTrans attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.readOnly**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#ObservationCodeTable name="ObservationCodeTable">ObservationCodeTable</a>

First included in: WorksheetLine/FBLedgerJournalTrans_FiscalBooks_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ObservationCodeTable attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#State name="State">State</a>

First included in: WorksheetLine/FBLedgerJournalTrans_FiscalBooks_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the State attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TaxAmount name="TaxAmount">TaxAmount</a>

First included in: WorksheetLine/FBLedgerJournalTrans_FiscalBooks_BR (this entity)  

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

### <a href=#TaxAmountOther name="TaxAmountOther">TaxAmountOther</a>

First included in: WorksheetLine/FBLedgerJournalTrans_FiscalBooks_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Other tax amount</td></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxAmountOther attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Other tax amount</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#TaxAdjustmentProcessNum name="TaxAdjustmentProcessNum">TaxAdjustmentProcessNum</a>

First included in: WorksheetLine/FBLedgerJournalTrans_FiscalBooks_BR (this entity)  

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

First included in: WorksheetLine/FBLedgerJournalTrans_FiscalBooks_BR (this entity)  

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

First included in: WorksheetLine/FBLedgerJournalTrans_FiscalBooks_BR (this entity)  

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

First included in: WorksheetLine/FBLedgerJournalTrans_FiscalBooks_BR (this entity)  

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

### <a href=#TaxType name="TaxType">TaxType</a>

First included in: WorksheetLine/FBLedgerJournalTrans_FiscalBooks_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxType attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#TaxValue name="TaxValue">TaxValue</a>

First included in: WorksheetLine/FBLedgerJournalTrans_FiscalBooks_BR (this entity)  

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

### <a href=#DataAreaId name="DataAreaId">DataAreaId</a>

First included in: WorksheetLine/FBLedgerJournalTrans_FiscalBooks_BR (this entity)  

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

### <a href=#Relationship_FBContribCreditType_BRRelationshipId name="Relationship_FBContribCreditType_BRRelationshipId">Relationship_FBContribCreditType_BRRelationshipId</a>

First included in: WorksheetLine/FBLedgerJournalTrans_FiscalBooks_BR (this entity)  

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

### <a href=#Relationship_FBFiscalDocumentAdjustmentCodeICMSRelationshipId name="Relationship_FBFiscalDocumentAdjustmentCodeICMSRelationshipId">Relationship_FBFiscalDocumentAdjustmentCodeICMSRelationshipId</a>

First included in: WorksheetLine/FBLedgerJournalTrans_FiscalBooks_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_FBFiscalDocumentAdjustmentCodeICMSRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Main/FBFiscalDocumentAdjustmentCodeICMS_BR.md" target="_blank">/core/operationsCommon/Tables/Finance/FiscalBooksBrazil/Main/FBFiscalDocumentAdjustmentCodeICMS_BR.cdm.json/FBFiscalDocumentAdjustmentCodeICMS_BR</a></td><td><a href="../Main/FBFiscalDocumentAdjustmentCodeICMS_BR.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_FBGeneralAdjustmentCodeRelationshipId name="Relationship_FBGeneralAdjustmentCodeRelationshipId">Relationship_FBGeneralAdjustmentCodeRelationshipId</a>

First included in: WorksheetLine/FBLedgerJournalTrans_FiscalBooks_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_FBGeneralAdjustmentCodeRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_FiscalDocumentRelationshipId name="Relationship_FiscalDocumentRelationshipId">Relationship_FiscalDocumentRelationshipId</a>

First included in: WorksheetLine/FBLedgerJournalTrans_FiscalBooks_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_FiscalDocumentRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Transaction/FiscalDocument_BR.md" target="_blank">/core/operationsCommon/Tables/Finance/FiscalBooksBrazil/Transaction/FiscalDocument_BR.cdm.json/FiscalDocument_BR</a></td><td><a href="../Transaction/FiscalDocument_BR.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_FiscalDocumentLine_BRRelationshipId name="Relationship_FiscalDocumentLine_BRRelationshipId">Relationship_FiscalDocumentLine_BRRelationshipId</a>

First included in: WorksheetLine/FBLedgerJournalTrans_FiscalBooks_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_FiscalDocumentLine_BRRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Transaction/FiscalDocumentLine_BR.md" target="_blank">/core/operationsCommon/Tables/Finance/FiscalBooksBrazil/Transaction/FiscalDocumentLine_BR.cdm.json/FiscalDocumentLine_BR</a></td><td><a href="../Transaction/FiscalDocumentLine_BR.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_FiscalDocumentTaxTrans_BRRelationshipId name="Relationship_FiscalDocumentTaxTrans_BRRelationshipId">Relationship_FiscalDocumentTaxTrans_BRRelationshipId</a>

First included in: WorksheetLine/FBLedgerJournalTrans_FiscalBooks_BR (this entity)  

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
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Transaction/FiscalDocumentTaxTrans_BR.md" target="_blank">/core/operationsCommon/Tables/Finance/FiscalBooksBrazil/Transaction/FiscalDocumentTaxTrans_BR.cdm.json/FiscalDocumentTaxTrans_BR</a></td><td><a href="../Transaction/FiscalDocumentTaxTrans_BR.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_FiscalEstablishmentRelationshipId name="Relationship_FiscalEstablishmentRelationshipId">Relationship_FiscalEstablishmentRelationshipId</a>

First included in: WorksheetLine/FBLedgerJournalTrans_FiscalBooks_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_FiscalEstablishmentRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Main/FiscalEstablishment_BR.md" target="_blank">/core/operationsCommon/Tables/Finance/FiscalBooksBrazil/Main/FiscalEstablishment_BR.cdm.json/FiscalEstablishment_BR</a></td><td><a href="../Main/FiscalEstablishment_BR.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_LedgerJournalTransRelationshipId name="Relationship_LedgerJournalTransRelationshipId">Relationship_LedgerJournalTransRelationshipId</a>

First included in: WorksheetLine/FBLedgerJournalTrans_FiscalBooks_BR (this entity)  

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

### <a href=#Relationship_ObservationCodeTableRelationshipId name="Relationship_ObservationCodeTableRelationshipId">Relationship_ObservationCodeTableRelationshipId</a>

First included in: WorksheetLine/FBLedgerJournalTrans_FiscalBooks_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_ObservationCodeTableRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Main/FBObservationCodeTable_BR.md" target="_blank">/core/operationsCommon/Tables/Finance/FiscalBooksBrazil/Main/FBObservationCodeTable_BR.cdm.json/FBObservationCodeTable_BR</a></td><td><a href="../Main/FBObservationCodeTable_BR.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_CompanyRelationshipId name="Relationship_CompanyRelationshipId">Relationship_CompanyRelationshipId</a>

First included in: WorksheetLine/FBLedgerJournalTrans_FiscalBooks_BR (this entity)  

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
