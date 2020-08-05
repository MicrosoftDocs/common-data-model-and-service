---
title: WHSWarehouseWorkerEntity in InventoryAndWarehouseManagement - Common Data Model | Microsoft Docs
description: undefined
author: llawwaii
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 8/5/2020
ms.author: weiluo
---

# Warehouse workers in InventoryAndWarehouseManagement(WHSWarehouseWorkerEntity)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/SupplyChain/InventoryAndWarehouseManagement/WHSWarehouseWorkerEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.1"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Warehouse workers</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[DefaultContainerClosingProfileId](#DefaultContainerClosingProfileId)||<a href="WHSWarehouseWorkerEntity.md" target="_blank">InventoryAndWarehouseManagement/WHSWarehouseWorkerEntity</a>|
|[DefaultContainerPackingProfileId](#DefaultContainerPackingProfileId)||<a href="WHSWarehouseWorkerEntity.md" target="_blank">InventoryAndWarehouseManagement/WHSWarehouseWorkerEntity</a>|
|[WarehouseWorkerPersonnelNumber](#WarehouseWorkerPersonnelNumber)||<a href="WHSWarehouseWorkerEntity.md" target="_blank">InventoryAndWarehouseManagement/WHSWarehouseWorkerEntity</a>|
|[WorkerId](#WorkerId)||<a href="WHSWarehouseWorkerEntity.md" target="_blank">InventoryAndWarehouseManagement/WHSWarehouseWorkerEntity</a>|
|[DefaultPackingStationWarehouseId](#DefaultPackingStationWarehouseId)||<a href="WHSWarehouseWorkerEntity.md" target="_blank">InventoryAndWarehouseManagement/WHSWarehouseWorkerEntity</a>|
|[DefaultPackingStationWarehouseLocationId](#DefaultPackingStationWarehouseLocationId)||<a href="WHSWarehouseWorkerEntity.md" target="_blank">InventoryAndWarehouseManagement/WHSWarehouseWorkerEntity</a>|
|[DefaultPackingStationWarehouseSiteId](#DefaultPackingStationWarehouseSiteId)||<a href="WHSWarehouseWorkerEntity.md" target="_blank">InventoryAndWarehouseManagement/WHSWarehouseWorkerEntity</a>|
|[Relationship_DefaultContainerClosingProfileRelationshipId](#Relationship_DefaultContainerClosingProfileRelationshipId)||<a href="WHSWarehouseWorkerEntity.md" target="_blank">InventoryAndWarehouseManagement/WHSWarehouseWorkerEntity</a>|
|[Relationship_DefaultWarehousePackingProfileRelationshipId](#Relationship_DefaultWarehousePackingProfileRelationshipId)||<a href="WHSWarehouseWorkerEntity.md" target="_blank">InventoryAndWarehouseManagement/WHSWarehouseWorkerEntity</a>|
|[Relationship_DefaultPackingStationWarehouseRelationshipId](#Relationship_DefaultPackingStationWarehouseRelationshipId)||<a href="WHSWarehouseWorkerEntity.md" target="_blank">InventoryAndWarehouseManagement/WHSWarehouseWorkerEntity</a>|
|[Relationship_DefaultPackingStationWarehouseLocationRelationshipId](#Relationship_DefaultPackingStationWarehouseLocationRelationshipId)||<a href="WHSWarehouseWorkerEntity.md" target="_blank">InventoryAndWarehouseManagement/WHSWarehouseWorkerEntity</a>|
|[Relationship_DefaultPackingStationWarehouseSiteRelationshipId](#Relationship_DefaultPackingStationWarehouseSiteRelationshipId)||<a href="WHSWarehouseWorkerEntity.md" target="_blank">InventoryAndWarehouseManagement/WHSWarehouseWorkerEntity</a>|
|[BackingTable_WHSWorkerRelationshipId](#BackingTable_WHSWorkerRelationshipId)||<a href="WHSWarehouseWorkerEntity.md" target="_blank">InventoryAndWarehouseManagement/WHSWarehouseWorkerEntity</a>|
|[Relationship_PrimaryCompanyContextRelationshipId](#Relationship_PrimaryCompanyContextRelationshipId)||<a href="WHSWarehouseWorkerEntity.md" target="_blank">InventoryAndWarehouseManagement/WHSWarehouseWorkerEntity</a>|

### <a href=#DefaultContainerClosingProfileId name="DefaultContainerClosingProfileId">DefaultContainerClosingProfileId</a>

First included in: InventoryAndWarehouseManagement/WHSWarehouseWorkerEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultContainerClosingProfileId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DefaultContainerPackingProfileId name="DefaultContainerPackingProfileId">DefaultContainerPackingProfileId</a>

First included in: InventoryAndWarehouseManagement/WHSWarehouseWorkerEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultContainerPackingProfileId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WarehouseWorkerPersonnelNumber name="WarehouseWorkerPersonnelNumber">WarehouseWorkerPersonnelNumber</a>

First included in: InventoryAndWarehouseManagement/WHSWarehouseWorkerEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WarehouseWorkerPersonnelNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WorkerId name="WorkerId">WorkerId</a>

First included in: InventoryAndWarehouseManagement/WHSWarehouseWorkerEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WorkerId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DefaultPackingStationWarehouseId name="DefaultPackingStationWarehouseId">DefaultPackingStationWarehouseId</a>

First included in: InventoryAndWarehouseManagement/WHSWarehouseWorkerEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultPackingStationWarehouseId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DefaultPackingStationWarehouseLocationId name="DefaultPackingStationWarehouseLocationId">DefaultPackingStationWarehouseLocationId</a>

First included in: InventoryAndWarehouseManagement/WHSWarehouseWorkerEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultPackingStationWarehouseLocationId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DefaultPackingStationWarehouseSiteId name="DefaultPackingStationWarehouseSiteId">DefaultPackingStationWarehouseSiteId</a>

First included in: InventoryAndWarehouseManagement/WHSWarehouseWorkerEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultPackingStationWarehouseSiteId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_DefaultContainerClosingProfileRelationshipId name="Relationship_DefaultContainerClosingProfileRelationshipId">Relationship_DefaultContainerClosingProfileRelationshipId</a>

First included in: InventoryAndWarehouseManagement/WHSWarehouseWorkerEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_DefaultContainerClosingProfileRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_DefaultWarehousePackingProfileRelationshipId name="Relationship_DefaultWarehousePackingProfileRelationshipId">Relationship_DefaultWarehousePackingProfileRelationshipId</a>

First included in: InventoryAndWarehouseManagement/WHSWarehouseWorkerEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_DefaultWarehousePackingProfileRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_DefaultPackingStationWarehouseRelationshipId name="Relationship_DefaultPackingStationWarehouseRelationshipId">Relationship_DefaultPackingStationWarehouseRelationshipId</a>

First included in: InventoryAndWarehouseManagement/WHSWarehouseWorkerEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_DefaultPackingStationWarehouseRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_DefaultPackingStationWarehouseLocationRelationshipId name="Relationship_DefaultPackingStationWarehouseLocationRelationshipId">Relationship_DefaultPackingStationWarehouseLocationRelationshipId</a>

First included in: InventoryAndWarehouseManagement/WHSWarehouseWorkerEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_DefaultPackingStationWarehouseLocationRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_DefaultPackingStationWarehouseSiteRelationshipId name="Relationship_DefaultPackingStationWarehouseSiteRelationshipId">Relationship_DefaultPackingStationWarehouseSiteRelationshipId</a>

First included in: InventoryAndWarehouseManagement/WHSWarehouseWorkerEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_DefaultPackingStationWarehouseSiteRelationshipId attribute are listed below.</summary>

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

### <a href=#BackingTable_WHSWorkerRelationshipId name="BackingTable_WHSWorkerRelationshipId">BackingTable_WHSWorkerRelationshipId</a>

First included in: InventoryAndWarehouseManagement/WHSWarehouseWorkerEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_WHSWorkerRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/SupplyChain/Inventory/Miscellaneous/WHSWorker.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/Inventory/Miscellaneous/WHSWorker.cdm.json/WHSWorker</a></td><td><a href="../../../Tables/SupplyChain/Inventory/Miscellaneous/WHSWorker.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PrimaryCompanyContextRelationshipId name="Relationship_PrimaryCompanyContextRelationshipId">Relationship_PrimaryCompanyContextRelationshipId</a>

First included in: InventoryAndWarehouseManagement/WHSWarehouseWorkerEntity (this entity)  

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
