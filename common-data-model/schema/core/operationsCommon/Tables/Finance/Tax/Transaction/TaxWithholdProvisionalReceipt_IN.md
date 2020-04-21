---
title: TaxWithholdProvisionalReceipt_IN - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/21/2020
ms.author: nebanfic
---

# TaxWithholdProvisionalReceipt_IN

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Tables/Finance/Tax/Transaction/TaxWithholdProvisionalReceipt_IN.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[TaxWithholdProvisionalReceipt_IN/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="TaxWithholdProvisionalReceipt_IN.md" target="_blank">Transaction/TaxWithholdProvisionalReceipt_IN</a>|
|[CorrectionType](#CorrectionType)||<a href="TaxWithholdProvisionalReceipt_IN.md" target="_blank">Transaction/TaxWithholdProvisionalReceipt_IN</a>|
|[FromDate](#FromDate)||<a href="TaxWithholdProvisionalReceipt_IN.md" target="_blank">Transaction/TaxWithholdProvisionalReceipt_IN</a>|
|[PeriodEnd](#PeriodEnd)||<a href="TaxWithholdProvisionalReceipt_IN.md" target="_blank">Transaction/TaxWithholdProvisionalReceipt_IN</a>|
|[PrintingDate](#PrintingDate)||<a href="TaxWithholdProvisionalReceipt_IN.md" target="_blank">Transaction/TaxWithholdProvisionalReceipt_IN</a>|
|[ProvisionalReceiptNumber](#ProvisionalReceiptNumber)||<a href="TaxWithholdProvisionalReceipt_IN.md" target="_blank">Transaction/TaxWithholdProvisionalReceipt_IN</a>|
|[ReceiptNumber](#ReceiptNumber)||<a href="TaxWithholdProvisionalReceipt_IN.md" target="_blank">Transaction/TaxWithholdProvisionalReceipt_IN</a>|
|[Statement](#Statement)||<a href="TaxWithholdProvisionalReceipt_IN.md" target="_blank">Transaction/TaxWithholdProvisionalReceipt_IN</a>|
|[Status](#Status)||<a href="TaxWithholdProvisionalReceipt_IN.md" target="_blank">Transaction/TaxWithholdProvisionalReceipt_IN</a>|
|[TaxType](#TaxType)||<a href="TaxWithholdProvisionalReceipt_IN.md" target="_blank">Transaction/TaxWithholdProvisionalReceipt_IN</a>|
|[TaxWithholdRegNumber](#TaxWithholdRegNumber)||<a href="TaxWithholdProvisionalReceipt_IN.md" target="_blank">Transaction/TaxWithholdProvisionalReceipt_IN</a>|
|[ToDate](#ToDate)||<a href="TaxWithholdProvisionalReceipt_IN.md" target="_blank">Transaction/TaxWithholdProvisionalReceipt_IN</a>|
|[DataAreaId](#DataAreaId)||<a href="TaxWithholdProvisionalReceipt_IN.md" target="_blank">Transaction/TaxWithholdProvisionalReceipt_IN</a>|
|[Relationship_TaxWithholdRegNumberRelationshipId](#Relationship_TaxWithholdRegNumberRelationshipId)||<a href="TaxWithholdProvisionalReceipt_IN.md" target="_blank">Transaction/TaxWithholdProvisionalReceipt_IN</a>|
|[Relationship_CompanyRelationshipId](#Relationship_CompanyRelationshipId)||<a href="TaxWithholdProvisionalReceipt_IN.md" target="_blank">Transaction/TaxWithholdProvisionalReceipt_IN</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: Transaction/TaxWithholdProvisionalReceipt_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[TaxWithholdProvisionalReceipt_IN/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#CorrectionType name="CorrectionType">CorrectionType</a>

First included in: Transaction/TaxWithholdProvisionalReceipt_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CorrectionType attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.readOnly**  
**is.dataFormat.integer**  
</details>

### <a href=#FromDate name="FromDate">FromDate</a>

First included in: Transaction/TaxWithholdProvisionalReceipt_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FromDate attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.readOnly**  
**is.dataFormat.date**  
</details>

### <a href=#PeriodEnd name="PeriodEnd">PeriodEnd</a>

First included in: Transaction/TaxWithholdProvisionalReceipt_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PeriodEnd attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.readOnly**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PrintingDate name="PrintingDate">PrintingDate</a>

First included in: Transaction/TaxWithholdProvisionalReceipt_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrintingDate attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.readOnly**  
**is.dataFormat.date**  
</details>

### <a href=#ProvisionalReceiptNumber name="ProvisionalReceiptNumber">ProvisionalReceiptNumber</a>

First included in: Transaction/TaxWithholdProvisionalReceipt_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProvisionalReceiptNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ReceiptNumber name="ReceiptNumber">ReceiptNumber</a>

First included in: Transaction/TaxWithholdProvisionalReceipt_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReceiptNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Statement name="Statement">Statement</a>

First included in: Transaction/TaxWithholdProvisionalReceipt_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Statement attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.readOnly**  
**is.dataFormat.integer**  
</details>

### <a href=#Status name="Status">Status</a>

First included in: Transaction/TaxWithholdProvisionalReceipt_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Status attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.readOnly**  
**is.dataFormat.integer**  
</details>

### <a href=#TaxType name="TaxType">TaxType</a>

First included in: Transaction/TaxWithholdProvisionalReceipt_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxType attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#TaxWithholdRegNumber name="TaxWithholdRegNumber">TaxWithholdRegNumber</a>

First included in: Transaction/TaxWithholdProvisionalReceipt_IN (this entity)  

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

First included in: Transaction/TaxWithholdProvisionalReceipt_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ToDate attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.readOnly**  
**is.dataFormat.date**  
</details>

### <a href=#DataAreaId name="DataAreaId">DataAreaId</a>

First included in: Transaction/TaxWithholdProvisionalReceipt_IN (this entity)  

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

First included in: Transaction/TaxWithholdProvisionalReceipt_IN (this entity)  

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

First included in: Transaction/TaxWithholdProvisionalReceipt_IN (this entity)  

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
