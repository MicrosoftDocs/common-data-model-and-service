---
title: RetailLoyaltySchemeChannelEntity in CommerceCustomers - Common Data Model | Microsoft Docs
description: undefined
author: llawwaii

ms.reviewer: deonhe
ms.topic: reference
ms.date: 8/7/2020
ms.author: weiluo
---

# Loyalty scheme channels in CommerceCustomers(RetailLoyaltySchemeChannelEntity)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/Commerce/CommerceCustomers/RetailLoyaltySchemeChannelEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Loyalty scheme channels</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[LoyaltyScheme](#LoyaltyScheme)||<a href="RetailLoyaltySchemeChannelEntity.md" target="_blank">CommerceCustomers/RetailLoyaltySchemeChannelEntity</a>|
|[OMHierarchyType](#OMHierarchyType)||<a href="RetailLoyaltySchemeChannelEntity.md" target="_blank">CommerceCustomers/RetailLoyaltySchemeChannelEntity</a>|
|[OMInternalOrganization](#OMInternalOrganization)||<a href="RetailLoyaltySchemeChannelEntity.md" target="_blank">CommerceCustomers/RetailLoyaltySchemeChannelEntity</a>|
|[OMHierarchyTypeName](#OMHierarchyTypeName)||<a href="RetailLoyaltySchemeChannelEntity.md" target="_blank">CommerceCustomers/RetailLoyaltySchemeChannelEntity</a>|
|[OrganizationPartyNumber](#OrganizationPartyNumber)||<a href="RetailLoyaltySchemeChannelEntity.md" target="_blank">CommerceCustomers/RetailLoyaltySchemeChannelEntity</a>|
|[LoyaltySchemeId](#LoyaltySchemeId)||<a href="RetailLoyaltySchemeChannelEntity.md" target="_blank">CommerceCustomers/RetailLoyaltySchemeChannelEntity</a>|
|[BackingTable_RetailLoyaltySchemeChannelRelationshipId](#BackingTable_RetailLoyaltySchemeChannelRelationshipId)||<a href="RetailLoyaltySchemeChannelEntity.md" target="_blank">CommerceCustomers/RetailLoyaltySchemeChannelEntity</a>|

### <a href=#LoyaltyScheme name="LoyaltyScheme">LoyaltyScheme</a>

First included in: CommerceCustomers/RetailLoyaltySchemeChannelEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LoyaltyScheme attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#OMHierarchyType name="OMHierarchyType">OMHierarchyType</a>

First included in: CommerceCustomers/RetailLoyaltySchemeChannelEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OMHierarchyType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#OMInternalOrganization name="OMInternalOrganization">OMInternalOrganization</a>

First included in: CommerceCustomers/RetailLoyaltySchemeChannelEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OMInternalOrganization attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#OMHierarchyTypeName name="OMHierarchyTypeName">OMHierarchyTypeName</a>

First included in: CommerceCustomers/RetailLoyaltySchemeChannelEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OMHierarchyTypeName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#OrganizationPartyNumber name="OrganizationPartyNumber">OrganizationPartyNumber</a>

First included in: CommerceCustomers/RetailLoyaltySchemeChannelEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OrganizationPartyNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LoyaltySchemeId name="LoyaltySchemeId">LoyaltySchemeId</a>

First included in: CommerceCustomers/RetailLoyaltySchemeChannelEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LoyaltySchemeId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BackingTable_RetailLoyaltySchemeChannelRelationshipId name="BackingTable_RetailLoyaltySchemeChannelRelationshipId">BackingTable_RetailLoyaltySchemeChannelRelationshipId</a>

First included in: CommerceCustomers/RetailLoyaltySchemeChannelEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_RetailLoyaltySchemeChannelRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/Commerce/CommerceCustomers/Miscellaneous/RetailLoyaltySchemeChannel.md" target="_blank">/core/operationsCommon/Tables/Commerce/CommerceCustomers/Miscellaneous/RetailLoyaltySchemeChannel.cdm.json/RetailLoyaltySchemeChannel</a></td><td><a href="../../../Tables/Commerce/CommerceCustomers/Miscellaneous/RetailLoyaltySchemeChannel.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>
