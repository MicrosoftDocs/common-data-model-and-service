---
title: RetailLoyaltyConflictCardSalesTable - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/17/2020
ms.author: nebanfic
---

# RetailLoyaltyConflictCardSalesTable

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/erp/Tables/Commerce/Retail/Miscellaneous/RetailLoyaltyConflictCardSalesTable.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[RetailLoyaltyConflictCardSalesTable/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="RetailLoyaltyConflictCardSalesTable.md" target="_blank">Miscellaneous/RetailLoyaltyConflictCardSalesTable</a>|
|[ConflictCard](#ConflictCard)||<a href="RetailLoyaltyConflictCardSalesTable.md" target="_blank">Miscellaneous/RetailLoyaltyConflictCardSalesTable</a>|
|[RetailSalesTable](#RetailSalesTable)||<a href="RetailLoyaltyConflictCardSalesTable.md" target="_blank">Miscellaneous/RetailLoyaltyConflictCardSalesTable</a>|
|[Relationship_RetailLoyaltyConflictCardRelationshipId](#Relationship_RetailLoyaltyConflictCardRelationshipId)||<a href="RetailLoyaltyConflictCardSalesTable.md" target="_blank">Miscellaneous/RetailLoyaltyConflictCardSalesTable</a>|
|[Relationship_RetailSalesTableRelationshipId](#Relationship_RetailSalesTableRelationshipId)||<a href="RetailLoyaltyConflictCardSalesTable.md" target="_blank">Miscellaneous/RetailLoyaltyConflictCardSalesTable</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: Miscellaneous/RetailLoyaltyConflictCardSalesTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[RetailLoyaltyConflictCardSalesTable/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#ConflictCard name="ConflictCard">ConflictCard</a>

First included in: Miscellaneous/RetailLoyaltyConflictCardSalesTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ConflictCard attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#RetailSalesTable name="RetailSalesTable">RetailSalesTable</a>

First included in: Miscellaneous/RetailLoyaltyConflictCardSalesTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RetailSalesTable attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#Relationship_RetailLoyaltyConflictCardRelationshipId name="Relationship_RetailLoyaltyConflictCardRelationshipId">Relationship_RetailLoyaltyConflictCardRelationshipId</a>

First included in: Miscellaneous/RetailLoyaltyConflictCardSalesTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_RetailLoyaltyConflictCardRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="RetailLoyaltyConflictCard.md" target="_blank">/core/erp/Tables/Commerce/Retail/Miscellaneous/RetailLoyaltyConflictCard.cdm.json/RetailLoyaltyConflictCard</a></td><td><a href="RetailLoyaltyConflictCard.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_RetailSalesTableRelationshipId name="Relationship_RetailSalesTableRelationshipId">Relationship_RetailSalesTableRelationshipId</a>

First included in: Miscellaneous/RetailLoyaltyConflictCardSalesTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_RetailSalesTableRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="RetailSalesTable.md" target="_blank">/core/erp/Tables/Commerce/Retail/Miscellaneous/RetailSalesTable.cdm.json/RetailSalesTable</a></td><td><a href="RetailSalesTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>
