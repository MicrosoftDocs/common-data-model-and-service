---
title: SysTaskRecorderNodeFormUserAction - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/21/2020
ms.author: nebanfic
---

# SysTaskRecorderNodeFormUserAction

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Tables/System/SystemAdministration/Miscellaneous/SysTaskRecorderNodeFormUserAction.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[SysTaskRecorderNodeFormUserAction/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="SysTaskRecorderNodeFormUserAction.md" target="_blank">Miscellaneous/SysTaskRecorderNodeFormUserAction</a>|
|[InstanceRelationType](#InstanceRelationType)||<a href="SysTaskRecorderNodeFormUserAction.md" target="_blank">Miscellaneous/SysTaskRecorderNodeFormUserAction</a>|
|[Sequence](#Sequence)||<a href="SysTaskRecorderNodeFormUserAction.md" target="_blank">Miscellaneous/SysTaskRecorderNodeFormUserAction</a>|
|[Recording](#Recording)||<a href="SysTaskRecorderNodeFormUserAction.md" target="_blank">Miscellaneous/SysTaskRecorderNodeFormUserAction</a>|
|[Id](#Id)||<a href="SysTaskRecorderNodeFormUserAction.md" target="_blank">Miscellaneous/SysTaskRecorderNodeFormUserAction</a>|
|[ParentSequence](#ParentSequence)||<a href="SysTaskRecorderNodeFormUserAction.md" target="_blank">Miscellaneous/SysTaskRecorderNodeFormUserAction</a>|
|[Description](#Description)||<a href="SysTaskRecorderNodeFormUserAction.md" target="_blank">Miscellaneous/SysTaskRecorderNodeFormUserAction</a>|
|[ScreenshotUri](#ScreenshotUri)||<a href="SysTaskRecorderNodeFormUserAction.md" target="_blank">Miscellaneous/SysTaskRecorderNodeFormUserAction</a>|
|[Annotations](#Annotations)||<a href="SysTaskRecorderNodeFormUserAction.md" target="_blank">Miscellaneous/SysTaskRecorderNodeFormUserAction</a>|
|[Relationship_RecordingRelationRelationshipId](#Relationship_RecordingRelationRelationshipId)||<a href="SysTaskRecorderNodeFormUserAction.md" target="_blank">Miscellaneous/SysTaskRecorderNodeFormUserAction</a>|
|[SystemGenerated](#SystemGenerated)||<a href="SysTaskRecorderNodeFormUserAction.md" target="_blank">Miscellaneous/SysTaskRecorderNodeFormUserAction</a>|
|[Deleted](#Deleted)||<a href="SysTaskRecorderNodeFormUserAction.md" target="_blank">Miscellaneous/SysTaskRecorderNodeFormUserAction</a>|
|[FormContextId](#FormContextId)||<a href="SysTaskRecorderNodeFormUserAction.md" target="_blank">Miscellaneous/SysTaskRecorderNodeFormUserAction</a>|
|[ControlLabel](#ControlLabel)||<a href="SysTaskRecorderNodeFormUserAction.md" target="_blank">Miscellaneous/SysTaskRecorderNodeFormUserAction</a>|
|[ControlLabelId](#ControlLabelId)||<a href="SysTaskRecorderNodeFormUserAction.md" target="_blank">Miscellaneous/SysTaskRecorderNodeFormUserAction</a>|
|[Relationship_FormContextRelationshipId](#Relationship_FormContextRelationshipId)||<a href="SysTaskRecorderNodeFormUserAction.md" target="_blank">Miscellaneous/SysTaskRecorderNodeFormUserAction</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: Miscellaneous/SysTaskRecorderNodeFormUserAction (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[SysTaskRecorderNodeFormUserAction/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#InstanceRelationType name="InstanceRelationType">InstanceRelationType</a>

First included in: Miscellaneous/SysTaskRecorderNodeFormUserAction (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InstanceRelationType attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#Sequence name="Sequence">Sequence</a>

First included in: Miscellaneous/SysTaskRecorderNodeFormUserAction (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Sequence attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#Recording name="Recording">Recording</a>

First included in: Miscellaneous/SysTaskRecorderNodeFormUserAction (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Recording attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#Id name="Id">Id</a>

First included in: Miscellaneous/SysTaskRecorderNodeFormUserAction (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>unknown</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Id attribute are listed below.</summary>

</details>

### <a href=#ParentSequence name="ParentSequence">ParentSequence</a>

First included in: Miscellaneous/SysTaskRecorderNodeFormUserAction (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ParentSequence attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#Description name="Description">Description</a>

First included in: Miscellaneous/SysTaskRecorderNodeFormUserAction (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>unknown</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Description attribute are listed below.</summary>

</details>

### <a href=#ScreenshotUri name="ScreenshotUri">ScreenshotUri</a>

First included in: Miscellaneous/SysTaskRecorderNodeFormUserAction (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>unknown</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ScreenshotUri attribute are listed below.</summary>

</details>

### <a href=#Annotations name="Annotations">Annotations</a>

First included in: Miscellaneous/SysTaskRecorderNodeFormUserAction (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Annotations attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_RecordingRelationRelationshipId name="Relationship_RecordingRelationRelationshipId">Relationship_RecordingRelationRelationshipId</a>

First included in: Miscellaneous/SysTaskRecorderNodeFormUserAction (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_RecordingRelationRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="SysTaskRecorderRecording.md" target="_blank">/core/operationsCommon/Tables/System/SystemAdministration/Miscellaneous/SysTaskRecorderRecording.cdm.json/SysTaskRecorderRecording</a></td><td><a href="SysTaskRecorderRecording.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SystemGenerated name="SystemGenerated">SystemGenerated</a>

First included in: Miscellaneous/SysTaskRecorderNodeFormUserAction (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SystemGenerated attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#Deleted name="Deleted">Deleted</a>

First included in: Miscellaneous/SysTaskRecorderNodeFormUserAction (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Deleted attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#FormContextId name="FormContextId">FormContextId</a>

First included in: Miscellaneous/SysTaskRecorderNodeFormUserAction (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FormContextId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ControlLabel name="ControlLabel">ControlLabel</a>

First included in: Miscellaneous/SysTaskRecorderNodeFormUserAction (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ControlLabel attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ControlLabelId name="ControlLabelId">ControlLabelId</a>

First included in: Miscellaneous/SysTaskRecorderNodeFormUserAction (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ControlLabelId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_FormContextRelationshipId name="Relationship_FormContextRelationshipId">Relationship_FormContextRelationshipId</a>

First included in: Miscellaneous/SysTaskRecorderNodeFormUserAction (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_FormContextRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="SysTaskRecorderFormContext.md" target="_blank">/core/operationsCommon/Tables/System/SystemAdministration/Miscellaneous/SysTaskRecorderFormContext.cdm.json/SysTaskRecorderFormContext</a></td><td><a href="SysTaskRecorderFormContext.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>
