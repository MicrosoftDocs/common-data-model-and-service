---
title: AssetImpairmentTestResultDocEntry_JP in WorksheetLine - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 7/8/2020
ms.author: nebanfic
---

# Asset impairment test result line in WorksheetLine(AssetImpairmentTestResultDocEntry_JP)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Tables/Finance/FixedAssets/WorksheetLine/AssetImpairmentTestResultDocEntry_JP.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[AssetImpairmentTestResultDocEntry_JP/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Asset impairment test result line</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="AssetImpairmentTestResultDocEntry_JP.md" target="_blank">WorksheetLine/AssetImpairmentTestResultDocEntry_JP</a>|
|[AccDepreciation](#AccDepreciation)||<a href="AssetImpairmentTestResultDocEntry_JP.md" target="_blank">WorksheetLine/AssetImpairmentTestResultDocEntry_JP</a>|
|[AcquisitionPrice](#AcquisitionPrice)||<a href="AssetImpairmentTestResultDocEntry_JP.md" target="_blank">WorksheetLine/AssetImpairmentTestResultDocEntry_JP</a>|
|[AllocationPriority](#AllocationPriority)||<a href="AssetImpairmentTestResultDocEntry_JP.md" target="_blank">WorksheetLine/AssetImpairmentTestResultDocEntry_JP</a>|
|[AssetDocumentEntry_JP](#AssetDocumentEntry_JP)||<a href="AssetImpairmentTestResultDocEntry_JP.md" target="_blank">WorksheetLine/AssetImpairmentTestResultDocEntry_JP</a>|
|[ExpectedScrapValue](#ExpectedScrapValue)||<a href="AssetImpairmentTestResultDocEntry_JP.md" target="_blank">WorksheetLine/AssetImpairmentTestResultDocEntry_JP</a>|
|[FairValue](#FairValue)||<a href="AssetImpairmentTestResultDocEntry_JP.md" target="_blank">WorksheetLine/AssetImpairmentTestResultDocEntry_JP</a>|
|[HoldingEntry](#HoldingEntry)||<a href="AssetImpairmentTestResultDocEntry_JP.md" target="_blank">WorksheetLine/AssetImpairmentTestResultDocEntry_JP</a>|
|[Impairment](#Impairment)||<a href="AssetImpairmentTestResultDocEntry_JP.md" target="_blank">WorksheetLine/AssetImpairmentTestResultDocEntry_JP</a>|
|[ImpairmentAdjustment](#ImpairmentAdjustment)||<a href="AssetImpairmentTestResultDocEntry_JP.md" target="_blank">WorksheetLine/AssetImpairmentTestResultDocEntry_JP</a>|
|[ImpairmentAllocationMethod](#ImpairmentAllocationMethod)||<a href="AssetImpairmentTestResultDocEntry_JP.md" target="_blank">WorksheetLine/AssetImpairmentTestResultDocEntry_JP</a>|
|[ImpairmentAmtCalculated](#ImpairmentAmtCalculated)||<a href="AssetImpairmentTestResultDocEntry_JP.md" target="_blank">WorksheetLine/AssetImpairmentTestResultDocEntry_JP</a>|
|[ImpairmentAmtFrom](#ImpairmentAmtFrom)||<a href="AssetImpairmentTestResultDocEntry_JP.md" target="_blank">WorksheetLine/AssetImpairmentTestResultDocEntry_JP</a>|
|[ImpairmentAmtTo](#ImpairmentAmtTo)||<a href="AssetImpairmentTestResultDocEntry_JP.md" target="_blank">WorksheetLine/AssetImpairmentTestResultDocEntry_JP</a>|
|[IsSharedAsset](#IsSharedAsset)||<a href="AssetImpairmentTestResultDocEntry_JP.md" target="_blank">WorksheetLine/AssetImpairmentTestResultDocEntry_JP</a>|
|[NetBookValue](#NetBookValue)||<a href="AssetImpairmentTestResultDocEntry_JP.md" target="_blank">WorksheetLine/AssetImpairmentTestResultDocEntry_JP</a>|
|[NetSellingPrice](#NetSellingPrice)||<a href="AssetImpairmentTestResultDocEntry_JP.md" target="_blank">WorksheetLine/AssetImpairmentTestResultDocEntry_JP</a>|
|[Percent](#Percent)||<a href="AssetImpairmentTestResultDocEntry_JP.md" target="_blank">WorksheetLine/AssetImpairmentTestResultDocEntry_JP</a>|
|[ProrationMethodOverride](#ProrationMethodOverride)||<a href="AssetImpairmentTestResultDocEntry_JP.md" target="_blank">WorksheetLine/AssetImpairmentTestResultDocEntry_JP</a>|
|[RecoverableAmountRef](#RecoverableAmountRef)||<a href="AssetImpairmentTestResultDocEntry_JP.md" target="_blank">WorksheetLine/AssetImpairmentTestResultDocEntry_JP</a>|
|[ResultDocument](#ResultDocument)||<a href="AssetImpairmentTestResultDocEntry_JP.md" target="_blank">WorksheetLine/AssetImpairmentTestResultDocEntry_JP</a>|
|[SharedAssetType](#SharedAssetType)||<a href="AssetImpairmentTestResultDocEntry_JP.md" target="_blank">WorksheetLine/AssetImpairmentTestResultDocEntry_JP</a>|
|[Status](#Status)||<a href="AssetImpairmentTestResultDocEntry_JP.md" target="_blank">WorksheetLine/AssetImpairmentTestResultDocEntry_JP</a>|
|[UndiscountedCashFlowRef](#UndiscountedCashFlowRef)||<a href="AssetImpairmentTestResultDocEntry_JP.md" target="_blank">WorksheetLine/AssetImpairmentTestResultDocEntry_JP</a>|
|[DataAreaId](#DataAreaId)||<a href="AssetImpairmentTestResultDocEntry_JP.md" target="_blank">WorksheetLine/AssetImpairmentTestResultDocEntry_JP</a>|
|[Relationship_AssetDocumentEntry_JPRelationshipId](#Relationship_AssetDocumentEntry_JPRelationshipId)||<a href="AssetImpairmentTestResultDocEntry_JP.md" target="_blank">WorksheetLine/AssetImpairmentTestResultDocEntry_JP</a>|
|[Relationship_RecoverableAmountRefRelationshipId](#Relationship_RecoverableAmountRefRelationshipId)||<a href="AssetImpairmentTestResultDocEntry_JP.md" target="_blank">WorksheetLine/AssetImpairmentTestResultDocEntry_JP</a>|
|[Relationship_TestResultDocumentRelationshipId](#Relationship_TestResultDocumentRelationshipId)||<a href="AssetImpairmentTestResultDocEntry_JP.md" target="_blank">WorksheetLine/AssetImpairmentTestResultDocEntry_JP</a>|
|[Relationship_UndiscountedCashFlowRefRelationshipId](#Relationship_UndiscountedCashFlowRefRelationshipId)||<a href="AssetImpairmentTestResultDocEntry_JP.md" target="_blank">WorksheetLine/AssetImpairmentTestResultDocEntry_JP</a>|
|[Relationship_CompanyRelationshipId](#Relationship_CompanyRelationshipId)||<a href="AssetImpairmentTestResultDocEntry_JP.md" target="_blank">WorksheetLine/AssetImpairmentTestResultDocEntry_JP</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: WorksheetLine/AssetImpairmentTestResultDocEntry_JP (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[AssetImpairmentTestResultDocEntry_JP/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#AccDepreciation name="AccDepreciation">AccDepreciation</a>

First included in: WorksheetLine/AssetImpairmentTestResultDocEntry_JP (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Accumulated depreciation</td></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AccDepreciation attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Accumulated depreciation</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#AcquisitionPrice name="AcquisitionPrice">AcquisitionPrice</a>

First included in: WorksheetLine/AssetImpairmentTestResultDocEntry_JP (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AcquisitionPrice attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#AllocationPriority name="AllocationPriority">AllocationPriority</a>

First included in: WorksheetLine/AssetImpairmentTestResultDocEntry_JP (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AllocationPriority attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#AssetDocumentEntry_JP name="AssetDocumentEntry_JP">AssetDocumentEntry_JP</a>

First included in: WorksheetLine/AssetImpairmentTestResultDocEntry_JP (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AssetDocumentEntry_JP attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#ExpectedScrapValue name="ExpectedScrapValue">ExpectedScrapValue</a>

First included in: WorksheetLine/AssetImpairmentTestResultDocEntry_JP (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ExpectedScrapValue attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#FairValue name="FairValue">FairValue</a>

First included in: WorksheetLine/AssetImpairmentTestResultDocEntry_JP (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FairValue attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#HoldingEntry name="HoldingEntry">HoldingEntry</a>

First included in: WorksheetLine/AssetImpairmentTestResultDocEntry_JP (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the HoldingEntry attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#Impairment name="Impairment">Impairment</a>

First included in: WorksheetLine/AssetImpairmentTestResultDocEntry_JP (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Impairment attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#ImpairmentAdjustment name="ImpairmentAdjustment">ImpairmentAdjustment</a>

First included in: WorksheetLine/AssetImpairmentTestResultDocEntry_JP (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ImpairmentAdjustment attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#ImpairmentAllocationMethod name="ImpairmentAllocationMethod">ImpairmentAllocationMethod</a>

First included in: WorksheetLine/AssetImpairmentTestResultDocEntry_JP (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ImpairmentAllocationMethod attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#ImpairmentAmtCalculated name="ImpairmentAmtCalculated">ImpairmentAmtCalculated</a>

First included in: WorksheetLine/AssetImpairmentTestResultDocEntry_JP (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Impairment amount after allocation</td></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ImpairmentAmtCalculated attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Impairment amount after allocation</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#ImpairmentAmtFrom name="ImpairmentAmtFrom">ImpairmentAmtFrom</a>

First included in: WorksheetLine/AssetImpairmentTestResultDocEntry_JP (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Impairment amount allocated from other fixed assets</td></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ImpairmentAmtFrom attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Impairment amount allocated from other fixed assets</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#ImpairmentAmtTo name="ImpairmentAmtTo">ImpairmentAmtTo</a>

First included in: WorksheetLine/AssetImpairmentTestResultDocEntry_JP (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Impairment amount allocated to other fixed assets</td></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ImpairmentAmtTo attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Impairment amount allocated to other fixed assets</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#IsSharedAsset name="IsSharedAsset">IsSharedAsset</a>

First included in: WorksheetLine/AssetImpairmentTestResultDocEntry_JP (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsSharedAsset attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#NetBookValue name="NetBookValue">NetBookValue</a>

First included in: WorksheetLine/AssetImpairmentTestResultDocEntry_JP (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the NetBookValue attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#NetSellingPrice name="NetSellingPrice">NetSellingPrice</a>

First included in: WorksheetLine/AssetImpairmentTestResultDocEntry_JP (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Net selling price</td></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the NetSellingPrice attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Net selling price</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#Percent name="Percent">Percent</a>

First included in: WorksheetLine/AssetImpairmentTestResultDocEntry_JP (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Percent attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#ProrationMethodOverride name="ProrationMethodOverride">ProrationMethodOverride</a>

First included in: WorksheetLine/AssetImpairmentTestResultDocEntry_JP (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProrationMethodOverride attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#RecoverableAmountRef name="RecoverableAmountRef">RecoverableAmountRef</a>

First included in: WorksheetLine/AssetImpairmentTestResultDocEntry_JP (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecoverableAmountRef attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#ResultDocument name="ResultDocument">ResultDocument</a>

First included in: WorksheetLine/AssetImpairmentTestResultDocEntry_JP (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ResultDocument attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#SharedAssetType name="SharedAssetType">SharedAssetType</a>

First included in: WorksheetLine/AssetImpairmentTestResultDocEntry_JP (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SharedAssetType attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#Status name="Status">Status</a>

First included in: WorksheetLine/AssetImpairmentTestResultDocEntry_JP (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Status attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#UndiscountedCashFlowRef name="UndiscountedCashFlowRef">UndiscountedCashFlowRef</a>

First included in: WorksheetLine/AssetImpairmentTestResultDocEntry_JP (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the UndiscountedCashFlowRef attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#DataAreaId name="DataAreaId">DataAreaId</a>

First included in: WorksheetLine/AssetImpairmentTestResultDocEntry_JP (this entity)  

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

### <a href=#Relationship_AssetDocumentEntry_JPRelationshipId name="Relationship_AssetDocumentEntry_JPRelationshipId">Relationship_AssetDocumentEntry_JPRelationshipId</a>

First included in: WorksheetLine/AssetImpairmentTestResultDocEntry_JP (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_AssetDocumentEntry_JPRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="AssetDocumentEntry_JP.md" target="_blank">/core/operationsCommon/Tables/Finance/FixedAssets/WorksheetLine/AssetDocumentEntry_JP.cdm.json/AssetDocumentEntry_JP</a></td><td><a href="AssetDocumentEntry_JP.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_RecoverableAmountRefRelationshipId name="Relationship_RecoverableAmountRefRelationshipId">Relationship_RecoverableAmountRefRelationshipId</a>

First included in: WorksheetLine/AssetImpairmentTestResultDocEntry_JP (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_RecoverableAmountRefRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Main/AssetImpairmentIndicator_JP.md" target="_blank">/core/operationsCommon/Tables/Finance/FixedAssets/Main/AssetImpairmentIndicator_JP.cdm.json/AssetImpairmentIndicator_JP</a></td><td><a href="../Main/AssetImpairmentIndicator_JP.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_TestResultDocumentRelationshipId name="Relationship_TestResultDocumentRelationshipId">Relationship_TestResultDocumentRelationshipId</a>

First included in: WorksheetLine/AssetImpairmentTestResultDocEntry_JP (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_TestResultDocumentRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../WorksheetHeader/AssetImpairmentTestResultDocument_JP.md" target="_blank">/core/operationsCommon/Tables/Finance/FixedAssets/WorksheetHeader/AssetImpairmentTestResultDocument_JP.cdm.json/AssetImpairmentTestResultDocument_JP</a></td><td><a href="../WorksheetHeader/AssetImpairmentTestResultDocument_JP.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_UndiscountedCashFlowRefRelationshipId name="Relationship_UndiscountedCashFlowRefRelationshipId">Relationship_UndiscountedCashFlowRefRelationshipId</a>

First included in: WorksheetLine/AssetImpairmentTestResultDocEntry_JP (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_UndiscountedCashFlowRefRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Main/AssetImpairmentIndicator_JP.md" target="_blank">/core/operationsCommon/Tables/Finance/FixedAssets/Main/AssetImpairmentIndicator_JP.cdm.json/AssetImpairmentIndicator_JP</a></td><td><a href="../Main/AssetImpairmentIndicator_JP.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_CompanyRelationshipId name="Relationship_CompanyRelationshipId">Relationship_CompanyRelationshipId</a>

First included in: WorksheetLine/AssetImpairmentTestResultDocEntry_JP (this entity)  

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
