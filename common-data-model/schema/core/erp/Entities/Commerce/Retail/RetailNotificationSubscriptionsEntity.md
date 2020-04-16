---
title: RetailNotificationSubscriptionsEntity - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/16/2020
ms.author: nebanfic
---

# RetailNotificationSubscriptionsEntity

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/erp/Entities/Commerce/Retail/RetailNotificationSubscriptionsEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.Application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Entity|
|---|---|---|
|[DisplayOrder](#DisplayOrder)||<a href="RetailNotificationSubscriptionsEntity.md" target="_blank">Retail/RetailNotificationSubscriptionsEntity</a>|
|[RetailOperation](#RetailOperation)||<a href="RetailNotificationSubscriptionsEntity.md" target="_blank">Retail/RetailNotificationSubscriptionsEntity</a>|
|[RetailPosPermissionGroup](#RetailPosPermissionGroup)||<a href="RetailNotificationSubscriptionsEntity.md" target="_blank">Retail/RetailNotificationSubscriptionsEntity</a>|
|[RetailPosPermissionGroup_PosPermissionGroupId](#RetailPosPermissionGroup_PosPermissionGroupId)||<a href="RetailNotificationSubscriptionsEntity.md" target="_blank">Retail/RetailNotificationSubscriptionsEntity</a>|
|[RetailOperation_OperationId](#RetailOperation_OperationId)||<a href="RetailNotificationSubscriptionsEntity.md" target="_blank">Retail/RetailNotificationSubscriptionsEntity</a>|
|[BackingTable_RetailNotificationSubscriptionsRelationshipId](#BackingTable_RetailNotificationSubscriptionsRelationshipId)||<a href="RetailNotificationSubscriptionsEntity.md" target="_blank">Retail/RetailNotificationSubscriptionsEntity</a>|

### <a href=#DisplayOrder name="DisplayOrder">DisplayOrder</a>

First included in: Retail/RetailNotificationSubscriptionsEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>7</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DisplayOrder attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RetailOperation name="RetailOperation">RetailOperation</a>

First included in: Retail/RetailNotificationSubscriptionsEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>7</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RetailOperation attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RetailPosPermissionGroup name="RetailPosPermissionGroup">RetailPosPermissionGroup</a>

First included in: Retail/RetailNotificationSubscriptionsEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>7</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RetailPosPermissionGroup attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RetailPosPermissionGroup_PosPermissionGroupId name="RetailPosPermissionGroup_PosPermissionGroupId">RetailPosPermissionGroup_PosPermissionGroupId</a>

First included in: Retail/RetailNotificationSubscriptionsEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>7</td></tr></table>

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

First included in: Retail/RetailNotificationSubscriptionsEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>7</td></tr></table>

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

First included in: Retail/RetailNotificationSubscriptionsEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>6</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_RetailNotificationSubscriptionsRelationshipId attribute are listed below.</summary>

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
