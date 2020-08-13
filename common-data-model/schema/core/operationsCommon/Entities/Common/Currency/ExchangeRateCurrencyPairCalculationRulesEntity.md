---
title: ExchangeRateCurrencyPairCalculationRulesEntity in Currency - Common Data Model | Microsoft Docs
description: undefined
author: llawwaii
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 8/7/2020
ms.author: weiluo
---

# Exchange rate calculation rules for sales tax in Currency(ExchangeRateCurrencyPairCalculationRulesEntity)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/Common/Currency/ExchangeRateCurrencyPairCalculationRulesEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.1"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Exchange rate calculation rules for sales tax</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[ValidForExchangeRateType](#ValidForExchangeRateType)||<a href="ExchangeRateCurrencyPairCalculationRulesEntity.md" target="_blank">Currency/ExchangeRateCurrencyPairCalculationRulesEntity</a>|
|[ExchangeRateTypeRecId](#ExchangeRateTypeRecId)||<a href="ExchangeRateCurrencyPairCalculationRulesEntity.md" target="_blank">Currency/ExchangeRateCurrencyPairCalculationRulesEntity</a>|
|[ExchangeRateType](#ExchangeRateType)||<a href="ExchangeRateCurrencyPairCalculationRulesEntity.md" target="_blank">Currency/ExchangeRateCurrencyPairCalculationRulesEntity</a>|
|[ValidForCompany](#ValidForCompany)||<a href="ExchangeRateCurrencyPairCalculationRulesEntity.md" target="_blank">Currency/ExchangeRateCurrencyPairCalculationRulesEntity</a>|
|[Company](#Company)||<a href="ExchangeRateCurrencyPairCalculationRulesEntity.md" target="_blank">Currency/ExchangeRateCurrencyPairCalculationRulesEntity</a>|
|[FromCurrency](#FromCurrency)||<a href="ExchangeRateCurrencyPairCalculationRulesEntity.md" target="_blank">Currency/ExchangeRateCurrencyPairCalculationRulesEntity</a>|
|[ToCurrency](#ToCurrency)||<a href="ExchangeRateCurrencyPairCalculationRulesEntity.md" target="_blank">Currency/ExchangeRateCurrencyPairCalculationRulesEntity</a>|
|[TriangulationCurrency](#TriangulationCurrency)||<a href="ExchangeRateCurrencyPairCalculationRulesEntity.md" target="_blank">Currency/ExchangeRateCurrencyPairCalculationRulesEntity</a>|
|[BackingTable_ExchangeRateCurrencyPairCalculationRulesRelationshipId](#BackingTable_ExchangeRateCurrencyPairCalculationRulesRelationshipId)||<a href="ExchangeRateCurrencyPairCalculationRulesEntity.md" target="_blank">Currency/ExchangeRateCurrencyPairCalculationRulesEntity</a>|

### <a href=#ValidForExchangeRateType name="ValidForExchangeRateType">ValidForExchangeRateType</a>

First included in: Currency/ExchangeRateCurrencyPairCalculationRulesEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ValidForExchangeRateType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ExchangeRateTypeRecId name="ExchangeRateTypeRecId">ExchangeRateTypeRecId</a>

First included in: Currency/ExchangeRateCurrencyPairCalculationRulesEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ExchangeRateTypeRecId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ExchangeRateType name="ExchangeRateType">ExchangeRateType</a>

First included in: Currency/ExchangeRateCurrencyPairCalculationRulesEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ExchangeRateType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ValidForCompany name="ValidForCompany">ValidForCompany</a>

First included in: Currency/ExchangeRateCurrencyPairCalculationRulesEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ValidForCompany attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Company name="Company">Company</a>

First included in: Currency/ExchangeRateCurrencyPairCalculationRulesEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Company attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FromCurrency name="FromCurrency">FromCurrency</a>

First included in: Currency/ExchangeRateCurrencyPairCalculationRulesEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FromCurrency attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ToCurrency name="ToCurrency">ToCurrency</a>

First included in: Currency/ExchangeRateCurrencyPairCalculationRulesEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ToCurrency attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TriangulationCurrency name="TriangulationCurrency">TriangulationCurrency</a>

First included in: Currency/ExchangeRateCurrencyPairCalculationRulesEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TriangulationCurrency attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BackingTable_ExchangeRateCurrencyPairCalculationRulesRelationshipId name="BackingTable_ExchangeRateCurrencyPairCalculationRulesRelationshipId">BackingTable_ExchangeRateCurrencyPairCalculationRulesRelationshipId</a>

First included in: Currency/ExchangeRateCurrencyPairCalculationRulesEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_ExchangeRateCurrencyPairCalculationRulesRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/Common/Currency/Miscellaneous/ExchangeRateCurrencyPairCalculationRules.md" target="_blank">/core/operationsCommon/Tables/Common/Currency/Miscellaneous/ExchangeRateCurrencyPairCalculationRules.cdm.json/ExchangeRateCurrencyPairCalculationRules</a></td><td><a href="../../../Tables/Common/Currency/Miscellaneous/ExchangeRateCurrencyPairCalculationRules.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>
