---
title: ExchangeRateCurrencyPairCalculationRules - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/17/2020
ms.author: nebanfic
---

# ExchangeRateCurrencyPairCalculationRules

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/erp/Tables/Common/Currency/Miscellaneous/ExchangeRateCurrencyPairCalculationRules.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[ExchangeRateCurrencyPairCalculationRules/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="ExchangeRateCurrencyPairCalculationRules.md" target="_blank">Miscellaneous/ExchangeRateCurrencyPairCalculationRules</a>|
|[CurrencyFrom](#CurrencyFrom)||<a href="ExchangeRateCurrencyPairCalculationRules.md" target="_blank">Miscellaneous/ExchangeRateCurrencyPairCalculationRules</a>|
|[CurrencyTo](#CurrencyTo)||<a href="ExchangeRateCurrencyPairCalculationRules.md" target="_blank">Miscellaneous/ExchangeRateCurrencyPairCalculationRules</a>|
|[CurrencyTriangulation](#CurrencyTriangulation)||<a href="ExchangeRateCurrencyPairCalculationRules.md" target="_blank">Miscellaneous/ExchangeRateCurrencyPairCalculationRules</a>|
|[DataArea](#DataArea)||<a href="ExchangeRateCurrencyPairCalculationRules.md" target="_blank">Miscellaneous/ExchangeRateCurrencyPairCalculationRules</a>|
|[DataAreaTableAll](#DataAreaTableAll)||<a href="ExchangeRateCurrencyPairCalculationRules.md" target="_blank">Miscellaneous/ExchangeRateCurrencyPairCalculationRules</a>|
|[ExchangeRateType](#ExchangeRateType)||<a href="ExchangeRateCurrencyPairCalculationRules.md" target="_blank">Miscellaneous/ExchangeRateCurrencyPairCalculationRules</a>|
|[ExchangeRateTypeTableAll](#ExchangeRateTypeTableAll)||<a href="ExchangeRateCurrencyPairCalculationRules.md" target="_blank">Miscellaneous/ExchangeRateCurrencyPairCalculationRules</a>|
|[Relationship_CurrencyFromRelationshipId](#Relationship_CurrencyFromRelationshipId)||<a href="ExchangeRateCurrencyPairCalculationRules.md" target="_blank">Miscellaneous/ExchangeRateCurrencyPairCalculationRules</a>|
|[Relationship_CurrencyToRelationshipId](#Relationship_CurrencyToRelationshipId)||<a href="ExchangeRateCurrencyPairCalculationRules.md" target="_blank">Miscellaneous/ExchangeRateCurrencyPairCalculationRules</a>|
|[Relationship_CurrencyTriangulationRelationshipId](#Relationship_CurrencyTriangulationRelationshipId)||<a href="ExchangeRateCurrencyPairCalculationRules.md" target="_blank">Miscellaneous/ExchangeRateCurrencyPairCalculationRules</a>|
|[Relationship_ExchangeRateTypeRelationshipId](#Relationship_ExchangeRateTypeRelationshipId)||<a href="ExchangeRateCurrencyPairCalculationRules.md" target="_blank">Miscellaneous/ExchangeRateCurrencyPairCalculationRules</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: Miscellaneous/ExchangeRateCurrencyPairCalculationRules (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[ExchangeRateCurrencyPairCalculationRules/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#CurrencyFrom name="CurrencyFrom">CurrencyFrom</a>

First included in: Miscellaneous/ExchangeRateCurrencyPairCalculationRules (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CurrencyFrom attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CurrencyTo name="CurrencyTo">CurrencyTo</a>

First included in: Miscellaneous/ExchangeRateCurrencyPairCalculationRules (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CurrencyTo attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CurrencyTriangulation name="CurrencyTriangulation">CurrencyTriangulation</a>

First included in: Miscellaneous/ExchangeRateCurrencyPairCalculationRules (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CurrencyTriangulation attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DataArea name="DataArea">DataArea</a>

First included in: Miscellaneous/ExchangeRateCurrencyPairCalculationRules (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DataArea attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DataAreaTableAll name="DataAreaTableAll">DataAreaTableAll</a>

First included in: Miscellaneous/ExchangeRateCurrencyPairCalculationRules (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DataAreaTableAll attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#ExchangeRateType name="ExchangeRateType">ExchangeRateType</a>

First included in: Miscellaneous/ExchangeRateCurrencyPairCalculationRules (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ExchangeRateType attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#ExchangeRateTypeTableAll name="ExchangeRateTypeTableAll">ExchangeRateTypeTableAll</a>

First included in: Miscellaneous/ExchangeRateCurrencyPairCalculationRules (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ExchangeRateTypeTableAll attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#Relationship_CurrencyFromRelationshipId name="Relationship_CurrencyFromRelationshipId">Relationship_CurrencyFromRelationshipId</a>

First included in: Miscellaneous/ExchangeRateCurrencyPairCalculationRules (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_CurrencyFromRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Group/Currency.md" target="_blank">/core/erp/Tables/Common/Currency/Group/Currency.cdm.json/Currency</a></td><td><a href="../Group/Currency.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_CurrencyToRelationshipId name="Relationship_CurrencyToRelationshipId">Relationship_CurrencyToRelationshipId</a>

First included in: Miscellaneous/ExchangeRateCurrencyPairCalculationRules (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_CurrencyToRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Group/Currency.md" target="_blank">/core/erp/Tables/Common/Currency/Group/Currency.cdm.json/Currency</a></td><td><a href="../Group/Currency.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_CurrencyTriangulationRelationshipId name="Relationship_CurrencyTriangulationRelationshipId">Relationship_CurrencyTriangulationRelationshipId</a>

First included in: Miscellaneous/ExchangeRateCurrencyPairCalculationRules (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_CurrencyTriangulationRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Group/Currency.md" target="_blank">/core/erp/Tables/Common/Currency/Group/Currency.cdm.json/Currency</a></td><td><a href="../Group/Currency.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_ExchangeRateTypeRelationshipId name="Relationship_ExchangeRateTypeRelationshipId">Relationship_ExchangeRateTypeRelationshipId</a>

First included in: Miscellaneous/ExchangeRateCurrencyPairCalculationRules (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_ExchangeRateTypeRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Group/ExchangeRateType.md" target="_blank">/core/erp/Tables/Common/Currency/Group/ExchangeRateType.cdm.json/ExchangeRateType</a></td><td><a href="../Group/ExchangeRateType.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>
