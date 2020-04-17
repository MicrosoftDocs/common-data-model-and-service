---
title: CustIntentLetterStaging_IT - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/17/2020
ms.author: nebanfic
---

# CustIntentLetterStaging_IT

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/erp/Tables/Finance/AccountsReceivable/Staging/CustIntentLetterStaging_IT.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[CustIntentLetterStaging_IT/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="CustIntentLetterStaging_IT.md" target="_blank">Staging/CustIntentLetterStaging_IT</a>|
|[DefinitionGroup](#DefinitionGroup)||<a href="CustIntentLetterStaging_IT.md" target="_blank">Staging/CustIntentLetterStaging_IT</a>|
|[ExecutionId](#ExecutionId)||<a href="CustIntentLetterStaging_IT.md" target="_blank">Staging/CustIntentLetterStaging_IT</a>|
|[IsSelected](#IsSelected)||<a href="CustIntentLetterStaging_IT.md" target="_blank">Staging/CustIntentLetterStaging_IT</a>|
|[TransferStatus](#TransferStatus)||<a href="CustIntentLetterStaging_IT.md" target="_blank">Staging/CustIntentLetterStaging_IT</a>|
|[AccountNum](#AccountNum)||<a href="CustIntentLetterStaging_IT.md" target="_blank">Staging/CustIntentLetterStaging_IT</a>|
|[ClosedDate](#ClosedDate)||<a href="CustIntentLetterStaging_IT.md" target="_blank">Staging/CustIntentLetterStaging_IT</a>|
|[DateLetter](#DateLetter)||<a href="CustIntentLetterStaging_IT.md" target="_blank">Staging/CustIntentLetterStaging_IT</a>|
|[DateRegister](#DateRegister)||<a href="CustIntentLetterStaging_IT.md" target="_blank">Staging/CustIntentLetterStaging_IT</a>|
|[FromDate](#FromDate)||<a href="CustIntentLetterStaging_IT.md" target="_blank">Staging/CustIntentLetterStaging_IT</a>|
|[IntentLetterAmountMST](#IntentLetterAmountMST)||<a href="CustIntentLetterStaging_IT.md" target="_blank">Staging/CustIntentLetterStaging_IT</a>|
|[IntentLetterType](#IntentLetterType)||<a href="CustIntentLetterStaging_IT.md" target="_blank">Staging/CustIntentLetterStaging_IT</a>|
|[InternalLetterId](#InternalLetterId)||<a href="CustIntentLetterStaging_IT.md" target="_blank">Staging/CustIntentLetterStaging_IT</a>|
|[LetterId](#LetterId)||<a href="CustIntentLetterStaging_IT.md" target="_blank">Staging/CustIntentLetterStaging_IT</a>|
|[Notes](#Notes)||<a href="CustIntentLetterStaging_IT.md" target="_blank">Staging/CustIntentLetterStaging_IT</a>|
|[Protocol](#Protocol)||<a href="CustIntentLetterStaging_IT.md" target="_blank">Staging/CustIntentLetterStaging_IT</a>|
|[Status](#Status)||<a href="CustIntentLetterStaging_IT.md" target="_blank">Staging/CustIntentLetterStaging_IT</a>|
|[ToDate](#ToDate)||<a href="CustIntentLetterStaging_IT.md" target="_blank">Staging/CustIntentLetterStaging_IT</a>|
|[IntentLetterYear](#IntentLetterYear)||<a href="CustIntentLetterStaging_IT.md" target="_blank">Staging/CustIntentLetterStaging_IT</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: Staging/CustIntentLetterStaging_IT (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[CustIntentLetterStaging_IT/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#DefinitionGroup name="DefinitionGroup">DefinitionGroup</a>

First included in: Staging/CustIntentLetterStaging_IT (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefinitionGroup attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ExecutionId name="ExecutionId">ExecutionId</a>

First included in: Staging/CustIntentLetterStaging_IT (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ExecutionId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsSelected name="IsSelected">IsSelected</a>

First included in: Staging/CustIntentLetterStaging_IT (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsSelected attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#TransferStatus name="TransferStatus">TransferStatus</a>

First included in: Staging/CustIntentLetterStaging_IT (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TransferStatus attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#AccountNum name="AccountNum">AccountNum</a>

First included in: Staging/CustIntentLetterStaging_IT (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AccountNum attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ClosedDate name="ClosedDate">ClosedDate</a>

First included in: Staging/CustIntentLetterStaging_IT (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ClosedDate attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.dataFormat.date**  
</details>

### <a href=#DateLetter name="DateLetter">DateLetter</a>

First included in: Staging/CustIntentLetterStaging_IT (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DateLetter attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.dataFormat.date**  
</details>

### <a href=#DateRegister name="DateRegister">DateRegister</a>

First included in: Staging/CustIntentLetterStaging_IT (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DateRegister attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.dataFormat.date**  
</details>

### <a href=#FromDate name="FromDate">FromDate</a>

First included in: Staging/CustIntentLetterStaging_IT (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FromDate attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.dataFormat.date**  
</details>

### <a href=#IntentLetterAmountMST name="IntentLetterAmountMST">IntentLetterAmountMST</a>

First included in: Staging/CustIntentLetterStaging_IT (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IntentLetterAmountMST attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#IntentLetterType name="IntentLetterType">IntentLetterType</a>

First included in: Staging/CustIntentLetterStaging_IT (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IntentLetterType attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#InternalLetterId name="InternalLetterId">InternalLetterId</a>

First included in: Staging/CustIntentLetterStaging_IT (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InternalLetterId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LetterId name="LetterId">LetterId</a>

First included in: Staging/CustIntentLetterStaging_IT (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LetterId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Notes name="Notes">Notes</a>

First included in: Staging/CustIntentLetterStaging_IT (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Notes attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Protocol name="Protocol">Protocol</a>

First included in: Staging/CustIntentLetterStaging_IT (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Protocol attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Status name="Status">Status</a>

First included in: Staging/CustIntentLetterStaging_IT (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Status attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#ToDate name="ToDate">ToDate</a>

First included in: Staging/CustIntentLetterStaging_IT (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ToDate attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.dataFormat.date**  
</details>

### <a href=#IntentLetterYear name="IntentLetterYear">IntentLetterYear</a>

First included in: Staging/CustIntentLetterStaging_IT (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IntentLetterYear attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>
