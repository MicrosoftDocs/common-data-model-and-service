---
title: WHSWarehouseMobileDeviceUserEntity - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/20/2020
ms.author: nebanfic
---

# WHSWarehouseMobileDeviceUserEntity

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/SupplyChain/WMS/WHSWarehouseMobileDeviceUserEntity.cdm.json" target="_blank">GitHub</a>.  

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
|[WarehouseWorkerPersonnelNumber](#WarehouseWorkerPersonnelNumber)||<a href="WHSWarehouseMobileDeviceUserEntity.md" target="_blank">WMS/WHSWarehouseMobileDeviceUserEntity</a>|
|[UserId](#UserId)||<a href="WHSWarehouseMobileDeviceUserEntity.md" target="_blank">WMS/WHSWarehouseMobileDeviceUserEntity</a>|
|[UserName](#UserName)||<a href="WHSWarehouseMobileDeviceUserEntity.md" target="_blank">WMS/WHSWarehouseMobileDeviceUserEntity</a>|
|[DefaultWarehouseId](#DefaultWarehouseId)||<a href="WHSWarehouseMobileDeviceUserEntity.md" target="_blank">WMS/WHSWarehouseMobileDeviceUserEntity</a>|
|[DefaultMobileDeviceMenuItemName](#DefaultMobileDeviceMenuItemName)||<a href="WHSWarehouseMobileDeviceUserEntity.md" target="_blank">WMS/WHSWarehouseMobileDeviceUserEntity</a>|
|[IsInactive](#IsInactive)||<a href="WHSWarehouseMobileDeviceUserEntity.md" target="_blank">WMS/WHSWarehouseMobileDeviceUserEntity</a>|
|[IsWarehousePickLocationOverrideAllowed](#IsWarehousePickLocationOverrideAllowed)||<a href="WHSWarehouseMobileDeviceUserEntity.md" target="_blank">WMS/WHSWarehouseMobileDeviceUserEntity</a>|
|[IsWarehousePutLocationOverrideAllowed](#IsWarehousePutLocationOverrideAllowed)||<a href="WHSWarehouseMobileDeviceUserEntity.md" target="_blank">WMS/WHSWarehouseMobileDeviceUserEntity</a>|
|[IsCountingSupervisor](#IsCountingSupervisor)||<a href="WHSWarehouseMobileDeviceUserEntity.md" target="_blank">WMS/WHSWarehouseMobileDeviceUserEntity</a>|
|[CountingApprovalPercentageLimit](#CountingApprovalPercentageLimit)||<a href="WHSWarehouseMobileDeviceUserEntity.md" target="_blank">WMS/WHSWarehouseMobileDeviceUserEntity</a>|
|[CountingApprovalQuantityLimit](#CountingApprovalQuantityLimit)||<a href="WHSWarehouseMobileDeviceUserEntity.md" target="_blank">WMS/WHSWarehouseMobileDeviceUserEntity</a>|
|[CountingApprovalValueLimit](#CountingApprovalValueLimit)||<a href="WHSWarehouseMobileDeviceUserEntity.md" target="_blank">WMS/WHSWarehouseMobileDeviceUserEntity</a>|
|[Worker](#Worker)||<a href="WHSWarehouseMobileDeviceUserEntity.md" target="_blank">WMS/WHSWarehouseMobileDeviceUserEntity</a>|
|[WarehouseWorkerId](#WarehouseWorkerId)||<a href="WHSWarehouseMobileDeviceUserEntity.md" target="_blank">WMS/WHSWarehouseMobileDeviceUserEntity</a>|
|[IsAutomatedWarehouseWorkUser](#IsAutomatedWarehouseWorkUser)||<a href="WHSWarehouseMobileDeviceUserEntity.md" target="_blank">WMS/WHSWarehouseMobileDeviceUserEntity</a>|
|[IsInventoryMovementWithAssociatedWorkAllowed](#IsInventoryMovementWithAssociatedWorkAllowed)||<a href="WHSWarehouseMobileDeviceUserEntity.md" target="_blank">WMS/WHSWarehouseMobileDeviceUserEntity</a>|
|[IsSalesOrderOverpickingAllowed](#IsSalesOrderOverpickingAllowed)||<a href="WHSWarehouseMobileDeviceUserEntity.md" target="_blank">WMS/WHSWarehouseMobileDeviceUserEntity</a>|
|[IsTransferOrderOverpickingAllowed](#IsTransferOrderOverpickingAllowed)||<a href="WHSWarehouseMobileDeviceUserEntity.md" target="_blank">WMS/WHSWarehouseMobileDeviceUserEntity</a>|
|[IsManualItemReallocationAllowed](#IsManualItemReallocationAllowed)||<a href="WHSWarehouseMobileDeviceUserEntity.md" target="_blank">WMS/WHSWarehouseMobileDeviceUserEntity</a>|
|[Relationship_WarehouseWorkerRelationshipId](#Relationship_WarehouseWorkerRelationshipId)||<a href="WHSWarehouseMobileDeviceUserEntity.md" target="_blank">WMS/WHSWarehouseMobileDeviceUserEntity</a>|
|[Relationship_DefaultWarehouseRelationshipId](#Relationship_DefaultWarehouseRelationshipId)||<a href="WHSWarehouseMobileDeviceUserEntity.md" target="_blank">WMS/WHSWarehouseMobileDeviceUserEntity</a>|
|[Relationship_DefaultWarehouseMobileDeviceMenuRelationshipId](#Relationship_DefaultWarehouseMobileDeviceMenuRelationshipId)||<a href="WHSWarehouseMobileDeviceUserEntity.md" target="_blank">WMS/WHSWarehouseMobileDeviceUserEntity</a>|
|[BackingTable_WHSWorkUserRelationshipId](#BackingTable_WHSWorkUserRelationshipId)||<a href="WHSWarehouseMobileDeviceUserEntity.md" target="_blank">WMS/WHSWarehouseMobileDeviceUserEntity</a>|
|[Relationship_PrimaryCompanyContextRelationshipId](#Relationship_PrimaryCompanyContextRelationshipId)||<a href="WHSWarehouseMobileDeviceUserEntity.md" target="_blank">WMS/WHSWarehouseMobileDeviceUserEntity</a>|

### <a href=#WarehouseWorkerPersonnelNumber name="WarehouseWorkerPersonnelNumber">WarehouseWorkerPersonnelNumber</a>

First included in: WMS/WHSWarehouseMobileDeviceUserEntity (this entity)  

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

### <a href=#UserId name="UserId">UserId</a>

First included in: WMS/WHSWarehouseMobileDeviceUserEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the UserId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#UserName name="UserName">UserName</a>

First included in: WMS/WHSWarehouseMobileDeviceUserEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the UserName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DefaultWarehouseId name="DefaultWarehouseId">DefaultWarehouseId</a>

First included in: WMS/WHSWarehouseMobileDeviceUserEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultWarehouseId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DefaultMobileDeviceMenuItemName name="DefaultMobileDeviceMenuItemName">DefaultMobileDeviceMenuItemName</a>

First included in: WMS/WHSWarehouseMobileDeviceUserEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultMobileDeviceMenuItemName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsInactive name="IsInactive">IsInactive</a>

First included in: WMS/WHSWarehouseMobileDeviceUserEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsInactive attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsWarehousePickLocationOverrideAllowed name="IsWarehousePickLocationOverrideAllowed">IsWarehousePickLocationOverrideAllowed</a>

First included in: WMS/WHSWarehouseMobileDeviceUserEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsWarehousePickLocationOverrideAllowed attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsWarehousePutLocationOverrideAllowed name="IsWarehousePutLocationOverrideAllowed">IsWarehousePutLocationOverrideAllowed</a>

First included in: WMS/WHSWarehouseMobileDeviceUserEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsWarehousePutLocationOverrideAllowed attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsCountingSupervisor name="IsCountingSupervisor">IsCountingSupervisor</a>

First included in: WMS/WHSWarehouseMobileDeviceUserEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsCountingSupervisor attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CountingApprovalPercentageLimit name="CountingApprovalPercentageLimit">CountingApprovalPercentageLimit</a>

First included in: WMS/WHSWarehouseMobileDeviceUserEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CountingApprovalPercentageLimit attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CountingApprovalQuantityLimit name="CountingApprovalQuantityLimit">CountingApprovalQuantityLimit</a>

First included in: WMS/WHSWarehouseMobileDeviceUserEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CountingApprovalQuantityLimit attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CountingApprovalValueLimit name="CountingApprovalValueLimit">CountingApprovalValueLimit</a>

First included in: WMS/WHSWarehouseMobileDeviceUserEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CountingApprovalValueLimit attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Worker name="Worker">Worker</a>

First included in: WMS/WHSWarehouseMobileDeviceUserEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Worker attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WarehouseWorkerId name="WarehouseWorkerId">WarehouseWorkerId</a>

First included in: WMS/WHSWarehouseMobileDeviceUserEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WarehouseWorkerId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsAutomatedWarehouseWorkUser name="IsAutomatedWarehouseWorkUser">IsAutomatedWarehouseWorkUser</a>

First included in: WMS/WHSWarehouseMobileDeviceUserEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsAutomatedWarehouseWorkUser attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsInventoryMovementWithAssociatedWorkAllowed name="IsInventoryMovementWithAssociatedWorkAllowed">IsInventoryMovementWithAssociatedWorkAllowed</a>

First included in: WMS/WHSWarehouseMobileDeviceUserEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsInventoryMovementWithAssociatedWorkAllowed attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsSalesOrderOverpickingAllowed name="IsSalesOrderOverpickingAllowed">IsSalesOrderOverpickingAllowed</a>

First included in: WMS/WHSWarehouseMobileDeviceUserEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsSalesOrderOverpickingAllowed attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsTransferOrderOverpickingAllowed name="IsTransferOrderOverpickingAllowed">IsTransferOrderOverpickingAllowed</a>

First included in: WMS/WHSWarehouseMobileDeviceUserEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsTransferOrderOverpickingAllowed attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsManualItemReallocationAllowed name="IsManualItemReallocationAllowed">IsManualItemReallocationAllowed</a>

First included in: WMS/WHSWarehouseMobileDeviceUserEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsManualItemReallocationAllowed attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_WarehouseWorkerRelationshipId name="Relationship_WarehouseWorkerRelationshipId">Relationship_WarehouseWorkerRelationshipId</a>

First included in: WMS/WHSWarehouseMobileDeviceUserEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_WarehouseWorkerRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_DefaultWarehouseRelationshipId name="Relationship_DefaultWarehouseRelationshipId">Relationship_DefaultWarehouseRelationshipId</a>

First included in: WMS/WHSWarehouseMobileDeviceUserEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_DefaultWarehouseRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_DefaultWarehouseMobileDeviceMenuRelationshipId name="Relationship_DefaultWarehouseMobileDeviceMenuRelationshipId">Relationship_DefaultWarehouseMobileDeviceMenuRelationshipId</a>

First included in: WMS/WHSWarehouseMobileDeviceUserEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_DefaultWarehouseMobileDeviceMenuRelationshipId attribute are listed below.</summary>

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

### <a href=#BackingTable_WHSWorkUserRelationshipId name="BackingTable_WHSWorkUserRelationshipId">BackingTable_WHSWorkUserRelationshipId</a>

First included in: WMS/WHSWarehouseMobileDeviceUserEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_WHSWorkUserRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/SupplyChain/Inventory/Main/WHSWorkUser.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/Inventory/Main/WHSWorkUser.cdm.json/WHSWorkUser</a></td><td><a href="../../../Tables/SupplyChain/Inventory/Main/WHSWorkUser.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PrimaryCompanyContextRelationshipId name="Relationship_PrimaryCompanyContextRelationshipId">Relationship_PrimaryCompanyContextRelationshipId</a>

First included in: WMS/WHSWarehouseMobileDeviceUserEntity (this entity)  

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
