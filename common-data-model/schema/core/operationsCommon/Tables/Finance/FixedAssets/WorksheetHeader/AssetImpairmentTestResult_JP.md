---
title: AssetImpairmentTestResult_JP in WorksheetHeader - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 7/13/2020
ms.author: nebanfic
---

# Asset impairment test result in WorksheetHeader(AssetImpairmentTestResult_JP)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Tables/Finance/FixedAssets/WorksheetHeader/AssetImpairmentTestResult_JP.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[AssetImpairmentTestResult_JP/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Asset impairment test result</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="AssetImpairmentTestResult_JP.md" target="_blank">WorksheetHeader/AssetImpairmentTestResult_JP</a>|
|[AssetBookType](#AssetBookType)||<a href="AssetImpairmentTestResult_JP.md" target="_blank">WorksheetHeader/AssetImpairmentTestResult_JP</a>|
|[CGUGroup](#CGUGroup)||<a href="AssetImpairmentTestResult_JP.md" target="_blank">WorksheetHeader/AssetImpairmentTestResult_JP</a>|
|[Description](#Description)||<a href="AssetImpairmentTestResult_JP.md" target="_blank">WorksheetHeader/AssetImpairmentTestResult_JP</a>|
|[NetSellingPriceAsRecovable](#NetSellingPriceAsRecovable)||<a href="AssetImpairmentTestResult_JP.md" target="_blank">WorksheetHeader/AssetImpairmentTestResult_JP</a>|
|[SessionId](#SessionId)||<a href="AssetImpairmentTestResult_JP.md" target="_blank">WorksheetHeader/AssetImpairmentTestResult_JP</a>|
|[SessionLoginDateTime](#SessionLoginDateTime)||<a href="AssetImpairmentTestResult_JP.md" target="_blank">WorksheetHeader/AssetImpairmentTestResult_JP</a>|
|[SharedAssetAllocBasis](#SharedAssetAllocBasis)||<a href="AssetImpairmentTestResult_JP.md" target="_blank">WorksheetHeader/AssetImpairmentTestResult_JP</a>|
|[SharedAssetHasHigherPriority](#SharedAssetHasHigherPriority)||<a href="AssetImpairmentTestResult_JP.md" target="_blank">WorksheetHeader/AssetImpairmentTestResult_JP</a>|
|[SharedAssetImpairMethod](#SharedAssetImpairMethod)||<a href="AssetImpairmentTestResult_JP.md" target="_blank">WorksheetHeader/AssetImpairmentTestResult_JP</a>|
|[SharedAssetsImpairmentAllocateToCGU](#SharedAssetsImpairmentAllocateToCGU)||<a href="AssetImpairmentTestResult_JP.md" target="_blank">WorksheetHeader/AssetImpairmentTestResult_JP</a>|
|[Status](#Status)||<a href="AssetImpairmentTestResult_JP.md" target="_blank">WorksheetHeader/AssetImpairmentTestResult_JP</a>|
|[TestDate](#TestDate)||<a href="AssetImpairmentTestResult_JP.md" target="_blank">WorksheetHeader/AssetImpairmentTestResult_JP</a>|
|[TestNum](#TestNum)||<a href="AssetImpairmentTestResult_JP.md" target="_blank">WorksheetHeader/AssetImpairmentTestResult_JP</a>|
|[DataAreaId](#DataAreaId)||<a href="AssetImpairmentTestResult_JP.md" target="_blank">WorksheetHeader/AssetImpairmentTestResult_JP</a>|
|[Relationship_CGUGroupRelationshipId](#Relationship_CGUGroupRelationshipId)||<a href="AssetImpairmentTestResult_JP.md" target="_blank">WorksheetHeader/AssetImpairmentTestResult_JP</a>|
|[Relationship_CompanyRelationshipId](#Relationship_CompanyRelationshipId)||<a href="AssetImpairmentTestResult_JP.md" target="_blank">WorksheetHeader/AssetImpairmentTestResult_JP</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: WorksheetHeader/AssetImpairmentTestResult_JP (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[AssetImpairmentTestResult_JP/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#AssetBookType name="AssetBookType">AssetBookType</a>

First included in: WorksheetHeader/AssetImpairmentTestResult_JP (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AssetBookType attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#CGUGroup name="CGUGroup">CGUGroup</a>

First included in: WorksheetHeader/AssetImpairmentTestResult_JP (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CGUGroup attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#Description name="Description">Description</a>

First included in: WorksheetHeader/AssetImpairmentTestResult_JP (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Description attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#NetSellingPriceAsRecovable name="NetSellingPriceAsRecovable">NetSellingPriceAsRecovable</a>

First included in: WorksheetHeader/AssetImpairmentTestResult_JP (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Shared asset is recoverable</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the NetSellingPriceAsRecovable attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Shared asset is recoverable</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#SessionId name="SessionId">SessionId</a>

First included in: WorksheetHeader/AssetImpairmentTestResult_JP (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SessionId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.readOnly**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#SessionLoginDateTime name="SessionLoginDateTime">SessionLoginDateTime</a>

First included in: WorksheetHeader/AssetImpairmentTestResult_JP (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SessionLoginDateTime attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.date**  
</details>

### <a href=#SharedAssetAllocBasis name="SharedAssetAllocBasis">SharedAssetAllocBasis</a>

First included in: WorksheetHeader/AssetImpairmentTestResult_JP (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SharedAssetAllocBasis attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#SharedAssetHasHigherPriority name="SharedAssetHasHigherPriority">SharedAssetHasHigherPriority</a>

First included in: WorksheetHeader/AssetImpairmentTestResult_JP (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Shared assets have higher priority than ordinary fixed asset</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SharedAssetHasHigherPriority attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Shared assets have higher priority than ordinary fixed asset</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#SharedAssetImpairMethod name="SharedAssetImpairMethod">SharedAssetImpairMethod</a>

First included in: WorksheetHeader/AssetImpairmentTestResult_JP (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SharedAssetImpairMethod attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#SharedAssetsImpairmentAllocateToCGU name="SharedAssetsImpairmentAllocateToCGU">SharedAssetsImpairmentAllocateToCGU</a>

First included in: WorksheetHeader/AssetImpairmentTestResult_JP (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SharedAssetsImpairmentAllocateToCGU attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#Status name="Status">Status</a>

First included in: WorksheetHeader/AssetImpairmentTestResult_JP (this entity)  

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

### <a href=#TestDate name="TestDate">TestDate</a>

First included in: WorksheetHeader/AssetImpairmentTestResult_JP (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TestDate attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.dataFormat.date**  
</details>

### <a href=#TestNum name="TestNum">TestNum</a>

First included in: WorksheetHeader/AssetImpairmentTestResult_JP (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TestNum attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DataAreaId name="DataAreaId">DataAreaId</a>

First included in: WorksheetHeader/AssetImpairmentTestResult_JP (this entity)  

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

### <a href=#Relationship_CGUGroupRelationshipId name="Relationship_CGUGroupRelationshipId">Relationship_CGUGroupRelationshipId</a>

First included in: WorksheetHeader/AssetImpairmentTestResult_JP (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_CGUGroupRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Group/AssetImpairmentCGUGroup_JP.md" target="_blank">/core/operationsCommon/Tables/Finance/FixedAssets/Group/AssetImpairmentCGUGroup_JP.cdm.json/AssetImpairmentCGUGroup_JP</a></td><td><a href="../Group/AssetImpairmentCGUGroup_JP.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_CompanyRelationshipId name="Relationship_CompanyRelationshipId">Relationship_CompanyRelationshipId</a>

First included in: WorksheetHeader/AssetImpairmentTestResult_JP (this entity)  

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
