---
title: LeanProductLeanScheduleGroupAssignmentV2Entity - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/28/2020
ms.author: nebanfic
---

# Lean scheduled items V2

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/SupplyChain/MasterPlanning/LeanProductLeanScheduleGroupAssignmentV2Entity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Lean scheduled items V2</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[LeanScheduleGroup](#LeanScheduleGroup)||<a href="LeanProductLeanScheduleGroupAssignmentV2Entity.md" target="_blank">MasterPlanning/LeanProductLeanScheduleGroupAssignmentV2Entity</a>|
|[LeanScheduleGroupId](#LeanScheduleGroupId)||<a href="LeanProductLeanScheduleGroupAssignmentV2Entity.md" target="_blank">MasterPlanning/LeanProductLeanScheduleGroupAssignmentV2Entity</a>|
|[WorkCellOperationsResourceGroup](#WorkCellOperationsResourceGroup)||<a href="LeanProductLeanScheduleGroupAssignmentV2Entity.md" target="_blank">MasterPlanning/LeanProductLeanScheduleGroupAssignmentV2Entity</a>|
|[NullableWorkCellOperationsResourceGroupId](#NullableWorkCellOperationsResourceGroupId)||<a href="LeanProductLeanScheduleGroupAssignmentV2Entity.md" target="_blank">MasterPlanning/LeanProductLeanScheduleGroupAssignmentV2Entity</a>|
|[WorkCellOperationsResourceGroupId](#WorkCellOperationsResourceGroupId)||<a href="LeanProductLeanScheduleGroupAssignmentV2Entity.md" target="_blank">MasterPlanning/LeanProductLeanScheduleGroupAssignmentV2Entity</a>|
|[ItemNumber](#ItemNumber)||<a href="LeanProductLeanScheduleGroupAssignmentV2Entity.md" target="_blank">MasterPlanning/LeanProductLeanScheduleGroupAssignmentV2Entity</a>|
|[ProductConfigurationId](#ProductConfigurationId)||<a href="LeanProductLeanScheduleGroupAssignmentV2Entity.md" target="_blank">MasterPlanning/LeanProductLeanScheduleGroupAssignmentV2Entity</a>|
|[ProductSizeId](#ProductSizeId)||<a href="LeanProductLeanScheduleGroupAssignmentV2Entity.md" target="_blank">MasterPlanning/LeanProductLeanScheduleGroupAssignmentV2Entity</a>|
|[ProductColorId](#ProductColorId)||<a href="LeanProductLeanScheduleGroupAssignmentV2Entity.md" target="_blank">MasterPlanning/LeanProductLeanScheduleGroupAssignmentV2Entity</a>|
|[ProductStyleId](#ProductStyleId)||<a href="LeanProductLeanScheduleGroupAssignmentV2Entity.md" target="_blank">MasterPlanning/LeanProductLeanScheduleGroupAssignmentV2Entity</a>|
|[ProductVersionId](#ProductVersionId)||<a href="LeanProductLeanScheduleGroupAssignmentV2Entity.md" target="_blank">MasterPlanning/LeanProductLeanScheduleGroupAssignmentV2Entity</a>|
|[ThroughputRatio](#ThroughputRatio)||<a href="LeanProductLeanScheduleGroupAssignmentV2Entity.md" target="_blank">MasterPlanning/LeanProductLeanScheduleGroupAssignmentV2Entity</a>|
|[Relationship_LeanScheduleGroupRelationshipId](#Relationship_LeanScheduleGroupRelationshipId)||<a href="LeanProductLeanScheduleGroupAssignmentV2Entity.md" target="_blank">MasterPlanning/LeanProductLeanScheduleGroupAssignmentV2Entity</a>|
|[BackingTable_LeanScheduleGroupItemRelationshipId](#BackingTable_LeanScheduleGroupItemRelationshipId)||<a href="LeanProductLeanScheduleGroupAssignmentV2Entity.md" target="_blank">MasterPlanning/LeanProductLeanScheduleGroupAssignmentV2Entity</a>|
|[Relationship_PrimaryCompanyContextRelationshipId](#Relationship_PrimaryCompanyContextRelationshipId)||<a href="LeanProductLeanScheduleGroupAssignmentV2Entity.md" target="_blank">MasterPlanning/LeanProductLeanScheduleGroupAssignmentV2Entity</a>|

### <a href=#LeanScheduleGroup name="LeanScheduleGroup">LeanScheduleGroup</a>

First included in: MasterPlanning/LeanProductLeanScheduleGroupAssignmentV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LeanScheduleGroup attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LeanScheduleGroupId name="LeanScheduleGroupId">LeanScheduleGroupId</a>

First included in: MasterPlanning/LeanProductLeanScheduleGroupAssignmentV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LeanScheduleGroupId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WorkCellOperationsResourceGroup name="WorkCellOperationsResourceGroup">WorkCellOperationsResourceGroup</a>

First included in: MasterPlanning/LeanProductLeanScheduleGroupAssignmentV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WorkCellOperationsResourceGroup attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#NullableWorkCellOperationsResourceGroupId name="NullableWorkCellOperationsResourceGroupId">NullableWorkCellOperationsResourceGroupId</a>

First included in: MasterPlanning/LeanProductLeanScheduleGroupAssignmentV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the NullableWorkCellOperationsResourceGroupId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WorkCellOperationsResourceGroupId name="WorkCellOperationsResourceGroupId">WorkCellOperationsResourceGroupId</a>

First included in: MasterPlanning/LeanProductLeanScheduleGroupAssignmentV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WorkCellOperationsResourceGroupId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ItemNumber name="ItemNumber">ItemNumber</a>

First included in: MasterPlanning/LeanProductLeanScheduleGroupAssignmentV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ItemNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProductConfigurationId name="ProductConfigurationId">ProductConfigurationId</a>

First included in: MasterPlanning/LeanProductLeanScheduleGroupAssignmentV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProductConfigurationId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProductSizeId name="ProductSizeId">ProductSizeId</a>

First included in: MasterPlanning/LeanProductLeanScheduleGroupAssignmentV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProductSizeId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProductColorId name="ProductColorId">ProductColorId</a>

First included in: MasterPlanning/LeanProductLeanScheduleGroupAssignmentV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProductColorId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProductStyleId name="ProductStyleId">ProductStyleId</a>

First included in: MasterPlanning/LeanProductLeanScheduleGroupAssignmentV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProductStyleId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProductVersionId name="ProductVersionId">ProductVersionId</a>

First included in: MasterPlanning/LeanProductLeanScheduleGroupAssignmentV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProductVersionId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ThroughputRatio name="ThroughputRatio">ThroughputRatio</a>

First included in: MasterPlanning/LeanProductLeanScheduleGroupAssignmentV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ThroughputRatio attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_LeanScheduleGroupRelationshipId name="Relationship_LeanScheduleGroupRelationshipId">Relationship_LeanScheduleGroupRelationshipId</a>

First included in: MasterPlanning/LeanProductLeanScheduleGroupAssignmentV2Entity (this entity)  

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

First included in: MasterPlanning/LeanProductLeanScheduleGroupAssignmentV2Entity (this entity)  

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

First included in: MasterPlanning/LeanProductLeanScheduleGroupAssignmentV2Entity (this entity)  

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
