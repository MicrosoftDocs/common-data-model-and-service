---
title: RetailNotificationSubscriptionsEntity in TransactionsAndOrders - Common Data Model | Microsoft Docs
description: undefined
author: llawwaii

ms.reviewer: deonhe
ms.topic: article
ms.date: 8/7/2020
ms.author: weiluo
---

# RetailNotificationSubscriptionsEntity in TransactionsAndOrders

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/Commerce/TransactionsAndOrders/RetailNotificationSubscriptionsEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[DisplayOrder](#DisplayOrder)||<a href="RetailNotificationSubscriptionsEntity.md" target="_blank">TransactionsAndOrders/RetailNotificationSubscriptionsEntity</a>|
|[RetailOperation](#RetailOperation)||<a href="RetailNotificationSubscriptionsEntity.md" target="_blank">TransactionsAndOrders/RetailNotificationSubscriptionsEntity</a>|
|[RetailPosPermissionGroup](#RetailPosPermissionGroup)||<a href="RetailNotificationSubscriptionsEntity.md" target="_blank">TransactionsAndOrders/RetailNotificationSubscriptionsEntity</a>|
|[RetailPosPermissionGroup_PosPermissionGroupId](#RetailPosPermissionGroup_PosPermissionGroupId)||<a href="RetailNotificationSubscriptionsEntity.md" target="_blank">TransactionsAndOrders/RetailNotificationSubscriptionsEntity</a>|
|[RetailOperation_OperationId](#RetailOperation_OperationId)||<a href="RetailNotificationSubscriptionsEntity.md" target="_blank">TransactionsAndOrders/RetailNotificationSubscriptionsEntity</a>|
|[BackingTable_RetailNotificationSubscriptionsRelationshipId](#BackingTable_RetailNotificationSubscriptionsRelationshipId)||<a href="RetailNotificationSubscriptionsEntity.md" target="_blank">TransactionsAndOrders/RetailNotificationSubscriptionsEntity</a>|

### <a href=#DisplayOrder name="DisplayOrder">DisplayOrder</a>

First included in: TransactionsAndOrders/RetailNotificationSubscriptionsEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DisplayOrder attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RetailOperation name="RetailOperation">RetailOperation</a>

First included in: TransactionsAndOrders/RetailNotificationSubscriptionsEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RetailOperation attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RetailPosPermissionGroup name="RetailPosPermissionGroup">RetailPosPermissionGroup</a>

First included in: TransactionsAndOrders/RetailNotificationSubscriptionsEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RetailPosPermissionGroup attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RetailPosPermissionGroup_PosPermissionGroupId name="RetailPosPermissionGroup_PosPermissionGroupId">RetailPosPermissionGroup_PosPermissionGroupId</a>

First included in: TransactionsAndOrders/RetailNotificationSubscriptionsEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RetailPosPermissionGroup_PosPermissionGroupId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RetailOperation_OperationId name="RetailOperation_OperationId">RetailOperation_OperationId</a>

First included in: TransactionsAndOrders/RetailNotificationSubscriptionsEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RetailOperation_OperationId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BackingTable_RetailNotificationSubscriptionsRelationshipId name="BackingTable_RetailNotificationSubscriptionsRelationshipId">BackingTable_RetailNotificationSubscriptionsRelationshipId</a>

First included in: TransactionsAndOrders/RetailNotificationSubscriptionsEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_RetailNotificationSubscriptionsRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/Commerce/InventoryAndAdvancedWarehouse/Miscellaneous/RetailNotificationSubscriptions.md" target="_blank">/core/operationsCommon/Tables/Commerce/InventoryAndAdvancedWarehouse/Miscellaneous/RetailNotificationSubscriptions.cdm.json/RetailNotificationSubscriptions</a></td><td><a href="../../../Tables/Commerce/InventoryAndAdvancedWarehouse/Miscellaneous/RetailNotificationSubscriptions.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>
