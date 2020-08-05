---
title: RetailFiscalPrinterConfigTableEntity in BrickAndMortarStore - Common Data Model | Microsoft Docs
description: undefined
author: llawwaii
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 8/5/2020
ms.author: weiluo
---

# Fiscal register configurations in BrickAndMortarStore(RetailFiscalPrinterConfigTableEntity)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/Commerce/ChannelManagement/BrickAndMortarStore/RetailFiscalPrinterConfigTableEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Fiscal register configurations</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[ConfigurationId](#ConfigurationId)||<a href="RetailFiscalPrinterConfigTableEntity.md" target="_blank">BrickAndMortarStore/RetailFiscalPrinterConfigTableEntity</a>|
|[Description](#Description)||<a href="RetailFiscalPrinterConfigTableEntity.md" target="_blank">BrickAndMortarStore/RetailFiscalPrinterConfigTableEntity</a>|
|[ConfigurationContent](#ConfigurationContent)||<a href="RetailFiscalPrinterConfigTableEntity.md" target="_blank">BrickAndMortarStore/RetailFiscalPrinterConfigTableEntity</a>|
|[BackingTable_RetailFiscalPrinterConfigTableRelationshipId](#BackingTable_RetailFiscalPrinterConfigTableRelationshipId)||<a href="RetailFiscalPrinterConfigTableEntity.md" target="_blank">BrickAndMortarStore/RetailFiscalPrinterConfigTableEntity</a>|

### <a href=#ConfigurationId name="ConfigurationId">ConfigurationId</a>

First included in: BrickAndMortarStore/RetailFiscalPrinterConfigTableEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ConfigurationId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Description name="Description">Description</a>

First included in: BrickAndMortarStore/RetailFiscalPrinterConfigTableEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Description attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ConfigurationContent name="ConfigurationContent">ConfigurationContent</a>

First included in: BrickAndMortarStore/RetailFiscalPrinterConfigTableEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ConfigurationContent attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BackingTable_RetailFiscalPrinterConfigTableRelationshipId name="BackingTable_RetailFiscalPrinterConfigTableRelationshipId">BackingTable_RetailFiscalPrinterConfigTableRelationshipId</a>

First included in: BrickAndMortarStore/RetailFiscalPrinterConfigTableEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_RetailFiscalPrinterConfigTableRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../../Tables/Commerce/ChannelManagement/BrickAndMortarStore/Group/RetailFiscalPrinterConfigTable.md" target="_blank">/core/operationsCommon/Tables/Commerce/ChannelManagement/BrickAndMortarStore/Group/RetailFiscalPrinterConfigTable.cdm.json/RetailFiscalPrinterConfigTable</a></td><td><a href="../../../../Tables/Commerce/ChannelManagement/BrickAndMortarStore/Group/RetailFiscalPrinterConfigTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>
