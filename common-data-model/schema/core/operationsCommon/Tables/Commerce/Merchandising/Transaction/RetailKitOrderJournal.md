---
title: RetailKitOrderJournal in Transaction - Common Data Model | Microsoft Docs
description: undefined
author: llawwaii
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 8/5/2020
ms.author: weiluo
---

# Product kit order journals in Transaction(RetailKitOrderJournal)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Tables/Commerce/Merchandising/Transaction/RetailKitOrderJournal.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[RetailKitOrderJournal/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Product kit order journals</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="RetailKitOrderJournal.md" target="_blank">Transaction/RetailKitOrderJournal</a>|
|[EcoResDistinctProductVariantID](#EcoResDistinctProductVariantID)||<a href="RetailKitOrderJournal.md" target="_blank">Transaction/RetailKitOrderJournal</a>|
|[InventDataAreaId](#InventDataAreaId)||<a href="RetailKitOrderJournal.md" target="_blank">Transaction/RetailKitOrderJournal</a>|
|[JournalId](#JournalId)||<a href="RetailKitOrderJournal.md" target="_blank">Transaction/RetailKitOrderJournal</a>|
|[Quantity](#Quantity)||<a href="RetailKitOrderJournal.md" target="_blank">Transaction/RetailKitOrderJournal</a>|
|[RetailKitOrder](#RetailKitOrder)||<a href="RetailKitOrderJournal.md" target="_blank">Transaction/RetailKitOrderJournal</a>|
|[Relationship_EcoResDistinctProductVariantRelationshipId](#Relationship_EcoResDistinctProductVariantRelationshipId)||<a href="RetailKitOrderJournal.md" target="_blank">Transaction/RetailKitOrderJournal</a>|
|[Relationship_InventJournalTableRelationshipId](#Relationship_InventJournalTableRelationshipId)||<a href="RetailKitOrderJournal.md" target="_blank">Transaction/RetailKitOrderJournal</a>|
|[Relationship_RetailKitOrderRelationshipId](#Relationship_RetailKitOrderRelationshipId)||<a href="RetailKitOrderJournal.md" target="_blank">Transaction/RetailKitOrderJournal</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: Transaction/RetailKitOrderJournal (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[RetailKitOrderJournal/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#EcoResDistinctProductVariantID name="EcoResDistinctProductVariantID">EcoResDistinctProductVariantID</a>

First included in: Transaction/RetailKitOrderJournal (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EcoResDistinctProductVariantID attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#InventDataAreaId name="InventDataAreaId">InventDataAreaId</a>

First included in: Transaction/RetailKitOrderJournal (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InventDataAreaId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#JournalId name="JournalId">JournalId</a>

First included in: Transaction/RetailKitOrderJournal (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the JournalId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Quantity name="Quantity">Quantity</a>

First included in: Transaction/RetailKitOrderJournal (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Quantity attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#RetailKitOrder name="RetailKitOrder">RetailKitOrder</a>

First included in: Transaction/RetailKitOrderJournal (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RetailKitOrder attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#Relationship_EcoResDistinctProductVariantRelationshipId name="Relationship_EcoResDistinctProductVariantRelationshipId">Relationship_EcoResDistinctProductVariantRelationshipId</a>

First included in: Transaction/RetailKitOrderJournal (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_EcoResDistinctProductVariantRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../SupplyChain/ProductInformationManagement/Main/EcoResDistinctProductVariant.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/ProductInformationManagement/Main/EcoResDistinctProductVariant.cdm.json/EcoResDistinctProductVariant</a></td><td><a href="../../../SupplyChain/ProductInformationManagement/Main/EcoResDistinctProductVariant.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_InventJournalTableRelationshipId name="Relationship_InventJournalTableRelationshipId">Relationship_InventJournalTableRelationshipId</a>

First included in: Transaction/RetailKitOrderJournal (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_InventJournalTableRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../SupplyChain/Inventory/WorksheetHeader/InventJournalTable.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/Inventory/WorksheetHeader/InventJournalTable.cdm.json/InventJournalTable</a></td><td><a href="../../../SupplyChain/Inventory/WorksheetHeader/InventJournalTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_RetailKitOrderRelationshipId name="Relationship_RetailKitOrderRelationshipId">Relationship_RetailKitOrderRelationshipId</a>

First included in: Transaction/RetailKitOrderJournal (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_RetailKitOrderRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="RetailKitOrder.md" target="_blank">/core/operationsCommon/Tables/Commerce/Merchandising/Transaction/RetailKitOrder.cdm.json/RetailKitOrder</a></td><td><a href="RetailKitOrder.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>
