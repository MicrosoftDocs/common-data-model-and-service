---
title: WHSLoadTableVendPackingSlipJour in Transaction - Common Data Model | Microsoft Docs
description: undefined
author: llawwaii
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 8/5/2020
ms.author: weiluo
---

# WHSLoadTableVendPackingSlipJour in Transaction

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Tables/SupplyChain/Inventory/Transaction/WHSLoadTableVendPackingSlipJour.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[WHSLoadTableVendPackingSlipJour/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.1"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="WHSLoadTableVendPackingSlipJour.md" target="_blank">Transaction/WHSLoadTableVendPackingSlipJour</a>|
|[VendPackingSlipJour](#VendPackingSlipJour)||<a href="WHSLoadTableVendPackingSlipJour.md" target="_blank">Transaction/WHSLoadTableVendPackingSlipJour</a>|
|[LoadDataAreaId](#LoadDataAreaId)||<a href="WHSLoadTableVendPackingSlipJour.md" target="_blank">Transaction/WHSLoadTableVendPackingSlipJour</a>|
|[LoadId](#LoadId)||<a href="WHSLoadTableVendPackingSlipJour.md" target="_blank">Transaction/WHSLoadTableVendPackingSlipJour</a>|
|[Relationship_WHSLoadTableRelationshipId](#Relationship_WHSLoadTableRelationshipId)||<a href="WHSLoadTableVendPackingSlipJour.md" target="_blank">Transaction/WHSLoadTableVendPackingSlipJour</a>|
|[Relationship_VendPackingSlipJourRelationshipId](#Relationship_VendPackingSlipJourRelationshipId)||<a href="WHSLoadTableVendPackingSlipJour.md" target="_blank">Transaction/WHSLoadTableVendPackingSlipJour</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: Transaction/WHSLoadTableVendPackingSlipJour (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[WHSLoadTableVendPackingSlipJour/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#VendPackingSlipJour name="VendPackingSlipJour">VendPackingSlipJour</a>

First included in: Transaction/WHSLoadTableVendPackingSlipJour (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VendPackingSlipJour attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#LoadDataAreaId name="LoadDataAreaId">LoadDataAreaId</a>

First included in: Transaction/WHSLoadTableVendPackingSlipJour (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LoadDataAreaId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.readOnly**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LoadId name="LoadId">LoadId</a>

First included in: Transaction/WHSLoadTableVendPackingSlipJour (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LoadId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.readOnly**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_WHSLoadTableRelationshipId name="Relationship_WHSLoadTableRelationshipId">Relationship_WHSLoadTableRelationshipId</a>

First included in: Transaction/WHSLoadTableVendPackingSlipJour (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_WHSLoadTableRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../WorksheetHeader/WHSLoadTable.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/Inventory/WorksheetHeader/WHSLoadTable.cdm.json/WHSLoadTable</a></td><td><a href="../WorksheetHeader/WHSLoadTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_VendPackingSlipJourRelationshipId name="Relationship_VendPackingSlipJourRelationshipId">Relationship_VendPackingSlipJourRelationshipId</a>

First included in: Transaction/WHSLoadTableVendPackingSlipJour (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_VendPackingSlipJourRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../ProcurementAndSourcing/Transaction/VendPackingSlipJour.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/ProcurementAndSourcing/Transaction/VendPackingSlipJour.cdm.json/VendPackingSlipJour</a></td><td><a href="../../ProcurementAndSourcing/Transaction/VendPackingSlipJour.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>
