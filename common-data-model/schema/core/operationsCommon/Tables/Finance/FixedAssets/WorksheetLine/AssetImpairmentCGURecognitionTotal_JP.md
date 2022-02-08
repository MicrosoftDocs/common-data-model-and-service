---
title: AssetImpairmentCGURecognitionTotal_JP in WorksheetLine - Common Data Model | Microsoft Docs
description: undefined
author: llawwaii
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: reference
ms.date: 8/7/2020
ms.author: weiluo
---

# Asset impairment test result and document table link table in WorksheetLine(AssetImpairmentCGURecognitionTotal_JP)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Tables/Finance/FixedAssets/WorksheetLine/AssetImpairmentCGURecognitionTotal_JP.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[AssetImpairmentCGURecognitionTotal_JP/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.1"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Asset impairment test result and document table link table</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="AssetImpairmentCGURecognitionTotal_JP.md" target="_blank">WorksheetLine/AssetImpairmentCGURecognitionTotal_JP</a>|
|[AssetImpairmentTestResult_JP](#AssetImpairmentTestResult_JP)||<a href="AssetImpairmentCGURecognitionTotal_JP.md" target="_blank">WorksheetLine/AssetImpairmentCGURecognitionTotal_JP</a>|
|[CGUSubtotalImpairmentAdj](#CGUSubtotalImpairmentAdj)||<a href="AssetImpairmentCGURecognitionTotal_JP.md" target="_blank">WorksheetLine/AssetImpairmentCGURecognitionTotal_JP</a>|
|[CGUSubtotalNbv](#CGUSubtotalNbv)||<a href="AssetImpairmentCGURecognitionTotal_JP.md" target="_blank">WorksheetLine/AssetImpairmentCGURecognitionTotal_JP</a>|
|[CGUSubtotalRecov](#CGUSubtotalRecov)||<a href="AssetImpairmentCGURecognitionTotal_JP.md" target="_blank">WorksheetLine/AssetImpairmentCGURecognitionTotal_JP</a>|
|[CGUSubtotalUndisc](#CGUSubtotalUndisc)||<a href="AssetImpairmentCGURecognitionTotal_JP.md" target="_blank">WorksheetLine/AssetImpairmentCGURecognitionTotal_JP</a>|
|[GrandTotalImpairmentAdj](#GrandTotalImpairmentAdj)||<a href="AssetImpairmentCGURecognitionTotal_JP.md" target="_blank">WorksheetLine/AssetImpairmentCGURecognitionTotal_JP</a>|
|[GrandTotalNbv](#GrandTotalNbv)||<a href="AssetImpairmentCGURecognitionTotal_JP.md" target="_blank">WorksheetLine/AssetImpairmentCGURecognitionTotal_JP</a>|
|[GrandTotalRecov](#GrandTotalRecov)||<a href="AssetImpairmentCGURecognitionTotal_JP.md" target="_blank">WorksheetLine/AssetImpairmentCGURecognitionTotal_JP</a>|
|[GrandTotalTestResult](#GrandTotalTestResult)||<a href="AssetImpairmentCGURecognitionTotal_JP.md" target="_blank">WorksheetLine/AssetImpairmentCGURecognitionTotal_JP</a>|
|[GrandTotalUndisc](#GrandTotalUndisc)||<a href="AssetImpairmentCGURecognitionTotal_JP.md" target="_blank">WorksheetLine/AssetImpairmentCGURecognitionTotal_JP</a>|
|[SharedAssetImpairmentAdjExceeded](#SharedAssetImpairmentAdjExceeded)||<a href="AssetImpairmentCGURecognitionTotal_JP.md" target="_blank">WorksheetLine/AssetImpairmentCGURecognitionTotal_JP</a>|
|[SharedAssetsSubtotalImpairmentAdj](#SharedAssetsSubtotalImpairmentAdj)||<a href="AssetImpairmentCGURecognitionTotal_JP.md" target="_blank">WorksheetLine/AssetImpairmentCGURecognitionTotal_JP</a>|
|[SharedAssetsSubtotalNbv](#SharedAssetsSubtotalNbv)||<a href="AssetImpairmentCGURecognitionTotal_JP.md" target="_blank">WorksheetLine/AssetImpairmentCGURecognitionTotal_JP</a>|
|[SharedAssetsSubtotalRecov](#SharedAssetsSubtotalRecov)||<a href="AssetImpairmentCGURecognitionTotal_JP.md" target="_blank">WorksheetLine/AssetImpairmentCGURecognitionTotal_JP</a>|
|[DataAreaId](#DataAreaId)||<a href="AssetImpairmentCGURecognitionTotal_JP.md" target="_blank">WorksheetLine/AssetImpairmentCGURecognitionTotal_JP</a>|
|[Relationship_AssetImpairmentTestResult_JPRelationshipId](#Relationship_AssetImpairmentTestResult_JPRelationshipId)||<a href="AssetImpairmentCGURecognitionTotal_JP.md" target="_blank">WorksheetLine/AssetImpairmentCGURecognitionTotal_JP</a>|
|[Relationship_CompanyRelationshipId](#Relationship_CompanyRelationshipId)||<a href="AssetImpairmentCGURecognitionTotal_JP.md" target="_blank">WorksheetLine/AssetImpairmentCGURecognitionTotal_JP</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: WorksheetLine/AssetImpairmentCGURecognitionTotal_JP (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[AssetImpairmentCGURecognitionTotal_JP/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#AssetImpairmentTestResult_JP name="AssetImpairmentTestResult_JP">AssetImpairmentTestResult_JP</a>

First included in: WorksheetLine/AssetImpairmentCGURecognitionTotal_JP (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AssetImpairmentTestResult_JP attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#CGUSubtotalImpairmentAdj name="CGUSubtotalImpairmentAdj">CGUSubtotalImpairmentAdj</a>

First included in: WorksheetLine/AssetImpairmentCGURecognitionTotal_JP (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CGUSubtotalImpairmentAdj attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#CGUSubtotalNbv name="CGUSubtotalNbv">CGUSubtotalNbv</a>

First included in: WorksheetLine/AssetImpairmentCGURecognitionTotal_JP (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CGUSubtotalNbv attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#CGUSubtotalRecov name="CGUSubtotalRecov">CGUSubtotalRecov</a>

First included in: WorksheetLine/AssetImpairmentCGURecognitionTotal_JP (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CGUSubtotalRecov attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#CGUSubtotalUndisc name="CGUSubtotalUndisc">CGUSubtotalUndisc</a>

First included in: WorksheetLine/AssetImpairmentCGURecognitionTotal_JP (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CGUSubtotalUndisc attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#GrandTotalImpairmentAdj name="GrandTotalImpairmentAdj">GrandTotalImpairmentAdj</a>

First included in: WorksheetLine/AssetImpairmentCGURecognitionTotal_JP (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the GrandTotalImpairmentAdj attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#GrandTotalNbv name="GrandTotalNbv">GrandTotalNbv</a>

First included in: WorksheetLine/AssetImpairmentCGURecognitionTotal_JP (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the GrandTotalNbv attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#GrandTotalRecov name="GrandTotalRecov">GrandTotalRecov</a>

First included in: WorksheetLine/AssetImpairmentCGURecognitionTotal_JP (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the GrandTotalRecov attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#GrandTotalTestResult name="GrandTotalTestResult">GrandTotalTestResult</a>

First included in: WorksheetLine/AssetImpairmentCGURecognitionTotal_JP (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the GrandTotalTestResult attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#GrandTotalUndisc name="GrandTotalUndisc">GrandTotalUndisc</a>

First included in: WorksheetLine/AssetImpairmentCGURecognitionTotal_JP (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the GrandTotalUndisc attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#SharedAssetImpairmentAdjExceeded name="SharedAssetImpairmentAdjExceeded">SharedAssetImpairmentAdjExceeded</a>

First included in: WorksheetLine/AssetImpairmentCGURecognitionTotal_JP (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SharedAssetImpairmentAdjExceeded attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#SharedAssetsSubtotalImpairmentAdj name="SharedAssetsSubtotalImpairmentAdj">SharedAssetsSubtotalImpairmentAdj</a>

First included in: WorksheetLine/AssetImpairmentCGURecognitionTotal_JP (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SharedAssetsSubtotalImpairmentAdj attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#SharedAssetsSubtotalNbv name="SharedAssetsSubtotalNbv">SharedAssetsSubtotalNbv</a>

First included in: WorksheetLine/AssetImpairmentCGURecognitionTotal_JP (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SharedAssetsSubtotalNbv attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#SharedAssetsSubtotalRecov name="SharedAssetsSubtotalRecov">SharedAssetsSubtotalRecov</a>

First included in: WorksheetLine/AssetImpairmentCGURecognitionTotal_JP (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Recoverable amount</td></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SharedAssetsSubtotalRecov attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Recoverable amount</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#DataAreaId name="DataAreaId">DataAreaId</a>

First included in: WorksheetLine/AssetImpairmentCGURecognitionTotal_JP (this entity)  

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

### <a href=#Relationship_AssetImpairmentTestResult_JPRelationshipId name="Relationship_AssetImpairmentTestResult_JPRelationshipId">Relationship_AssetImpairmentTestResult_JPRelationshipId</a>

First included in: WorksheetLine/AssetImpairmentCGURecognitionTotal_JP (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_AssetImpairmentTestResult_JPRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../WorksheetHeader/AssetImpairmentTestResult_JP.md" target="_blank">/core/operationsCommon/Tables/Finance/FixedAssets/WorksheetHeader/AssetImpairmentTestResult_JP.cdm.json/AssetImpairmentTestResult_JP</a></td><td><a href="../WorksheetHeader/AssetImpairmentTestResult_JP.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_CompanyRelationshipId name="Relationship_CompanyRelationshipId">Relationship_CompanyRelationshipId</a>

First included in: WorksheetLine/AssetImpairmentCGURecognitionTotal_JP (this entity)  

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
