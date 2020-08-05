---
title: TaxUncommitted_IN in WorksheetLine - Common Data Model | Microsoft Docs
description: undefined
author: llawwaii
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 8/5/2020
ms.author: weiluo
---

# Uncommitted sales tax in WorksheetLine(TaxUncommitted_IN)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Tables/Finance/Tax/WorksheetLine/TaxUncommitted_IN.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[TaxUncommitted_IN/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.1"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Uncommitted sales tax</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="TaxUncommitted_IN.md" target="_blank">WorksheetLine/TaxUncommitted_IN</a>|
|[AbatementAmount](#AbatementAmount)||<a href="TaxUncommitted_IN.md" target="_blank">WorksheetLine/TaxUncommitted_IN</a>|
|[ClaimPercentage](#ClaimPercentage)||<a href="TaxUncommitted_IN.md" target="_blank">WorksheetLine/TaxUncommitted_IN</a>|
|[CustomsDuty](#CustomsDuty)||<a href="TaxUncommitted_IN.md" target="_blank">WorksheetLine/TaxUncommitted_IN</a>|
|[EximAuthorizationId](#EximAuthorizationId)||<a href="TaxUncommitted_IN.md" target="_blank">WorksheetLine/TaxUncommitted_IN</a>|
|[EximBalanceTaxAmount](#EximBalanceTaxAmount)||<a href="TaxUncommitted_IN.md" target="_blank">WorksheetLine/TaxUncommitted_IN</a>|
|[EximBalanceTaxAmountCur](#EximBalanceTaxAmountCur)||<a href="TaxUncommitted_IN.md" target="_blank">WorksheetLine/TaxUncommitted_IN</a>|
|[EximBalanceTaxCorrectedAmount](#EximBalanceTaxCorrectedAmount)||<a href="TaxUncommitted_IN.md" target="_blank">WorksheetLine/TaxUncommitted_IN</a>|
|[EximBalanceTaxCorrectedAmountCur](#EximBalanceTaxCorrectedAmountCur)||<a href="TaxUncommitted_IN.md" target="_blank">WorksheetLine/TaxUncommitted_IN</a>|
|[EximDEPBAmount](#EximDEPBAmount)||<a href="TaxUncommitted_IN.md" target="_blank">WorksheetLine/TaxUncommitted_IN</a>|
|[EximDEPBAmountCur](#EximDEPBAmountCur)||<a href="TaxUncommitted_IN.md" target="_blank">WorksheetLine/TaxUncommitted_IN</a>|
|[EximIncentiveScheme](#EximIncentiveScheme)||<a href="TaxUncommitted_IN.md" target="_blank">WorksheetLine/TaxUncommitted_IN</a>|
|[EximTaxAmount](#EximTaxAmount)||<a href="TaxUncommitted_IN.md" target="_blank">WorksheetLine/TaxUncommitted_IN</a>|
|[EximTaxAmountCur](#EximTaxAmountCur)||<a href="TaxUncommitted_IN.md" target="_blank">WorksheetLine/TaxUncommitted_IN</a>|
|[EximTaxCorrectedAmount](#EximTaxCorrectedAmount)||<a href="TaxUncommitted_IN.md" target="_blank">WorksheetLine/TaxUncommitted_IN</a>|
|[EximTaxCorrectedAmountCur](#EximTaxCorrectedAmountCur)||<a href="TaxUncommitted_IN.md" target="_blank">WorksheetLine/TaxUncommitted_IN</a>|
|[FormulaID](#FormulaID)||<a href="TaxUncommitted_IN.md" target="_blank">WorksheetLine/TaxUncommitted_IN</a>|
|[IsScrapQtyLine_IN](#IsScrapQtyLine_IN)||<a href="TaxUncommitted_IN.md" target="_blank">WorksheetLine/TaxUncommitted_IN</a>|
|[LoadOnInventoryTax](#LoadOnInventoryTax)||<a href="TaxUncommitted_IN.md" target="_blank">WorksheetLine/TaxUncommitted_IN</a>|
|[MainVoucher](#MainVoucher)||<a href="TaxUncommitted_IN.md" target="_blank">WorksheetLine/TaxUncommitted_IN</a>|
|[ServiceTaxReverseChargePercentage](#ServiceTaxReverseChargePercentage)||<a href="TaxUncommitted_IN.md" target="_blank">WorksheetLine/TaxUncommitted_IN</a>|
|[ServTaxRevChargeOriginAmountCur_IN](#ServTaxRevChargeOriginAmountCur_IN)||<a href="TaxUncommitted_IN.md" target="_blank">WorksheetLine/TaxUncommitted_IN</a>|
|[SourceRegulateAmountCustoms](#SourceRegulateAmountCustoms)||<a href="TaxUncommitted_IN.md" target="_blank">WorksheetLine/TaxUncommitted_IN</a>|
|[TaxAccountType](#TaxAccountType)||<a href="TaxUncommitted_IN.md" target="_blank">WorksheetLine/TaxUncommitted_IN</a>|
|[TaxRegistrationNumberTable_IN](#TaxRegistrationNumberTable_IN)||<a href="TaxUncommitted_IN.md" target="_blank">WorksheetLine/TaxUncommitted_IN</a>|
|[TaxUncommitted](#TaxUncommitted)||<a href="TaxUncommitted_IN.md" target="_blank">WorksheetLine/TaxUncommitted_IN</a>|
|[DataAreaId](#DataAreaId)||<a href="TaxUncommitted_IN.md" target="_blank">WorksheetLine/TaxUncommitted_IN</a>|
|[Relationship_TaxRegistrationNumberTable_INRelationshipId](#Relationship_TaxRegistrationNumberTable_INRelationshipId)||<a href="TaxUncommitted_IN.md" target="_blank">WorksheetLine/TaxUncommitted_IN</a>|
|[Relationship_TaxUncommittedRelationshipId](#Relationship_TaxUncommittedRelationshipId)||<a href="TaxUncommitted_IN.md" target="_blank">WorksheetLine/TaxUncommitted_IN</a>|
|[Relationship_CompanyRelationshipId](#Relationship_CompanyRelationshipId)||<a href="TaxUncommitted_IN.md" target="_blank">WorksheetLine/TaxUncommitted_IN</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: WorksheetLine/TaxUncommitted_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[TaxUncommitted_IN/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#AbatementAmount name="AbatementAmount">AbatementAmount</a>

First included in: WorksheetLine/TaxUncommitted_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AbatementAmount attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#ClaimPercentage name="ClaimPercentage">ClaimPercentage</a>

First included in: WorksheetLine/TaxUncommitted_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Claim percentage</td></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ClaimPercentage attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Claim percentage</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#CustomsDuty name="CustomsDuty">CustomsDuty</a>

First included in: WorksheetLine/TaxUncommitted_IN (this entity)  

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

### <a href=#EximAuthorizationId name="EximAuthorizationId">EximAuthorizationId</a>

First included in: WorksheetLine/TaxUncommitted_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EximAuthorizationId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#EximBalanceTaxAmount name="EximBalanceTaxAmount">EximBalanceTaxAmount</a>

First included in: WorksheetLine/TaxUncommitted_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EximBalanceTaxAmount attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#EximBalanceTaxAmountCur name="EximBalanceTaxAmountCur">EximBalanceTaxAmountCur</a>

First included in: WorksheetLine/TaxUncommitted_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EximBalanceTaxAmountCur attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#EximBalanceTaxCorrectedAmount name="EximBalanceTaxCorrectedAmount">EximBalanceTaxCorrectedAmount</a>

First included in: WorksheetLine/TaxUncommitted_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EximBalanceTaxCorrectedAmount attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#EximBalanceTaxCorrectedAmountCur name="EximBalanceTaxCorrectedAmountCur">EximBalanceTaxCorrectedAmountCur</a>

First included in: WorksheetLine/TaxUncommitted_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EximBalanceTaxCorrectedAmountCur attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#EximDEPBAmount name="EximDEPBAmount">EximDEPBAmount</a>

First included in: WorksheetLine/TaxUncommitted_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EximDEPBAmount attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#EximDEPBAmountCur name="EximDEPBAmountCur">EximDEPBAmountCur</a>

First included in: WorksheetLine/TaxUncommitted_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EximDEPBAmountCur attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#EximIncentiveScheme name="EximIncentiveScheme">EximIncentiveScheme</a>

First included in: WorksheetLine/TaxUncommitted_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EximIncentiveScheme attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#EximTaxAmount name="EximTaxAmount">EximTaxAmount</a>

First included in: WorksheetLine/TaxUncommitted_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EximTaxAmount attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#EximTaxAmountCur name="EximTaxAmountCur">EximTaxAmountCur</a>

First included in: WorksheetLine/TaxUncommitted_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EximTaxAmountCur attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#EximTaxCorrectedAmount name="EximTaxCorrectedAmount">EximTaxCorrectedAmount</a>

First included in: WorksheetLine/TaxUncommitted_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EximTaxCorrectedAmount attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#EximTaxCorrectedAmountCur name="EximTaxCorrectedAmountCur">EximTaxCorrectedAmountCur</a>

First included in: WorksheetLine/TaxUncommitted_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EximTaxCorrectedAmountCur attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#FormulaID name="FormulaID">FormulaID</a>

First included in: WorksheetLine/TaxUncommitted_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FormulaID attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#IsScrapQtyLine_IN name="IsScrapQtyLine_IN">IsScrapQtyLine_IN</a>

First included in: WorksheetLine/TaxUncommitted_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsScrapQtyLine_IN attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#LoadOnInventoryTax name="LoadOnInventoryTax">LoadOnInventoryTax</a>

First included in: WorksheetLine/TaxUncommitted_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LoadOnInventoryTax attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#MainVoucher name="MainVoucher">MainVoucher</a>

First included in: WorksheetLine/TaxUncommitted_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MainVoucher attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ServiceTaxReverseChargePercentage name="ServiceTaxReverseChargePercentage">ServiceTaxReverseChargePercentage</a>

First included in: WorksheetLine/TaxUncommitted_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ServiceTaxReverseChargePercentage attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#ServTaxRevChargeOriginAmountCur_IN name="ServTaxRevChargeOriginAmountCur_IN">ServTaxRevChargeOriginAmountCur_IN</a>

First included in: WorksheetLine/TaxUncommitted_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ServTaxRevChargeOriginAmountCur_IN attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#SourceRegulateAmountCustoms name="SourceRegulateAmountCustoms">SourceRegulateAmountCustoms</a>

First included in: WorksheetLine/TaxUncommitted_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SourceRegulateAmountCustoms attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#TaxAccountType name="TaxAccountType">TaxAccountType</a>

First included in: WorksheetLine/TaxUncommitted_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxAccountType attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#TaxRegistrationNumberTable_IN name="TaxRegistrationNumberTable_IN">TaxRegistrationNumberTable_IN</a>

First included in: WorksheetLine/TaxUncommitted_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Registration number</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxRegistrationNumberTable_IN attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Registration number</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#TaxUncommitted name="TaxUncommitted">TaxUncommitted</a>

First included in: WorksheetLine/TaxUncommitted_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxUncommitted attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#DataAreaId name="DataAreaId">DataAreaId</a>

First included in: WorksheetLine/TaxUncommitted_IN (this entity)  

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

### <a href=#Relationship_TaxRegistrationNumberTable_INRelationshipId name="Relationship_TaxRegistrationNumberTable_INRelationshipId">Relationship_TaxRegistrationNumberTable_INRelationshipId</a>

First included in: WorksheetLine/TaxUncommitted_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_TaxRegistrationNumberTable_INRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Main/TaxRegistrationNumbers_IN.md" target="_blank">/core/operationsCommon/Tables/Finance/Tax/Main/TaxRegistrationNumbers_IN.cdm.json/TaxRegistrationNumbers_IN</a></td><td><a href="../Main/TaxRegistrationNumbers_IN.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_TaxUncommittedRelationshipId name="Relationship_TaxUncommittedRelationshipId">Relationship_TaxUncommittedRelationshipId</a>

First included in: WorksheetLine/TaxUncommitted_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_TaxUncommittedRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="TaxUncommitted.md" target="_blank">/core/operationsCommon/Tables/Finance/Tax/WorksheetLine/TaxUncommitted.cdm.json/TaxUncommitted</a></td><td><a href="TaxUncommitted.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_CompanyRelationshipId name="Relationship_CompanyRelationshipId">Relationship_CompanyRelationshipId</a>

First included in: WorksheetLine/TaxUncommitted_IN (this entity)  

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
