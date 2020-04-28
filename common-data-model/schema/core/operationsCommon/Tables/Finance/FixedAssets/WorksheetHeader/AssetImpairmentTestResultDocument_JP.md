---
title: AssetImpairmentTestResultDocument_JP - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/28/2020
ms.author: nebanfic
---

# Asset impairment test result and document table link table

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Tables/Finance/FixedAssets/WorksheetHeader/AssetImpairmentTestResultDocument_JP.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[AssetImpairmentTestResultDocument_JP/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Asset impairment test result and document table link table</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="AssetImpairmentTestResultDocument_JP.md" target="_blank">WorksheetHeader/AssetImpairmentTestResultDocument_JP</a>|
|[AssetDocumentTable_JP](#AssetDocumentTable_JP)||<a href="AssetImpairmentTestResultDocument_JP.md" target="_blank">WorksheetHeader/AssetImpairmentTestResultDocument_JP</a>|
|[AssetImpairmentTestResult_JP](#AssetImpairmentTestResult_JP)||<a href="AssetImpairmentTestResultDocument_JP.md" target="_blank">WorksheetHeader/AssetImpairmentTestResultDocument_JP</a>|
|[CGU](#CGU)||<a href="AssetImpairmentTestResultDocument_JP.md" target="_blank">WorksheetHeader/AssetImpairmentTestResultDocument_JP</a>|
|[DocTestResult](#DocTestResult)||<a href="AssetImpairmentTestResultDocument_JP.md" target="_blank">WorksheetHeader/AssetImpairmentTestResultDocument_JP</a>|
|[ImpairmentAdjExceeded](#ImpairmentAdjExceeded)||<a href="AssetImpairmentTestResultDocument_JP.md" target="_blank">WorksheetHeader/AssetImpairmentTestResultDocument_JP</a>|
|[ImpairmentAdjustment](#ImpairmentAdjustment)||<a href="AssetImpairmentTestResultDocument_JP.md" target="_blank">WorksheetHeader/AssetImpairmentTestResultDocument_JP</a>|
|[ImpairmentAllocBasis](#ImpairmentAllocBasis)||<a href="AssetImpairmentTestResultDocument_JP.md" target="_blank">WorksheetHeader/AssetImpairmentTestResultDocument_JP</a>|
|[LastUpdatedDate](#LastUpdatedDate)||<a href="AssetImpairmentTestResultDocument_JP.md" target="_blank">WorksheetHeader/AssetImpairmentTestResultDocument_JP</a>|
|[NetBookValue](#NetBookValue)||<a href="AssetImpairmentTestResultDocument_JP.md" target="_blank">WorksheetHeader/AssetImpairmentTestResultDocument_JP</a>|
|[NotRecoverable](#NotRecoverable)||<a href="AssetImpairmentTestResultDocument_JP.md" target="_blank">WorksheetHeader/AssetImpairmentTestResultDocument_JP</a>|
|[RecoverableAmount](#RecoverableAmount)||<a href="AssetImpairmentTestResultDocument_JP.md" target="_blank">WorksheetHeader/AssetImpairmentTestResultDocument_JP</a>|
|[UndiscountedCashFlow](#UndiscountedCashFlow)||<a href="AssetImpairmentTestResultDocument_JP.md" target="_blank">WorksheetHeader/AssetImpairmentTestResultDocument_JP</a>|
|[DataAreaId](#DataAreaId)||<a href="AssetImpairmentTestResultDocument_JP.md" target="_blank">WorksheetHeader/AssetImpairmentTestResultDocument_JP</a>|
|[Relationship_AssetDocumentTable_JPRelationshipId](#Relationship_AssetDocumentTable_JPRelationshipId)||<a href="AssetImpairmentTestResultDocument_JP.md" target="_blank">WorksheetHeader/AssetImpairmentTestResultDocument_JP</a>|
|[Relationship_AssetImpairmentTestResult_JPRelationshipId](#Relationship_AssetImpairmentTestResult_JPRelationshipId)||<a href="AssetImpairmentTestResultDocument_JP.md" target="_blank">WorksheetHeader/AssetImpairmentTestResultDocument_JP</a>|
|[Relationship_CGURelationshipId](#Relationship_CGURelationshipId)||<a href="AssetImpairmentTestResultDocument_JP.md" target="_blank">WorksheetHeader/AssetImpairmentTestResultDocument_JP</a>|
|[Relationship_CompanyRelationshipId](#Relationship_CompanyRelationshipId)||<a href="AssetImpairmentTestResultDocument_JP.md" target="_blank">WorksheetHeader/AssetImpairmentTestResultDocument_JP</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: WorksheetHeader/AssetImpairmentTestResultDocument_JP (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[AssetImpairmentTestResultDocument_JP/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#AssetDocumentTable_JP name="AssetDocumentTable_JP">AssetDocumentTable_JP</a>

First included in: WorksheetHeader/AssetImpairmentTestResultDocument_JP (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AssetDocumentTable_JP attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#AssetImpairmentTestResult_JP name="AssetImpairmentTestResult_JP">AssetImpairmentTestResult_JP</a>

First included in: WorksheetHeader/AssetImpairmentTestResultDocument_JP (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AssetImpairmentTestResult_JP attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#CGU name="CGU">CGU</a>

First included in: WorksheetHeader/AssetImpairmentTestResultDocument_JP (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CGU attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#DocTestResult name="DocTestResult">DocTestResult</a>

First included in: WorksheetHeader/AssetImpairmentTestResultDocument_JP (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Test result</td></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DocTestResult attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Test result</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#ImpairmentAdjExceeded name="ImpairmentAdjExceeded">ImpairmentAdjExceeded</a>

First included in: WorksheetHeader/AssetImpairmentTestResultDocument_JP (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ImpairmentAdjExceeded attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#ImpairmentAdjustment name="ImpairmentAdjustment">ImpairmentAdjustment</a>

First included in: WorksheetHeader/AssetImpairmentTestResultDocument_JP (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ImpairmentAdjustment attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#ImpairmentAllocBasis name="ImpairmentAllocBasis">ImpairmentAllocBasis</a>

First included in: WorksheetHeader/AssetImpairmentTestResultDocument_JP (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ImpairmentAllocBasis attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#LastUpdatedDate name="LastUpdatedDate">LastUpdatedDate</a>

First included in: WorksheetHeader/AssetImpairmentTestResultDocument_JP (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Last update</td></tr><tr><td>dataFormat</td><td>date</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LastUpdatedDate attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Last update</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.date**  
</details>

### <a href=#NetBookValue name="NetBookValue">NetBookValue</a>

First included in: WorksheetHeader/AssetImpairmentTestResultDocument_JP (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the NetBookValue attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#NotRecoverable name="NotRecoverable">NotRecoverable</a>

First included in: WorksheetHeader/AssetImpairmentTestResultDocument_JP (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Not recoverable</td></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the NotRecoverable attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Not recoverable</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#RecoverableAmount name="RecoverableAmount">RecoverableAmount</a>

First included in: WorksheetHeader/AssetImpairmentTestResultDocument_JP (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecoverableAmount attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#UndiscountedCashFlow name="UndiscountedCashFlow">UndiscountedCashFlow</a>

First included in: WorksheetHeader/AssetImpairmentTestResultDocument_JP (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the UndiscountedCashFlow attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#DataAreaId name="DataAreaId">DataAreaId</a>

First included in: WorksheetHeader/AssetImpairmentTestResultDocument_JP (this entity)  

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

### <a href=#Relationship_AssetDocumentTable_JPRelationshipId name="Relationship_AssetDocumentTable_JPRelationshipId">Relationship_AssetDocumentTable_JPRelationshipId</a>

First included in: WorksheetHeader/AssetImpairmentTestResultDocument_JP (this entity)  

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

### <a href=#Relationship_AssetImpairmentTestResult_JPRelationshipId name="Relationship_AssetImpairmentTestResult_JPRelationshipId">Relationship_AssetImpairmentTestResult_JPRelationshipId</a>

First included in: WorksheetHeader/AssetImpairmentTestResultDocument_JP (this entity)  

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
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="AssetImpairmentTestResult_JP.md" target="_blank">/core/operationsCommon/Tables/Finance/FixedAssets/WorksheetHeader/AssetImpairmentTestResult_JP.cdm.json/AssetImpairmentTestResult_JP</a></td><td><a href="AssetImpairmentTestResult_JP.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_CGURelationshipId name="Relationship_CGURelationshipId">Relationship_CGURelationshipId</a>

First included in: WorksheetHeader/AssetImpairmentTestResultDocument_JP (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_CGURelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Main/AssetImpairmentCGU_JP.md" target="_blank">/core/operationsCommon/Tables/Finance/FixedAssets/Main/AssetImpairmentCGU_JP.cdm.json/AssetImpairmentCGU_JP</a></td><td><a href="../Main/AssetImpairmentCGU_JP.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_CompanyRelationshipId name="Relationship_CompanyRelationshipId">Relationship_CompanyRelationshipId</a>

First included in: WorksheetHeader/AssetImpairmentTestResultDocument_JP (this entity)  

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
