---
title: RetailOperations in Parameter - Common Data Model | Microsoft Docs
description: undefined
author: llawwaii

ms.reviewer: deonhe
ms.topic: reference
ms.date: 8/7/2020
ms.author: weiluo
---

# POS operations in Parameter(RetailOperations)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Tables/Commerce/ChannelManagement/Parameter/RetailOperations.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[RetailOperations/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>POS operations</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="RetailOperations.md" target="_blank">Parameter/RetailOperations</a>|
|[OperationId](#OperationId)||<a href="RetailOperations.md" target="_blank">Parameter/RetailOperations</a>|
|[ActionPropertyLookupType](#ActionPropertyLookupType)||<a href="RetailOperations.md" target="_blank">Parameter/RetailOperations</a>|
|[CheckUserAccess](#CheckUserAccess)||<a href="RetailOperations.md" target="_blank">Parameter/RetailOperations</a>|
|[OperationName](#OperationName)||<a href="RetailOperations.md" target="_blank">Parameter/RetailOperations</a>|
|[PermissionId](#PermissionId)||<a href="RetailOperations.md" target="_blank">Parameter/RetailOperations</a>|
|[PermissionId2](#PermissionId2)||<a href="RetailOperations.md" target="_blank">Parameter/RetailOperations</a>|
|[UserOperation](#UserOperation)||<a href="RetailOperations.md" target="_blank">Parameter/RetailOperations</a>|
|[AllowAnonymousAccess](#AllowAnonymousAccess)||<a href="RetailOperations.md" target="_blank">Parameter/RetailOperations</a>|
|[AllowCustomerAccess](#AllowCustomerAccess)||<a href="RetailOperations.md" target="_blank">Parameter/RetailOperations</a>|
|[PermissionIdEx](#PermissionIdEx)||<a href="RetailOperations.md" target="_blank">Parameter/RetailOperations</a>|
|[AllowApplicationAccess](#AllowApplicationAccess)||<a href="RetailOperations.md" target="_blank">Parameter/RetailOperations</a>|
|[EnableNotifications](#EnableNotifications)||<a href="RetailOperations.md" target="_blank">Parameter/RetailOperations</a>|
|[AllowTaskLink](#AllowTaskLink)||<a href="RetailOperations.md" target="_blank">Parameter/RetailOperations</a>|
|[Relationship_RetailPermissionsRelationshipId](#Relationship_RetailPermissionsRelationshipId)||<a href="RetailOperations.md" target="_blank">Parameter/RetailOperations</a>|
|[Relationship_RetailPermissions1RelationshipId](#Relationship_RetailPermissions1RelationshipId)||<a href="RetailOperations.md" target="_blank">Parameter/RetailOperations</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: Parameter/RetailOperations (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[RetailOperations/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#OperationId name="OperationId">OperationId</a>

First included in: Parameter/RetailOperations (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OperationId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#ActionPropertyLookupType name="ActionPropertyLookupType">ActionPropertyLookupType</a>

First included in: Parameter/RetailOperations (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ActionPropertyLookupType attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#CheckUserAccess name="CheckUserAccess">CheckUserAccess</a>

First included in: Parameter/RetailOperations (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CheckUserAccess attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#OperationName name="OperationName">OperationName</a>

First included in: Parameter/RetailOperations (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OperationName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PermissionId name="PermissionId">PermissionId</a>

First included in: Parameter/RetailOperations (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PermissionId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#PermissionId2 name="PermissionId2">PermissionId2</a>

First included in: Parameter/RetailOperations (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PermissionId2 attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#UserOperation name="UserOperation">UserOperation</a>

First included in: Parameter/RetailOperations (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the UserOperation attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#AllowAnonymousAccess name="AllowAnonymousAccess">AllowAnonymousAccess</a>

First included in: Parameter/RetailOperations (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AllowAnonymousAccess attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#AllowCustomerAccess name="AllowCustomerAccess">AllowCustomerAccess</a>

First included in: Parameter/RetailOperations (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AllowCustomerAccess attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#PermissionIdEx name="PermissionIdEx">PermissionIdEx</a>

First included in: Parameter/RetailOperations (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PermissionIdEx attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#AllowApplicationAccess name="AllowApplicationAccess">AllowApplicationAccess</a>

First included in: Parameter/RetailOperations (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AllowApplicationAccess attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#EnableNotifications name="EnableNotifications">EnableNotifications</a>

First included in: Parameter/RetailOperations (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EnableNotifications attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#AllowTaskLink name="AllowTaskLink">AllowTaskLink</a>

First included in: Parameter/RetailOperations (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AllowTaskLink attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#Relationship_RetailPermissionsRelationshipId name="Relationship_RetailPermissionsRelationshipId">Relationship_RetailPermissionsRelationshipId</a>

First included in: Parameter/RetailOperations (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_RetailPermissionsRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../BrickAndMortarStore/Parameter/RetailPermissions.md" target="_blank">/core/operationsCommon/Tables/Commerce/ChannelManagement/BrickAndMortarStore/Parameter/RetailPermissions.cdm.json/RetailPermissions</a></td><td><a href="../BrickAndMortarStore/Parameter/RetailPermissions.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_RetailPermissions1RelationshipId name="Relationship_RetailPermissions1RelationshipId">Relationship_RetailPermissions1RelationshipId</a>

First included in: Parameter/RetailOperations (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_RetailPermissions1RelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../BrickAndMortarStore/Parameter/RetailPermissions.md" target="_blank">/core/operationsCommon/Tables/Commerce/ChannelManagement/BrickAndMortarStore/Parameter/RetailPermissions.cdm.json/RetailPermissions</a></td><td><a href="../BrickAndMortarStore/Parameter/RetailPermissions.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>
