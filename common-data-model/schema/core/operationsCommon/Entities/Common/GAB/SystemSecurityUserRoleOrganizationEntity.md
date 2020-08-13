---
title: SystemSecurityUserRoleOrganizationEntity in GAB - Common Data Model | Microsoft Docs
description: undefined
author: llawwaii
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 8/7/2020
ms.author: weiluo
---

# System security user role organization in GAB(SystemSecurityUserRoleOrganizationEntity)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/Common/GAB/SystemSecurityUserRoleOrganizationEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.1"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>System security user role organization</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[UserId](#UserId)||<a href="SystemSecurityUserRoleOrganizationEntity.md" target="_blank">GAB/SystemSecurityUserRoleOrganizationEntity</a>|
|[SecurityRoleIdentifier](#SecurityRoleIdentifier)||<a href="SystemSecurityUserRoleOrganizationEntity.md" target="_blank">GAB/SystemSecurityUserRoleOrganizationEntity</a>|
|[OrganizationType](#OrganizationType)||<a href="SystemSecurityUserRoleOrganizationEntity.md" target="_blank">GAB/SystemSecurityUserRoleOrganizationEntity</a>|
|[OrganizationId](#OrganizationId)||<a href="SystemSecurityUserRoleOrganizationEntity.md" target="_blank">GAB/SystemSecurityUserRoleOrganizationEntity</a>|
|[OperatingUnitType](#OperatingUnitType)||<a href="SystemSecurityUserRoleOrganizationEntity.md" target="_blank">GAB/SystemSecurityUserRoleOrganizationEntity</a>|
|[HierarchyType](#HierarchyType)||<a href="SystemSecurityUserRoleOrganizationEntity.md" target="_blank">GAB/SystemSecurityUserRoleOrganizationEntity</a>|
|[HierarchyTypeReference](#HierarchyTypeReference)||<a href="SystemSecurityUserRoleOrganizationEntity.md" target="_blank">GAB/SystemSecurityUserRoleOrganizationEntity</a>|
|[InternalOrganizationReference](#InternalOrganizationReference)||<a href="SystemSecurityUserRoleOrganizationEntity.md" target="_blank">GAB/SystemSecurityUserRoleOrganizationEntity</a>|
|[SecurityRoleReference](#SecurityRoleReference)||<a href="SystemSecurityUserRoleOrganizationEntity.md" target="_blank">GAB/SystemSecurityUserRoleOrganizationEntity</a>|
|[BackingTable_OMUserRoleOrganizationRelationshipId](#BackingTable_OMUserRoleOrganizationRelationshipId)||<a href="SystemSecurityUserRoleOrganizationEntity.md" target="_blank">GAB/SystemSecurityUserRoleOrganizationEntity</a>|

### <a href=#UserId name="UserId">UserId</a>

First included in: GAB/SystemSecurityUserRoleOrganizationEntity (this entity)  

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

### <a href=#SecurityRoleIdentifier name="SecurityRoleIdentifier">SecurityRoleIdentifier</a>

First included in: GAB/SystemSecurityUserRoleOrganizationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SecurityRoleIdentifier attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#OrganizationType name="OrganizationType">OrganizationType</a>

First included in: GAB/SystemSecurityUserRoleOrganizationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OrganizationType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#OrganizationId name="OrganizationId">OrganizationId</a>

First included in: GAB/SystemSecurityUserRoleOrganizationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OrganizationId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#OperatingUnitType name="OperatingUnitType">OperatingUnitType</a>

First included in: GAB/SystemSecurityUserRoleOrganizationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OperatingUnitType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#HierarchyType name="HierarchyType">HierarchyType</a>

First included in: GAB/SystemSecurityUserRoleOrganizationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the HierarchyType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#HierarchyTypeReference name="HierarchyTypeReference">HierarchyTypeReference</a>

First included in: GAB/SystemSecurityUserRoleOrganizationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the HierarchyTypeReference attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InternalOrganizationReference name="InternalOrganizationReference">InternalOrganizationReference</a>

First included in: GAB/SystemSecurityUserRoleOrganizationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InternalOrganizationReference attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SecurityRoleReference name="SecurityRoleReference">SecurityRoleReference</a>

First included in: GAB/SystemSecurityUserRoleOrganizationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SecurityRoleReference attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BackingTable_OMUserRoleOrganizationRelationshipId name="BackingTable_OMUserRoleOrganizationRelationshipId">BackingTable_OMUserRoleOrganizationRelationshipId</a>

First included in: GAB/SystemSecurityUserRoleOrganizationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_OMUserRoleOrganizationRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/Common/GAB/Main/OMUserRoleOrganization.md" target="_blank">/core/operationsCommon/Tables/Common/GAB/Main/OMUserRoleOrganization.cdm.json/OMUserRoleOrganization</a></td><td><a href="../../../Tables/Common/GAB/Main/OMUserRoleOrganization.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>
