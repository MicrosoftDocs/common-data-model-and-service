---
title: WHSWarehousePutawayClusterProfileWorkTemplateEntity - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 5/5/2020
ms.author: nebanfic
---

# The WHSWarehousePutawayClusterProfileWorkTemplates data entity contains information for putaway cluster work templates.

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/SupplyChain/WMS/WHSWarehousePutawayClusterProfileWorkTemplateEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>The WHSWarehousePutawayClusterProfileWorkTemplates data entity contains information for putaway cluster work templates.</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[PutawayWarehouseClusterProfileId](#PutawayWarehouseClusterProfileId)||<a href="WHSWarehousePutawayClusterProfileWorkTemplateEntity.md" target="_blank">WMS/WHSWarehousePutawayClusterProfileWorkTemplateEntity</a>|
|[WarehouseWorkTemplateWorkOrderType](#WarehouseWorkTemplateWorkOrderType)||<a href="WHSWarehousePutawayClusterProfileWorkTemplateEntity.md" target="_blank">WMS/WHSWarehousePutawayClusterProfileWorkTemplateEntity</a>|
|[WarehouseWorkTemplateId](#WarehouseWorkTemplateId)||<a href="WHSWarehousePutawayClusterProfileWorkTemplateEntity.md" target="_blank">WMS/WHSWarehousePutawayClusterProfileWorkTemplateEntity</a>|
|[Relationship_WHSWarehouseClusterProfileEntityV2RelationshipId](#Relationship_WHSWarehouseClusterProfileEntityV2RelationshipId)||<a href="WHSWarehousePutawayClusterProfileWorkTemplateEntity.md" target="_blank">WMS/WHSWarehousePutawayClusterProfileWorkTemplateEntity</a>|
|[BackingTable_WHSPutawayClusterWorkTemplateRelationshipId](#BackingTable_WHSPutawayClusterWorkTemplateRelationshipId)||<a href="WHSWarehousePutawayClusterProfileWorkTemplateEntity.md" target="_blank">WMS/WHSWarehousePutawayClusterProfileWorkTemplateEntity</a>|
|[Relationship_PrimaryCompanyContextRelationshipId](#Relationship_PrimaryCompanyContextRelationshipId)||<a href="WHSWarehousePutawayClusterProfileWorkTemplateEntity.md" target="_blank">WMS/WHSWarehousePutawayClusterProfileWorkTemplateEntity</a>|

### <a href=#PutawayWarehouseClusterProfileId name="PutawayWarehouseClusterProfileId">PutawayWarehouseClusterProfileId</a>

First included in: WMS/WHSWarehousePutawayClusterProfileWorkTemplateEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PutawayWarehouseClusterProfileId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WarehouseWorkTemplateWorkOrderType name="WarehouseWorkTemplateWorkOrderType">WarehouseWorkTemplateWorkOrderType</a>

First included in: WMS/WHSWarehousePutawayClusterProfileWorkTemplateEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WarehouseWorkTemplateWorkOrderType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WarehouseWorkTemplateId name="WarehouseWorkTemplateId">WarehouseWorkTemplateId</a>

First included in: WMS/WHSWarehousePutawayClusterProfileWorkTemplateEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WarehouseWorkTemplateId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_WHSWarehouseClusterProfileEntityV2RelationshipId name="Relationship_WHSWarehouseClusterProfileEntityV2RelationshipId">Relationship_WHSWarehouseClusterProfileEntityV2RelationshipId</a>

First included in: WMS/WHSWarehousePutawayClusterProfileWorkTemplateEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_WHSWarehouseClusterProfileEntityV2RelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td>empty table</td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BackingTable_WHSPutawayClusterWorkTemplateRelationshipId name="BackingTable_WHSPutawayClusterWorkTemplateRelationshipId">BackingTable_WHSPutawayClusterWorkTemplateRelationshipId</a>

First included in: WMS/WHSWarehousePutawayClusterProfileWorkTemplateEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_WHSPutawayClusterWorkTemplateRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/SupplyChain/Inventory/Group/WHSPutawayClusterWorkTemplate.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/Inventory/Group/WHSPutawayClusterWorkTemplate.cdm.json/WHSPutawayClusterWorkTemplate</a></td><td><a href="../../../Tables/SupplyChain/Inventory/Group/WHSPutawayClusterWorkTemplate.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PrimaryCompanyContextRelationshipId name="Relationship_PrimaryCompanyContextRelationshipId">Relationship_PrimaryCompanyContextRelationshipId</a>

First included in: WMS/WHSWarehousePutawayClusterProfileWorkTemplateEntity (this entity)  

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
