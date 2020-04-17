---
title: ReleaseUpdateBulkCopyField - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/17/2020
ms.author: nebanfic
---

# ReleaseUpdateBulkCopyField

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/erp/Tables/System/SystemAdministration/Framework/ReleaseUpdateBulkCopyField.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[ReleaseUpdateBulkCopyField/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="ReleaseUpdateBulkCopyField.md" target="_blank">Framework/ReleaseUpdateBulkCopyField</a>|
|[EDTName](#EDTName)||<a href="ReleaseUpdateBulkCopyField.md" target="_blank">Framework/ReleaseUpdateBulkCopyField</a>|
|[IsRecIdField](#IsRecIdField)||<a href="ReleaseUpdateBulkCopyField.md" target="_blank">Framework/ReleaseUpdateBulkCopyField</a>|
|[IsSpecialMapping](#IsSpecialMapping)||<a href="ReleaseUpdateBulkCopyField.md" target="_blank">Framework/ReleaseUpdateBulkCopyField</a>|
|[NewFieldName](#NewFieldName)||<a href="ReleaseUpdateBulkCopyField.md" target="_blank">Framework/ReleaseUpdateBulkCopyField</a>|
|[NewFieldSqlName](#NewFieldSqlName)||<a href="ReleaseUpdateBulkCopyField.md" target="_blank">Framework/ReleaseUpdateBulkCopyField</a>|
|[NewTableId](#NewTableId)||<a href="ReleaseUpdateBulkCopyField.md" target="_blank">Framework/ReleaseUpdateBulkCopyField</a>|
|[OldFieldName](#OldFieldName)||<a href="ReleaseUpdateBulkCopyField.md" target="_blank">Framework/ReleaseUpdateBulkCopyField</a>|
|[OldFieldSqlName](#OldFieldSqlName)||<a href="ReleaseUpdateBulkCopyField.md" target="_blank">Framework/ReleaseUpdateBulkCopyField</a>|
|[OldShadowTableSqlName](#OldShadowTableSqlName)||<a href="ReleaseUpdateBulkCopyField.md" target="_blank">Framework/ReleaseUpdateBulkCopyField</a>|
|[OldTableId](#OldTableId)||<a href="ReleaseUpdateBulkCopyField.md" target="_blank">Framework/ReleaseUpdateBulkCopyField</a>|
|[RecIdDataAreaSQLName](#RecIdDataAreaSQLName)||<a href="ReleaseUpdateBulkCopyField.md" target="_blank">Framework/ReleaseUpdateBulkCopyField</a>|
|[RecIdTableIdSqlName](#RecIdTableIdSqlName)||<a href="ReleaseUpdateBulkCopyField.md" target="_blank">Framework/ReleaseUpdateBulkCopyField</a>|
|[RecIdTableSqlName](#RecIdTableSqlName)||<a href="ReleaseUpdateBulkCopyField.md" target="_blank">Framework/ReleaseUpdateBulkCopyField</a>|
|[Status](#Status)||<a href="ReleaseUpdateBulkCopyField.md" target="_blank">Framework/ReleaseUpdateBulkCopyField</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: Framework/ReleaseUpdateBulkCopyField (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[ReleaseUpdateBulkCopyField/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#EDTName name="EDTName">EDTName</a>

First included in: Framework/ReleaseUpdateBulkCopyField (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EDTName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsRecIdField name="IsRecIdField">IsRecIdField</a>

First included in: Framework/ReleaseUpdateBulkCopyField (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsRecIdField attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#IsSpecialMapping name="IsSpecialMapping">IsSpecialMapping</a>

First included in: Framework/ReleaseUpdateBulkCopyField (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsSpecialMapping attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#NewFieldName name="NewFieldName">NewFieldName</a>

First included in: Framework/ReleaseUpdateBulkCopyField (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the NewFieldName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#NewFieldSqlName name="NewFieldSqlName">NewFieldSqlName</a>

First included in: Framework/ReleaseUpdateBulkCopyField (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the NewFieldSqlName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#NewTableId name="NewTableId">NewTableId</a>

First included in: Framework/ReleaseUpdateBulkCopyField (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the NewTableId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#OldFieldName name="OldFieldName">OldFieldName</a>

First included in: Framework/ReleaseUpdateBulkCopyField (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OldFieldName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#OldFieldSqlName name="OldFieldSqlName">OldFieldSqlName</a>

First included in: Framework/ReleaseUpdateBulkCopyField (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OldFieldSqlName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#OldShadowTableSqlName name="OldShadowTableSqlName">OldShadowTableSqlName</a>

First included in: Framework/ReleaseUpdateBulkCopyField (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OldShadowTableSqlName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#OldTableId name="OldTableId">OldTableId</a>

First included in: Framework/ReleaseUpdateBulkCopyField (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OldTableId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#RecIdDataAreaSQLName name="RecIdDataAreaSQLName">RecIdDataAreaSQLName</a>

First included in: Framework/ReleaseUpdateBulkCopyField (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecIdDataAreaSQLName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RecIdTableIdSqlName name="RecIdTableIdSqlName">RecIdTableIdSqlName</a>

First included in: Framework/ReleaseUpdateBulkCopyField (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecIdTableIdSqlName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RecIdTableSqlName name="RecIdTableSqlName">RecIdTableSqlName</a>

First included in: Framework/ReleaseUpdateBulkCopyField (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecIdTableSqlName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Status name="Status">Status</a>

First included in: Framework/ReleaseUpdateBulkCopyField (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Status attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>
