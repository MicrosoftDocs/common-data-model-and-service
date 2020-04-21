---
title: AssetDepDistributionLine_JP - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/21/2020
ms.author: nebanfic
---

# AssetDepDistributionLine_JP

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Tables/Finance/FixedAssets/Transaction/AssetDepDistributionLine_JP.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[AssetDepDistributionLine_JP/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="AssetDepDistributionLine_JP.md" target="_blank">Transaction/AssetDepDistributionLine_JP</a>|
|[AmountCur](#AmountCur)||<a href="AssetDepDistributionLine_JP.md" target="_blank">Transaction/AssetDepDistributionLine_JP</a>|
|[AmountMST](#AmountMST)||<a href="AssetDepDistributionLine_JP.md" target="_blank">Transaction/AssetDepDistributionLine_JP</a>|
|[AssetDepDistribution_JP](#AssetDepDistribution_JP)||<a href="AssetDepDistributionLine_JP.md" target="_blank">Transaction/AssetDepDistributionLine_JP</a>|
|[Description](#Description)||<a href="AssetDepDistributionLine_JP.md" target="_blank">Transaction/AssetDepDistributionLine_JP</a>|
|[DocmentType](#DocmentType)||<a href="AssetDepDistributionLine_JP.md" target="_blank">Transaction/AssetDepDistributionLine_JP</a>|
|[RefReserveAmount](#RefReserveAmount)||<a href="AssetDepDistributionLine_JP.md" target="_blank">Transaction/AssetDepDistributionLine_JP</a>|
|[RefReserveDate](#RefReserveDate)||<a href="AssetDepDistributionLine_JP.md" target="_blank">Transaction/AssetDepDistributionLine_JP</a>|
|[RefReserveDocType](#RefReserveDocType)||<a href="AssetDepDistributionLine_JP.md" target="_blank">Transaction/AssetDepDistributionLine_JP</a>|
|[RefReserveRecId](#RefReserveRecId)||<a href="AssetDepDistributionLine_JP.md" target="_blank">Transaction/AssetDepDistributionLine_JP</a>|
|[RefReserveTableId](#RefReserveTableId)||<a href="AssetDepDistributionLine_JP.md" target="_blank">Transaction/AssetDepDistributionLine_JP</a>|
|[TransDate](#TransDate)||<a href="AssetDepDistributionLine_JP.md" target="_blank">Transaction/AssetDepDistributionLine_JP</a>|
|[TransType](#TransType)||<a href="AssetDepDistributionLine_JP.md" target="_blank">Transaction/AssetDepDistributionLine_JP</a>|
|[Voucher](#Voucher)||<a href="AssetDepDistributionLine_JP.md" target="_blank">Transaction/AssetDepDistributionLine_JP</a>|
|[DataAreaId](#DataAreaId)||<a href="AssetDepDistributionLine_JP.md" target="_blank">Transaction/AssetDepDistributionLine_JP</a>|
|[Relationship_AssetDepDistribution_JPRelationshipId](#Relationship_AssetDepDistribution_JPRelationshipId)||<a href="AssetDepDistributionLine_JP.md" target="_blank">Transaction/AssetDepDistributionLine_JP</a>|
|[Relationship_CompanyRelationshipId](#Relationship_CompanyRelationshipId)||<a href="AssetDepDistributionLine_JP.md" target="_blank">Transaction/AssetDepDistributionLine_JP</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: Transaction/AssetDepDistributionLine_JP (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[AssetDepDistributionLine_JP/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#AmountCur name="AmountCur">AmountCur</a>

First included in: Transaction/AssetDepDistributionLine_JP (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AmountCur attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#AmountMST name="AmountMST">AmountMST</a>

First included in: Transaction/AssetDepDistributionLine_JP (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AmountMST attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#AssetDepDistribution_JP name="AssetDepDistribution_JP">AssetDepDistribution_JP</a>

First included in: Transaction/AssetDepDistributionLine_JP (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AssetDepDistribution_JP attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#Description name="Description">Description</a>

First included in: Transaction/AssetDepDistributionLine_JP (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Description attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DocmentType name="DocmentType">DocmentType</a>

First included in: Transaction/AssetDepDistributionLine_JP (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DocmentType attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#RefReserveAmount name="RefReserveAmount">RefReserveAmount</a>

First included in: Transaction/AssetDepDistributionLine_JP (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RefReserveAmount attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#RefReserveDate name="RefReserveDate">RefReserveDate</a>

First included in: Transaction/AssetDepDistributionLine_JP (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RefReserveDate attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.dataFormat.date**  
</details>

### <a href=#RefReserveDocType name="RefReserveDocType">RefReserveDocType</a>

First included in: Transaction/AssetDepDistributionLine_JP (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RefReserveDocType attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#RefReserveRecId name="RefReserveRecId">RefReserveRecId</a>

First included in: Transaction/AssetDepDistributionLine_JP (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RefReserveRecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#RefReserveTableId name="RefReserveTableId">RefReserveTableId</a>

First included in: Transaction/AssetDepDistributionLine_JP (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RefReserveTableId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#TransDate name="TransDate">TransDate</a>

First included in: Transaction/AssetDepDistributionLine_JP (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TransDate attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.dataFormat.date**  
</details>

### <a href=#TransType name="TransType">TransType</a>

First included in: Transaction/AssetDepDistributionLine_JP (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TransType attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#Voucher name="Voucher">Voucher</a>

First included in: Transaction/AssetDepDistributionLine_JP (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Voucher attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DataAreaId name="DataAreaId">DataAreaId</a>

First included in: Transaction/AssetDepDistributionLine_JP (this entity)  

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

### <a href=#Relationship_AssetDepDistribution_JPRelationshipId name="Relationship_AssetDepDistribution_JPRelationshipId">Relationship_AssetDepDistribution_JPRelationshipId</a>

First included in: Transaction/AssetDepDistributionLine_JP (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_AssetDepDistribution_JPRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="AssetDepDistribution_JP.md" target="_blank">/core/operationsCommon/Tables/Finance/FixedAssets/Transaction/AssetDepDistribution_JP.cdm.json/AssetDepDistribution_JP</a></td><td><a href="AssetDepDistribution_JP.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_CompanyRelationshipId name="Relationship_CompanyRelationshipId">Relationship_CompanyRelationshipId</a>

First included in: Transaction/AssetDepDistributionLine_JP (this entity)  

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
