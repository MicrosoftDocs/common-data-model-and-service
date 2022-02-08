---
title: LeanProductAllocationKeyLeanScheduleGroupAssignmentEntity in ProductionControl - Common Data Model | Microsoft Docs
description: undefined
author: llawwaii
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: reference
ms.date: 8/7/2020
ms.author: weiluo
---

# Lean schedule allocation keys in ProductionControl(LeanProductAllocationKeyLeanScheduleGroupAssignmentEntity)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/SupplyChain/ProductionControl/LeanProductAllocationKeyLeanScheduleGroupAssignmentEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.1"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Lean schedule allocation keys</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[LeanScheduleGroup](#LeanScheduleGroup)||<a href="LeanProductAllocationKeyLeanScheduleGroupAssignmentEntity.md" target="_blank">ProductionControl/LeanProductAllocationKeyLeanScheduleGroupAssignmentEntity</a>|
|[LeanScheduleGroupId](#LeanScheduleGroupId)||<a href="LeanProductAllocationKeyLeanScheduleGroupAssignmentEntity.md" target="_blank">ProductionControl/LeanProductAllocationKeyLeanScheduleGroupAssignmentEntity</a>|
|[WorkCellOperationsResourceGroup](#WorkCellOperationsResourceGroup)||<a href="LeanProductAllocationKeyLeanScheduleGroupAssignmentEntity.md" target="_blank">ProductionControl/LeanProductAllocationKeyLeanScheduleGroupAssignmentEntity</a>|
|[NullableWorkCellOperationsResourceGroupId](#NullableWorkCellOperationsResourceGroupId)||<a href="LeanProductAllocationKeyLeanScheduleGroupAssignmentEntity.md" target="_blank">ProductionControl/LeanProductAllocationKeyLeanScheduleGroupAssignmentEntity</a>|
|[WorkCellOperationsResourceGroupId](#WorkCellOperationsResourceGroupId)||<a href="LeanProductAllocationKeyLeanScheduleGroupAssignmentEntity.md" target="_blank">ProductionControl/LeanProductAllocationKeyLeanScheduleGroupAssignmentEntity</a>|
|[ProductAllocationKeyId](#ProductAllocationKeyId)||<a href="LeanProductAllocationKeyLeanScheduleGroupAssignmentEntity.md" target="_blank">ProductionControl/LeanProductAllocationKeyLeanScheduleGroupAssignmentEntity</a>|
|[ThroughputRatio](#ThroughputRatio)||<a href="LeanProductAllocationKeyLeanScheduleGroupAssignmentEntity.md" target="_blank">ProductionControl/LeanProductAllocationKeyLeanScheduleGroupAssignmentEntity</a>|
|[Relationship_LeanScheduleGroupRelationshipId](#Relationship_LeanScheduleGroupRelationshipId)||<a href="LeanProductAllocationKeyLeanScheduleGroupAssignmentEntity.md" target="_blank">ProductionControl/LeanProductAllocationKeyLeanScheduleGroupAssignmentEntity</a>|
|[BackingTable_LeanScheduleGroupItemRelationshipId](#BackingTable_LeanScheduleGroupItemRelationshipId)||<a href="LeanProductAllocationKeyLeanScheduleGroupAssignmentEntity.md" target="_blank">ProductionControl/LeanProductAllocationKeyLeanScheduleGroupAssignmentEntity</a>|
|[Relationship_PrimaryCompanyContextRelationshipId](#Relationship_PrimaryCompanyContextRelationshipId)||<a href="LeanProductAllocationKeyLeanScheduleGroupAssignmentEntity.md" target="_blank">ProductionControl/LeanProductAllocationKeyLeanScheduleGroupAssignmentEntity</a>|

### <a href=#LeanScheduleGroup name="LeanScheduleGroup">LeanScheduleGroup</a>

First included in: ProductionControl/LeanProductAllocationKeyLeanScheduleGroupAssignmentEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LeanScheduleGroup attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LeanScheduleGroupId name="LeanScheduleGroupId">LeanScheduleGroupId</a>

First included in: ProductionControl/LeanProductAllocationKeyLeanScheduleGroupAssignmentEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LeanScheduleGroupId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WorkCellOperationsResourceGroup name="WorkCellOperationsResourceGroup">WorkCellOperationsResourceGroup</a>

First included in: ProductionControl/LeanProductAllocationKeyLeanScheduleGroupAssignmentEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WorkCellOperationsResourceGroup attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#NullableWorkCellOperationsResourceGroupId name="NullableWorkCellOperationsResourceGroupId">NullableWorkCellOperationsResourceGroupId</a>

First included in: ProductionControl/LeanProductAllocationKeyLeanScheduleGroupAssignmentEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the NullableWorkCellOperationsResourceGroupId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WorkCellOperationsResourceGroupId name="WorkCellOperationsResourceGroupId">WorkCellOperationsResourceGroupId</a>

First included in: ProductionControl/LeanProductAllocationKeyLeanScheduleGroupAssignmentEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WorkCellOperationsResourceGroupId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProductAllocationKeyId name="ProductAllocationKeyId">ProductAllocationKeyId</a>

First included in: ProductionControl/LeanProductAllocationKeyLeanScheduleGroupAssignmentEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProductAllocationKeyId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ThroughputRatio name="ThroughputRatio">ThroughputRatio</a>

First included in: ProductionControl/LeanProductAllocationKeyLeanScheduleGroupAssignmentEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ThroughputRatio attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_LeanScheduleGroupRelationshipId name="Relationship_LeanScheduleGroupRelationshipId">Relationship_LeanScheduleGroupRelationshipId</a>

First included in: ProductionControl/LeanProductAllocationKeyLeanScheduleGroupAssignmentEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_LeanScheduleGroupRelationshipId attribute are listed below.</summary>

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

### <a href=#BackingTable_LeanScheduleGroupItemRelationshipId name="BackingTable_LeanScheduleGroupItemRelationshipId">BackingTable_LeanScheduleGroupItemRelationshipId</a>

First included in: ProductionControl/LeanProductAllocationKeyLeanScheduleGroupAssignmentEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_LeanScheduleGroupItemRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/SupplyChain/MasterPlanning/Main/LeanScheduleGroupItem.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/MasterPlanning/Main/LeanScheduleGroupItem.cdm.json/LeanScheduleGroupItem</a></td><td><a href="../../../Tables/SupplyChain/MasterPlanning/Main/LeanScheduleGroupItem.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PrimaryCompanyContextRelationshipId name="Relationship_PrimaryCompanyContextRelationshipId">Relationship_PrimaryCompanyContextRelationshipId</a>

First included in: ProductionControl/LeanProductAllocationKeyLeanScheduleGroupAssignmentEntity (this entity)  

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
