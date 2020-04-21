---
title: InventQualityTestGroupEntity - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/21/2020
ms.author: nebanfic
---

# InventQualityTestGroupEntity

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/SupplyChain/InventoryAndWarehouseManagement/InventQualityTestGroupEntity.cdm.json" target="_blank">GitHub</a>.  

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
|[AcceptableQualityLevelPercentage](#AcceptableQualityLevelPercentage)||<a href="InventQualityTestGroupEntity.md" target="_blank">InventoryAndWarehouseManagement/InventQualityTestGroupEntity</a>|
|[Description](#Description)||<a href="InventQualityTestGroupEntity.md" target="_blank">InventoryAndWarehouseManagement/InventQualityTestGroupEntity</a>|
|[FailedQualityOrderInventoryStatusId](#FailedQualityOrderInventoryStatusId)||<a href="InventQualityTestGroupEntity.md" target="_blank">InventoryAndWarehouseManagement/InventQualityTestGroupEntity</a>|
|[ItemSamplingId](#ItemSamplingId)||<a href="InventQualityTestGroupEntity.md" target="_blank">InventoryAndWarehouseManagement/InventQualityTestGroupEntity</a>|
|[PassedQualityOrderInventoryStatusId](#PassedQualityOrderInventoryStatusId)||<a href="InventQualityTestGroupEntity.md" target="_blank">InventoryAndWarehouseManagement/InventQualityTestGroupEntity</a>|
|[FailedQualityOrderBatchDispositionCode](#FailedQualityOrderBatchDispositionCode)||<a href="InventQualityTestGroupEntity.md" target="_blank">InventoryAndWarehouseManagement/InventQualityTestGroupEntity</a>|
|[PassedQualityOrderBatchDispositionCode](#PassedQualityOrderBatchDispositionCode)||<a href="InventQualityTestGroupEntity.md" target="_blank">InventoryAndWarehouseManagement/InventQualityTestGroupEntity</a>|
|[IsBatchAttributeValueDefaultedWithTestMeasurement](#IsBatchAttributeValueDefaultedWithTestMeasurement)||<a href="InventQualityTestGroupEntity.md" target="_blank">InventoryAndWarehouseManagement/InventQualityTestGroupEntity</a>|
|[IsBatchDispositionStatusDefaultedWithTestMeasurement](#IsBatchDispositionStatusDefaultedWithTestMeasurement)||<a href="InventQualityTestGroupEntity.md" target="_blank">InventoryAndWarehouseManagement/InventQualityTestGroupEntity</a>|
|[IsDestructiveTest](#IsDestructiveTest)||<a href="InventQualityTestGroupEntity.md" target="_blank">InventoryAndWarehouseManagement/InventQualityTestGroupEntity</a>|
|[QualityTestGroupId](#QualityTestGroupId)||<a href="InventQualityTestGroupEntity.md" target="_blank">InventoryAndWarehouseManagement/InventQualityTestGroupEntity</a>|
|[IsInventoryStatusDefaultedWithTestMeasurement](#IsInventoryStatusDefaultedWithTestMeasurement)||<a href="InventQualityTestGroupEntity.md" target="_blank">InventoryAndWarehouseManagement/InventQualityTestGroupEntity</a>|
|[Relationship_FailedQualityOrderInventoryStatusRelationshipId](#Relationship_FailedQualityOrderInventoryStatusRelationshipId)||<a href="InventQualityTestGroupEntity.md" target="_blank">InventoryAndWarehouseManagement/InventQualityTestGroupEntity</a>|
|[Relationship_PassedQualityOrderInventoryStatusRelationshipId](#Relationship_PassedQualityOrderInventoryStatusRelationshipId)||<a href="InventQualityTestGroupEntity.md" target="_blank">InventoryAndWarehouseManagement/InventQualityTestGroupEntity</a>|
|[Relationship_ItemSamplingRelationshipId](#Relationship_ItemSamplingRelationshipId)||<a href="InventQualityTestGroupEntity.md" target="_blank">InventoryAndWarehouseManagement/InventQualityTestGroupEntity</a>|
|[Relationship_FailedQualityOrderBatchDispositionRelationshipId](#Relationship_FailedQualityOrderBatchDispositionRelationshipId)||<a href="InventQualityTestGroupEntity.md" target="_blank">InventoryAndWarehouseManagement/InventQualityTestGroupEntity</a>|
|[Relationship_PassedQualityOrderBatchDispositionRelationshipId](#Relationship_PassedQualityOrderBatchDispositionRelationshipId)||<a href="InventQualityTestGroupEntity.md" target="_blank">InventoryAndWarehouseManagement/InventQualityTestGroupEntity</a>|
|[BackingTable_InventTestGroupRelationshipId](#BackingTable_InventTestGroupRelationshipId)||<a href="InventQualityTestGroupEntity.md" target="_blank">InventoryAndWarehouseManagement/InventQualityTestGroupEntity</a>|
|[Relationship_PrimaryCompanyContextRelationshipId](#Relationship_PrimaryCompanyContextRelationshipId)||<a href="InventQualityTestGroupEntity.md" target="_blank">InventoryAndWarehouseManagement/InventQualityTestGroupEntity</a>|

### <a href=#AcceptableQualityLevelPercentage name="AcceptableQualityLevelPercentage">AcceptableQualityLevelPercentage</a>

First included in: InventoryAndWarehouseManagement/InventQualityTestGroupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AcceptableQualityLevelPercentage attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Description name="Description">Description</a>

First included in: InventoryAndWarehouseManagement/InventQualityTestGroupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Description attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FailedQualityOrderInventoryStatusId name="FailedQualityOrderInventoryStatusId">FailedQualityOrderInventoryStatusId</a>

First included in: InventoryAndWarehouseManagement/InventQualityTestGroupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FailedQualityOrderInventoryStatusId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ItemSamplingId name="ItemSamplingId">ItemSamplingId</a>

First included in: InventoryAndWarehouseManagement/InventQualityTestGroupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ItemSamplingId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PassedQualityOrderInventoryStatusId name="PassedQualityOrderInventoryStatusId">PassedQualityOrderInventoryStatusId</a>

First included in: InventoryAndWarehouseManagement/InventQualityTestGroupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PassedQualityOrderInventoryStatusId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FailedQualityOrderBatchDispositionCode name="FailedQualityOrderBatchDispositionCode">FailedQualityOrderBatchDispositionCode</a>

First included in: InventoryAndWarehouseManagement/InventQualityTestGroupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FailedQualityOrderBatchDispositionCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PassedQualityOrderBatchDispositionCode name="PassedQualityOrderBatchDispositionCode">PassedQualityOrderBatchDispositionCode</a>

First included in: InventoryAndWarehouseManagement/InventQualityTestGroupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PassedQualityOrderBatchDispositionCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsBatchAttributeValueDefaultedWithTestMeasurement name="IsBatchAttributeValueDefaultedWithTestMeasurement">IsBatchAttributeValueDefaultedWithTestMeasurement</a>

First included in: InventoryAndWarehouseManagement/InventQualityTestGroupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsBatchAttributeValueDefaultedWithTestMeasurement attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsBatchDispositionStatusDefaultedWithTestMeasurement name="IsBatchDispositionStatusDefaultedWithTestMeasurement">IsBatchDispositionStatusDefaultedWithTestMeasurement</a>

First included in: InventoryAndWarehouseManagement/InventQualityTestGroupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsBatchDispositionStatusDefaultedWithTestMeasurement attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsDestructiveTest name="IsDestructiveTest">IsDestructiveTest</a>

First included in: InventoryAndWarehouseManagement/InventQualityTestGroupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsDestructiveTest attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#QualityTestGroupId name="QualityTestGroupId">QualityTestGroupId</a>

First included in: InventoryAndWarehouseManagement/InventQualityTestGroupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the QualityTestGroupId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsInventoryStatusDefaultedWithTestMeasurement name="IsInventoryStatusDefaultedWithTestMeasurement">IsInventoryStatusDefaultedWithTestMeasurement</a>

First included in: InventoryAndWarehouseManagement/InventQualityTestGroupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsInventoryStatusDefaultedWithTestMeasurement attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_FailedQualityOrderInventoryStatusRelationshipId name="Relationship_FailedQualityOrderInventoryStatusRelationshipId">Relationship_FailedQualityOrderInventoryStatusRelationshipId</a>

First included in: InventoryAndWarehouseManagement/InventQualityTestGroupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_FailedQualityOrderInventoryStatusRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_PassedQualityOrderInventoryStatusRelationshipId name="Relationship_PassedQualityOrderInventoryStatusRelationshipId">Relationship_PassedQualityOrderInventoryStatusRelationshipId</a>

First included in: InventoryAndWarehouseManagement/InventQualityTestGroupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_PassedQualityOrderInventoryStatusRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_ItemSamplingRelationshipId name="Relationship_ItemSamplingRelationshipId">Relationship_ItemSamplingRelationshipId</a>

First included in: InventoryAndWarehouseManagement/InventQualityTestGroupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_ItemSamplingRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_FailedQualityOrderBatchDispositionRelationshipId name="Relationship_FailedQualityOrderBatchDispositionRelationshipId">Relationship_FailedQualityOrderBatchDispositionRelationshipId</a>

First included in: InventoryAndWarehouseManagement/InventQualityTestGroupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_FailedQualityOrderBatchDispositionRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_PassedQualityOrderBatchDispositionRelationshipId name="Relationship_PassedQualityOrderBatchDispositionRelationshipId">Relationship_PassedQualityOrderBatchDispositionRelationshipId</a>

First included in: InventoryAndWarehouseManagement/InventQualityTestGroupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_PassedQualityOrderBatchDispositionRelationshipId attribute are listed below.</summary>

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

### <a href=#BackingTable_InventTestGroupRelationshipId name="BackingTable_InventTestGroupRelationshipId">BackingTable_InventTestGroupRelationshipId</a>

First included in: InventoryAndWarehouseManagement/InventQualityTestGroupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_InventTestGroupRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/SupplyChain/Inventory/Group/InventTestGroup.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/Inventory/Group/InventTestGroup.cdm.json/InventTestGroup</a></td><td><a href="../../../Tables/SupplyChain/Inventory/Group/InventTestGroup.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PrimaryCompanyContextRelationshipId name="Relationship_PrimaryCompanyContextRelationshipId">Relationship_PrimaryCompanyContextRelationshipId</a>

First included in: InventoryAndWarehouseManagement/InventQualityTestGroupEntity (this entity)  

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
