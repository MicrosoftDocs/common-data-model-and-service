---
title: SysTaskRecorderNodeFormUserActionInputOutput in Miscellaneous - Common Data Model | Microsoft Docs
description: undefined
author: llawwaii
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 8/5/2020
ms.author: weiluo
---

# Form user action in Miscellaneous(SysTaskRecorderNodeFormUserActionInputOutput)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Tables/System/SystemAdministration/Miscellaneous/SysTaskRecorderNodeFormUserActionInputOutput.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[SysTaskRecorderNodeFormUserActionInputOutput/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.1"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Task recording node</td></tr><tr><td>en</td><td>User action</td></tr><tr><td>en</td><td>Form user action</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="SysTaskRecorderNodeFormUserActionInputOutput.md" target="_blank">Miscellaneous/SysTaskRecorderNodeFormUserActionInputOutput</a>|
|[InstanceRelationType](#InstanceRelationType)||<a href="SysTaskRecorderNodeFormUserActionInputOutput.md" target="_blank">Miscellaneous/SysTaskRecorderNodeFormUserActionInputOutput</a>|
|[Sequence](#Sequence)||<a href="SysTaskRecorderNodeFormUserActionInputOutput.md" target="_blank">Miscellaneous/SysTaskRecorderNodeFormUserActionInputOutput</a>|
|[Recording](#Recording)||<a href="SysTaskRecorderNodeFormUserActionInputOutput.md" target="_blank">Miscellaneous/SysTaskRecorderNodeFormUserActionInputOutput</a>|
|[Id](#Id)||<a href="SysTaskRecorderNodeFormUserActionInputOutput.md" target="_blank">Miscellaneous/SysTaskRecorderNodeFormUserActionInputOutput</a>|
|[ParentSequence](#ParentSequence)||<a href="SysTaskRecorderNodeFormUserActionInputOutput.md" target="_blank">Miscellaneous/SysTaskRecorderNodeFormUserActionInputOutput</a>|
|[Description](#Description)||<a href="SysTaskRecorderNodeFormUserActionInputOutput.md" target="_blank">Miscellaneous/SysTaskRecorderNodeFormUserActionInputOutput</a>|
|[ScreenshotUri](#ScreenshotUri)||<a href="SysTaskRecorderNodeFormUserActionInputOutput.md" target="_blank">Miscellaneous/SysTaskRecorderNodeFormUserActionInputOutput</a>|
|[Annotations](#Annotations)||<a href="SysTaskRecorderNodeFormUserActionInputOutput.md" target="_blank">Miscellaneous/SysTaskRecorderNodeFormUserActionInputOutput</a>|
|[Relationship_RecordingRelationRelationshipId](#Relationship_RecordingRelationRelationshipId)||<a href="SysTaskRecorderNodeFormUserActionInputOutput.md" target="_blank">Miscellaneous/SysTaskRecorderNodeFormUserActionInputOutput</a>|
|[SystemGenerated](#SystemGenerated)||<a href="SysTaskRecorderNodeFormUserActionInputOutput.md" target="_blank">Miscellaneous/SysTaskRecorderNodeFormUserActionInputOutput</a>|
|[Deleted](#Deleted)||<a href="SysTaskRecorderNodeFormUserActionInputOutput.md" target="_blank">Miscellaneous/SysTaskRecorderNodeFormUserActionInputOutput</a>|
|[FormContextId](#FormContextId)||<a href="SysTaskRecorderNodeFormUserActionInputOutput.md" target="_blank">Miscellaneous/SysTaskRecorderNodeFormUserActionInputOutput</a>|
|[ControlLabel](#ControlLabel)||<a href="SysTaskRecorderNodeFormUserActionInputOutput.md" target="_blank">Miscellaneous/SysTaskRecorderNodeFormUserActionInputOutput</a>|
|[ControlLabelId](#ControlLabelId)||<a href="SysTaskRecorderNodeFormUserActionInputOutput.md" target="_blank">Miscellaneous/SysTaskRecorderNodeFormUserActionInputOutput</a>|
|[Relationship_FormContextRelationshipId](#Relationship_FormContextRelationshipId)||<a href="SysTaskRecorderNodeFormUserActionInputOutput.md" target="_blank">Miscellaneous/SysTaskRecorderNodeFormUserActionInputOutput</a>|
|[ControlName](#ControlName)||<a href="SysTaskRecorderNodeFormUserActionInputOutput.md" target="_blank">Miscellaneous/SysTaskRecorderNodeFormUserActionInputOutput</a>|
|[ControlType](#ControlType)||<a href="SysTaskRecorderNodeFormUserActionInputOutput.md" target="_blank">Miscellaneous/SysTaskRecorderNodeFormUserActionInputOutput</a>|
|[LabelId](#LabelId)||<a href="SysTaskRecorderNodeFormUserActionInputOutput.md" target="_blank">Miscellaneous/SysTaskRecorderNodeFormUserActionInputOutput</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: Miscellaneous/SysTaskRecorderNodeFormUserActionInputOutput (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[SysTaskRecorderNodeFormUserActionInputOutput/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#InstanceRelationType name="InstanceRelationType">InstanceRelationType</a>

First included in: Miscellaneous/SysTaskRecorderNodeFormUserActionInputOutput (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InstanceRelationType attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#Sequence name="Sequence">Sequence</a>

First included in: Miscellaneous/SysTaskRecorderNodeFormUserActionInputOutput (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Sequence attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#Recording name="Recording">Recording</a>

First included in: Miscellaneous/SysTaskRecorderNodeFormUserActionInputOutput (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Task recording ID</td></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Recording attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Task recording ID</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#Id name="Id">Id</a>

First included in: Miscellaneous/SysTaskRecorderNodeFormUserActionInputOutput (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Node ID</td></tr><tr><td>dataFormat</td><td>unknown</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Id attribute are listed below.</summary>

**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Node ID</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

### <a href=#ParentSequence name="ParentSequence">ParentSequence</a>

First included in: Miscellaneous/SysTaskRecorderNodeFormUserActionInputOutput (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Sequence number</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ParentSequence attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Sequence number</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#Description name="Description">Description</a>

First included in: Miscellaneous/SysTaskRecorderNodeFormUserActionInputOutput (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Description</td></tr><tr><td>dataFormat</td><td>unknown</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Description attribute are listed below.</summary>

**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Description</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

### <a href=#ScreenshotUri name="ScreenshotUri">ScreenshotUri</a>

First included in: Miscellaneous/SysTaskRecorderNodeFormUserActionInputOutput (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>unknown</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ScreenshotUri attribute are listed below.</summary>

**is.nullable**  
The attribute value may be set to NULL.  

</details>

### <a href=#Annotations name="Annotations">Annotations</a>

First included in: Miscellaneous/SysTaskRecorderNodeFormUserActionInputOutput (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Annotations attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_RecordingRelationRelationshipId name="Relationship_RecordingRelationRelationshipId">Relationship_RecordingRelationRelationshipId</a>

First included in: Miscellaneous/SysTaskRecorderNodeFormUserActionInputOutput (this entity)  

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

First included in: Miscellaneous/SysTaskRecorderNodeFormUserActionInputOutput (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>System Generated</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SystemGenerated attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>System Generated</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#Deleted name="Deleted">Deleted</a>

First included in: Miscellaneous/SysTaskRecorderNodeFormUserActionInputOutput (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Deleted attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#FormContextId name="FormContextId">FormContextId</a>

First included in: Miscellaneous/SysTaskRecorderNodeFormUserActionInputOutput (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Form ID</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FormContextId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Form ID</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ControlLabel name="ControlLabel">ControlLabel</a>

First included in: Miscellaneous/SysTaskRecorderNodeFormUserActionInputOutput (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>unknown</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ControlLabel attribute are listed below.</summary>

**is.nullable**  
The attribute value may be set to NULL.  

</details>

### <a href=#ControlLabelId name="ControlLabelId">ControlLabelId</a>

First included in: Miscellaneous/SysTaskRecorderNodeFormUserActionInputOutput (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>unknown</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ControlLabelId attribute are listed below.</summary>

**is.nullable**  
The attribute value may be set to NULL.  

</details>

### <a href=#Relationship_FormContextRelationshipId name="Relationship_FormContextRelationshipId">Relationship_FormContextRelationshipId</a>

First included in: Miscellaneous/SysTaskRecorderNodeFormUserActionInputOutput (this entity)  

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

### <a href=#ControlName name="ControlName">ControlName</a>

First included in: Miscellaneous/SysTaskRecorderNodeFormUserActionInputOutput (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ControlName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ControlType name="ControlType">ControlType</a>

First included in: Miscellaneous/SysTaskRecorderNodeFormUserActionInputOutput (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Control type</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ControlType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Control type</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LabelId name="LabelId">LabelId</a>

First included in: Miscellaneous/SysTaskRecorderNodeFormUserActionInputOutput (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LabelId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>
