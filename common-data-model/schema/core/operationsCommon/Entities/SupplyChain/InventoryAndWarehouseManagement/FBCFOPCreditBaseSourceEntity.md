---
title: FBCFOPCreditBaseSourceEntity in InventoryAndWarehouseManagement - Common Data Model | Microsoft Docs
description: undefined
author: llawwaii

ms.reviewer: deonhe
ms.topic: reference
ms.date: 8/7/2020
ms.author: weiluo
---

# CFOP and Credit base source in InventoryAndWarehouseManagement(FBCFOPCreditBaseSourceEntity)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/SupplyChain/InventoryAndWarehouseManagement/FBCFOPCreditBaseSourceEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.1"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>CFOP and Credit base source</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[CFOP](#CFOP)||<a href="FBCFOPCreditBaseSourceEntity.md" target="_blank">InventoryAndWarehouseManagement/FBCFOPCreditBaseSourceEntity</a>|
|[CFOPDescription](#CFOPDescription)||<a href="FBCFOPCreditBaseSourceEntity.md" target="_blank">InventoryAndWarehouseManagement/FBCFOPCreditBaseSourceEntity</a>|
|[ValidFromDate](#ValidFromDate)||<a href="FBCFOPCreditBaseSourceEntity.md" target="_blank">InventoryAndWarehouseManagement/FBCFOPCreditBaseSourceEntity</a>|
|[ValidToDate](#ValidToDate)||<a href="FBCFOPCreditBaseSourceEntity.md" target="_blank">InventoryAndWarehouseManagement/FBCFOPCreditBaseSourceEntity</a>|
|[CreditBaseSource](#CreditBaseSource)||<a href="FBCFOPCreditBaseSourceEntity.md" target="_blank">InventoryAndWarehouseManagement/FBCFOPCreditBaseSourceEntity</a>|
|[BackingTable_FBCFOPCreditBaseSource_BRRelationshipId](#BackingTable_FBCFOPCreditBaseSource_BRRelationshipId)||<a href="FBCFOPCreditBaseSourceEntity.md" target="_blank">InventoryAndWarehouseManagement/FBCFOPCreditBaseSourceEntity</a>|

### <a href=#CFOP name="CFOP">CFOP</a>

First included in: InventoryAndWarehouseManagement/FBCFOPCreditBaseSourceEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CFOP attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CFOPDescription name="CFOPDescription">CFOPDescription</a>

First included in: InventoryAndWarehouseManagement/FBCFOPCreditBaseSourceEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CFOPDescription attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ValidFromDate name="ValidFromDate">ValidFromDate</a>

First included in: InventoryAndWarehouseManagement/FBCFOPCreditBaseSourceEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ValidFromDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ValidToDate name="ValidToDate">ValidToDate</a>

First included in: InventoryAndWarehouseManagement/FBCFOPCreditBaseSourceEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ValidToDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CreditBaseSource name="CreditBaseSource">CreditBaseSource</a>

First included in: InventoryAndWarehouseManagement/FBCFOPCreditBaseSourceEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CreditBaseSource attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BackingTable_FBCFOPCreditBaseSource_BRRelationshipId name="BackingTable_FBCFOPCreditBaseSource_BRRelationshipId">BackingTable_FBCFOPCreditBaseSource_BRRelationshipId</a>

First included in: InventoryAndWarehouseManagement/FBCFOPCreditBaseSourceEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_FBCFOPCreditBaseSource_BRRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/Finance/FiscalBooksBrazil/Miscellaneous/FBCFOPCreditBaseSource_BR.md" target="_blank">/core/operationsCommon/Tables/Finance/FiscalBooksBrazil/Miscellaneous/FBCFOPCreditBaseSource_BR.cdm.json/FBCFOPCreditBaseSource_BR</a></td><td><a href="../../../Tables/Finance/FiscalBooksBrazil/Miscellaneous/FBCFOPCreditBaseSource_BR.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>
