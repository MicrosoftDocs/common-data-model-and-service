---
title: RetailFiscalDocumentModel2_BR - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/21/2020
ms.author: nebanfic
---

# RetailFiscalDocumentModel2_BR

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Tables/Finance/FiscalBooksBrazil/TransactionHeader/RetailFiscalDocumentModel2_BR.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[RetailFiscalDocumentModel2_BR/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="RetailFiscalDocumentModel2_BR.md" target="_blank">TransactionHeader/RetailFiscalDocumentModel2_BR</a>|
|[ConsumerCNPJCPFNumber](#ConsumerCNPJCPFNumber)||<a href="RetailFiscalDocumentModel2_BR.md" target="_blank">TransactionHeader/RetailFiscalDocumentModel2_BR</a>|
|[FiscalDocumentAccountNum](#FiscalDocumentAccountNum)||<a href="RetailFiscalDocumentModel2_BR.md" target="_blank">TransactionHeader/RetailFiscalDocumentModel2_BR</a>|
|[FiscalDocumentDate](#FiscalDocumentDate)||<a href="RetailFiscalDocumentModel2_BR.md" target="_blank">TransactionHeader/RetailFiscalDocumentModel2_BR</a>|
|[FiscalDocumentNumber](#FiscalDocumentNumber)||<a href="RetailFiscalDocumentModel2_BR.md" target="_blank">TransactionHeader/RetailFiscalDocumentModel2_BR</a>|
|[FiscalDocumentSeries](#FiscalDocumentSeries)||<a href="RetailFiscalDocumentModel2_BR.md" target="_blank">TransactionHeader/RetailFiscalDocumentModel2_BR</a>|
|[Origin](#Origin)||<a href="RetailFiscalDocumentModel2_BR.md" target="_blank">TransactionHeader/RetailFiscalDocumentModel2_BR</a>|
|[ReplicationCounterFromOrigin](#ReplicationCounterFromOrigin)||<a href="RetailFiscalDocumentModel2_BR.md" target="_blank">TransactionHeader/RetailFiscalDocumentModel2_BR</a>|
|[Status](#Status)||<a href="RetailFiscalDocumentModel2_BR.md" target="_blank">TransactionHeader/RetailFiscalDocumentModel2_BR</a>|
|[StoreId](#StoreId)||<a href="RetailFiscalDocumentModel2_BR.md" target="_blank">TransactionHeader/RetailFiscalDocumentModel2_BR</a>|
|[TerminalId](#TerminalId)||<a href="RetailFiscalDocumentModel2_BR.md" target="_blank">TransactionHeader/RetailFiscalDocumentModel2_BR</a>|
|[TotalAmount](#TotalAmount)||<a href="RetailFiscalDocumentModel2_BR.md" target="_blank">TransactionHeader/RetailFiscalDocumentModel2_BR</a>|
|[TotalDiscountAmount](#TotalDiscountAmount)||<a href="RetailFiscalDocumentModel2_BR.md" target="_blank">TransactionHeader/RetailFiscalDocumentModel2_BR</a>|
|[TotalSurchargeAmount](#TotalSurchargeAmount)||<a href="RetailFiscalDocumentModel2_BR.md" target="_blank">TransactionHeader/RetailFiscalDocumentModel2_BR</a>|
|[TransactionId](#TransactionId)||<a href="RetailFiscalDocumentModel2_BR.md" target="_blank">TransactionHeader/RetailFiscalDocumentModel2_BR</a>|
|[DataAreaId](#DataAreaId)||<a href="RetailFiscalDocumentModel2_BR.md" target="_blank">TransactionHeader/RetailFiscalDocumentModel2_BR</a>|
|[Relationship_CompanyRelationshipId](#Relationship_CompanyRelationshipId)||<a href="RetailFiscalDocumentModel2_BR.md" target="_blank">TransactionHeader/RetailFiscalDocumentModel2_BR</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: TransactionHeader/RetailFiscalDocumentModel2_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[RetailFiscalDocumentModel2_BR/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#ConsumerCNPJCPFNumber name="ConsumerCNPJCPFNumber">ConsumerCNPJCPFNumber</a>

First included in: TransactionHeader/RetailFiscalDocumentModel2_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ConsumerCNPJCPFNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FiscalDocumentAccountNum name="FiscalDocumentAccountNum">FiscalDocumentAccountNum</a>

First included in: TransactionHeader/RetailFiscalDocumentModel2_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FiscalDocumentAccountNum attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FiscalDocumentDate name="FiscalDocumentDate">FiscalDocumentDate</a>

First included in: TransactionHeader/RetailFiscalDocumentModel2_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FiscalDocumentDate attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.dataFormat.date**  
</details>

### <a href=#FiscalDocumentNumber name="FiscalDocumentNumber">FiscalDocumentNumber</a>

First included in: TransactionHeader/RetailFiscalDocumentModel2_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FiscalDocumentNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FiscalDocumentSeries name="FiscalDocumentSeries">FiscalDocumentSeries</a>

First included in: TransactionHeader/RetailFiscalDocumentModel2_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FiscalDocumentSeries attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Origin name="Origin">Origin</a>

First included in: TransactionHeader/RetailFiscalDocumentModel2_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Origin attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ReplicationCounterFromOrigin name="ReplicationCounterFromOrigin">ReplicationCounterFromOrigin</a>

First included in: TransactionHeader/RetailFiscalDocumentModel2_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReplicationCounterFromOrigin attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#Status name="Status">Status</a>

First included in: TransactionHeader/RetailFiscalDocumentModel2_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Status attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#StoreId name="StoreId">StoreId</a>

First included in: TransactionHeader/RetailFiscalDocumentModel2_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the StoreId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TerminalId name="TerminalId">TerminalId</a>

First included in: TransactionHeader/RetailFiscalDocumentModel2_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TerminalId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TotalAmount name="TotalAmount">TotalAmount</a>

First included in: TransactionHeader/RetailFiscalDocumentModel2_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TotalAmount attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#TotalDiscountAmount name="TotalDiscountAmount">TotalDiscountAmount</a>

First included in: TransactionHeader/RetailFiscalDocumentModel2_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TotalDiscountAmount attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#TotalSurchargeAmount name="TotalSurchargeAmount">TotalSurchargeAmount</a>

First included in: TransactionHeader/RetailFiscalDocumentModel2_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TotalSurchargeAmount attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#TransactionId name="TransactionId">TransactionId</a>

First included in: TransactionHeader/RetailFiscalDocumentModel2_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TransactionId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DataAreaId name="DataAreaId">DataAreaId</a>

First included in: TransactionHeader/RetailFiscalDocumentModel2_BR (this entity)  

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

### <a href=#Relationship_CompanyRelationshipId name="Relationship_CompanyRelationshipId">Relationship_CompanyRelationshipId</a>

First included in: TransactionHeader/RetailFiscalDocumentModel2_BR (this entity)  

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
