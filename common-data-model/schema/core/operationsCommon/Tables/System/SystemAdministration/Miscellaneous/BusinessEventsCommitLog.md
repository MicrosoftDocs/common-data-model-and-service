---
title: BusinessEventsCommitLog - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/29/2020
ms.author: nebanfic
---

# BusinessEventsCommitLog

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Tables/System/SystemAdministration/Miscellaneous/BusinessEventsCommitLog.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[BusinessEventsCommitLog/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="BusinessEventsCommitLog.md" target="_blank">Miscellaneous/BusinessEventsCommitLog</a>|
|[BusinessEventId](#BusinessEventId)||<a href="BusinessEventsCommitLog.md" target="_blank">Miscellaneous/BusinessEventsCommitLog</a>|
|[EventId](#EventId)||<a href="BusinessEventsCommitLog.md" target="_blank">Miscellaneous/BusinessEventsCommitLog</a>|
|[EventTime](#EventTime)||<a href="BusinessEventsCommitLog.md" target="_blank">Miscellaneous/BusinessEventsCommitLog</a>|
|[SessionId](#SessionId)||<a href="BusinessEventsCommitLog.md" target="_blank">Miscellaneous/BusinessEventsCommitLog</a>|
|[SerializedContract](#SerializedContract)||<a href="BusinessEventsCommitLog.md" target="_blank">Miscellaneous/BusinessEventsCommitLog</a>|
|[LegalEntity](#LegalEntity)||<a href="BusinessEventsCommitLog.md" target="_blank">Miscellaneous/BusinessEventsCommitLog</a>|
|[State](#State)||<a href="BusinessEventsCommitLog.md" target="_blank">Miscellaneous/BusinessEventsCommitLog</a>|
|[TaskNumber](#TaskNumber)||<a href="BusinessEventsCommitLog.md" target="_blank">Miscellaneous/BusinessEventsCommitLog</a>|
|[TargetEndpoint](#TargetEndpoint)||<a href="BusinessEventsCommitLog.md" target="_blank">Miscellaneous/BusinessEventsCommitLog</a>|
|[SerializedFilterProperties](#SerializedFilterProperties)||<a href="BusinessEventsCommitLog.md" target="_blank">Miscellaneous/BusinessEventsCommitLog</a>|
|[Relationship_BusinessEventsEndpointRelationshipId](#Relationship_BusinessEventsEndpointRelationshipId)||<a href="BusinessEventsCommitLog.md" target="_blank">Miscellaneous/BusinessEventsCommitLog</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: Miscellaneous/BusinessEventsCommitLog (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[BusinessEventsCommitLog/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#BusinessEventId name="BusinessEventId">BusinessEventId</a>

First included in: Miscellaneous/BusinessEventsCommitLog (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BusinessEventId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#EventId name="EventId">EventId</a>

First included in: Miscellaneous/BusinessEventsCommitLog (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EventId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#EventTime name="EventTime">EventTime</a>

First included in: Miscellaneous/BusinessEventsCommitLog (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EventTime attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.dataFormat.date**  
</details>

### <a href=#SessionId name="SessionId">SessionId</a>

First included in: Miscellaneous/BusinessEventsCommitLog (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SessionId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SerializedContract name="SerializedContract">SerializedContract</a>

First included in: Miscellaneous/BusinessEventsCommitLog (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SerializedContract attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LegalEntity name="LegalEntity">LegalEntity</a>

First included in: Miscellaneous/BusinessEventsCommitLog (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LegalEntity attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#State name="State">State</a>

First included in: Miscellaneous/BusinessEventsCommitLog (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the State attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#TaskNumber name="TaskNumber">TaskNumber</a>

First included in: Miscellaneous/BusinessEventsCommitLog (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaskNumber attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#TargetEndpoint name="TargetEndpoint">TargetEndpoint</a>

First included in: Miscellaneous/BusinessEventsCommitLog (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TargetEndpoint attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#SerializedFilterProperties name="SerializedFilterProperties">SerializedFilterProperties</a>

First included in: Miscellaneous/BusinessEventsCommitLog (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SerializedFilterProperties attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_BusinessEventsEndpointRelationshipId name="Relationship_BusinessEventsEndpointRelationshipId">Relationship_BusinessEventsEndpointRelationshipId</a>

First included in: Miscellaneous/BusinessEventsCommitLog (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_BusinessEventsEndpointRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="BusinessEventsEndpoint.md" target="_blank">/core/operationsCommon/Tables/System/SystemAdministration/Miscellaneous/BusinessEventsEndpoint.cdm.json/BusinessEventsEndpoint</a></td><td><a href="BusinessEventsEndpoint.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>
