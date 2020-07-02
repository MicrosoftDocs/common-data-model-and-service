---
title: SystemSecurityDutyV2Entity - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 6/30/2020
ms.author: nebanfic
---

# System Security Duty V2

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/System/SystemAdministration/SystemSecurityDutyV2Entity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>System Security Duty V2</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[SecurityRoleIdentifier](#SecurityRoleIdentifier)||<a href="SystemSecurityDutyV2Entity.md" target="_blank">SystemAdministration/SystemSecurityDutyV2Entity</a>|
|[SecurityRoleName](#SecurityRoleName)||<a href="SystemSecurityDutyV2Entity.md" target="_blank">SystemAdministration/SystemSecurityDutyV2Entity</a>|
|[SecurityDutyIdentifier](#SecurityDutyIdentifier)||<a href="SystemSecurityDutyV2Entity.md" target="_blank">SystemAdministration/SystemSecurityDutyV2Entity</a>|
|[SecurityDutyName](#SecurityDutyName)||<a href="SystemSecurityDutyV2Entity.md" target="_blank">SystemAdministration/SystemSecurityDutyV2Entity</a>|
|[SecurityPrivilegeName](#SecurityPrivilegeName)||<a href="SystemSecurityDutyV2Entity.md" target="_blank">SystemAdministration/SystemSecurityDutyV2Entity</a>|
|[SecurityPrivilege](#SecurityPrivilege)||<a href="SystemSecurityDutyV2Entity.md" target="_blank">SystemAdministration/SystemSecurityDutyV2Entity</a>|
|[SecurityPrivilegeIdentifier](#SecurityPrivilegeIdentifier)||<a href="SystemSecurityDutyV2Entity.md" target="_blank">SystemAdministration/SystemSecurityDutyV2Entity</a>|
|[BackingTable_SecurityRoleDutyPrivilegeExplodedGraphRelationshipId](#BackingTable_SecurityRoleDutyPrivilegeExplodedGraphRelationshipId)||<a href="SystemSecurityDutyV2Entity.md" target="_blank">SystemAdministration/SystemSecurityDutyV2Entity</a>|

### <a href=#SecurityRoleIdentifier name="SecurityRoleIdentifier">SecurityRoleIdentifier</a>

First included in: SystemAdministration/SystemSecurityDutyV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SecurityRoleIdentifier attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SecurityRoleName name="SecurityRoleName">SecurityRoleName</a>

First included in: SystemAdministration/SystemSecurityDutyV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SecurityRoleName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SecurityDutyIdentifier name="SecurityDutyIdentifier">SecurityDutyIdentifier</a>

First included in: SystemAdministration/SystemSecurityDutyV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SecurityDutyIdentifier attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SecurityDutyName name="SecurityDutyName">SecurityDutyName</a>

First included in: SystemAdministration/SystemSecurityDutyV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SecurityDutyName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SecurityPrivilegeName name="SecurityPrivilegeName">SecurityPrivilegeName</a>

First included in: SystemAdministration/SystemSecurityDutyV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SecurityPrivilegeName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SecurityPrivilege name="SecurityPrivilege">SecurityPrivilege</a>

First included in: SystemAdministration/SystemSecurityDutyV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SecurityPrivilege attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SecurityPrivilegeIdentifier name="SecurityPrivilegeIdentifier">SecurityPrivilegeIdentifier</a>

First included in: SystemAdministration/SystemSecurityDutyV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SecurityPrivilegeIdentifier attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BackingTable_SecurityRoleDutyPrivilegeExplodedGraphRelationshipId name="BackingTable_SecurityRoleDutyPrivilegeExplodedGraphRelationshipId">BackingTable_SecurityRoleDutyPrivilegeExplodedGraphRelationshipId</a>

First included in: SystemAdministration/SystemSecurityDutyV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_SecurityRoleDutyPrivilegeExplodedGraphRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/System/SystemAdministration/Miscellaneous/SecurityRoleDutyPrivilegeExplodedGraph.md" target="_blank">/core/operationsCommon/Tables/System/SystemAdministration/Miscellaneous/SecurityRoleDutyPrivilegeExplodedGraph.cdm.json/SecurityRoleDutyPrivilegeExplodedGraph</a></td><td><a href="../../../Tables/System/SystemAdministration/Miscellaneous/SecurityRoleDutyPrivilegeExplodedGraph.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>
