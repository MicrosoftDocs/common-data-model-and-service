---
title: TradeNonStockedConversionLog in Transaction - Common Data Model | Microsoft Docs
description: undefined
author: llawwaii
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 8/5/2020
ms.author: weiluo
---

# Conversion log for products not stocked in Transaction(TradeNonStockedConversionLog)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Tables/SupplyChain/SalesAndMarketing/Transaction/TradeNonStockedConversionLog.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[TradeNonStockedConversionLog/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.1"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Conversion log for products not stocked</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="TradeNonStockedConversionLog.md" target="_blank">Transaction/TradeNonStockedConversionLog</a>|
|[IdentifyingAttributeValue](#IdentifyingAttributeValue)||<a href="TradeNonStockedConversionLog.md" target="_blank">Transaction/TradeNonStockedConversionLog</a>|
|[IdentifyingField](#IdentifyingField)||<a href="TradeNonStockedConversionLog.md" target="_blank">Transaction/TradeNonStockedConversionLog</a>|
|[IdentifyingTable](#IdentifyingTable)||<a href="TradeNonStockedConversionLog.md" target="_blank">Transaction/TradeNonStockedConversionLog</a>|
|[InstanceRelationType](#InstanceRelationType)||<a href="TradeNonStockedConversionLog.md" target="_blank">Transaction/TradeNonStockedConversionLog</a>|
|[NonStockedConversionItem](#NonStockedConversionItem)||<a href="TradeNonStockedConversionLog.md" target="_blank">Transaction/TradeNonStockedConversionLog</a>|
|[NonStockedConversionLogParent](#NonStockedConversionLogParent)||<a href="TradeNonStockedConversionLog.md" target="_blank">Transaction/TradeNonStockedConversionLog</a>|
|[Relationship_TradeNonStockedConversionItemRelationshipId](#Relationship_TradeNonStockedConversionItemRelationshipId)||<a href="TradeNonStockedConversionLog.md" target="_blank">Transaction/TradeNonStockedConversionLog</a>|
|[Relationship_TradeNonStockedConversionLogParentRelationshipId](#Relationship_TradeNonStockedConversionLogParentRelationshipId)||<a href="TradeNonStockedConversionLog.md" target="_blank">Transaction/TradeNonStockedConversionLog</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: Transaction/TradeNonStockedConversionLog (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[TradeNonStockedConversionLog/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#IdentifyingAttributeValue name="IdentifyingAttributeValue">IdentifyingAttributeValue</a>

First included in: Transaction/TradeNonStockedConversionLog (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IdentifyingAttributeValue attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IdentifyingField name="IdentifyingField">IdentifyingField</a>

First included in: Transaction/TradeNonStockedConversionLog (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IdentifyingField attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#IdentifyingTable name="IdentifyingTable">IdentifyingTable</a>

First included in: Transaction/TradeNonStockedConversionLog (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IdentifyingTable attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#InstanceRelationType name="InstanceRelationType">InstanceRelationType</a>

First included in: Transaction/TradeNonStockedConversionLog (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InstanceRelationType attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.readOnly**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#NonStockedConversionItem name="NonStockedConversionItem">NonStockedConversionItem</a>

First included in: Transaction/TradeNonStockedConversionLog (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>unknown</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the NonStockedConversionItem attribute are listed below.</summary>

**is.nullable**  
The attribute value may be set to NULL.  

</details>

### <a href=#NonStockedConversionLogParent name="NonStockedConversionLogParent">NonStockedConversionLogParent</a>

First included in: Transaction/TradeNonStockedConversionLog (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>unknown</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the NonStockedConversionLogParent attribute are listed below.</summary>

**is.nullable**  
The attribute value may be set to NULL.  

</details>

### <a href=#Relationship_TradeNonStockedConversionItemRelationshipId name="Relationship_TradeNonStockedConversionItemRelationshipId">Relationship_TradeNonStockedConversionItemRelationshipId</a>

First included in: Transaction/TradeNonStockedConversionLog (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_TradeNonStockedConversionItemRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../WorksheetLine/TradeNonStockedConversionItem.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/SalesAndMarketing/WorksheetLine/TradeNonStockedConversionItem.cdm.json/TradeNonStockedConversionItem</a></td><td><a href="../WorksheetLine/TradeNonStockedConversionItem.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_TradeNonStockedConversionLogParentRelationshipId name="Relationship_TradeNonStockedConversionLogParentRelationshipId">Relationship_TradeNonStockedConversionLogParentRelationshipId</a>

First included in: Transaction/TradeNonStockedConversionLog (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_TradeNonStockedConversionLogParentRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="TradeNonStockedConversionLogParent.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/SalesAndMarketing/Transaction/TradeNonStockedConversionLogParent.cdm.json/TradeNonStockedConversionLogParent</a></td><td><a href="TradeNonStockedConversionLogParent.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>
