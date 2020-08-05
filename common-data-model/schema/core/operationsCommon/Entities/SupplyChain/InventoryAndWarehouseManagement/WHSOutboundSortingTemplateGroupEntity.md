---
title: WHSOutboundSortingTemplateGroupEntity in InventoryAndWarehouseManagement - Common Data Model | Microsoft Docs
description: undefined
author: llawwaii
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 8/5/2020
ms.author: weiluo
---

# Outbound sorting template group table in InventoryAndWarehouseManagement(WHSOutboundSortingTemplateGroupEntity)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/SupplyChain/InventoryAndWarehouseManagement/WHSOutboundSortingTemplateGroupEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.1"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Outbound sorting template group table</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[SortTemplateId](#SortTemplateId)||<a href="WHSOutboundSortingTemplateGroupEntity.md" target="_blank">InventoryAndWarehouseManagement/WHSOutboundSortingTemplateGroupEntity</a>|
|[LineNumber](#LineNumber)||<a href="WHSOutboundSortingTemplateGroupEntity.md" target="_blank">InventoryAndWarehouseManagement/WHSOutboundSortingTemplateGroupEntity</a>|
|[GroupTableFieldId](#GroupTableFieldId)||<a href="WHSOutboundSortingTemplateGroupEntity.md" target="_blank">InventoryAndWarehouseManagement/WHSOutboundSortingTemplateGroupEntity</a>|
|[GroupTableId](#GroupTableId)||<a href="WHSOutboundSortingTemplateGroupEntity.md" target="_blank">InventoryAndWarehouseManagement/WHSOutboundSortingTemplateGroupEntity</a>|
|[SortGroupBy](#SortGroupBy)||<a href="WHSOutboundSortingTemplateGroupEntity.md" target="_blank">InventoryAndWarehouseManagement/WHSOutboundSortingTemplateGroupEntity</a>|
|[GroupTableFieldName](#GroupTableFieldName)||<a href="WHSOutboundSortingTemplateGroupEntity.md" target="_blank">InventoryAndWarehouseManagement/WHSOutboundSortingTemplateGroupEntity</a>|
|[GroupTableName](#GroupTableName)||<a href="WHSOutboundSortingTemplateGroupEntity.md" target="_blank">InventoryAndWarehouseManagement/WHSOutboundSortingTemplateGroupEntity</a>|
|[BackingTable_WHSOutboundSortTemplateGroupRelationshipId](#BackingTable_WHSOutboundSortTemplateGroupRelationshipId)||<a href="WHSOutboundSortingTemplateGroupEntity.md" target="_blank">InventoryAndWarehouseManagement/WHSOutboundSortingTemplateGroupEntity</a>|
|[Relationship_PrimaryCompanyContextRelationshipId](#Relationship_PrimaryCompanyContextRelationshipId)||<a href="WHSOutboundSortingTemplateGroupEntity.md" target="_blank">InventoryAndWarehouseManagement/WHSOutboundSortingTemplateGroupEntity</a>|

### <a href=#SortTemplateId name="SortTemplateId">SortTemplateId</a>

First included in: InventoryAndWarehouseManagement/WHSOutboundSortingTemplateGroupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SortTemplateId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LineNumber name="LineNumber">LineNumber</a>

First included in: InventoryAndWarehouseManagement/WHSOutboundSortingTemplateGroupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LineNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#GroupTableFieldId name="GroupTableFieldId">GroupTableFieldId</a>

First included in: InventoryAndWarehouseManagement/WHSOutboundSortingTemplateGroupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the GroupTableFieldId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#GroupTableId name="GroupTableId">GroupTableId</a>

First included in: InventoryAndWarehouseManagement/WHSOutboundSortingTemplateGroupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the GroupTableId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SortGroupBy name="SortGroupBy">SortGroupBy</a>

First included in: InventoryAndWarehouseManagement/WHSOutboundSortingTemplateGroupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SortGroupBy attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#GroupTableFieldName name="GroupTableFieldName">GroupTableFieldName</a>

First included in: InventoryAndWarehouseManagement/WHSOutboundSortingTemplateGroupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the GroupTableFieldName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#GroupTableName name="GroupTableName">GroupTableName</a>

First included in: InventoryAndWarehouseManagement/WHSOutboundSortingTemplateGroupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the GroupTableName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BackingTable_WHSOutboundSortTemplateGroupRelationshipId name="BackingTable_WHSOutboundSortTemplateGroupRelationshipId">BackingTable_WHSOutboundSortTemplateGroupRelationshipId</a>

First included in: InventoryAndWarehouseManagement/WHSOutboundSortingTemplateGroupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_WHSOutboundSortTemplateGroupRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/SupplyChain/Inventory/Group/WHSOutboundSortTemplateGroup.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/Inventory/Group/WHSOutboundSortTemplateGroup.cdm.json/WHSOutboundSortTemplateGroup</a></td><td><a href="../../../Tables/SupplyChain/Inventory/Group/WHSOutboundSortTemplateGroup.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PrimaryCompanyContextRelationshipId name="Relationship_PrimaryCompanyContextRelationshipId">Relationship_PrimaryCompanyContextRelationshipId</a>

First included in: InventoryAndWarehouseManagement/WHSOutboundSortingTemplateGroupEntity (this entity)  

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
