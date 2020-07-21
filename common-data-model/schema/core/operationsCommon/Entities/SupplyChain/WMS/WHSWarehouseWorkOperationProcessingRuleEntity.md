---
title: WHSWarehouseWorkOperationProcessingRuleEntity in WMS - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 7/21/2020
ms.author: nebanfic
---

# Work operation processing rule in WMS(WHSWarehouseWorkOperationProcessingRuleEntity)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/SupplyChain/WMS/WHSWarehouseWorkOperationProcessingRuleEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Work operation processing rule</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[WarehouseWorkProcessingPolicyName](#WarehouseWorkProcessingPolicyName)||<a href="WHSWarehouseWorkOperationProcessingRuleEntity.md" target="_blank">WMS/WHSWarehouseWorkOperationProcessingRuleEntity</a>|
|[WorkOrderType](#WorkOrderType)||<a href="WHSWarehouseWorkOperationProcessingRuleEntity.md" target="_blank">WMS/WHSWarehouseWorkOperationProcessingRuleEntity</a>|
|[OperationType](#OperationType)||<a href="WHSWarehouseWorkOperationProcessingRuleEntity.md" target="_blank">WMS/WHSWarehouseWorkOperationProcessingRuleEntity</a>|
|[ProcessingMethod](#ProcessingMethod)||<a href="WHSWarehouseWorkOperationProcessingRuleEntity.md" target="_blank">WMS/WHSWarehouseWorkOperationProcessingRuleEntity</a>|
|[DeferredProcessingThreshold](#DeferredProcessingThreshold)||<a href="WHSWarehouseWorkOperationProcessingRuleEntity.md" target="_blank">WMS/WHSWarehouseWorkOperationProcessingRuleEntity</a>|
|[DeferredProcessingBatchGroupId](#DeferredProcessingBatchGroupId)||<a href="WHSWarehouseWorkOperationProcessingRuleEntity.md" target="_blank">WMS/WHSWarehouseWorkOperationProcessingRuleEntity</a>|
|[Relationship_WHSWarehouseWorkProcessingPolicyRelationshipId](#Relationship_WHSWarehouseWorkProcessingPolicyRelationshipId)||<a href="WHSWarehouseWorkOperationProcessingRuleEntity.md" target="_blank">WMS/WHSWarehouseWorkOperationProcessingRuleEntity</a>|
|[BackingTable_WHSWorkOperationProcessingRuleRelationshipId](#BackingTable_WHSWorkOperationProcessingRuleRelationshipId)||<a href="WHSWarehouseWorkOperationProcessingRuleEntity.md" target="_blank">WMS/WHSWarehouseWorkOperationProcessingRuleEntity</a>|

### <a href=#WarehouseWorkProcessingPolicyName name="WarehouseWorkProcessingPolicyName">WarehouseWorkProcessingPolicyName</a>

First included in: WMS/WHSWarehouseWorkOperationProcessingRuleEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WarehouseWorkProcessingPolicyName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WorkOrderType name="WorkOrderType">WorkOrderType</a>

First included in: WMS/WHSWarehouseWorkOperationProcessingRuleEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WorkOrderType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#OperationType name="OperationType">OperationType</a>

First included in: WMS/WHSWarehouseWorkOperationProcessingRuleEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OperationType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProcessingMethod name="ProcessingMethod">ProcessingMethod</a>

First included in: WMS/WHSWarehouseWorkOperationProcessingRuleEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProcessingMethod attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DeferredProcessingThreshold name="DeferredProcessingThreshold">DeferredProcessingThreshold</a>

First included in: WMS/WHSWarehouseWorkOperationProcessingRuleEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DeferredProcessingThreshold attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DeferredProcessingBatchGroupId name="DeferredProcessingBatchGroupId">DeferredProcessingBatchGroupId</a>

First included in: WMS/WHSWarehouseWorkOperationProcessingRuleEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DeferredProcessingBatchGroupId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_WHSWarehouseWorkProcessingPolicyRelationshipId name="Relationship_WHSWarehouseWorkProcessingPolicyRelationshipId">Relationship_WHSWarehouseWorkProcessingPolicyRelationshipId</a>

First included in: WMS/WHSWarehouseWorkOperationProcessingRuleEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_WHSWarehouseWorkProcessingPolicyRelationshipId attribute are listed below.</summary>

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

### <a href=#BackingTable_WHSWorkOperationProcessingRuleRelationshipId name="BackingTable_WHSWorkOperationProcessingRuleRelationshipId">BackingTable_WHSWorkOperationProcessingRuleRelationshipId</a>

First included in: WMS/WHSWarehouseWorkOperationProcessingRuleEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_WHSWorkOperationProcessingRuleRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/SupplyChain/Inventory/Group/WHSWorkOperationProcessingRule.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/Inventory/Group/WHSWorkOperationProcessingRule.cdm.json/WHSWorkOperationProcessingRule</a></td><td><a href="../../../Tables/SupplyChain/Inventory/Group/WHSWorkOperationProcessingRule.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>
