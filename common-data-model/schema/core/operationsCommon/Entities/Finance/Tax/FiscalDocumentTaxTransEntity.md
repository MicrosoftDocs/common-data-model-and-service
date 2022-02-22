---
title: FiscalDocumentTaxTransEntity in Tax - Common Data Model | Microsoft Docs
description: undefined
author: llawwaii

ms.reviewer: deonhe
ms.topic: reference
ms.date: 8/7/2020
ms.author: weiluo
---

# Fiscal document tax totals entity in Tax(FiscalDocumentTaxTransEntity)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/Finance/Tax/FiscalDocumentTaxTransEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.1"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Fiscal document tax totals entity</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[FiscalDocumentDirection](#FiscalDocumentDirection)||<a href="FiscalDocumentTaxTransEntity.md" target="_blank">Tax/FiscalDocumentTaxTransEntity</a>|
|[FiscalDocumentFiscalEstablishmentId](#FiscalDocumentFiscalEstablishmentId)||<a href="FiscalDocumentTaxTransEntity.md" target="_blank">Tax/FiscalDocumentTaxTransEntity</a>|
|[FiscalDocumentLine](#FiscalDocumentLine)||<a href="FiscalDocumentTaxTransEntity.md" target="_blank">Tax/FiscalDocumentTaxTransEntity</a>|
|[FiscalDocumentLineNumber](#FiscalDocumentLineNumber)||<a href="FiscalDocumentTaxTransEntity.md" target="_blank">Tax/FiscalDocumentTaxTransEntity</a>|
|[FiscalDocumentNumber](#FiscalDocumentNumber)||<a href="FiscalDocumentTaxTransEntity.md" target="_blank">Tax/FiscalDocumentTaxTransEntity</a>|
|[FiscalDocumentSeries](#FiscalDocumentSeries)||<a href="FiscalDocumentTaxTransEntity.md" target="_blank">Tax/FiscalDocumentTaxTransEntity</a>|
|[FiscalDocumentStatus](#FiscalDocumentStatus)||<a href="FiscalDocumentTaxTransEntity.md" target="_blank">Tax/FiscalDocumentTaxTransEntity</a>|
|[FiscalDocumentThirdPartyCNPJorCPF](#FiscalDocumentThirdPartyCNPJorCPF)||<a href="FiscalDocumentTaxTransEntity.md" target="_blank">Tax/FiscalDocumentTaxTransEntity</a>|
|[FiscalDocumentVoucher](#FiscalDocumentVoucher)||<a href="FiscalDocumentTaxTransEntity.md" target="_blank">Tax/FiscalDocumentTaxTransEntity</a>|
|[FiscalValue](#FiscalValue)||<a href="FiscalDocumentTaxTransEntity.md" target="_blank">Tax/FiscalDocumentTaxTransEntity</a>|
|[IncludedTax](#IncludedTax)||<a href="FiscalDocumentTaxTransEntity.md" target="_blank">Tax/FiscalDocumentTaxTransEntity</a>|
|[RetainedTax](#RetainedTax)||<a href="FiscalDocumentTaxTransEntity.md" target="_blank">Tax/FiscalDocumentTaxTransEntity</a>|
|[TaxAmount](#TaxAmount)||<a href="FiscalDocumentTaxTransEntity.md" target="_blank">Tax/FiscalDocumentTaxTransEntity</a>|
|[TaxAmountOther](#TaxAmountOther)||<a href="FiscalDocumentTaxTransEntity.md" target="_blank">Tax/FiscalDocumentTaxTransEntity</a>|
|[TaxationCode](#TaxationCode)||<a href="FiscalDocumentTaxTransEntity.md" target="_blank">Tax/FiscalDocumentTaxTransEntity</a>|
|[TaxationOrigin](#TaxationOrigin)||<a href="FiscalDocumentTaxTransEntity.md" target="_blank">Tax/FiscalDocumentTaxTransEntity</a>|
|[TaxBaseAmount](#TaxBaseAmount)||<a href="FiscalDocumentTaxTransEntity.md" target="_blank">Tax/FiscalDocumentTaxTransEntity</a>|
|[TaxBaseAmountExempt](#TaxBaseAmountExempt)||<a href="FiscalDocumentTaxTransEntity.md" target="_blank">Tax/FiscalDocumentTaxTransEntity</a>|
|[TaxBaseAmountOther](#TaxBaseAmountOther)||<a href="FiscalDocumentTaxTransEntity.md" target="_blank">Tax/FiscalDocumentTaxTransEntity</a>|
|[TaxExemptCode](#TaxExemptCode)||<a href="FiscalDocumentTaxTransEntity.md" target="_blank">Tax/FiscalDocumentTaxTransEntity</a>|
|[TaxNonRecoverablePct](#TaxNonRecoverablePct)||<a href="FiscalDocumentTaxTransEntity.md" target="_blank">Tax/FiscalDocumentTaxTransEntity</a>|
|[TaxPovertyFundAmount](#TaxPovertyFundAmount)||<a href="FiscalDocumentTaxTransEntity.md" target="_blank">Tax/FiscalDocumentTaxTransEntity</a>|
|[TaxPovertyFundPercentage](#TaxPovertyFundPercentage)||<a href="FiscalDocumentTaxTransEntity.md" target="_blank">Tax/FiscalDocumentTaxTransEntity</a>|
|[TaxReductionPct](#TaxReductionPct)||<a href="FiscalDocumentTaxTransEntity.md" target="_blank">Tax/FiscalDocumentTaxTransEntity</a>|
|[TaxSubstitutionMarkupPct](#TaxSubstitutionMarkupPct)||<a href="FiscalDocumentTaxTransEntity.md" target="_blank">Tax/FiscalDocumentTaxTransEntity</a>|
|[TaxValue](#TaxValue)||<a href="FiscalDocumentTaxTransEntity.md" target="_blank">Tax/FiscalDocumentTaxTransEntity</a>|
|[Type](#Type)||<a href="FiscalDocumentTaxTransEntity.md" target="_blank">Tax/FiscalDocumentTaxTransEntity</a>|
|[Relationship_FiscalDocumentLineEntityRelationshipId](#Relationship_FiscalDocumentLineEntityRelationshipId)||<a href="FiscalDocumentTaxTransEntity.md" target="_blank">Tax/FiscalDocumentTaxTransEntity</a>|
|[BackingTable_FiscalDocumentTaxTrans_BRRelationshipId](#BackingTable_FiscalDocumentTaxTrans_BRRelationshipId)||<a href="FiscalDocumentTaxTransEntity.md" target="_blank">Tax/FiscalDocumentTaxTransEntity</a>|
|[Relationship_PrimaryCompanyContextRelationshipId](#Relationship_PrimaryCompanyContextRelationshipId)||<a href="FiscalDocumentTaxTransEntity.md" target="_blank">Tax/FiscalDocumentTaxTransEntity</a>|

### <a href=#FiscalDocumentDirection name="FiscalDocumentDirection">FiscalDocumentDirection</a>

First included in: Tax/FiscalDocumentTaxTransEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FiscalDocumentDirection attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FiscalDocumentFiscalEstablishmentId name="FiscalDocumentFiscalEstablishmentId">FiscalDocumentFiscalEstablishmentId</a>

First included in: Tax/FiscalDocumentTaxTransEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FiscalDocumentFiscalEstablishmentId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FiscalDocumentLine name="FiscalDocumentLine">FiscalDocumentLine</a>

First included in: Tax/FiscalDocumentTaxTransEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FiscalDocumentLine attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FiscalDocumentLineNumber name="FiscalDocumentLineNumber">FiscalDocumentLineNumber</a>

First included in: Tax/FiscalDocumentTaxTransEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FiscalDocumentLineNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FiscalDocumentNumber name="FiscalDocumentNumber">FiscalDocumentNumber</a>

First included in: Tax/FiscalDocumentTaxTransEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FiscalDocumentNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FiscalDocumentSeries name="FiscalDocumentSeries">FiscalDocumentSeries</a>

First included in: Tax/FiscalDocumentTaxTransEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FiscalDocumentSeries attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FiscalDocumentStatus name="FiscalDocumentStatus">FiscalDocumentStatus</a>

First included in: Tax/FiscalDocumentTaxTransEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FiscalDocumentStatus attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FiscalDocumentThirdPartyCNPJorCPF name="FiscalDocumentThirdPartyCNPJorCPF">FiscalDocumentThirdPartyCNPJorCPF</a>

First included in: Tax/FiscalDocumentTaxTransEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FiscalDocumentThirdPartyCNPJorCPF attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FiscalDocumentVoucher name="FiscalDocumentVoucher">FiscalDocumentVoucher</a>

First included in: Tax/FiscalDocumentTaxTransEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FiscalDocumentVoucher attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FiscalValue name="FiscalValue">FiscalValue</a>

First included in: Tax/FiscalDocumentTaxTransEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FiscalValue attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IncludedTax name="IncludedTax">IncludedTax</a>

First included in: Tax/FiscalDocumentTaxTransEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IncludedTax attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RetainedTax name="RetainedTax">RetainedTax</a>

First included in: Tax/FiscalDocumentTaxTransEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RetainedTax attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TaxAmount name="TaxAmount">TaxAmount</a>

First included in: Tax/FiscalDocumentTaxTransEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxAmount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TaxAmountOther name="TaxAmountOther">TaxAmountOther</a>

First included in: Tax/FiscalDocumentTaxTransEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxAmountOther attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TaxationCode name="TaxationCode">TaxationCode</a>

First included in: Tax/FiscalDocumentTaxTransEntity (this entity)  

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

### <a href=#TaxationOrigin name="TaxationOrigin">TaxationOrigin</a>

First included in: Tax/FiscalDocumentTaxTransEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxationOrigin attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TaxBaseAmount name="TaxBaseAmount">TaxBaseAmount</a>

First included in: Tax/FiscalDocumentTaxTransEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxBaseAmount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TaxBaseAmountExempt name="TaxBaseAmountExempt">TaxBaseAmountExempt</a>

First included in: Tax/FiscalDocumentTaxTransEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxBaseAmountExempt attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TaxBaseAmountOther name="TaxBaseAmountOther">TaxBaseAmountOther</a>

First included in: Tax/FiscalDocumentTaxTransEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxBaseAmountOther attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TaxExemptCode name="TaxExemptCode">TaxExemptCode</a>

First included in: Tax/FiscalDocumentTaxTransEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxExemptCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TaxNonRecoverablePct name="TaxNonRecoverablePct">TaxNonRecoverablePct</a>

First included in: Tax/FiscalDocumentTaxTransEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxNonRecoverablePct attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TaxPovertyFundAmount name="TaxPovertyFundAmount">TaxPovertyFundAmount</a>

First included in: Tax/FiscalDocumentTaxTransEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxPovertyFundAmount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TaxPovertyFundPercentage name="TaxPovertyFundPercentage">TaxPovertyFundPercentage</a>

First included in: Tax/FiscalDocumentTaxTransEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxPovertyFundPercentage attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TaxReductionPct name="TaxReductionPct">TaxReductionPct</a>

First included in: Tax/FiscalDocumentTaxTransEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxReductionPct attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TaxSubstitutionMarkupPct name="TaxSubstitutionMarkupPct">TaxSubstitutionMarkupPct</a>

First included in: Tax/FiscalDocumentTaxTransEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxSubstitutionMarkupPct attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TaxValue name="TaxValue">TaxValue</a>

First included in: Tax/FiscalDocumentTaxTransEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxValue attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Type name="Type">Type</a>

First included in: Tax/FiscalDocumentTaxTransEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Type attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_FiscalDocumentLineEntityRelationshipId name="Relationship_FiscalDocumentLineEntityRelationshipId">Relationship_FiscalDocumentLineEntityRelationshipId</a>

First included in: Tax/FiscalDocumentTaxTransEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_FiscalDocumentLineEntityRelationshipId attribute are listed below.</summary>

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

### <a href=#BackingTable_FiscalDocumentTaxTrans_BRRelationshipId name="BackingTable_FiscalDocumentTaxTrans_BRRelationshipId">BackingTable_FiscalDocumentTaxTrans_BRRelationshipId</a>

First included in: Tax/FiscalDocumentTaxTransEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_FiscalDocumentTaxTrans_BRRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/Finance/FiscalBooksBrazil/Transaction/FiscalDocumentTaxTrans_BR.md" target="_blank">/core/operationsCommon/Tables/Finance/FiscalBooksBrazil/Transaction/FiscalDocumentTaxTrans_BR.cdm.json/FiscalDocumentTaxTrans_BR</a></td><td><a href="../../../Tables/Finance/FiscalBooksBrazil/Transaction/FiscalDocumentTaxTrans_BR.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PrimaryCompanyContextRelationshipId name="Relationship_PrimaryCompanyContextRelationshipId">Relationship_PrimaryCompanyContextRelationshipId</a>

First included in: Tax/FiscalDocumentTaxTransEntity (this entity)  

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
