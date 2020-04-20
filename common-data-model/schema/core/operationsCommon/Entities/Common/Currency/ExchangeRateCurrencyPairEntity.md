---
title: ExchangeRateCurrencyPairEntity - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/20/2020
ms.author: nebanfic
---

# ExchangeRateCurrencyPairEntity

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/Common/Currency/ExchangeRateCurrencyPairEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[ExchangeRateDisplayFactor](#ExchangeRateDisplayFactor)||<a href="ExchangeRateCurrencyPairEntity.md" target="_blank">Currency/ExchangeRateCurrencyPairEntity</a>|
|[ExchangeRateType](#ExchangeRateType)||<a href="ExchangeRateCurrencyPairEntity.md" target="_blank">Currency/ExchangeRateCurrencyPairEntity</a>|
|[FromCurrencyCode](#FromCurrencyCode)||<a href="ExchangeRateCurrencyPairEntity.md" target="_blank">Currency/ExchangeRateCurrencyPairEntity</a>|
|[ToCurrencyCode](#ToCurrencyCode)||<a href="ExchangeRateCurrencyPairEntity.md" target="_blank">Currency/ExchangeRateCurrencyPairEntity</a>|
|[ExchangeRateTypeName](#ExchangeRateTypeName)||<a href="ExchangeRateCurrencyPairEntity.md" target="_blank">Currency/ExchangeRateCurrencyPairEntity</a>|
|[Relationship_ExchangeRateTypeEntityRelationshipId](#Relationship_ExchangeRateTypeEntityRelationshipId)||<a href="ExchangeRateCurrencyPairEntity.md" target="_blank">Currency/ExchangeRateCurrencyPairEntity</a>|
|[BackingTable_ExchangeRateCurrencyPairRelationshipId](#BackingTable_ExchangeRateCurrencyPairRelationshipId)||<a href="ExchangeRateCurrencyPairEntity.md" target="_blank">Currency/ExchangeRateCurrencyPairEntity</a>|

### <a href=#ExchangeRateDisplayFactor name="ExchangeRateDisplayFactor">ExchangeRateDisplayFactor</a>

First included in: Currency/ExchangeRateCurrencyPairEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ExchangeRateDisplayFactor attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ExchangeRateType name="ExchangeRateType">ExchangeRateType</a>

First included in: Currency/ExchangeRateCurrencyPairEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ExchangeRateType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FromCurrencyCode name="FromCurrencyCode">FromCurrencyCode</a>

First included in: Currency/ExchangeRateCurrencyPairEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FromCurrencyCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ToCurrencyCode name="ToCurrencyCode">ToCurrencyCode</a>

First included in: Currency/ExchangeRateCurrencyPairEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ToCurrencyCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ExchangeRateTypeName name="ExchangeRateTypeName">ExchangeRateTypeName</a>

First included in: Currency/ExchangeRateCurrencyPairEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ExchangeRateTypeName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_ExchangeRateTypeEntityRelationshipId name="Relationship_ExchangeRateTypeEntityRelationshipId">Relationship_ExchangeRateTypeEntityRelationshipId</a>

First included in: Currency/ExchangeRateCurrencyPairEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_ExchangeRateTypeEntityRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td>empty table</td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BackingTable_ExchangeRateCurrencyPairRelationshipId name="BackingTable_ExchangeRateCurrencyPairRelationshipId">BackingTable_ExchangeRateCurrencyPairRelationshipId</a>

First included in: Currency/ExchangeRateCurrencyPairEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_ExchangeRateCurrencyPairRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/Common/Currency/Group/ExchangeRateCurrencyPair.md" target="_blank">/core/operationsCommon/Tables/Common/Currency/Group/ExchangeRateCurrencyPair.cdm.json/ExchangeRateCurrencyPair</a></td><td><a href="../../../Tables/Common/Currency/Group/ExchangeRateCurrencyPair.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>
