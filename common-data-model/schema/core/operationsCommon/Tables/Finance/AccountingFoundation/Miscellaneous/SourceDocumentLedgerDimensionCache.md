---
title: SourceDocumentLedgerDimensionCache - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/29/2020
ms.author: nebanfic
---

# SourceDocumentLedgerDimensionCache

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Tables/Finance/AccountingFoundation/Miscellaneous/SourceDocumentLedgerDimensionCache.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[SourceDocumentLedgerDimensionCache/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="SourceDocumentLedgerDimensionCache.md" target="_blank">Miscellaneous/SourceDocumentLedgerDimensionCache</a>|
|[AccountingLegalEntity](#AccountingLegalEntity)||<a href="SourceDocumentLedgerDimensionCache.md" target="_blank">Miscellaneous/SourceDocumentLedgerDimensionCache</a>|
|[DefaultDimension1](#DefaultDimension1)||<a href="SourceDocumentLedgerDimensionCache.md" target="_blank">Miscellaneous/SourceDocumentLedgerDimensionCache</a>|
|[DefaultDimension2](#DefaultDimension2)||<a href="SourceDocumentLedgerDimensionCache.md" target="_blank">Miscellaneous/SourceDocumentLedgerDimensionCache</a>|
|[DefaultDimension3](#DefaultDimension3)||<a href="SourceDocumentLedgerDimensionCache.md" target="_blank">Miscellaneous/SourceDocumentLedgerDimensionCache</a>|
|[InputLedgerDimension](#InputLedgerDimension)||<a href="SourceDocumentLedgerDimensionCache.md" target="_blank">Miscellaneous/SourceDocumentLedgerDimensionCache</a>|
|[ResultLedgerDimension](#ResultLedgerDimension)||<a href="SourceDocumentLedgerDimensionCache.md" target="_blank">Miscellaneous/SourceDocumentLedgerDimensionCache</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: Miscellaneous/SourceDocumentLedgerDimensionCache (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[SourceDocumentLedgerDimensionCache/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#AccountingLegalEntity name="AccountingLegalEntity">AccountingLegalEntity</a>

First included in: Miscellaneous/SourceDocumentLedgerDimensionCache (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AccountingLegalEntity attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#DefaultDimension1 name="DefaultDimension1">DefaultDimension1</a>

First included in: Miscellaneous/SourceDocumentLedgerDimensionCache (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultDimension1 attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#DefaultDimension2 name="DefaultDimension2">DefaultDimension2</a>

First included in: Miscellaneous/SourceDocumentLedgerDimensionCache (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultDimension2 attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#DefaultDimension3 name="DefaultDimension3">DefaultDimension3</a>

First included in: Miscellaneous/SourceDocumentLedgerDimensionCache (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultDimension3 attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#InputLedgerDimension name="InputLedgerDimension">InputLedgerDimension</a>

First included in: Miscellaneous/SourceDocumentLedgerDimensionCache (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InputLedgerDimension attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#ResultLedgerDimension name="ResultLedgerDimension">ResultLedgerDimension</a>

First included in: Miscellaneous/SourceDocumentLedgerDimensionCache (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ResultLedgerDimension attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>
