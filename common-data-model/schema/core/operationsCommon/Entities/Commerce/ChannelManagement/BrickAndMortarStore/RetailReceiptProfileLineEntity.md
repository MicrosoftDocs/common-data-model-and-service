---
title: RetailReceiptProfileLineEntity in BrickAndMortarStore - Common Data Model | Microsoft Docs
description: undefined
author: llawwaii
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: reference
ms.date: 8/7/2020
ms.author: weiluo
---

# Receipt profile line in BrickAndMortarStore(RetailReceiptProfileLineEntity)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/Commerce/ChannelManagement/BrickAndMortarStore/RetailReceiptProfileLineEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Receipt profile line</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[FormLayoutId](#FormLayoutId)||<a href="RetailReceiptProfileLineEntity.md" target="_blank">BrickAndMortarStore/RetailReceiptProfileLineEntity</a>|
|[ProfileId](#ProfileId)||<a href="RetailReceiptProfileLineEntity.md" target="_blank">BrickAndMortarStore/RetailReceiptProfileLineEntity</a>|
|[ReceiptType](#ReceiptType)||<a href="RetailReceiptProfileLineEntity.md" target="_blank">BrickAndMortarStore/RetailReceiptProfileLineEntity</a>|
|[RetailReceiptProfile1_ProfileId](#RetailReceiptProfile1_ProfileId)||<a href="RetailReceiptProfileLineEntity.md" target="_blank">BrickAndMortarStore/RetailReceiptProfileLineEntity</a>|
|[RetailFormLayout1_FormLayoutId](#RetailFormLayout1_FormLayoutId)||<a href="RetailReceiptProfileLineEntity.md" target="_blank">BrickAndMortarStore/RetailReceiptProfileLineEntity</a>|
|[RetailFormLayout1_LayoutType](#RetailFormLayout1_LayoutType)||<a href="RetailReceiptProfileLineEntity.md" target="_blank">BrickAndMortarStore/RetailReceiptProfileLineEntity</a>|
|[BackingTable_RetailReceiptProfileLineRelationshipId](#BackingTable_RetailReceiptProfileLineRelationshipId)||<a href="RetailReceiptProfileLineEntity.md" target="_blank">BrickAndMortarStore/RetailReceiptProfileLineEntity</a>|

### <a href=#FormLayoutId name="FormLayoutId">FormLayoutId</a>

First included in: BrickAndMortarStore/RetailReceiptProfileLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FormLayoutId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProfileId name="ProfileId">ProfileId</a>

First included in: BrickAndMortarStore/RetailReceiptProfileLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProfileId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ReceiptType name="ReceiptType">ReceiptType</a>

First included in: BrickAndMortarStore/RetailReceiptProfileLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReceiptType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RetailReceiptProfile1_ProfileId name="RetailReceiptProfile1_ProfileId">RetailReceiptProfile1_ProfileId</a>

First included in: BrickAndMortarStore/RetailReceiptProfileLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RetailReceiptProfile1_ProfileId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RetailFormLayout1_FormLayoutId name="RetailFormLayout1_FormLayoutId">RetailFormLayout1_FormLayoutId</a>

First included in: BrickAndMortarStore/RetailReceiptProfileLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RetailFormLayout1_FormLayoutId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RetailFormLayout1_LayoutType name="RetailFormLayout1_LayoutType">RetailFormLayout1_LayoutType</a>

First included in: BrickAndMortarStore/RetailReceiptProfileLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RetailFormLayout1_LayoutType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BackingTable_RetailReceiptProfileLineRelationshipId name="BackingTable_RetailReceiptProfileLineRelationshipId">BackingTable_RetailReceiptProfileLineRelationshipId</a>

First included in: BrickAndMortarStore/RetailReceiptProfileLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_RetailReceiptProfileLineRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../../Tables/Commerce/ChannelManagement/BrickAndMortarStore/Miscellaneous/RetailReceiptProfileLine.md" target="_blank">/core/operationsCommon/Tables/Commerce/ChannelManagement/BrickAndMortarStore/Miscellaneous/RetailReceiptProfileLine.cdm.json/RetailReceiptProfileLine</a></td><td><a href="../../../../Tables/Commerce/ChannelManagement/BrickAndMortarStore/Miscellaneous/RetailReceiptProfileLine.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>
