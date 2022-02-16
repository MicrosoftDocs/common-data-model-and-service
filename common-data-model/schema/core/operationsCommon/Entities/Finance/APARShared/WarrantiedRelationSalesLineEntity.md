---
title: WarrantiedRelationSalesLineEntity in APARShared - Common Data Model | Microsoft Docs
description: undefined
author: llawwaii

ms.reviewer: deonhe
ms.topic: article
ms.date: 8/7/2020
ms.author: weiluo
---

# Warrantied relation for sales line. in APARShared(WarrantiedRelationSalesLineEntity)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/Finance/APARShared/WarrantiedRelationSalesLineEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.1"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Warrantied relation for sales line.</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[CustomerAccount](#CustomerAccount)||<a href="WarrantiedRelationSalesLineEntity.md" target="_blank">APARShared/WarrantiedRelationSalesLineEntity</a>|
|[WarrantiedOrderType](#WarrantiedOrderType)||<a href="WarrantiedRelationSalesLineEntity.md" target="_blank">APARShared/WarrantiedRelationSalesLineEntity</a>|
|[WarrantiedSalesId](#WarrantiedSalesId)||<a href="WarrantiedRelationSalesLineEntity.md" target="_blank">APARShared/WarrantiedRelationSalesLineEntity</a>|
|[WarrantiedItemId](#WarrantiedItemId)||<a href="WarrantiedRelationSalesLineEntity.md" target="_blank">APARShared/WarrantiedRelationSalesLineEntity</a>|
|[WarrantiedSalesLineNumber](#WarrantiedSalesLineNumber)||<a href="WarrantiedRelationSalesLineEntity.md" target="_blank">APARShared/WarrantiedRelationSalesLineEntity</a>|
|[WarrantiedInventoryLotId](#WarrantiedInventoryLotId)||<a href="WarrantiedRelationSalesLineEntity.md" target="_blank">APARShared/WarrantiedRelationSalesLineEntity</a>|
|[WarrantiedSerialNumber](#WarrantiedSerialNumber)||<a href="WarrantiedRelationSalesLineEntity.md" target="_blank">APARShared/WarrantiedRelationSalesLineEntity</a>|
|[WarrantyOrderType](#WarrantyOrderType)||<a href="WarrantiedRelationSalesLineEntity.md" target="_blank">APARShared/WarrantiedRelationSalesLineEntity</a>|
|[WarrantySalesId](#WarrantySalesId)||<a href="WarrantiedRelationSalesLineEntity.md" target="_blank">APARShared/WarrantiedRelationSalesLineEntity</a>|
|[WarrantyItemId](#WarrantyItemId)||<a href="WarrantiedRelationSalesLineEntity.md" target="_blank">APARShared/WarrantiedRelationSalesLineEntity</a>|
|[WarrantySalesLineNumber](#WarrantySalesLineNumber)||<a href="WarrantiedRelationSalesLineEntity.md" target="_blank">APARShared/WarrantiedRelationSalesLineEntity</a>|
|[WarrantyInventoryLotId](#WarrantyInventoryLotId)||<a href="WarrantiedRelationSalesLineEntity.md" target="_blank">APARShared/WarrantiedRelationSalesLineEntity</a>|
|[Relation](#Relation)||<a href="WarrantiedRelationSalesLineEntity.md" target="_blank">APARShared/WarrantiedRelationSalesLineEntity</a>|
|[BackingTable_WarrantiedRelationSalesLineRelationshipId](#BackingTable_WarrantiedRelationSalesLineRelationshipId)||<a href="WarrantiedRelationSalesLineEntity.md" target="_blank">APARShared/WarrantiedRelationSalesLineEntity</a>|
|[Relationship_PrimaryCompanyContextRelationshipId](#Relationship_PrimaryCompanyContextRelationshipId)||<a href="WarrantiedRelationSalesLineEntity.md" target="_blank">APARShared/WarrantiedRelationSalesLineEntity</a>|

### <a href=#CustomerAccount name="CustomerAccount">CustomerAccount</a>

First included in: APARShared/WarrantiedRelationSalesLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CustomerAccount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WarrantiedOrderType name="WarrantiedOrderType">WarrantiedOrderType</a>

First included in: APARShared/WarrantiedRelationSalesLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WarrantiedOrderType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WarrantiedSalesId name="WarrantiedSalesId">WarrantiedSalesId</a>

First included in: APARShared/WarrantiedRelationSalesLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WarrantiedSalesId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WarrantiedItemId name="WarrantiedItemId">WarrantiedItemId</a>

First included in: APARShared/WarrantiedRelationSalesLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WarrantiedItemId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WarrantiedSalesLineNumber name="WarrantiedSalesLineNumber">WarrantiedSalesLineNumber</a>

First included in: APARShared/WarrantiedRelationSalesLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WarrantiedSalesLineNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WarrantiedInventoryLotId name="WarrantiedInventoryLotId">WarrantiedInventoryLotId</a>

First included in: APARShared/WarrantiedRelationSalesLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WarrantiedInventoryLotId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WarrantiedSerialNumber name="WarrantiedSerialNumber">WarrantiedSerialNumber</a>

First included in: APARShared/WarrantiedRelationSalesLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WarrantiedSerialNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WarrantyOrderType name="WarrantyOrderType">WarrantyOrderType</a>

First included in: APARShared/WarrantiedRelationSalesLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WarrantyOrderType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WarrantySalesId name="WarrantySalesId">WarrantySalesId</a>

First included in: APARShared/WarrantiedRelationSalesLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WarrantySalesId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WarrantyItemId name="WarrantyItemId">WarrantyItemId</a>

First included in: APARShared/WarrantiedRelationSalesLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WarrantyItemId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WarrantySalesLineNumber name="WarrantySalesLineNumber">WarrantySalesLineNumber</a>

First included in: APARShared/WarrantiedRelationSalesLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WarrantySalesLineNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WarrantyInventoryLotId name="WarrantyInventoryLotId">WarrantyInventoryLotId</a>

First included in: APARShared/WarrantiedRelationSalesLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WarrantyInventoryLotId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relation name="Relation">Relation</a>

First included in: APARShared/WarrantiedRelationSalesLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relation attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BackingTable_WarrantiedRelationSalesLineRelationshipId name="BackingTable_WarrantiedRelationSalesLineRelationshipId">BackingTable_WarrantiedRelationSalesLineRelationshipId</a>

First included in: APARShared/WarrantiedRelationSalesLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_WarrantiedRelationSalesLineRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/Finance/AccountsReceivable/Transaction/WarrantiedRelationSalesLine.md" target="_blank">/core/operationsCommon/Tables/Finance/AccountsReceivable/Transaction/WarrantiedRelationSalesLine.cdm.json/WarrantiedRelationSalesLine</a></td><td><a href="../../../Tables/Finance/AccountsReceivable/Transaction/WarrantiedRelationSalesLine.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PrimaryCompanyContextRelationshipId name="Relationship_PrimaryCompanyContextRelationshipId">Relationship_PrimaryCompanyContextRelationshipId</a>

First included in: APARShared/WarrantiedRelationSalesLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_PrimaryCompanyContextRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/Finance/Ledger/Main/CompanyInfo.md" target="_blank">/core/operationsCommon/Tables/Finance/Ledger/Main/CompanyInfo.cdm.json/CompanyInfo</a></td><td><a href="../../../Tables/Finance/Ledger/Main/CompanyInfo.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>
