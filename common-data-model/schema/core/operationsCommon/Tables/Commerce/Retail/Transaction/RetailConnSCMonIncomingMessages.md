---
title: RetailConnSCMonIncomingMessages - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/20/2020
ms.author: nebanfic
---

# RetailConnSCMonIncomingMessages

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Tables/Commerce/Retail/Transaction/RetailConnSCMonIncomingMessages.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[RetailConnSCMonIncomingMessages/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="RetailConnSCMonIncomingMessages.md" target="_blank">Transaction/RetailConnSCMonIncomingMessages</a>|
|[Action](#Action)||<a href="RetailConnSCMonIncomingMessages.md" target="_blank">Transaction/RetailConnSCMonIncomingMessages</a>|
|[BatchID](#BatchID)||<a href="RetailConnSCMonIncomingMessages.md" target="_blank">Transaction/RetailConnSCMonIncomingMessages</a>|
|[CancelledByUser](#CancelledByUser)||<a href="RetailConnSCMonIncomingMessages.md" target="_blank">Transaction/RetailConnSCMonIncomingMessages</a>|
|[ConnectString](#ConnectString)||<a href="RetailConnSCMonIncomingMessages.md" target="_blank">Transaction/RetailConnSCMonIncomingMessages</a>|
|[DataTarget](#DataTarget)||<a href="RetailConnSCMonIncomingMessages.md" target="_blank">Transaction/RetailConnSCMonIncomingMessages</a>|
|[ErrorNo](#ErrorNo)||<a href="RetailConnSCMonIncomingMessages.md" target="_blank">Transaction/RetailConnSCMonIncomingMessages</a>|
|[FinishedDateTime](#FinishedDateTime)||<a href="RetailConnSCMonIncomingMessages.md" target="_blank">Transaction/RetailConnSCMonIncomingMessages</a>|
|[HopCount](#HopCount)||<a href="RetailConnSCMonIncomingMessages.md" target="_blank">Transaction/RetailConnSCMonIncomingMessages</a>|
|[JobID](#JobID)||<a href="RetailConnSCMonIncomingMessages.md" target="_blank">Transaction/RetailConnSCMonIncomingMessages</a>|
|[MessageGUID](#MessageGUID)||<a href="RetailConnSCMonIncomingMessages.md" target="_blank">Transaction/RetailConnSCMonIncomingMessages</a>|
|[MessageId](#MessageId)||<a href="RetailConnSCMonIncomingMessages.md" target="_blank">Transaction/RetailConnSCMonIncomingMessages</a>|
|[NumRecs](#NumRecs)||<a href="RetailConnSCMonIncomingMessages.md" target="_blank">Transaction/RetailConnSCMonIncomingMessages</a>|
|[PackageNo](#PackageNo)||<a href="RetailConnSCMonIncomingMessages.md" target="_blank">Transaction/RetailConnSCMonIncomingMessages</a>|
|[PkgDeleted](#PkgDeleted)||<a href="RetailConnSCMonIncomingMessages.md" target="_blank">Transaction/RetailConnSCMonIncomingMessages</a>|
|[ProcessedFile](#ProcessedFile)||<a href="RetailConnSCMonIncomingMessages.md" target="_blank">Transaction/RetailConnSCMonIncomingMessages</a>|
|[ReceivedDateTime](#ReceivedDateTime)||<a href="RetailConnSCMonIncomingMessages.md" target="_blank">Transaction/RetailConnSCMonIncomingMessages</a>|
|[ReceivedFile](#ReceivedFile)||<a href="RetailConnSCMonIncomingMessages.md" target="_blank">Transaction/RetailConnSCMonIncomingMessages</a>|
|[RemotePkg](#RemotePkg)||<a href="RetailConnSCMonIncomingMessages.md" target="_blank">Transaction/RetailConnSCMonIncomingMessages</a>|
|[ServerMsg](#ServerMsg)||<a href="RetailConnSCMonIncomingMessages.md" target="_blank">Transaction/RetailConnSCMonIncomingMessages</a>|
|[ServiceName](#ServiceName)||<a href="RetailConnSCMonIncomingMessages.md" target="_blank">Transaction/RetailConnSCMonIncomingMessages</a>|
|[SourceServiceName](#SourceServiceName)||<a href="RetailConnSCMonIncomingMessages.md" target="_blank">Transaction/RetailConnSCMonIncomingMessages</a>|
|[Status](#Status)||<a href="RetailConnSCMonIncomingMessages.md" target="_blank">Transaction/RetailConnSCMonIncomingMessages</a>|
|[Trycount](#Trycount)||<a href="RetailConnSCMonIncomingMessages.md" target="_blank">Transaction/RetailConnSCMonIncomingMessages</a>|
|[Relationship_RetailConnSchedulerJobTableRelationshipId](#Relationship_RetailConnSchedulerJobTableRelationshipId)||<a href="RetailConnSCMonIncomingMessages.md" target="_blank">Transaction/RetailConnSCMonIncomingMessages</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: Transaction/RetailConnSCMonIncomingMessages (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[RetailConnSCMonIncomingMessages/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#Action name="Action">Action</a>

First included in: Transaction/RetailConnSCMonIncomingMessages (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Action attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#BatchID name="BatchID">BatchID</a>

First included in: Transaction/RetailConnSCMonIncomingMessages (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BatchID attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CancelledByUser name="CancelledByUser">CancelledByUser</a>

First included in: Transaction/RetailConnSCMonIncomingMessages (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CancelledByUser attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#ConnectString name="ConnectString">ConnectString</a>

First included in: Transaction/RetailConnSCMonIncomingMessages (this entity)  

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

First included in: Transaction/RetailConnSCMonIncomingMessages (this entity)  

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

### <a href=#ErrorNo name="ErrorNo">ErrorNo</a>

First included in: Transaction/RetailConnSCMonIncomingMessages (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ErrorNo attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#FinishedDateTime name="FinishedDateTime">FinishedDateTime</a>

First included in: Transaction/RetailConnSCMonIncomingMessages (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FinishedDateTime attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.dataFormat.date**  
</details>

### <a href=#HopCount name="HopCount">HopCount</a>

First included in: Transaction/RetailConnSCMonIncomingMessages (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the HopCount attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#JobID name="JobID">JobID</a>

First included in: Transaction/RetailConnSCMonIncomingMessages (this entity)  

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

First included in: Transaction/RetailConnSCMonIncomingMessages (this entity)  

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

### <a href=#MessageId name="MessageId">MessageId</a>

First included in: Transaction/RetailConnSCMonIncomingMessages (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MessageId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#NumRecs name="NumRecs">NumRecs</a>

First included in: Transaction/RetailConnSCMonIncomingMessages (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the NumRecs attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#PackageNo name="PackageNo">PackageNo</a>

First included in: Transaction/RetailConnSCMonIncomingMessages (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PackageNo attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#PkgDeleted name="PkgDeleted">PkgDeleted</a>

First included in: Transaction/RetailConnSCMonIncomingMessages (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PkgDeleted attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#ProcessedFile name="ProcessedFile">ProcessedFile</a>

First included in: Transaction/RetailConnSCMonIncomingMessages (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProcessedFile attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ReceivedDateTime name="ReceivedDateTime">ReceivedDateTime</a>

First included in: Transaction/RetailConnSCMonIncomingMessages (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReceivedDateTime attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.dataFormat.date**  
</details>

### <a href=#ReceivedFile name="ReceivedFile">ReceivedFile</a>

First included in: Transaction/RetailConnSCMonIncomingMessages (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReceivedFile attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RemotePkg name="RemotePkg">RemotePkg</a>

First included in: Transaction/RetailConnSCMonIncomingMessages (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RemotePkg attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#ServerMsg name="ServerMsg">ServerMsg</a>

First included in: Transaction/RetailConnSCMonIncomingMessages (this entity)  

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

First included in: Transaction/RetailConnSCMonIncomingMessages (this entity)  

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

### <a href=#SourceServiceName name="SourceServiceName">SourceServiceName</a>

First included in: Transaction/RetailConnSCMonIncomingMessages (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SourceServiceName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Status name="Status">Status</a>

First included in: Transaction/RetailConnSCMonIncomingMessages (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Status attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#Trycount name="Trycount">Trycount</a>

First included in: Transaction/RetailConnSCMonIncomingMessages (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Trycount attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#Relationship_RetailConnSchedulerJobTableRelationshipId name="Relationship_RetailConnSchedulerJobTableRelationshipId">Relationship_RetailConnSchedulerJobTableRelationshipId</a>

First included in: Transaction/RetailConnSCMonIncomingMessages (this entity)  

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
