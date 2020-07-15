---
title: AssetDocumentAcceleratedDepTable_JP in WorksheetHeader - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 7/15/2020
ms.author: nebanfic
---

# Document table for accelerated depreciation in WorksheetHeader(AssetDocumentAcceleratedDepTable_JP)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Tables/Finance/FixedAssets/WorksheetHeader/AssetDocumentAcceleratedDepTable_JP.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[AssetDocumentAcceleratedDepTable_JP/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Document table for accelerated depreciation</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="AssetDocumentAcceleratedDepTable_JP.md" target="_blank">WorksheetHeader/AssetDocumentAcceleratedDepTable_JP</a>|
|[AssetAcceleratedDepGroup_JP](#AssetAcceleratedDepGroup_JP)||<a href="AssetDocumentAcceleratedDepTable_JP.md" target="_blank">WorksheetHeader/AssetDocumentAcceleratedDepTable_JP</a>|
|[AssetDocumentTable_JP](#AssetDocumentTable_JP)||<a href="AssetDocumentAcceleratedDepTable_JP.md" target="_blank">WorksheetHeader/AssetDocumentAcceleratedDepTable_JP</a>|
|[DocumentId](#DocumentId)||<a href="AssetDocumentAcceleratedDepTable_JP.md" target="_blank">WorksheetHeader/AssetDocumentAcceleratedDepTable_JP</a>|
|[OperationDaysPerYear](#OperationDaysPerYear)||<a href="AssetDocumentAcceleratedDepTable_JP.md" target="_blank">WorksheetHeader/AssetDocumentAcceleratedDepTable_JP</a>|
|[ValidFrom](#ValidFrom)||<a href="AssetDocumentAcceleratedDepTable_JP.md" target="_blank">WorksheetHeader/AssetDocumentAcceleratedDepTable_JP</a>|
|[ValidTo](#ValidTo)||<a href="AssetDocumentAcceleratedDepTable_JP.md" target="_blank">WorksheetHeader/AssetDocumentAcceleratedDepTable_JP</a>|
|[Description](#Description)||<a href="AssetDocumentAcceleratedDepTable_JP.md" target="_blank">WorksheetHeader/AssetDocumentAcceleratedDepTable_JP</a>|
|[Status](#Status)||<a href="AssetDocumentAcceleratedDepTable_JP.md" target="_blank">WorksheetHeader/AssetDocumentAcceleratedDepTable_JP</a>|
|[CalculationMethod](#CalculationMethod)||<a href="AssetDocumentAcceleratedDepTable_JP.md" target="_blank">WorksheetHeader/AssetDocumentAcceleratedDepTable_JP</a>|
|[AverageHours](#AverageHours)||<a href="AssetDocumentAcceleratedDepTable_JP.md" target="_blank">WorksheetHeader/AssetDocumentAcceleratedDepTable_JP</a>|
|[AssetLocation](#AssetLocation)||<a href="AssetDocumentAcceleratedDepTable_JP.md" target="_blank">WorksheetHeader/AssetDocumentAcceleratedDepTable_JP</a>|
|[TotalOveruseHours](#TotalOveruseHours)||<a href="AssetDocumentAcceleratedDepTable_JP.md" target="_blank">WorksheetHeader/AssetDocumentAcceleratedDepTable_JP</a>|
|[AverageOveruseHours](#AverageOveruseHours)||<a href="AssetDocumentAcceleratedDepTable_JP.md" target="_blank">WorksheetHeader/AssetDocumentAcceleratedDepTable_JP</a>|
|[RateFactor](#RateFactor)||<a href="AssetDocumentAcceleratedDepTable_JP.md" target="_blank">WorksheetHeader/AssetDocumentAcceleratedDepTable_JP</a>|
|[OveruseRate](#OveruseRate)||<a href="AssetDocumentAcceleratedDepTable_JP.md" target="_blank">WorksheetHeader/AssetDocumentAcceleratedDepTable_JP</a>|
|[ReportPrintDate](#ReportPrintDate)||<a href="AssetDocumentAcceleratedDepTable_JP.md" target="_blank">WorksheetHeader/AssetDocumentAcceleratedDepTable_JP</a>|
|[LegalRepresentativeName](#LegalRepresentativeName)||<a href="AssetDocumentAcceleratedDepTable_JP.md" target="_blank">WorksheetHeader/AssetDocumentAcceleratedDepTable_JP</a>|
|[ReasonComment](#ReasonComment)||<a href="AssetDocumentAcceleratedDepTable_JP.md" target="_blank">WorksheetHeader/AssetDocumentAcceleratedDepTable_JP</a>|
|[AccountantName](#AccountantName)||<a href="AssetDocumentAcceleratedDepTable_JP.md" target="_blank">WorksheetHeader/AssetDocumentAcceleratedDepTable_JP</a>|
|[LegalRepresentativeAddress](#LegalRepresentativeAddress)||<a href="AssetDocumentAcceleratedDepTable_JP.md" target="_blank">WorksheetHeader/AssetDocumentAcceleratedDepTable_JP</a>|
|[ReferenceDocument](#ReferenceDocument)||<a href="AssetDocumentAcceleratedDepTable_JP.md" target="_blank">WorksheetHeader/AssetDocumentAcceleratedDepTable_JP</a>|
|[RateThreshold](#RateThreshold)||<a href="AssetDocumentAcceleratedDepTable_JP.md" target="_blank">WorksheetHeader/AssetDocumentAcceleratedDepTable_JP</a>|
|[CurrentOperationsTax](#CurrentOperationsTax)||<a href="AssetDocumentAcceleratedDepTable_JP.md" target="_blank">WorksheetHeader/AssetDocumentAcceleratedDepTable_JP</a>|
|[DataAreaId](#DataAreaId)||<a href="AssetDocumentAcceleratedDepTable_JP.md" target="_blank">WorksheetHeader/AssetDocumentAcceleratedDepTable_JP</a>|
|[Relationship_AssetAcceleratedDepGroup_JPRelationshipId](#Relationship_AssetAcceleratedDepGroup_JPRelationshipId)||<a href="AssetDocumentAcceleratedDepTable_JP.md" target="_blank">WorksheetHeader/AssetDocumentAcceleratedDepTable_JP</a>|
|[Relationship_AssetDocumentTable_JPRelationshipId](#Relationship_AssetDocumentTable_JPRelationshipId)||<a href="AssetDocumentAcceleratedDepTable_JP.md" target="_blank">WorksheetHeader/AssetDocumentAcceleratedDepTable_JP</a>|
|[Relationship_CompanyRelationshipId](#Relationship_CompanyRelationshipId)||<a href="AssetDocumentAcceleratedDepTable_JP.md" target="_blank">WorksheetHeader/AssetDocumentAcceleratedDepTable_JP</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: WorksheetHeader/AssetDocumentAcceleratedDepTable_JP (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[AssetDocumentAcceleratedDepTable_JP/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#AssetAcceleratedDepGroup_JP name="AssetAcceleratedDepGroup_JP">AssetAcceleratedDepGroup_JP</a>

First included in: WorksheetHeader/AssetDocumentAcceleratedDepTable_JP (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AssetAcceleratedDepGroup_JP attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#AssetDocumentTable_JP name="AssetDocumentTable_JP">AssetDocumentTable_JP</a>

First included in: WorksheetHeader/AssetDocumentAcceleratedDepTable_JP (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AssetDocumentTable_JP attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#DocumentId name="DocumentId">DocumentId</a>

First included in: WorksheetHeader/AssetDocumentAcceleratedDepTable_JP (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Document ID</td></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DocumentId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Document ID</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#OperationDaysPerYear name="OperationDaysPerYear">OperationDaysPerYear</a>

First included in: WorksheetHeader/AssetDocumentAcceleratedDepTable_JP (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OperationDaysPerYear attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#ValidFrom name="ValidFrom">ValidFrom</a>

First included in: WorksheetHeader/AssetDocumentAcceleratedDepTable_JP (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>From date</td></tr><tr><td>dataFormat</td><td>date</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ValidFrom attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>From date</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.date**  
</details>

### <a href=#ValidTo name="ValidTo">ValidTo</a>

First included in: WorksheetHeader/AssetDocumentAcceleratedDepTable_JP (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>To date</td></tr><tr><td>dataFormat</td><td>date</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ValidTo attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>To date</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.date**  
</details>

### <a href=#Description name="Description">Description</a>

First included in: WorksheetHeader/AssetDocumentAcceleratedDepTable_JP (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Description</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Description attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Description</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Status name="Status">Status</a>

First included in: WorksheetHeader/AssetDocumentAcceleratedDepTable_JP (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Status attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.readOnly**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#CalculationMethod name="CalculationMethod">CalculationMethod</a>

First included in: WorksheetHeader/AssetDocumentAcceleratedDepTable_JP (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CalculationMethod attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#AverageHours name="AverageHours">AverageHours</a>

First included in: WorksheetHeader/AssetDocumentAcceleratedDepTable_JP (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AverageHours attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#AssetLocation name="AssetLocation">AssetLocation</a>

First included in: WorksheetHeader/AssetDocumentAcceleratedDepTable_JP (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AssetLocation attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TotalOveruseHours name="TotalOveruseHours">TotalOveruseHours</a>

First included in: WorksheetHeader/AssetDocumentAcceleratedDepTable_JP (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Total overuse hours</td></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TotalOveruseHours attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Total overuse hours</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#AverageOveruseHours name="AverageOveruseHours">AverageOveruseHours</a>

First included in: WorksheetHeader/AssetDocumentAcceleratedDepTable_JP (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Overuse hours per day</td></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AverageOveruseHours attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Overuse hours per day</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#RateFactor name="RateFactor">RateFactor</a>

First included in: WorksheetHeader/AssetDocumentAcceleratedDepTable_JP (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Rate factor</td></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RateFactor attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Rate factor</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#OveruseRate name="OveruseRate">OveruseRate</a>

First included in: WorksheetHeader/AssetDocumentAcceleratedDepTable_JP (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Overuse rate</td></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OveruseRate attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Overuse rate</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#ReportPrintDate name="ReportPrintDate">ReportPrintDate</a>

First included in: WorksheetHeader/AssetDocumentAcceleratedDepTable_JP (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Report printing date</td></tr><tr><td>dataFormat</td><td>date</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReportPrintDate attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Report printing date</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.date**  
</details>

### <a href=#LegalRepresentativeName name="LegalRepresentativeName">LegalRepresentativeName</a>

First included in: WorksheetHeader/AssetDocumentAcceleratedDepTable_JP (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LegalRepresentativeName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ReasonComment name="ReasonComment">ReasonComment</a>

First included in: WorksheetHeader/AssetDocumentAcceleratedDepTable_JP (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Reason for exceeding operation hours</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReasonComment attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Reason for exceeding operation hours</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AccountantName name="AccountantName">AccountantName</a>

First included in: WorksheetHeader/AssetDocumentAcceleratedDepTable_JP (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Name of tax accountant</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AccountantName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Name of tax accountant</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LegalRepresentativeAddress name="LegalRepresentativeAddress">LegalRepresentativeAddress</a>

First included in: WorksheetHeader/AssetDocumentAcceleratedDepTable_JP (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Legal representative address</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LegalRepresentativeAddress attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Legal representative address</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ReferenceDocument name="ReferenceDocument">ReferenceDocument</a>

First included in: WorksheetHeader/AssetDocumentAcceleratedDepTable_JP (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Reference document details</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReferenceDocument attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Reference document details</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RateThreshold name="RateThreshold">RateThreshold</a>

First included in: WorksheetHeader/AssetDocumentAcceleratedDepTable_JP (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Rate threshold</td></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RateThreshold attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Rate threshold</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#CurrentOperationsTax name="CurrentOperationsTax">CurrentOperationsTax</a>

First included in: WorksheetHeader/AssetDocumentAcceleratedDepTable_JP (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CurrentOperationsTax attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#DataAreaId name="DataAreaId">DataAreaId</a>

First included in: WorksheetHeader/AssetDocumentAcceleratedDepTable_JP (this entity)  

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

### <a href=#Relationship_AssetAcceleratedDepGroup_JPRelationshipId name="Relationship_AssetAcceleratedDepGroup_JPRelationshipId">Relationship_AssetAcceleratedDepGroup_JPRelationshipId</a>

First included in: WorksheetHeader/AssetDocumentAcceleratedDepTable_JP (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_AssetAcceleratedDepGroup_JPRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Group/AssetAcceleratedDepGroup_JP.md" target="_blank">/core/operationsCommon/Tables/Finance/FixedAssets/Group/AssetAcceleratedDepGroup_JP.cdm.json/AssetAcceleratedDepGroup_JP</a></td><td><a href="../Group/AssetAcceleratedDepGroup_JP.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_AssetDocumentTable_JPRelationshipId name="Relationship_AssetDocumentTable_JPRelationshipId">Relationship_AssetDocumentTable_JPRelationshipId</a>

First included in: WorksheetHeader/AssetDocumentAcceleratedDepTable_JP (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_AssetDocumentTable_JPRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="AssetDocumentTable_JP.md" target="_blank">/core/operationsCommon/Tables/Finance/FixedAssets/WorksheetHeader/AssetDocumentTable_JP.cdm.json/AssetDocumentTable_JP</a></td><td><a href="AssetDocumentTable_JP.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_CompanyRelationshipId name="Relationship_CompanyRelationshipId">Relationship_CompanyRelationshipId</a>

First included in: WorksheetHeader/AssetDocumentAcceleratedDepTable_JP (this entity)  

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
