---
title: WHSCrossDockingTemplateV2Entity - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/21/2020
ms.author: nebanfic
---

# WHSCrossDockingTemplateV2Entity

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/SupplyChain/InventoryAndWarehouseManagement/WHSCrossDockingTemplateV2Entity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[TemplateId](#TemplateId)||<a href="WHSCrossDockingTemplateV2Entity.md" target="_blank">InventoryAndWarehouseManagement/WHSCrossDockingTemplateV2Entity</a>|
|[TemplateDescription](#TemplateDescription)||<a href="WHSCrossDockingTemplateV2Entity.md" target="_blank">InventoryAndWarehouseManagement/WHSCrossDockingTemplateV2Entity</a>|
|[WarehouseId](#WarehouseId)||<a href="WHSCrossDockingTemplateV2Entity.md" target="_blank">InventoryAndWarehouseManagement/WHSCrossDockingTemplateV2Entity</a>|
|[FEFOExpirationDaysRange](#FEFOExpirationDaysRange)||<a href="WHSCrossDockingTemplateV2Entity.md" target="_blank">InventoryAndWarehouseManagement/WHSCrossDockingTemplateV2Entity</a>|
|[PutLocationStorageCriteria](#PutLocationStorageCriteria)||<a href="WHSCrossDockingTemplateV2Entity.md" target="_blank">InventoryAndWarehouseManagement/WHSCrossDockingTemplateV2Entity</a>|
|[MaximumTimeWindow](#MaximumTimeWindow)||<a href="WHSCrossDockingTemplateV2Entity.md" target="_blank">InventoryAndWarehouseManagement/WHSCrossDockingTemplateV2Entity</a>|
|[MaximumTimeWindowUnit](#MaximumTimeWindowUnit)||<a href="WHSCrossDockingTemplateV2Entity.md" target="_blank">InventoryAndWarehouseManagement/WHSCrossDockingTemplateV2Entity</a>|
|[MinimumTimeWindow](#MinimumTimeWindow)||<a href="WHSCrossDockingTemplateV2Entity.md" target="_blank">InventoryAndWarehouseManagement/WHSCrossDockingTemplateV2Entity</a>|
|[MinimumTimeWindowUnit](#MinimumTimeWindowUnit)||<a href="WHSCrossDockingTemplateV2Entity.md" target="_blank">InventoryAndWarehouseManagement/WHSCrossDockingTemplateV2Entity</a>|
|[DemandRequirementRule](#DemandRequirementRule)||<a href="WHSCrossDockingTemplateV2Entity.md" target="_blank">InventoryAndWarehouseManagement/WHSCrossDockingTemplateV2Entity</a>|
|[WillReceiptRevalidateSupply](#WillReceiptRevalidateSupply)||<a href="WHSCrossDockingTemplateV2Entity.md" target="_blank">InventoryAndWarehouseManagement/WHSCrossDockingTemplateV2Entity</a>|
|[IsMaximumTimeWindowValidated](#IsMaximumTimeWindowValidated)||<a href="WHSCrossDockingTemplateV2Entity.md" target="_blank">InventoryAndWarehouseManagement/WHSCrossDockingTemplateV2Entity</a>|
|[ProductQuery](#ProductQuery)||<a href="WHSCrossDockingTemplateV2Entity.md" target="_blank">InventoryAndWarehouseManagement/WHSCrossDockingTemplateV2Entity</a>|
|[SequenceNumber](#SequenceNumber)||<a href="WHSCrossDockingTemplateV2Entity.md" target="_blank">InventoryAndWarehouseManagement/WHSCrossDockingTemplateV2Entity</a>|
|[CrossDockingWorkTemplateId](#CrossDockingWorkTemplateId)||<a href="WHSCrossDockingTemplateV2Entity.md" target="_blank">InventoryAndWarehouseManagement/WHSCrossDockingTemplateV2Entity</a>|
|[DemandReleasePolicy](#DemandReleasePolicy)||<a href="WHSCrossDockingTemplateV2Entity.md" target="_blank">InventoryAndWarehouseManagement/WHSCrossDockingTemplateV2Entity</a>|
|[BackingTable_WHSCrossDockTemplateRelationshipId](#BackingTable_WHSCrossDockTemplateRelationshipId)||<a href="WHSCrossDockingTemplateV2Entity.md" target="_blank">InventoryAndWarehouseManagement/WHSCrossDockingTemplateV2Entity</a>|
|[Relationship_PrimaryCompanyContextRelationshipId](#Relationship_PrimaryCompanyContextRelationshipId)||<a href="WHSCrossDockingTemplateV2Entity.md" target="_blank">InventoryAndWarehouseManagement/WHSCrossDockingTemplateV2Entity</a>|

### <a href=#TemplateId name="TemplateId">TemplateId</a>

First included in: InventoryAndWarehouseManagement/WHSCrossDockingTemplateV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TemplateId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TemplateDescription name="TemplateDescription">TemplateDescription</a>

First included in: InventoryAndWarehouseManagement/WHSCrossDockingTemplateV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TemplateDescription attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WarehouseId name="WarehouseId">WarehouseId</a>

First included in: InventoryAndWarehouseManagement/WHSCrossDockingTemplateV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WarehouseId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FEFOExpirationDaysRange name="FEFOExpirationDaysRange">FEFOExpirationDaysRange</a>

First included in: InventoryAndWarehouseManagement/WHSCrossDockingTemplateV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FEFOExpirationDaysRange attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PutLocationStorageCriteria name="PutLocationStorageCriteria">PutLocationStorageCriteria</a>

First included in: InventoryAndWarehouseManagement/WHSCrossDockingTemplateV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PutLocationStorageCriteria attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MaximumTimeWindow name="MaximumTimeWindow">MaximumTimeWindow</a>

First included in: InventoryAndWarehouseManagement/WHSCrossDockingTemplateV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MaximumTimeWindow attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MaximumTimeWindowUnit name="MaximumTimeWindowUnit">MaximumTimeWindowUnit</a>

First included in: InventoryAndWarehouseManagement/WHSCrossDockingTemplateV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MaximumTimeWindowUnit attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MinimumTimeWindow name="MinimumTimeWindow">MinimumTimeWindow</a>

First included in: InventoryAndWarehouseManagement/WHSCrossDockingTemplateV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MinimumTimeWindow attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MinimumTimeWindowUnit name="MinimumTimeWindowUnit">MinimumTimeWindowUnit</a>

First included in: InventoryAndWarehouseManagement/WHSCrossDockingTemplateV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MinimumTimeWindowUnit attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DemandRequirementRule name="DemandRequirementRule">DemandRequirementRule</a>

First included in: InventoryAndWarehouseManagement/WHSCrossDockingTemplateV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DemandRequirementRule attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WillReceiptRevalidateSupply name="WillReceiptRevalidateSupply">WillReceiptRevalidateSupply</a>

First included in: InventoryAndWarehouseManagement/WHSCrossDockingTemplateV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WillReceiptRevalidateSupply attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsMaximumTimeWindowValidated name="IsMaximumTimeWindowValidated">IsMaximumTimeWindowValidated</a>

First included in: InventoryAndWarehouseManagement/WHSCrossDockingTemplateV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsMaximumTimeWindowValidated attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProductQuery name="ProductQuery">ProductQuery</a>

First included in: InventoryAndWarehouseManagement/WHSCrossDockingTemplateV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProductQuery attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SequenceNumber name="SequenceNumber">SequenceNumber</a>

First included in: InventoryAndWarehouseManagement/WHSCrossDockingTemplateV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SequenceNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CrossDockingWorkTemplateId name="CrossDockingWorkTemplateId">CrossDockingWorkTemplateId</a>

First included in: InventoryAndWarehouseManagement/WHSCrossDockingTemplateV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CrossDockingWorkTemplateId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DemandReleasePolicy name="DemandReleasePolicy">DemandReleasePolicy</a>

First included in: InventoryAndWarehouseManagement/WHSCrossDockingTemplateV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DemandReleasePolicy attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BackingTable_WHSCrossDockTemplateRelationshipId name="BackingTable_WHSCrossDockTemplateRelationshipId">BackingTable_WHSCrossDockTemplateRelationshipId</a>

First included in: InventoryAndWarehouseManagement/WHSCrossDockingTemplateV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_WHSCrossDockTemplateRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/SupplyChain/Inventory/Main/WHSCrossDockTemplate.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/Inventory/Main/WHSCrossDockTemplate.cdm.json/WHSCrossDockTemplate</a></td><td><a href="../../../Tables/SupplyChain/Inventory/Main/WHSCrossDockTemplate.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PrimaryCompanyContextRelationshipId name="Relationship_PrimaryCompanyContextRelationshipId">Relationship_PrimaryCompanyContextRelationshipId</a>

First included in: InventoryAndWarehouseManagement/WHSCrossDockingTemplateV2Entity (this entity)  

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
