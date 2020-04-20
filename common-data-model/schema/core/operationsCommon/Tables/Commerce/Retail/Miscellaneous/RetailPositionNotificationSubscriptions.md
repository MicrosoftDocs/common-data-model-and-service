---
title: RetailPositionNotificationSubscriptions - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/20/2020
ms.author: nebanfic
---

# RetailPositionNotificationSubscriptions

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Tables/Commerce/Retail/Miscellaneous/RetailPositionNotificationSubscriptions.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[RetailPositionNotificationSubscriptions/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="RetailPositionNotificationSubscriptions.md" target="_blank">Miscellaneous/RetailPositionNotificationSubscriptions</a>|
|[DisplayOrder](#DisplayOrder)||<a href="RetailPositionNotificationSubscriptions.md" target="_blank">Miscellaneous/RetailPositionNotificationSubscriptions</a>|
|[RetailOperation](#RetailOperation)||<a href="RetailPositionNotificationSubscriptions.md" target="_blank">Miscellaneous/RetailPositionNotificationSubscriptions</a>|
|[RetailPositionPosPermission](#RetailPositionPosPermission)||<a href="RetailPositionNotificationSubscriptions.md" target="_blank">Miscellaneous/RetailPositionNotificationSubscriptions</a>|
|[Relationship_RetailOperationRelationshipId](#Relationship_RetailOperationRelationshipId)||<a href="RetailPositionNotificationSubscriptions.md" target="_blank">Miscellaneous/RetailPositionNotificationSubscriptions</a>|
|[Relationship_RetailPositionPosPermissionRelationshipId](#Relationship_RetailPositionPosPermissionRelationshipId)||<a href="RetailPositionNotificationSubscriptions.md" target="_blank">Miscellaneous/RetailPositionNotificationSubscriptions</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: Miscellaneous/RetailPositionNotificationSubscriptions (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[RetailPositionNotificationSubscriptions/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#DisplayOrder name="DisplayOrder">DisplayOrder</a>

First included in: Miscellaneous/RetailPositionNotificationSubscriptions (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DisplayOrder attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#RetailOperation name="RetailOperation">RetailOperation</a>

First included in: Miscellaneous/RetailPositionNotificationSubscriptions (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RetailOperation attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#RetailPositionPosPermission name="RetailPositionPosPermission">RetailPositionPosPermission</a>

First included in: Miscellaneous/RetailPositionNotificationSubscriptions (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RetailPositionPosPermission attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#Relationship_RetailOperationRelationshipId name="Relationship_RetailOperationRelationshipId">Relationship_RetailOperationRelationshipId</a>

First included in: Miscellaneous/RetailPositionNotificationSubscriptions (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_RetailOperationRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Parameter/RetailOperations.md" target="_blank">/core/operationsCommon/Tables/Commerce/Retail/Parameter/RetailOperations.cdm.json/RetailOperations</a></td><td><a href="../Parameter/RetailOperations.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_RetailPositionPosPermissionRelationshipId name="Relationship_RetailPositionPosPermissionRelationshipId">Relationship_RetailPositionPosPermissionRelationshipId</a>

First included in: Miscellaneous/RetailPositionNotificationSubscriptions (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_RetailPositionPosPermissionRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Group/RetailPositionPosPermission.md" target="_blank">/core/operationsCommon/Tables/Commerce/Retail/Group/RetailPositionPosPermission.cdm.json/RetailPositionPosPermission</a></td><td><a href="../Group/RetailPositionPosPermission.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>
