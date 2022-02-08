---
title: TaxWithholdBatchHeader_IN in Transaction - Common Data Model | Microsoft Docs
description: undefined
author: llawwaii
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: reference
ms.date: 8/7/2020
ms.author: weiluo
---

# Header in Transaction(TaxWithholdBatchHeader_IN)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Tables/Finance/Tax/Transaction/TaxWithholdBatchHeader_IN.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[TaxWithholdBatchHeader_IN/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.1"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Header</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="TaxWithholdBatchHeader_IN.md" target="_blank">Transaction/TaxWithholdBatchHeader_IN</a>|
|[BatchRecordNumber](#BatchRecordNumber)||<a href="TaxWithholdBatchHeader_IN.md" target="_blank">Transaction/TaxWithholdBatchHeader_IN</a>|
|[CorrectionType](#CorrectionType)||<a href="TaxWithholdBatchHeader_IN.md" target="_blank">Transaction/TaxWithholdBatchHeader_IN</a>|
|[DeductorAddress](#DeductorAddress)||<a href="TaxWithholdBatchHeader_IN.md" target="_blank">Transaction/TaxWithholdBatchHeader_IN</a>|
|[DeductorBranchId](#DeductorBranchId)||<a href="TaxWithholdBatchHeader_IN.md" target="_blank">Transaction/TaxWithholdBatchHeader_IN</a>|
|[DeductorChangeOfAddress](#DeductorChangeOfAddress)||<a href="TaxWithholdBatchHeader_IN.md" target="_blank">Transaction/TaxWithholdBatchHeader_IN</a>|
|[DeductorEmail](#DeductorEmail)||<a href="TaxWithholdBatchHeader_IN.md" target="_blank">Transaction/TaxWithholdBatchHeader_IN</a>|
|[DeductorName](#DeductorName)||<a href="TaxWithholdBatchHeader_IN.md" target="_blank">Transaction/TaxWithholdBatchHeader_IN</a>|
|[DeductorStateCode](#DeductorStateCode)||<a href="TaxWithholdBatchHeader_IN.md" target="_blank">Transaction/TaxWithholdBatchHeader_IN</a>|
|[DeductorTelePhone](#DeductorTelePhone)||<a href="TaxWithholdBatchHeader_IN.md" target="_blank">Transaction/TaxWithholdBatchHeader_IN</a>|
|[DeductorType](#DeductorType)||<a href="TaxWithholdBatchHeader_IN.md" target="_blank">Transaction/TaxWithholdBatchHeader_IN</a>|
|[DeliveyLocation](#DeliveyLocation)||<a href="TaxWithholdBatchHeader_IN.md" target="_blank">Transaction/TaxWithholdBatchHeader_IN</a>|
|[NilChallanIndicator](#NilChallanIndicator)||<a href="TaxWithholdBatchHeader_IN.md" target="_blank">Transaction/TaxWithholdBatchHeader_IN</a>|
|[PanNumber](#PanNumber)||<a href="TaxWithholdBatchHeader_IN.md" target="_blank">Transaction/TaxWithholdBatchHeader_IN</a>|
|[RecIdFileHdr](#RecIdFileHdr)||<a href="TaxWithholdBatchHeader_IN.md" target="_blank">Transaction/TaxWithholdBatchHeader_IN</a>|
|[ResponsiblePersonAddress](#ResponsiblePersonAddress)||<a href="TaxWithholdBatchHeader_IN.md" target="_blank">Transaction/TaxWithholdBatchHeader_IN</a>|
|[ResponsiblePersonChangeOfAddress](#ResponsiblePersonChangeOfAddress)||<a href="TaxWithholdBatchHeader_IN.md" target="_blank">Transaction/TaxWithholdBatchHeader_IN</a>|
|[ResponsiblePersonEmail](#ResponsiblePersonEmail)||<a href="TaxWithholdBatchHeader_IN.md" target="_blank">Transaction/TaxWithholdBatchHeader_IN</a>|
|[ResponsiblePersonsDesignation](#ResponsiblePersonsDesignation)||<a href="TaxWithholdBatchHeader_IN.md" target="_blank">Transaction/TaxWithholdBatchHeader_IN</a>|
|[ResponsiblePersonsName](#ResponsiblePersonsName)||<a href="TaxWithholdBatchHeader_IN.md" target="_blank">Transaction/TaxWithholdBatchHeader_IN</a>|
|[ResponsiblePersonStateCode](#ResponsiblePersonStateCode)||<a href="TaxWithholdBatchHeader_IN.md" target="_blank">Transaction/TaxWithholdBatchHeader_IN</a>|
|[ResponsiblePersonTelePhone](#ResponsiblePersonTelePhone)||<a href="TaxWithholdBatchHeader_IN.md" target="_blank">Transaction/TaxWithholdBatchHeader_IN</a>|
|[RRROriginal](#RRROriginal)||<a href="TaxWithholdBatchHeader_IN.md" target="_blank">Transaction/TaxWithholdBatchHeader_IN</a>|
|[RRRPrevious](#RRRPrevious)||<a href="TaxWithholdBatchHeader_IN.md" target="_blank">Transaction/TaxWithholdBatchHeader_IN</a>|
|[TaxWithholdRegNumber](#TaxWithholdRegNumber)||<a href="TaxWithholdBatchHeader_IN.md" target="_blank">Transaction/TaxWithholdBatchHeader_IN</a>|
|[TaxWithholdRegNumberPrevious](#TaxWithholdRegNumberPrevious)||<a href="TaxWithholdBatchHeader_IN.md" target="_blank">Transaction/TaxWithholdBatchHeader_IN</a>|
|[DataAreaId](#DataAreaId)||<a href="TaxWithholdBatchHeader_IN.md" target="_blank">Transaction/TaxWithholdBatchHeader_IN</a>|
|[Relationship_DeliveyLocationRelationshipId](#Relationship_DeliveyLocationRelationshipId)||<a href="TaxWithholdBatchHeader_IN.md" target="_blank">Transaction/TaxWithholdBatchHeader_IN</a>|
|[Relationship_TaxWithholdFileHeaderRelationshipId](#Relationship_TaxWithholdFileHeaderRelationshipId)||<a href="TaxWithholdBatchHeader_IN.md" target="_blank">Transaction/TaxWithholdBatchHeader_IN</a>|
|[Relationship_TaxWithholdRegNumberRelationshipId](#Relationship_TaxWithholdRegNumberRelationshipId)||<a href="TaxWithholdBatchHeader_IN.md" target="_blank">Transaction/TaxWithholdBatchHeader_IN</a>|
|[Relationship_TaxWithholdRegNumberPreviousRelationshipId](#Relationship_TaxWithholdRegNumberPreviousRelationshipId)||<a href="TaxWithholdBatchHeader_IN.md" target="_blank">Transaction/TaxWithholdBatchHeader_IN</a>|
|[Relationship_CompanyRelationshipId](#Relationship_CompanyRelationshipId)||<a href="TaxWithholdBatchHeader_IN.md" target="_blank">Transaction/TaxWithholdBatchHeader_IN</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: Transaction/TaxWithholdBatchHeader_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[TaxWithholdBatchHeader_IN/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#BatchRecordNumber name="BatchRecordNumber">BatchRecordNumber</a>

First included in: Transaction/TaxWithholdBatchHeader_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BatchRecordNumber attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#CorrectionType name="CorrectionType">CorrectionType</a>

First included in: Transaction/TaxWithholdBatchHeader_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CorrectionType attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#DeductorAddress name="DeductorAddress">DeductorAddress</a>

First included in: Transaction/TaxWithholdBatchHeader_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DeductorAddress attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DeductorBranchId name="DeductorBranchId">DeductorBranchId</a>

First included in: Transaction/TaxWithholdBatchHeader_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DeductorBranchId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DeductorChangeOfAddress name="DeductorChangeOfAddress">DeductorChangeOfAddress</a>

First included in: Transaction/TaxWithholdBatchHeader_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Address</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DeductorChangeOfAddress attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Address</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#DeductorEmail name="DeductorEmail">DeductorEmail</a>

First included in: Transaction/TaxWithholdBatchHeader_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DeductorEmail attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DeductorName name="DeductorName">DeductorName</a>

First included in: Transaction/TaxWithholdBatchHeader_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DeductorName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DeductorStateCode name="DeductorStateCode">DeductorStateCode</a>

First included in: Transaction/TaxWithholdBatchHeader_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DeductorStateCode attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#DeductorTelePhone name="DeductorTelePhone">DeductorTelePhone</a>

First included in: Transaction/TaxWithholdBatchHeader_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DeductorTelePhone attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DeductorType name="DeductorType">DeductorType</a>

First included in: Transaction/TaxWithholdBatchHeader_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Status</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DeductorType attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Status</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#DeliveyLocation name="DeliveyLocation">DeliveyLocation</a>

First included in: Transaction/TaxWithholdBatchHeader_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DeliveyLocation attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#NilChallanIndicator name="NilChallanIndicator">NilChallanIndicator</a>

First included in: Transaction/TaxWithholdBatchHeader_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the NilChallanIndicator attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#PanNumber name="PanNumber">PanNumber</a>

First included in: Transaction/TaxWithholdBatchHeader_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PanNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RecIdFileHdr name="RecIdFileHdr">RecIdFileHdr</a>

First included in: Transaction/TaxWithholdBatchHeader_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecIdFileHdr attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#ResponsiblePersonAddress name="ResponsiblePersonAddress">ResponsiblePersonAddress</a>

First included in: Transaction/TaxWithholdBatchHeader_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ResponsiblePersonAddress attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ResponsiblePersonChangeOfAddress name="ResponsiblePersonChangeOfAddress">ResponsiblePersonChangeOfAddress</a>

First included in: Transaction/TaxWithholdBatchHeader_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Address</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ResponsiblePersonChangeOfAddress attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Address</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#ResponsiblePersonEmail name="ResponsiblePersonEmail">ResponsiblePersonEmail</a>

First included in: Transaction/TaxWithholdBatchHeader_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ResponsiblePersonEmail attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ResponsiblePersonsDesignation name="ResponsiblePersonsDesignation">ResponsiblePersonsDesignation</a>

First included in: Transaction/TaxWithholdBatchHeader_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ResponsiblePersonsDesignation attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ResponsiblePersonsName name="ResponsiblePersonsName">ResponsiblePersonsName</a>

First included in: Transaction/TaxWithholdBatchHeader_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ResponsiblePersonsName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ResponsiblePersonStateCode name="ResponsiblePersonStateCode">ResponsiblePersonStateCode</a>

First included in: Transaction/TaxWithholdBatchHeader_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ResponsiblePersonStateCode attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#ResponsiblePersonTelePhone name="ResponsiblePersonTelePhone">ResponsiblePersonTelePhone</a>

First included in: Transaction/TaxWithholdBatchHeader_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ResponsiblePersonTelePhone attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RRROriginal name="RRROriginal">RRROriginal</a>

First included in: Transaction/TaxWithholdBatchHeader_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RRROriginal attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RRRPrevious name="RRRPrevious">RRRPrevious</a>

First included in: Transaction/TaxWithholdBatchHeader_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RRRPrevious attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TaxWithholdRegNumber name="TaxWithholdRegNumber">TaxWithholdRegNumber</a>

First included in: Transaction/TaxWithholdBatchHeader_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxWithholdRegNumber attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#TaxWithholdRegNumberPrevious name="TaxWithholdRegNumberPrevious">TaxWithholdRegNumberPrevious</a>

First included in: Transaction/TaxWithholdBatchHeader_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxWithholdRegNumberPrevious attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#DataAreaId name="DataAreaId">DataAreaId</a>

First included in: Transaction/TaxWithholdBatchHeader_IN (this entity)  

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

### <a href=#Relationship_DeliveyLocationRelationshipId name="Relationship_DeliveyLocationRelationshipId">Relationship_DeliveyLocationRelationshipId</a>

First included in: Transaction/TaxWithholdBatchHeader_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_DeliveyLocationRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Common/GAB/Main/LogisticsPostalAddress.md" target="_blank">/core/operationsCommon/Tables/Common/GAB/Main/LogisticsPostalAddress.cdm.json/LogisticsPostalAddress</a></td><td><a href="../../../Common/GAB/Main/LogisticsPostalAddress.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_TaxWithholdFileHeaderRelationshipId name="Relationship_TaxWithholdFileHeaderRelationshipId">Relationship_TaxWithholdFileHeaderRelationshipId</a>

First included in: Transaction/TaxWithholdBatchHeader_IN (this entity)  

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

First included in: Transaction/TaxWithholdBatchHeader_IN (this entity)  

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

### <a href=#Relationship_TaxWithholdRegNumberPreviousRelationshipId name="Relationship_TaxWithholdRegNumberPreviousRelationshipId">Relationship_TaxWithholdRegNumberPreviousRelationshipId</a>

First included in: Transaction/TaxWithholdBatchHeader_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_TaxWithholdRegNumberPreviousRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_CompanyRelationshipId name="Relationship_CompanyRelationshipId">Relationship_CompanyRelationshipId</a>

First included in: Transaction/TaxWithholdBatchHeader_IN (this entity)  

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
