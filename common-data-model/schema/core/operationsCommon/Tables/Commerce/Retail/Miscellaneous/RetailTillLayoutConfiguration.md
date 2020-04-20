---
title: RetailTillLayoutConfiguration - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/20/2020
ms.author: nebanfic
---

# RetailTillLayoutConfiguration

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Tables/Commerce/Retail/Miscellaneous/RetailTillLayoutConfiguration.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[RetailTillLayoutConfiguration/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="RetailTillLayoutConfiguration.md" target="_blank">Miscellaneous/RetailTillLayoutConfiguration</a>|
|[LayoutId](#LayoutId)||<a href="RetailTillLayoutConfiguration.md" target="_blank">Miscellaneous/RetailTillLayoutConfiguration</a>|
|[SizeId](#SizeId)||<a href="RetailTillLayoutConfiguration.md" target="_blank">Miscellaneous/RetailTillLayoutConfiguration</a>|
|[LayoutLandscape](#LayoutLandscape)||<a href="RetailTillLayoutConfiguration.md" target="_blank">Miscellaneous/RetailTillLayoutConfiguration</a>|
|[LayoutPortrait](#LayoutPortrait)||<a href="RetailTillLayoutConfiguration.md" target="_blank">Miscellaneous/RetailTillLayoutConfiguration</a>|
|[CashChangerLayout](#CashChangerLayout)||<a href="RetailTillLayoutConfiguration.md" target="_blank">Miscellaneous/RetailTillLayoutConfiguration</a>|
|[customerLayoutId](#customerLayoutId)||<a href="RetailTillLayoutConfiguration.md" target="_blank">Miscellaneous/RetailTillLayoutConfiguration</a>|
|[CustomerLayout](#CustomerLayout)||<a href="RetailTillLayoutConfiguration.md" target="_blank">Miscellaneous/RetailTillLayoutConfiguration</a>|
|[IMG_CashChangerLayout](#IMG_CashChangerLayout)||<a href="RetailTillLayoutConfiguration.md" target="_blank">Miscellaneous/RetailTillLayoutConfiguration</a>|
|[receiptId](#receiptId)||<a href="RetailTillLayoutConfiguration.md" target="_blank">Miscellaneous/RetailTillLayoutConfiguration</a>|
|[ReceiptItemsLayout](#ReceiptItemsLayout)||<a href="RetailTillLayoutConfiguration.md" target="_blank">Miscellaneous/RetailTillLayoutConfiguration</a>|
|[ReceiptPaymentLayout](#ReceiptPaymentLayout)||<a href="RetailTillLayoutConfiguration.md" target="_blank">Miscellaneous/RetailTillLayoutConfiguration</a>|
|[totalId](#totalId)||<a href="RetailTillLayoutConfiguration.md" target="_blank">Miscellaneous/RetailTillLayoutConfiguration</a>|
|[TotalsLayout](#TotalsLayout)||<a href="RetailTillLayoutConfiguration.md" target="_blank">Miscellaneous/RetailTillLayoutConfiguration</a>|
|[Relationship_RetailTillLayoutRelationshipId](#Relationship_RetailTillLayoutRelationshipId)||<a href="RetailTillLayoutConfiguration.md" target="_blank">Miscellaneous/RetailTillLayoutConfiguration</a>|
|[Relationship_RetailTillLayoutSizeRelationshipId](#Relationship_RetailTillLayoutSizeRelationshipId)||<a href="RetailTillLayoutConfiguration.md" target="_blank">Miscellaneous/RetailTillLayoutConfiguration</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: Miscellaneous/RetailTillLayoutConfiguration (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[RetailTillLayoutConfiguration/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#LayoutId name="LayoutId">LayoutId</a>

First included in: Miscellaneous/RetailTillLayoutConfiguration (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LayoutId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SizeId name="SizeId">SizeId</a>

First included in: Miscellaneous/RetailTillLayoutConfiguration (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SizeId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LayoutLandscape name="LayoutLandscape">LayoutLandscape</a>

First included in: Miscellaneous/RetailTillLayoutConfiguration (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LayoutLandscape attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LayoutPortrait name="LayoutPortrait">LayoutPortrait</a>

First included in: Miscellaneous/RetailTillLayoutConfiguration (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LayoutPortrait attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CashChangerLayout name="CashChangerLayout">CashChangerLayout</a>

First included in: Miscellaneous/RetailTillLayoutConfiguration (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CashChangerLayout attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#customerLayoutId name="customerLayoutId">customerLayoutId</a>

First included in: Miscellaneous/RetailTillLayoutConfiguration (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the customerLayoutId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CustomerLayout name="CustomerLayout">CustomerLayout</a>

First included in: Miscellaneous/RetailTillLayoutConfiguration (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CustomerLayout attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IMG_CashChangerLayout name="IMG_CashChangerLayout">IMG_CashChangerLayout</a>

First included in: Miscellaneous/RetailTillLayoutConfiguration (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>binary</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IMG_CashChangerLayout attribute are listed below.</summary>

**is.dataFormat.byte**  
**is.dataFormat.array**  
**is.dataFormat.byte**  
**is.dataFormat.array**  
</details>

### <a href=#receiptId name="receiptId">receiptId</a>

First included in: Miscellaneous/RetailTillLayoutConfiguration (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the receiptId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ReceiptItemsLayout name="ReceiptItemsLayout">ReceiptItemsLayout</a>

First included in: Miscellaneous/RetailTillLayoutConfiguration (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReceiptItemsLayout attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ReceiptPaymentLayout name="ReceiptPaymentLayout">ReceiptPaymentLayout</a>

First included in: Miscellaneous/RetailTillLayoutConfiguration (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReceiptPaymentLayout attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#totalId name="totalId">totalId</a>

First included in: Miscellaneous/RetailTillLayoutConfiguration (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the totalId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TotalsLayout name="TotalsLayout">TotalsLayout</a>

First included in: Miscellaneous/RetailTillLayoutConfiguration (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TotalsLayout attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_RetailTillLayoutRelationshipId name="Relationship_RetailTillLayoutRelationshipId">Relationship_RetailTillLayoutRelationshipId</a>

First included in: Miscellaneous/RetailTillLayoutConfiguration (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_RetailTillLayoutRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Parameter/RetailTillLayout.md" target="_blank">/core/operationsCommon/Tables/Commerce/Retail/Parameter/RetailTillLayout.cdm.json/RetailTillLayout</a></td><td><a href="../Parameter/RetailTillLayout.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_RetailTillLayoutSizeRelationshipId name="Relationship_RetailTillLayoutSizeRelationshipId">Relationship_RetailTillLayoutSizeRelationshipId</a>

First included in: Miscellaneous/RetailTillLayoutConfiguration (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_RetailTillLayoutSizeRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="RetailTillLayoutSize.md" target="_blank">/core/operationsCommon/Tables/Commerce/Retail/Miscellaneous/RetailTillLayoutSize.cdm.json/RetailTillLayoutSize</a></td><td><a href="RetailTillLayoutSize.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>
