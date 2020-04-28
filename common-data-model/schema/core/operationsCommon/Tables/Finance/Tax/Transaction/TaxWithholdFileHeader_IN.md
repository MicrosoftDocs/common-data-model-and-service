---
title: TaxWithholdFileHeader_IN - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/28/2020
ms.author: nebanfic
---

# Lines

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Tables/Finance/Tax/Transaction/TaxWithholdFileHeader_IN.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[TaxWithholdFileHeader_IN/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Lines</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="TaxWithholdFileHeader_IN.md" target="_blank">Transaction/TaxWithholdFileHeader_IN</a>|
|[AssesmentYear](#AssesmentYear)||<a href="TaxWithholdFileHeader_IN.md" target="_blank">Transaction/TaxWithholdFileHeader_IN</a>|
|[CorrectionFile](#CorrectionFile)||<a href="TaxWithholdFileHeader_IN.md" target="_blank">Transaction/TaxWithholdFileHeader_IN</a>|
|[FileCreationDate](#FileCreationDate)||<a href="TaxWithholdFileHeader_IN.md" target="_blank">Transaction/TaxWithholdFileHeader_IN</a>|
|[FileSequenceNumber](#FileSequenceNumber)||<a href="TaxWithholdFileHeader_IN.md" target="_blank">Transaction/TaxWithholdFileHeader_IN</a>|
|[FinancialYear](#FinancialYear)||<a href="TaxWithholdFileHeader_IN.md" target="_blank">Transaction/TaxWithholdFileHeader_IN</a>|
|[FormNumber](#FormNumber)||<a href="TaxWithholdFileHeader_IN.md" target="_blank">Transaction/TaxWithholdFileHeader_IN</a>|
|[FromDate](#FromDate)||<a href="TaxWithholdFileHeader_IN.md" target="_blank">Transaction/TaxWithholdFileHeader_IN</a>|
|[TaxWithholdRegNumber](#TaxWithholdRegNumber)||<a href="TaxWithholdFileHeader_IN.md" target="_blank">Transaction/TaxWithholdFileHeader_IN</a>|
|[ToDate](#ToDate)||<a href="TaxWithholdFileHeader_IN.md" target="_blank">Transaction/TaxWithholdFileHeader_IN</a>|
|[TotalBatches](#TotalBatches)||<a href="TaxWithholdFileHeader_IN.md" target="_blank">Transaction/TaxWithholdFileHeader_IN</a>|
|[DataAreaId](#DataAreaId)||<a href="TaxWithholdFileHeader_IN.md" target="_blank">Transaction/TaxWithholdFileHeader_IN</a>|
|[Relationship_TaxWithholdRegNumberRelationshipId](#Relationship_TaxWithholdRegNumberRelationshipId)||<a href="TaxWithholdFileHeader_IN.md" target="_blank">Transaction/TaxWithholdFileHeader_IN</a>|
|[Relationship_CompanyRelationshipId](#Relationship_CompanyRelationshipId)||<a href="TaxWithholdFileHeader_IN.md" target="_blank">Transaction/TaxWithholdFileHeader_IN</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: Transaction/TaxWithholdFileHeader_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[TaxWithholdFileHeader_IN/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#AssesmentYear name="AssesmentYear">AssesmentYear</a>

First included in: Transaction/TaxWithholdFileHeader_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AssesmentYear attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CorrectionFile name="CorrectionFile">CorrectionFile</a>

First included in: Transaction/TaxWithholdFileHeader_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CorrectionFile attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#FileCreationDate name="FileCreationDate">FileCreationDate</a>

First included in: Transaction/TaxWithholdFileHeader_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FileCreationDate attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.dataFormat.date**  
</details>

### <a href=#FileSequenceNumber name="FileSequenceNumber">FileSequenceNumber</a>

First included in: Transaction/TaxWithholdFileHeader_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FileSequenceNumber attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#FinancialYear name="FinancialYear">FinancialYear</a>

First included in: Transaction/TaxWithholdFileHeader_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FinancialYear attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FormNumber name="FormNumber">FormNumber</a>

First included in: Transaction/TaxWithholdFileHeader_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FormNumber attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#FromDate name="FromDate">FromDate</a>

First included in: Transaction/TaxWithholdFileHeader_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FromDate attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.dataFormat.date**  
</details>

### <a href=#TaxWithholdRegNumber name="TaxWithholdRegNumber">TaxWithholdRegNumber</a>

First included in: Transaction/TaxWithholdFileHeader_IN (this entity)  

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

First included in: Transaction/TaxWithholdFileHeader_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ToDate attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.dataFormat.date**  
</details>

### <a href=#TotalBatches name="TotalBatches">TotalBatches</a>

First included in: Transaction/TaxWithholdFileHeader_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TotalBatches attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#DataAreaId name="DataAreaId">DataAreaId</a>

First included in: Transaction/TaxWithholdFileHeader_IN (this entity)  

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

### <a href=#Relationship_TaxWithholdRegNumberRelationshipId name="Relationship_TaxWithholdRegNumberRelationshipId">Relationship_TaxWithholdRegNumberRelationshipId</a>

First included in: Transaction/TaxWithholdFileHeader_IN (this entity)  

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

### <a href=#Relationship_CompanyRelationshipId name="Relationship_CompanyRelationshipId">Relationship_CompanyRelationshipId</a>

First included in: Transaction/TaxWithholdFileHeader_IN (this entity)  

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
