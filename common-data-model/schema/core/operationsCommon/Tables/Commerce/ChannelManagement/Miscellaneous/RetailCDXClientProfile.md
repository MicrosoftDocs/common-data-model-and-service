---
title: RetailCDXClientProfile in Miscellaneous - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 7/20/2020
ms.author: nebanfic
---

# RetailCDXClientProfile in Miscellaneous

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Tables/Commerce/ChannelManagement/Miscellaneous/RetailCDXClientProfile.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[RetailCDXClientProfile/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>RetailCDXClientProfile</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="RetailCDXClientProfile.md" target="_blank">Miscellaneous/RetailCDXClientProfile</a>|
|[ChannelDBConnectionStringServerName](#ChannelDBConnectionStringServerName)||<a href="RetailCDXClientProfile.md" target="_blank">Miscellaneous/RetailCDXClientProfile</a>|
|[Description](#Description)||<a href="RetailCDXClientProfile.md" target="_blank">Miscellaneous/RetailCDXClientProfile</a>|
|[InstallFolder](#InstallFolder)||<a href="RetailCDXClientProfile.md" target="_blank">Miscellaneous/RetailCDXClientProfile</a>|
|[MessageDBComputer](#MessageDBComputer)||<a href="RetailCDXClientProfile.md" target="_blank">Miscellaneous/RetailCDXClientProfile</a>|
|[MessageDBInstanceName](#MessageDBInstanceName)||<a href="RetailCDXClientProfile.md" target="_blank">Miscellaneous/RetailCDXClientProfile</a>|
|[MessageDBName](#MessageDBName)||<a href="RetailCDXClientProfile.md" target="_blank">Miscellaneous/RetailCDXClientProfile</a>|
|[MsgDBConnectionStringServerName](#MsgDBConnectionStringServerName)||<a href="RetailCDXClientProfile.md" target="_blank">Miscellaneous/RetailCDXClientProfile</a>|
|[Name](#Name)||<a href="RetailCDXClientProfile.md" target="_blank">Miscellaneous/RetailCDXClientProfile</a>|
|[RetailCDXHeadOfficeProfile](#RetailCDXHeadOfficeProfile)||<a href="RetailCDXClientProfile.md" target="_blank">Miscellaneous/RetailCDXClientProfile</a>|
|[RetailChannelDatabaseProfiles](#RetailChannelDatabaseProfiles)||<a href="RetailCDXClientProfile.md" target="_blank">Miscellaneous/RetailCDXClientProfile</a>|
|[SyncInterval](#SyncInterval)||<a href="RetailCDXClientProfile.md" target="_blank">Miscellaneous/RetailCDXClientProfile</a>|
|[Relationship_RetailChannelDatabaseProfileRelationshipId](#Relationship_RetailChannelDatabaseProfileRelationshipId)||<a href="RetailCDXClientProfile.md" target="_blank">Miscellaneous/RetailCDXClientProfile</a>|
|[Relationship_RetailMachineRelationshipId](#Relationship_RetailMachineRelationshipId)||<a href="RetailCDXClientProfile.md" target="_blank">Miscellaneous/RetailCDXClientProfile</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: Miscellaneous/RetailCDXClientProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[RetailCDXClientProfile/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#ChannelDBConnectionStringServerName name="ChannelDBConnectionStringServerName">ChannelDBConnectionStringServerName</a>

First included in: Miscellaneous/RetailCDXClientProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ChannelDBConnectionStringServerName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Description name="Description">Description</a>

First included in: Miscellaneous/RetailCDXClientProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Description attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InstallFolder name="InstallFolder">InstallFolder</a>

First included in: Miscellaneous/RetailCDXClientProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InstallFolder attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MessageDBComputer name="MessageDBComputer">MessageDBComputer</a>

First included in: Miscellaneous/RetailCDXClientProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Computer name</td></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MessageDBComputer attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Computer name</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#MessageDBInstanceName name="MessageDBInstanceName">MessageDBInstanceName</a>

First included in: Miscellaneous/RetailCDXClientProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MessageDBInstanceName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MessageDBName name="MessageDBName">MessageDBName</a>

First included in: Miscellaneous/RetailCDXClientProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MessageDBName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MsgDBConnectionStringServerName name="MsgDBConnectionStringServerName">MsgDBConnectionStringServerName</a>

First included in: Miscellaneous/RetailCDXClientProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MsgDBConnectionStringServerName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Name name="Name">Name</a>

First included in: Miscellaneous/RetailCDXClientProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Name attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RetailCDXHeadOfficeProfile name="RetailCDXHeadOfficeProfile">RetailCDXHeadOfficeProfile</a>

First included in: Miscellaneous/RetailCDXClientProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RetailCDXHeadOfficeProfile attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#RetailChannelDatabaseProfiles name="RetailChannelDatabaseProfiles">RetailChannelDatabaseProfiles</a>

First included in: Miscellaneous/RetailCDXClientProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Channel database profile</td></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RetailChannelDatabaseProfiles attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Channel database profile</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#SyncInterval name="SyncInterval">SyncInterval</a>

First included in: Miscellaneous/RetailCDXClientProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SyncInterval attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#Relationship_RetailChannelDatabaseProfileRelationshipId name="Relationship_RetailChannelDatabaseProfileRelationshipId">Relationship_RetailChannelDatabaseProfileRelationshipId</a>

First included in: Miscellaneous/RetailCDXClientProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_RetailChannelDatabaseProfileRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="RetailChannelDatabaseProfiles.md" target="_blank">/core/operationsCommon/Tables/Commerce/ChannelManagement/Miscellaneous/RetailChannelDatabaseProfiles.cdm.json/RetailChannelDatabaseProfiles</a></td><td><a href="RetailChannelDatabaseProfiles.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_RetailMachineRelationshipId name="Relationship_RetailMachineRelationshipId">Relationship_RetailMachineRelationshipId</a>

First included in: Miscellaneous/RetailCDXClientProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_RetailMachineRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../BrickAndMortarStore/Miscellaneous/RetailMachine.md" target="_blank">/core/operationsCommon/Tables/Commerce/ChannelManagement/BrickAndMortarStore/Miscellaneous/RetailMachine.cdm.json/RetailMachine</a></td><td><a href="../BrickAndMortarStore/Miscellaneous/RetailMachine.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>
