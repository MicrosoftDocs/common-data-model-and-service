---
title: RetailDeploymentCDXSyncServiceProfiles - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/20/2020
ms.author: nebanfic
---

# RetailDeploymentCDXSyncServiceProfiles

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Tables/Commerce/Retail/Miscellaneous/RetailDeploymentCDXSyncServiceProfiles.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[RetailDeploymentCDXSyncServiceProfiles/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="RetailDeploymentCDXSyncServiceProfiles.md" target="_blank">Miscellaneous/RetailDeploymentCDXSyncServiceProfiles</a>|
|[Description](#Description)||<a href="RetailDeploymentCDXSyncServiceProfiles.md" target="_blank">Miscellaneous/RetailDeploymentCDXSyncServiceProfiles</a>|
|[MsgDatabaseComputer](#MsgDatabaseComputer)||<a href="RetailDeploymentCDXSyncServiceProfiles.md" target="_blank">Miscellaneous/RetailDeploymentCDXSyncServiceProfiles</a>|
|[MsgDatabaseInstance](#MsgDatabaseInstance)||<a href="RetailDeploymentCDXSyncServiceProfiles.md" target="_blank">Miscellaneous/RetailDeploymentCDXSyncServiceProfiles</a>|
|[MsgDatabaseName](#MsgDatabaseName)||<a href="RetailDeploymentCDXSyncServiceProfiles.md" target="_blank">Miscellaneous/RetailDeploymentCDXSyncServiceProfiles</a>|
|[Name](#Name)||<a href="RetailDeploymentCDXSyncServiceProfiles.md" target="_blank">Miscellaneous/RetailDeploymentCDXSyncServiceProfiles</a>|
|[NoIPSec](#NoIPSec)||<a href="RetailDeploymentCDXSyncServiceProfiles.md" target="_blank">Miscellaneous/RetailDeploymentCDXSyncServiceProfiles</a>|
|[Port](#Port)||<a href="RetailDeploymentCDXSyncServiceProfiles.md" target="_blank">Miscellaneous/RetailDeploymentCDXSyncServiceProfiles</a>|
|[PreferIPV6](#PreferIPV6)||<a href="RetailDeploymentCDXSyncServiceProfiles.md" target="_blank">Miscellaneous/RetailDeploymentCDXSyncServiceProfiles</a>|
|[RetailDeploymentBusinessConnectorProfile](#RetailDeploymentBusinessConnectorProfile)||<a href="RetailDeploymentCDXSyncServiceProfiles.md" target="_blank">Miscellaneous/RetailDeploymentCDXSyncServiceProfiles</a>|
|[RetailMachine_Server](#RetailMachine_Server)||<a href="RetailDeploymentCDXSyncServiceProfiles.md" target="_blank">Miscellaneous/RetailDeploymentCDXSyncServiceProfiles</a>|
|[Timeout](#Timeout)||<a href="RetailDeploymentCDXSyncServiceProfiles.md" target="_blank">Miscellaneous/RetailDeploymentCDXSyncServiceProfiles</a>|
|[Relationship_RetailDeploymentBusinessConnectorProfileRelationshipId](#Relationship_RetailDeploymentBusinessConnectorProfileRelationshipId)||<a href="RetailDeploymentCDXSyncServiceProfiles.md" target="_blank">Miscellaneous/RetailDeploymentCDXSyncServiceProfiles</a>|
|[Relationship_RetailMachine_MsgComputerRelationshipId](#Relationship_RetailMachine_MsgComputerRelationshipId)||<a href="RetailDeploymentCDXSyncServiceProfiles.md" target="_blank">Miscellaneous/RetailDeploymentCDXSyncServiceProfiles</a>|
|[Relationship_RetailMachine_ServerRelationshipId](#Relationship_RetailMachine_ServerRelationshipId)||<a href="RetailDeploymentCDXSyncServiceProfiles.md" target="_blank">Miscellaneous/RetailDeploymentCDXSyncServiceProfiles</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: Miscellaneous/RetailDeploymentCDXSyncServiceProfiles (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[RetailDeploymentCDXSyncServiceProfiles/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#Description name="Description">Description</a>

First included in: Miscellaneous/RetailDeploymentCDXSyncServiceProfiles (this entity)  

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

### <a href=#MsgDatabaseComputer name="MsgDatabaseComputer">MsgDatabaseComputer</a>

First included in: Miscellaneous/RetailDeploymentCDXSyncServiceProfiles (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MsgDatabaseComputer attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#MsgDatabaseInstance name="MsgDatabaseInstance">MsgDatabaseInstance</a>

First included in: Miscellaneous/RetailDeploymentCDXSyncServiceProfiles (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MsgDatabaseInstance attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MsgDatabaseName name="MsgDatabaseName">MsgDatabaseName</a>

First included in: Miscellaneous/RetailDeploymentCDXSyncServiceProfiles (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MsgDatabaseName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Name name="Name">Name</a>

First included in: Miscellaneous/RetailDeploymentCDXSyncServiceProfiles (this entity)  

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

### <a href=#NoIPSec name="NoIPSec">NoIPSec</a>

First included in: Miscellaneous/RetailDeploymentCDXSyncServiceProfiles (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the NoIPSec attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#Port name="Port">Port</a>

First included in: Miscellaneous/RetailDeploymentCDXSyncServiceProfiles (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Port attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#PreferIPV6 name="PreferIPV6">PreferIPV6</a>

First included in: Miscellaneous/RetailDeploymentCDXSyncServiceProfiles (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PreferIPV6 attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#RetailDeploymentBusinessConnectorProfile name="RetailDeploymentBusinessConnectorProfile">RetailDeploymentBusinessConnectorProfile</a>

First included in: Miscellaneous/RetailDeploymentCDXSyncServiceProfiles (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RetailDeploymentBusinessConnectorProfile attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#RetailMachine_Server name="RetailMachine_Server">RetailMachine_Server</a>

First included in: Miscellaneous/RetailDeploymentCDXSyncServiceProfiles (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RetailMachine_Server attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#Timeout name="Timeout">Timeout</a>

First included in: Miscellaneous/RetailDeploymentCDXSyncServiceProfiles (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Timeout attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#Relationship_RetailDeploymentBusinessConnectorProfileRelationshipId name="Relationship_RetailDeploymentBusinessConnectorProfileRelationshipId">Relationship_RetailDeploymentBusinessConnectorProfileRelationshipId</a>

First included in: Miscellaneous/RetailDeploymentCDXSyncServiceProfiles (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_RetailDeploymentBusinessConnectorProfileRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="RetailDeploymentBusinessConnectorProfile.md" target="_blank">/core/operationsCommon/Tables/Commerce/Retail/Miscellaneous/RetailDeploymentBusinessConnectorProfile.cdm.json/RetailDeploymentBusinessConnectorProfile</a></td><td><a href="RetailDeploymentBusinessConnectorProfile.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_RetailMachine_MsgComputerRelationshipId name="Relationship_RetailMachine_MsgComputerRelationshipId">Relationship_RetailMachine_MsgComputerRelationshipId</a>

First included in: Miscellaneous/RetailDeploymentCDXSyncServiceProfiles (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_RetailMachine_MsgComputerRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_RetailMachine_ServerRelationshipId name="Relationship_RetailMachine_ServerRelationshipId">Relationship_RetailMachine_ServerRelationshipId</a>

First included in: Miscellaneous/RetailDeploymentCDXSyncServiceProfiles (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_RetailMachine_ServerRelationshipId attribute are listed below.</summary>

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
