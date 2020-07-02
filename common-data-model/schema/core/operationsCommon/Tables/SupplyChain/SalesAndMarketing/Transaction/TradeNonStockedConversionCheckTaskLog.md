---
title: TradeNonStockedConversionCheckTaskLog - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 6/30/2020
ms.author: nebanfic
---

# Conversion check task log for products not stocked

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Tables/SupplyChain/SalesAndMarketing/Transaction/TradeNonStockedConversionCheckTaskLog.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[TradeNonStockedConversionCheckTaskLog/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Conversion check task log for products not stocked</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="TradeNonStockedConversionCheckTaskLog.md" target="_blank">Transaction/TradeNonStockedConversionCheckTaskLog</a>|
|[NonStockedConversion](#NonStockedConversion)||<a href="TradeNonStockedConversionCheckTaskLog.md" target="_blank">Transaction/TradeNonStockedConversionCheckTaskLog</a>|
|[ReadinessRunDateTimeEnd](#ReadinessRunDateTimeEnd)||<a href="TradeNonStockedConversionCheckTaskLog.md" target="_blank">Transaction/TradeNonStockedConversionCheckTaskLog</a>|
|[ReadinessRunDateTimeStart](#ReadinessRunDateTimeStart)||<a href="TradeNonStockedConversionCheckTaskLog.md" target="_blank">Transaction/TradeNonStockedConversionCheckTaskLog</a>|
|[Relationship_TradeNonStockedConversionRelationshipId](#Relationship_TradeNonStockedConversionRelationshipId)||<a href="TradeNonStockedConversionCheckTaskLog.md" target="_blank">Transaction/TradeNonStockedConversionCheckTaskLog</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: Transaction/TradeNonStockedConversionCheckTaskLog (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[TradeNonStockedConversionCheckTaskLog/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#NonStockedConversion name="NonStockedConversion">NonStockedConversion</a>

First included in: Transaction/TradeNonStockedConversionCheckTaskLog (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the NonStockedConversion attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#ReadinessRunDateTimeEnd name="ReadinessRunDateTimeEnd">ReadinessRunDateTimeEnd</a>

First included in: Transaction/TradeNonStockedConversionCheckTaskLog (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReadinessRunDateTimeEnd attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.readOnly**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.date**  
</details>

### <a href=#ReadinessRunDateTimeStart name="ReadinessRunDateTimeStart">ReadinessRunDateTimeStart</a>

First included in: Transaction/TradeNonStockedConversionCheckTaskLog (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReadinessRunDateTimeStart attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.readOnly**  
**is.dataFormat.date**  
</details>

### <a href=#Relationship_TradeNonStockedConversionRelationshipId name="Relationship_TradeNonStockedConversionRelationshipId">Relationship_TradeNonStockedConversionRelationshipId</a>

First included in: Transaction/TradeNonStockedConversionCheckTaskLog (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_TradeNonStockedConversionRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../WorksheetHeader/TradeNonStockedConversion.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/SalesAndMarketing/WorksheetHeader/TradeNonStockedConversion.cdm.json/TradeNonStockedConversion</a></td><td><a href="../WorksheetHeader/TradeNonStockedConversion.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>
