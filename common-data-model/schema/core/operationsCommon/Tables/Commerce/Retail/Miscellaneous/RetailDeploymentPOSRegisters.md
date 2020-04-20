---
title: RetailDeploymentPOSRegisters - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/20/2020
ms.author: nebanfic
---

# RetailDeploymentPOSRegisters

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Tables/Commerce/Retail/Miscellaneous/RetailDeploymentPOSRegisters.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[RetailDeploymentPOSRegisters/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="RetailDeploymentPOSRegisters.md" target="_blank">Miscellaneous/RetailDeploymentPOSRegisters</a>|
|[ConnectionStringServerName](#ConnectionStringServerName)||<a href="RetailDeploymentPOSRegisters.md" target="_blank">Miscellaneous/RetailDeploymentPOSRegisters</a>|
|[Description](#Description)||<a href="RetailDeploymentPOSRegisters.md" target="_blank">Miscellaneous/RetailDeploymentPOSRegisters</a>|
|[Name](#Name)||<a href="RetailDeploymentPOSRegisters.md" target="_blank">Miscellaneous/RetailDeploymentPOSRegisters</a>|
|[offlineDbInstance](#offlineDbInstance)||<a href="RetailDeploymentPOSRegisters.md" target="_blank">Miscellaneous/RetailDeploymentPOSRegisters</a>|
|[offlineDbName](#offlineDbName)||<a href="RetailDeploymentPOSRegisters.md" target="_blank">Miscellaneous/RetailDeploymentPOSRegisters</a>|
|[RetailChannelDatabaseProfiles](#RetailChannelDatabaseProfiles)||<a href="RetailDeploymentPOSRegisters.md" target="_blank">Miscellaneous/RetailDeploymentPOSRegisters</a>|
|[RetailDeploymentRTSProfile](#RetailDeploymentRTSProfile)||<a href="RetailDeploymentPOSRegisters.md" target="_blank">Miscellaneous/RetailDeploymentPOSRegisters</a>|
|[RetailMachine](#RetailMachine)||<a href="RetailDeploymentPOSRegisters.md" target="_blank">Miscellaneous/RetailDeploymentPOSRegisters</a>|
|[RetailTerminalTable](#RetailTerminalTable)||<a href="RetailDeploymentPOSRegisters.md" target="_blank">Miscellaneous/RetailDeploymentPOSRegisters</a>|
|[PosUserCredentials](#PosUserCredentials)||<a href="RetailDeploymentPOSRegisters.md" target="_blank">Miscellaneous/RetailDeploymentPOSRegisters</a>|
|[Relationship_RetailChannelDatabaseProfilesRelationshipId](#Relationship_RetailChannelDatabaseProfilesRelationshipId)||<a href="RetailDeploymentPOSRegisters.md" target="_blank">Miscellaneous/RetailDeploymentPOSRegisters</a>|
|[Relationship_RetailDeploymentRTSProfileRelationshipId](#Relationship_RetailDeploymentRTSProfileRelationshipId)||<a href="RetailDeploymentPOSRegisters.md" target="_blank">Miscellaneous/RetailDeploymentPOSRegisters</a>|
|[Relationship_RetailMachineRelationshipId](#Relationship_RetailMachineRelationshipId)||<a href="RetailDeploymentPOSRegisters.md" target="_blank">Miscellaneous/RetailDeploymentPOSRegisters</a>|
|[Relationship_RetailTerminalTableRelationshipId](#Relationship_RetailTerminalTableRelationshipId)||<a href="RetailDeploymentPOSRegisters.md" target="_blank">Miscellaneous/RetailDeploymentPOSRegisters</a>|
|[Relationship_RetailDeploymentCredentialRelationshipId](#Relationship_RetailDeploymentCredentialRelationshipId)||<a href="RetailDeploymentPOSRegisters.md" target="_blank">Miscellaneous/RetailDeploymentPOSRegisters</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: Miscellaneous/RetailDeploymentPOSRegisters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[RetailDeploymentPOSRegisters/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#ConnectionStringServerName name="ConnectionStringServerName">ConnectionStringServerName</a>

First included in: Miscellaneous/RetailDeploymentPOSRegisters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ConnectionStringServerName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Description name="Description">Description</a>

First included in: Miscellaneous/RetailDeploymentPOSRegisters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Description attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Name name="Name">Name</a>

First included in: Miscellaneous/RetailDeploymentPOSRegisters (this entity)  

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

### <a href=#offlineDbInstance name="offlineDbInstance">offlineDbInstance</a>

First included in: Miscellaneous/RetailDeploymentPOSRegisters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the offlineDbInstance attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#offlineDbName name="offlineDbName">offlineDbName</a>

First included in: Miscellaneous/RetailDeploymentPOSRegisters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the offlineDbName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RetailChannelDatabaseProfiles name="RetailChannelDatabaseProfiles">RetailChannelDatabaseProfiles</a>

First included in: Miscellaneous/RetailDeploymentPOSRegisters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RetailChannelDatabaseProfiles attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#RetailDeploymentRTSProfile name="RetailDeploymentRTSProfile">RetailDeploymentRTSProfile</a>

First included in: Miscellaneous/RetailDeploymentPOSRegisters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RetailDeploymentRTSProfile attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#RetailMachine name="RetailMachine">RetailMachine</a>

First included in: Miscellaneous/RetailDeploymentPOSRegisters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RetailMachine attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#RetailTerminalTable name="RetailTerminalTable">RetailTerminalTable</a>

First included in: Miscellaneous/RetailDeploymentPOSRegisters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RetailTerminalTable attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PosUserCredentials name="PosUserCredentials">PosUserCredentials</a>

First included in: Miscellaneous/RetailDeploymentPOSRegisters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PosUserCredentials attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#Relationship_RetailChannelDatabaseProfilesRelationshipId name="Relationship_RetailChannelDatabaseProfilesRelationshipId">Relationship_RetailChannelDatabaseProfilesRelationshipId</a>

First included in: Miscellaneous/RetailDeploymentPOSRegisters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_RetailChannelDatabaseProfilesRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="RetailChannelDatabaseProfiles.md" target="_blank">/core/operationsCommon/Tables/Commerce/Retail/Miscellaneous/RetailChannelDatabaseProfiles.cdm.json/RetailChannelDatabaseProfiles</a></td><td><a href="RetailChannelDatabaseProfiles.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_RetailDeploymentRTSProfileRelationshipId name="Relationship_RetailDeploymentRTSProfileRelationshipId">Relationship_RetailDeploymentRTSProfileRelationshipId</a>

First included in: Miscellaneous/RetailDeploymentPOSRegisters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_RetailDeploymentRTSProfileRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="RetailDeploymentRTSProfile.md" target="_blank">/core/operationsCommon/Tables/Commerce/Retail/Miscellaneous/RetailDeploymentRTSProfile.cdm.json/RetailDeploymentRTSProfile</a></td><td><a href="RetailDeploymentRTSProfile.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_RetailMachineRelationshipId name="Relationship_RetailMachineRelationshipId">Relationship_RetailMachineRelationshipId</a>

First included in: Miscellaneous/RetailDeploymentPOSRegisters (this entity)  

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
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="RetailMachine.md" target="_blank">/core/operationsCommon/Tables/Commerce/Retail/Miscellaneous/RetailMachine.cdm.json/RetailMachine</a></td><td><a href="RetailMachine.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_RetailTerminalTableRelationshipId name="Relationship_RetailTerminalTableRelationshipId">Relationship_RetailTerminalTableRelationshipId</a>

First included in: Miscellaneous/RetailDeploymentPOSRegisters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_RetailTerminalTableRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Main/RetailTerminalTable.md" target="_blank">/core/operationsCommon/Tables/Commerce/Retail/Main/RetailTerminalTable.cdm.json/RetailTerminalTable</a></td><td><a href="../Main/RetailTerminalTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_RetailDeploymentCredentialRelationshipId name="Relationship_RetailDeploymentCredentialRelationshipId">Relationship_RetailDeploymentCredentialRelationshipId</a>

First included in: Miscellaneous/RetailDeploymentPOSRegisters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_RetailDeploymentCredentialRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="RetailDeploymentCredentials.md" target="_blank">/core/operationsCommon/Tables/Commerce/Retail/Miscellaneous/RetailDeploymentCredentials.cdm.json/RetailDeploymentCredentials</a></td><td><a href="RetailDeploymentCredentials.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>
