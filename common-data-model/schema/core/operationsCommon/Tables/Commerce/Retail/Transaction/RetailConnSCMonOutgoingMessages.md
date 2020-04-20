---
title: RetailConnSCMonOutgoingMessages - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/20/2020
ms.author: nebanfic
---

# RetailConnSCMonOutgoingMessages

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Tables/Commerce/Retail/Transaction/RetailConnSCMonOutgoingMessages.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[RetailConnSCMonOutgoingMessages/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="RetailConnSCMonOutgoingMessages.md" target="_blank">Transaction/RetailConnSCMonOutgoingMessages</a>|
|[Action](#Action)||<a href="RetailConnSCMonOutgoingMessages.md" target="_blank">Transaction/RetailConnSCMonOutgoingMessages</a>|
|[CancelledByUser](#CancelledByUser)||<a href="RetailConnSCMonOutgoingMessages.md" target="_blank">Transaction/RetailConnSCMonOutgoingMessages</a>|
|[ConnectString](#ConnectString)||<a href="RetailConnSCMonOutgoingMessages.md" target="_blank">Transaction/RetailConnSCMonOutgoingMessages</a>|
|[DataTarget](#DataTarget)||<a href="RetailConnSCMonOutgoingMessages.md" target="_blank">Transaction/RetailConnSCMonOutgoingMessages</a>|
|[DestPort](#DestPort)||<a href="RetailConnSCMonOutgoingMessages.md" target="_blank">Transaction/RetailConnSCMonOutgoingMessages</a>|
|[DestServerName](#DestServerName)||<a href="RetailConnSCMonOutgoingMessages.md" target="_blank">Transaction/RetailConnSCMonOutgoingMessages</a>|
|[DestServiceName](#DestServiceName)||<a href="RetailConnSCMonOutgoingMessages.md" target="_blank">Transaction/RetailConnSCMonOutgoingMessages</a>|
|[ErrorNo](#ErrorNo)||<a href="RetailConnSCMonOutgoingMessages.md" target="_blank">Transaction/RetailConnSCMonOutgoingMessages</a>|
|[FinishedDateTime](#FinishedDateTime)||<a href="RetailConnSCMonOutgoingMessages.md" target="_blank">Transaction/RetailConnSCMonOutgoingMessages</a>|
|[Forwarder](#Forwarder)||<a href="RetailConnSCMonOutgoingMessages.md" target="_blank">Transaction/RetailConnSCMonOutgoingMessages</a>|
|[JobID](#JobID)||<a href="RetailConnSCMonOutgoingMessages.md" target="_blank">Transaction/RetailConnSCMonOutgoingMessages</a>|
|[MessageGUID](#MessageGUID)||<a href="RetailConnSCMonOutgoingMessages.md" target="_blank">Transaction/RetailConnSCMonOutgoingMessages</a>|
|[PackageNo](#PackageNo)||<a href="RetailConnSCMonOutgoingMessages.md" target="_blank">Transaction/RetailConnSCMonOutgoingMessages</a>|
|[RemotePkg](#RemotePkg)||<a href="RetailConnSCMonOutgoingMessages.md" target="_blank">Transaction/RetailConnSCMonOutgoingMessages</a>|
|[ServerMsg](#ServerMsg)||<a href="RetailConnSCMonOutgoingMessages.md" target="_blank">Transaction/RetailConnSCMonOutgoingMessages</a>|
|[ServiceName](#ServiceName)||<a href="RetailConnSCMonOutgoingMessages.md" target="_blank">Transaction/RetailConnSCMonOutgoingMessages</a>|
|[Status](#Status)||<a href="RetailConnSCMonOutgoingMessages.md" target="_blank">Transaction/RetailConnSCMonOutgoingMessages</a>|
|[Trycount](#Trycount)||<a href="RetailConnSCMonOutgoingMessages.md" target="_blank">Transaction/RetailConnSCMonOutgoingMessages</a>|
|[Relationship_RetailConnSchedulerJobTableRelationshipId](#Relationship_RetailConnSchedulerJobTableRelationshipId)||<a href="RetailConnSCMonOutgoingMessages.md" target="_blank">Transaction/RetailConnSCMonOutgoingMessages</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: Transaction/RetailConnSCMonOutgoingMessages (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[RetailConnSCMonOutgoingMessages/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#Action name="Action">Action</a>

First included in: Transaction/RetailConnSCMonOutgoingMessages (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Action attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#CancelledByUser name="CancelledByUser">CancelledByUser</a>

First included in: Transaction/RetailConnSCMonOutgoingMessages (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CancelledByUser attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#ConnectString name="ConnectString">ConnectString</a>

First included in: Transaction/RetailConnSCMonOutgoingMessages (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ConnectString attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DataTarget name="DataTarget">DataTarget</a>

First included in: Transaction/RetailConnSCMonOutgoingMessages (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DataTarget attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DestPort name="DestPort">DestPort</a>

First included in: Transaction/RetailConnSCMonOutgoingMessages (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DestPort attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#DestServerName name="DestServerName">DestServerName</a>

First included in: Transaction/RetailConnSCMonOutgoingMessages (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DestServerName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DestServiceName name="DestServiceName">DestServiceName</a>

First included in: Transaction/RetailConnSCMonOutgoingMessages (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DestServiceName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ErrorNo name="ErrorNo">ErrorNo</a>

First included in: Transaction/RetailConnSCMonOutgoingMessages (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ErrorNo attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#FinishedDateTime name="FinishedDateTime">FinishedDateTime</a>

First included in: Transaction/RetailConnSCMonOutgoingMessages (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FinishedDateTime attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.dataFormat.date**  
</details>

### <a href=#Forwarder name="Forwarder">Forwarder</a>

First included in: Transaction/RetailConnSCMonOutgoingMessages (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Forwarder attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#JobID name="JobID">JobID</a>

First included in: Transaction/RetailConnSCMonOutgoingMessages (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the JobID attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MessageGUID name="MessageGUID">MessageGUID</a>

First included in: Transaction/RetailConnSCMonOutgoingMessages (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MessageGUID attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PackageNo name="PackageNo">PackageNo</a>

First included in: Transaction/RetailConnSCMonOutgoingMessages (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PackageNo attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#RemotePkg name="RemotePkg">RemotePkg</a>

First included in: Transaction/RetailConnSCMonOutgoingMessages (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RemotePkg attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#ServerMsg name="ServerMsg">ServerMsg</a>

First included in: Transaction/RetailConnSCMonOutgoingMessages (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ServerMsg attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ServiceName name="ServiceName">ServiceName</a>

First included in: Transaction/RetailConnSCMonOutgoingMessages (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ServiceName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Status name="Status">Status</a>

First included in: Transaction/RetailConnSCMonOutgoingMessages (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Status attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#Trycount name="Trycount">Trycount</a>

First included in: Transaction/RetailConnSCMonOutgoingMessages (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Trycount attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#Relationship_RetailConnSchedulerJobTableRelationshipId name="Relationship_RetailConnSchedulerJobTableRelationshipId">Relationship_RetailConnSchedulerJobTableRelationshipId</a>

First included in: Transaction/RetailConnSCMonOutgoingMessages (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_RetailConnSchedulerJobTableRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Main/RetailConnSchedulerJobTable.md" target="_blank">/core/operationsCommon/Tables/Commerce/Retail/Main/RetailConnSchedulerJobTable.cdm.json/RetailConnSchedulerJobTable</a></td><td><a href="../Main/RetailConnSchedulerJobTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>
