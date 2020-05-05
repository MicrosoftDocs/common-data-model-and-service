---
title: SysTaskRecorderNodeMenuItemUserAction - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 5/5/2020
ms.author: nebanfic
---

# Menu item user action

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Tables/System/SystemAdministration/Miscellaneous/SysTaskRecorderNodeMenuItemUserAction.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[SysTaskRecorderNodeMenuItemUserAction/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Task recording node</td></tr><tr><td>en</td><td>User action</td></tr><tr><td>en</td><td>Menu item user action</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="SysTaskRecorderNodeMenuItemUserAction.md" target="_blank">Miscellaneous/SysTaskRecorderNodeMenuItemUserAction</a>|
|[InstanceRelationType](#InstanceRelationType)||<a href="SysTaskRecorderNodeMenuItemUserAction.md" target="_blank">Miscellaneous/SysTaskRecorderNodeMenuItemUserAction</a>|
|[Sequence](#Sequence)||<a href="SysTaskRecorderNodeMenuItemUserAction.md" target="_blank">Miscellaneous/SysTaskRecorderNodeMenuItemUserAction</a>|
|[Recording](#Recording)||<a href="SysTaskRecorderNodeMenuItemUserAction.md" target="_blank">Miscellaneous/SysTaskRecorderNodeMenuItemUserAction</a>|
|[Id](#Id)||<a href="SysTaskRecorderNodeMenuItemUserAction.md" target="_blank">Miscellaneous/SysTaskRecorderNodeMenuItemUserAction</a>|
|[ParentSequence](#ParentSequence)||<a href="SysTaskRecorderNodeMenuItemUserAction.md" target="_blank">Miscellaneous/SysTaskRecorderNodeMenuItemUserAction</a>|
|[Description](#Description)||<a href="SysTaskRecorderNodeMenuItemUserAction.md" target="_blank">Miscellaneous/SysTaskRecorderNodeMenuItemUserAction</a>|
|[ScreenshotUri](#ScreenshotUri)||<a href="SysTaskRecorderNodeMenuItemUserAction.md" target="_blank">Miscellaneous/SysTaskRecorderNodeMenuItemUserAction</a>|
|[Annotations](#Annotations)||<a href="SysTaskRecorderNodeMenuItemUserAction.md" target="_blank">Miscellaneous/SysTaskRecorderNodeMenuItemUserAction</a>|
|[Relationship_RecordingRelationRelationshipId](#Relationship_RecordingRelationRelationshipId)||<a href="SysTaskRecorderNodeMenuItemUserAction.md" target="_blank">Miscellaneous/SysTaskRecorderNodeMenuItemUserAction</a>|
|[SystemGenerated](#SystemGenerated)||<a href="SysTaskRecorderNodeMenuItemUserAction.md" target="_blank">Miscellaneous/SysTaskRecorderNodeMenuItemUserAction</a>|
|[Deleted](#Deleted)||<a href="SysTaskRecorderNodeMenuItemUserAction.md" target="_blank">Miscellaneous/SysTaskRecorderNodeMenuItemUserAction</a>|
|[MenuItemType](#MenuItemType)||<a href="SysTaskRecorderNodeMenuItemUserAction.md" target="_blank">Miscellaneous/SysTaskRecorderNodeMenuItemUserAction</a>|
|[MenuItemName](#MenuItemName)||<a href="SysTaskRecorderNodeMenuItemUserAction.md" target="_blank">Miscellaneous/SysTaskRecorderNodeMenuItemUserAction</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: Miscellaneous/SysTaskRecorderNodeMenuItemUserAction (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[SysTaskRecorderNodeMenuItemUserAction/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#InstanceRelationType name="InstanceRelationType">InstanceRelationType</a>

First included in: Miscellaneous/SysTaskRecorderNodeMenuItemUserAction (this entity)  

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

First included in: Miscellaneous/SysTaskRecorderNodeMenuItemUserAction (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>unknown</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Sequence attribute are listed below.</summary>

</details>

### <a href=#Recording name="Recording">Recording</a>

First included in: Miscellaneous/SysTaskRecorderNodeMenuItemUserAction (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Task recording ID</td></tr><tr><td>dataFormat</td><td>unknown</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Recording attribute are listed below.</summary>

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Task recording ID</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

### <a href=#Id name="Id">Id</a>

First included in: Miscellaneous/SysTaskRecorderNodeMenuItemUserAction (this entity)  

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

First included in: Miscellaneous/SysTaskRecorderNodeMenuItemUserAction (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Sequence number</td></tr><tr><td>dataFormat</td><td>unknown</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ParentSequence attribute are listed below.</summary>

**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Sequence number</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

### <a href=#Description name="Description">Description</a>

First included in: Miscellaneous/SysTaskRecorderNodeMenuItemUserAction (this entity)  

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

First included in: Miscellaneous/SysTaskRecorderNodeMenuItemUserAction (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>unknown</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ScreenshotUri attribute are listed below.</summary>

**is.nullable**  
The attribute value may be set to NULL.  

</details>

### <a href=#Annotations name="Annotations">Annotations</a>

First included in: Miscellaneous/SysTaskRecorderNodeMenuItemUserAction (this entity)  

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

First included in: Miscellaneous/SysTaskRecorderNodeMenuItemUserAction (this entity)  

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

First included in: Miscellaneous/SysTaskRecorderNodeMenuItemUserAction (this entity)  

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

First included in: Miscellaneous/SysTaskRecorderNodeMenuItemUserAction (this entity)  

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

### <a href=#MenuItemType name="MenuItemType">MenuItemType</a>

First included in: Miscellaneous/SysTaskRecorderNodeMenuItemUserAction (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Menu item type</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MenuItemType attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Menu item type</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#MenuItemName name="MenuItemName">MenuItemName</a>

First included in: Miscellaneous/SysTaskRecorderNodeMenuItemUserAction (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Menu item name</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MenuItemName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Menu item name</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>
