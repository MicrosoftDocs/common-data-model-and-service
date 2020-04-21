---
title: TaxWithholdDeducteeDetail_IN - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/21/2020
ms.author: nebanfic
---

# TaxWithholdDeducteeDetail_IN

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Tables/Finance/Tax/Transaction/TaxWithholdDeducteeDetail_IN.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[TaxWithholdDeducteeDetail_IN/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="TaxWithholdDeducteeDetail_IN.md" target="_blank">Transaction/TaxWithholdDeducteeDetail_IN</a>|
|[BatchRecordNumber](#BatchRecordNumber)||<a href="TaxWithholdDeducteeDetail_IN.md" target="_blank">Transaction/TaxWithholdDeducteeDetail_IN</a>|
|[CertificateNumber](#CertificateNumber)||<a href="TaxWithholdDeducteeDetail_IN.md" target="_blank">Transaction/TaxWithholdDeducteeDetail_IN</a>|
|[ChallanDetailRecordNumber](#ChallanDetailRecordNumber)||<a href="TaxWithholdDeducteeDetail_IN.md" target="_blank">Transaction/TaxWithholdDeducteeDetail_IN</a>|
|[CorrectionFile](#CorrectionFile)||<a href="TaxWithholdDeducteeDetail_IN.md" target="_blank">Transaction/TaxWithholdDeducteeDetail_IN</a>|
|[DeducteeCode](#DeducteeCode)||<a href="TaxWithholdDeducteeDetail_IN.md" target="_blank">Transaction/TaxWithholdDeducteeDetail_IN</a>|
|[DeducteeDetailRecordNumber](#DeducteeDetailRecordNumber)||<a href="TaxWithholdDeducteeDetail_IN.md" target="_blank">Transaction/TaxWithholdDeducteeDetail_IN</a>|
|[DeducteeName](#DeducteeName)||<a href="TaxWithholdDeducteeDetail_IN.md" target="_blank">Transaction/TaxWithholdDeducteeDetail_IN</a>|
|[DeducteeNumber](#DeducteeNumber)||<a href="TaxWithholdDeducteeDetail_IN.md" target="_blank">Transaction/TaxWithholdDeducteeDetail_IN</a>|
|[DeducteePANNumber](#DeducteePANNumber)||<a href="TaxWithholdDeducteeDetail_IN.md" target="_blank">Transaction/TaxWithholdDeducteeDetail_IN</a>|
|[DeducteePANRefNumber](#DeducteePANRefNumber)||<a href="TaxWithholdDeducteeDetail_IN.md" target="_blank">Transaction/TaxWithholdDeducteeDetail_IN</a>|
|[DeducteePANStatus](#DeducteePANStatus)||<a href="TaxWithholdDeducteeDetail_IN.md" target="_blank">Transaction/TaxWithholdDeducteeDetail_IN</a>|
|[FormNumber](#FormNumber)||<a href="TaxWithholdDeducteeDetail_IN.md" target="_blank">Transaction/TaxWithholdDeducteeDetail_IN</a>|
|[FromDate](#FromDate)||<a href="TaxWithholdDeducteeDetail_IN.md" target="_blank">Transaction/TaxWithholdDeducteeDetail_IN</a>|
|[PECessAmount](#PECessAmount)||<a href="TaxWithholdDeducteeDetail_IN.md" target="_blank">Transaction/TaxWithholdDeducteeDetail_IN</a>|
|[Reason](#Reason)||<a href="TaxWithholdDeducteeDetail_IN.md" target="_blank">Transaction/TaxWithholdDeducteeDetail_IN</a>|
|[RecIdFileHdr](#RecIdFileHdr)||<a href="TaxWithholdDeducteeDetail_IN.md" target="_blank">Transaction/TaxWithholdDeducteeDetail_IN</a>|
|[SectionCode](#SectionCode)||<a href="TaxWithholdDeducteeDetail_IN.md" target="_blank">Transaction/TaxWithholdDeducteeDetail_IN</a>|
|[SurchargeAmount](#SurchargeAmount)||<a href="TaxWithholdDeducteeDetail_IN.md" target="_blank">Transaction/TaxWithholdDeducteeDetail_IN</a>|
|[TaxApplicability](#TaxApplicability)||<a href="TaxWithholdDeducteeDetail_IN.md" target="_blank">Transaction/TaxWithholdDeducteeDetail_IN</a>|
|[TaxWithholdAcknowledgementNumber](#TaxWithholdAcknowledgementNumber)||<a href="TaxWithholdDeducteeDetail_IN.md" target="_blank">Transaction/TaxWithholdDeducteeDetail_IN</a>|
|[TaxWithholdAmount](#TaxWithholdAmount)||<a href="TaxWithholdDeducteeDetail_IN.md" target="_blank">Transaction/TaxWithholdDeducteeDetail_IN</a>|
|[TaxWithholdCountryRegionToRemittance](#TaxWithholdCountryRegionToRemittance)||<a href="TaxWithholdDeducteeDetail_IN.md" target="_blank">Transaction/TaxWithholdDeducteeDetail_IN</a>|
|[TaxWithholdDate](#TaxWithholdDate)||<a href="TaxWithholdDeducteeDetail_IN.md" target="_blank">Transaction/TaxWithholdDeducteeDetail_IN</a>|
|[TaxWithholdNatureOfRemittance](#TaxWithholdNatureOfRemittance)||<a href="TaxWithholdDeducteeDetail_IN.md" target="_blank">Transaction/TaxWithholdDeducteeDetail_IN</a>|
|[TaxWithholdRegNumber](#TaxWithholdRegNumber)||<a href="TaxWithholdDeducteeDetail_IN.md" target="_blank">Transaction/TaxWithholdDeducteeDetail_IN</a>|
|[ToDate](#ToDate)||<a href="TaxWithholdDeducteeDetail_IN.md" target="_blank">Transaction/TaxWithholdDeducteeDetail_IN</a>|
|[TotalAmountPaid](#TotalAmountPaid)||<a href="TaxWithholdDeducteeDetail_IN.md" target="_blank">Transaction/TaxWithholdDeducteeDetail_IN</a>|
|[TotalIncomeTax](#TotalIncomeTax)||<a href="TaxWithholdDeducteeDetail_IN.md" target="_blank">Transaction/TaxWithholdDeducteeDetail_IN</a>|
|[TotalRate](#TotalRate)||<a href="TaxWithholdDeducteeDetail_IN.md" target="_blank">Transaction/TaxWithholdDeducteeDetail_IN</a>|
|[TotalTaxDeducted](#TotalTaxDeducted)||<a href="TaxWithholdDeducteeDetail_IN.md" target="_blank">Transaction/TaxWithholdDeducteeDetail_IN</a>|
|[TransDate](#TransDate)||<a href="TaxWithholdDeducteeDetail_IN.md" target="_blank">Transaction/TaxWithholdDeducteeDetail_IN</a>|
|[VendDeducteeNumber](#VendDeducteeNumber)||<a href="TaxWithholdDeducteeDetail_IN.md" target="_blank">Transaction/TaxWithholdDeducteeDetail_IN</a>|
|[DataAreaId](#DataAreaId)||<a href="TaxWithholdDeducteeDetail_IN.md" target="_blank">Transaction/TaxWithholdDeducteeDetail_IN</a>|
|[Relationship_CustTableRelationshipId](#Relationship_CustTableRelationshipId)||<a href="TaxWithholdDeducteeDetail_IN.md" target="_blank">Transaction/TaxWithholdDeducteeDetail_IN</a>|
|[Relationship_TaxWithholdFileHeaderRelationshipId](#Relationship_TaxWithholdFileHeaderRelationshipId)||<a href="TaxWithholdDeducteeDetail_IN.md" target="_blank">Transaction/TaxWithholdDeducteeDetail_IN</a>|
|[Relationship_TaxWithholdRegNumberRelationshipId](#Relationship_TaxWithholdRegNumberRelationshipId)||<a href="TaxWithholdDeducteeDetail_IN.md" target="_blank">Transaction/TaxWithholdDeducteeDetail_IN</a>|
|[Relationship_VendTableRelationshipId](#Relationship_VendTableRelationshipId)||<a href="TaxWithholdDeducteeDetail_IN.md" target="_blank">Transaction/TaxWithholdDeducteeDetail_IN</a>|
|[Relationship_CompanyRelationshipId](#Relationship_CompanyRelationshipId)||<a href="TaxWithholdDeducteeDetail_IN.md" target="_blank">Transaction/TaxWithholdDeducteeDetail_IN</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: Transaction/TaxWithholdDeducteeDetail_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[TaxWithholdDeducteeDetail_IN/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#BatchRecordNumber name="BatchRecordNumber">BatchRecordNumber</a>

First included in: Transaction/TaxWithholdDeducteeDetail_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BatchRecordNumber attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#CertificateNumber name="CertificateNumber">CertificateNumber</a>

First included in: Transaction/TaxWithholdDeducteeDetail_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CertificateNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ChallanDetailRecordNumber name="ChallanDetailRecordNumber">ChallanDetailRecordNumber</a>

First included in: Transaction/TaxWithholdDeducteeDetail_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ChallanDetailRecordNumber attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#CorrectionFile name="CorrectionFile">CorrectionFile</a>

First included in: Transaction/TaxWithholdDeducteeDetail_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CorrectionFile attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#DeducteeCode name="DeducteeCode">DeducteeCode</a>

First included in: Transaction/TaxWithholdDeducteeDetail_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DeducteeCode attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#DeducteeDetailRecordNumber name="DeducteeDetailRecordNumber">DeducteeDetailRecordNumber</a>

First included in: Transaction/TaxWithholdDeducteeDetail_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DeducteeDetailRecordNumber attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#DeducteeName name="DeducteeName">DeducteeName</a>

First included in: Transaction/TaxWithholdDeducteeDetail_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DeducteeName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DeducteeNumber name="DeducteeNumber">DeducteeNumber</a>

First included in: Transaction/TaxWithholdDeducteeDetail_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DeducteeNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DeducteePANNumber name="DeducteePANNumber">DeducteePANNumber</a>

First included in: Transaction/TaxWithholdDeducteeDetail_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DeducteePANNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DeducteePANRefNumber name="DeducteePANRefNumber">DeducteePANRefNumber</a>

First included in: Transaction/TaxWithholdDeducteeDetail_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DeducteePANRefNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DeducteePANStatus name="DeducteePANStatus">DeducteePANStatus</a>

First included in: Transaction/TaxWithholdDeducteeDetail_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DeducteePANStatus attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#FormNumber name="FormNumber">FormNumber</a>

First included in: Transaction/TaxWithholdDeducteeDetail_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FormNumber attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#FromDate name="FromDate">FromDate</a>

First included in: Transaction/TaxWithholdDeducteeDetail_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FromDate attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.dataFormat.date**  
</details>

### <a href=#PECessAmount name="PECessAmount">PECessAmount</a>

First included in: Transaction/TaxWithholdDeducteeDetail_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PECessAmount attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#Reason name="Reason">Reason</a>

First included in: Transaction/TaxWithholdDeducteeDetail_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Reason attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RecIdFileHdr name="RecIdFileHdr">RecIdFileHdr</a>

First included in: Transaction/TaxWithholdDeducteeDetail_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecIdFileHdr attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#SectionCode name="SectionCode">SectionCode</a>

First included in: Transaction/TaxWithholdDeducteeDetail_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SectionCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SurchargeAmount name="SurchargeAmount">SurchargeAmount</a>

First included in: Transaction/TaxWithholdDeducteeDetail_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SurchargeAmount attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#TaxApplicability name="TaxApplicability">TaxApplicability</a>

First included in: Transaction/TaxWithholdDeducteeDetail_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxApplicability attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#TaxWithholdAcknowledgementNumber name="TaxWithholdAcknowledgementNumber">TaxWithholdAcknowledgementNumber</a>

First included in: Transaction/TaxWithholdDeducteeDetail_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxWithholdAcknowledgementNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TaxWithholdAmount name="TaxWithholdAmount">TaxWithholdAmount</a>

First included in: Transaction/TaxWithholdDeducteeDetail_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxWithholdAmount attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#TaxWithholdCountryRegionToRemittance name="TaxWithholdCountryRegionToRemittance">TaxWithholdCountryRegionToRemittance</a>

First included in: Transaction/TaxWithholdDeducteeDetail_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxWithholdCountryRegionToRemittance attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#TaxWithholdDate name="TaxWithholdDate">TaxWithholdDate</a>

First included in: Transaction/TaxWithholdDeducteeDetail_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxWithholdDate attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.dataFormat.date**  
</details>

### <a href=#TaxWithholdNatureOfRemittance name="TaxWithholdNatureOfRemittance">TaxWithholdNatureOfRemittance</a>

First included in: Transaction/TaxWithholdDeducteeDetail_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxWithholdNatureOfRemittance attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#TaxWithholdRegNumber name="TaxWithholdRegNumber">TaxWithholdRegNumber</a>

First included in: Transaction/TaxWithholdDeducteeDetail_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxWithholdRegNumber attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#ToDate name="ToDate">ToDate</a>

First included in: Transaction/TaxWithholdDeducteeDetail_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ToDate attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.dataFormat.date**  
</details>

### <a href=#TotalAmountPaid name="TotalAmountPaid">TotalAmountPaid</a>

First included in: Transaction/TaxWithholdDeducteeDetail_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TotalAmountPaid attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#TotalIncomeTax name="TotalIncomeTax">TotalIncomeTax</a>

First included in: Transaction/TaxWithholdDeducteeDetail_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TotalIncomeTax attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#TotalRate name="TotalRate">TotalRate</a>

First included in: Transaction/TaxWithholdDeducteeDetail_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TotalRate attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#TotalTaxDeducted name="TotalTaxDeducted">TotalTaxDeducted</a>

First included in: Transaction/TaxWithholdDeducteeDetail_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TotalTaxDeducted attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#TransDate name="TransDate">TransDate</a>

First included in: Transaction/TaxWithholdDeducteeDetail_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TransDate attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.dataFormat.date**  
</details>

### <a href=#VendDeducteeNumber name="VendDeducteeNumber">VendDeducteeNumber</a>

First included in: Transaction/TaxWithholdDeducteeDetail_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VendDeducteeNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DataAreaId name="DataAreaId">DataAreaId</a>

First included in: Transaction/TaxWithholdDeducteeDetail_IN (this entity)  

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

### <a href=#Relationship_CustTableRelationshipId name="Relationship_CustTableRelationshipId">Relationship_CustTableRelationshipId</a>

First included in: Transaction/TaxWithholdDeducteeDetail_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_CustTableRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Common/Customer/Main/CustTable.md" target="_blank">/core/operationsCommon/Tables/Common/Customer/Main/CustTable.cdm.json/CustTable</a></td><td><a href="../../../Common/Customer/Main/CustTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_TaxWithholdFileHeaderRelationshipId name="Relationship_TaxWithholdFileHeaderRelationshipId">Relationship_TaxWithholdFileHeaderRelationshipId</a>

First included in: Transaction/TaxWithholdDeducteeDetail_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_TaxWithholdFileHeaderRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="TaxWithholdFileHeader_IN.md" target="_blank">/core/operationsCommon/Tables/Finance/Tax/Transaction/TaxWithholdFileHeader_IN.cdm.json/TaxWithholdFileHeader_IN</a></td><td><a href="TaxWithholdFileHeader_IN.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_TaxWithholdRegNumberRelationshipId name="Relationship_TaxWithholdRegNumberRelationshipId">Relationship_TaxWithholdRegNumberRelationshipId</a>

First included in: Transaction/TaxWithholdDeducteeDetail_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_TaxWithholdRegNumberRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Main/TaxWithholdRegNumbers_IN.md" target="_blank">/core/operationsCommon/Tables/Finance/Tax/Main/TaxWithholdRegNumbers_IN.cdm.json/TaxWithholdRegNumbers_IN</a></td><td><a href="../Main/TaxWithholdRegNumbers_IN.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_VendTableRelationshipId name="Relationship_VendTableRelationshipId">Relationship_VendTableRelationshipId</a>

First included in: Transaction/TaxWithholdDeducteeDetail_IN (this entity)  

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

First included in: Transaction/TaxWithholdDeducteeDetail_IN (this entity)  

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
