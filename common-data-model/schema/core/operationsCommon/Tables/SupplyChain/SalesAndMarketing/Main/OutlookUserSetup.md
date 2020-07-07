---
title: OutlookUserSetup in Main - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 7/7/2020
ms.author: nebanfic
---

# Outlook worker in Main

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Tables/SupplyChain/SalesAndMarketing/Main/OutlookUserSetup.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[OutlookUserSetup/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Outlook worker</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="OutlookUserSetup.md" target="_blank">Main/OutlookUserSetup</a>|
|[ActivateAnswer](#ActivateAnswer)||<a href="OutlookUserSetup.md" target="_blank">Main/OutlookUserSetup</a>|
|[ActivityEndTime](#ActivityEndTime)||<a href="OutlookUserSetup.md" target="_blank">Main/OutlookUserSetup</a>|
|[ActivityReminderMinutes](#ActivityReminderMinutes)||<a href="OutlookUserSetup.md" target="_blank">Main/OutlookUserSetup</a>|
|[ActivityStartTime](#ActivityStartTime)||<a href="OutlookUserSetup.md" target="_blank">Main/OutlookUserSetup</a>|
|[CalendarDataAreaId](#CalendarDataAreaId)||<a href="OutlookUserSetup.md" target="_blank">Main/OutlookUserSetup</a>|
|[CalendarId](#CalendarId)||<a href="OutlookUserSetup.md" target="_blank">Main/OutlookUserSetup</a>|
|[eMailSaveCopy](#eMailSaveCopy)||<a href="OutlookUserSetup.md" target="_blank">Main/OutlookUserSetup</a>|
|[InclPrivateAppointments](#InclPrivateAppointments)||<a href="OutlookUserSetup.md" target="_blank">Main/OutlookUserSetup</a>|
|[InclPrivateTasks](#InclPrivateTasks)||<a href="OutlookUserSetup.md" target="_blank">Main/OutlookUserSetup</a>|
|[InclRecurringAppointments](#InclRecurringAppointments)||<a href="OutlookUserSetup.md" target="_blank">Main/OutlookUserSetup</a>|
|[OutlookCalendarFolderName](#OutlookCalendarFolderName)||<a href="OutlookUserSetup.md" target="_blank">Main/OutlookUserSetup</a>|
|[OutlookCalendarOutlookEntryID](#OutlookCalendarOutlookEntryID)||<a href="OutlookUserSetup.md" target="_blank">Main/OutlookUserSetup</a>|
|[OutlookCalendarOutlookStoreID](#OutlookCalendarOutlookStoreID)||<a href="OutlookUserSetup.md" target="_blank">Main/OutlookUserSetup</a>|
|[OutlookContactFolderEntryID](#OutlookContactFolderEntryID)||<a href="OutlookUserSetup.md" target="_blank">Main/OutlookUserSetup</a>|
|[OutlookContactFolderName](#OutlookContactFolderName)||<a href="OutlookUserSetup.md" target="_blank">Main/OutlookUserSetup</a>|
|[OutlookContactFolderStoreID](#OutlookContactFolderStoreID)||<a href="OutlookUserSetup.md" target="_blank">Main/OutlookUserSetup</a>|
|[OutlookTaskFolderName](#OutlookTaskFolderName)||<a href="OutlookUserSetup.md" target="_blank">Main/OutlookUserSetup</a>|
|[OutlookTaskOutlookEntryID](#OutlookTaskOutlookEntryID)||<a href="OutlookUserSetup.md" target="_blank">Main/OutlookUserSetup</a>|
|[OutlookTaskOutlookStoreID](#OutlookTaskOutlookStoreID)||<a href="OutlookUserSetup.md" target="_blank">Main/OutlookUserSetup</a>|
|[OutlookUserEntryID](#OutlookUserEntryID)||<a href="OutlookUserSetup.md" target="_blank">Main/OutlookUserSetup</a>|
|[OutlookUserID](#OutlookUserID)||<a href="OutlookUserSetup.md" target="_blank">Main/OutlookUserSetup</a>|
|[smmSynchronizeDaysBack](#smmSynchronizeDaysBack)||<a href="OutlookUserSetup.md" target="_blank">Main/OutlookUserSetup</a>|
|[smmSynchronizeDaysForward](#smmSynchronizeDaysForward)||<a href="OutlookUserSetup.md" target="_blank">Main/OutlookUserSetup</a>|
|[UserId](#UserId)||<a href="OutlookUserSetup.md" target="_blank">Main/OutlookUserSetup</a>|
|[ExchangeServerUrl](#ExchangeServerUrl)||<a href="OutlookUserSetup.md" target="_blank">Main/OutlookUserSetup</a>|
|[Relationship_WorkCalendarTable_FKRelationshipId](#Relationship_WorkCalendarTable_FKRelationshipId)||<a href="OutlookUserSetup.md" target="_blank">Main/OutlookUserSetup</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: Main/OutlookUserSetup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[OutlookUserSetup/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#ActivateAnswer name="ActivateAnswer">ActivateAnswer</a>

First included in: Main/OutlookUserSetup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ActivateAnswer attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#ActivityEndTime name="ActivityEndTime">ActivityEndTime</a>

First included in: Main/OutlookUserSetup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>time</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ActivityEndTime attribute are listed below.</summary>

**is.dataFormat.time**  
**means.measurement.time**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.time**  
</details>

### <a href=#ActivityReminderMinutes name="ActivityReminderMinutes">ActivityReminderMinutes</a>

First included in: Main/OutlookUserSetup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ActivityReminderMinutes attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#ActivityStartTime name="ActivityStartTime">ActivityStartTime</a>

First included in: Main/OutlookUserSetup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>time</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ActivityStartTime attribute are listed below.</summary>

**is.dataFormat.time**  
**means.measurement.time**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.time**  
</details>

### <a href=#CalendarDataAreaId name="CalendarDataAreaId">CalendarDataAreaId</a>

First included in: Main/OutlookUserSetup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CalendarDataAreaId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CalendarId name="CalendarId">CalendarId</a>

First included in: Main/OutlookUserSetup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CalendarId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#eMailSaveCopy name="eMailSaveCopy">eMailSaveCopy</a>

First included in: Main/OutlookUserSetup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the eMailSaveCopy attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#InclPrivateAppointments name="InclPrivateAppointments">InclPrivateAppointments</a>

First included in: Main/OutlookUserSetup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InclPrivateAppointments attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#InclPrivateTasks name="InclPrivateTasks">InclPrivateTasks</a>

First included in: Main/OutlookUserSetup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InclPrivateTasks attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#InclRecurringAppointments name="InclRecurringAppointments">InclRecurringAppointments</a>

First included in: Main/OutlookUserSetup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InclRecurringAppointments attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#OutlookCalendarFolderName name="OutlookCalendarFolderName">OutlookCalendarFolderName</a>

First included in: Main/OutlookUserSetup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OutlookCalendarFolderName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.readOnly**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#OutlookCalendarOutlookEntryID name="OutlookCalendarOutlookEntryID">OutlookCalendarOutlookEntryID</a>

First included in: Main/OutlookUserSetup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OutlookCalendarOutlookEntryID attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#OutlookCalendarOutlookStoreID name="OutlookCalendarOutlookStoreID">OutlookCalendarOutlookStoreID</a>

First included in: Main/OutlookUserSetup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OutlookCalendarOutlookStoreID attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#OutlookContactFolderEntryID name="OutlookContactFolderEntryID">OutlookContactFolderEntryID</a>

First included in: Main/OutlookUserSetup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OutlookContactFolderEntryID attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.readOnly**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#OutlookContactFolderName name="OutlookContactFolderName">OutlookContactFolderName</a>

First included in: Main/OutlookUserSetup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OutlookContactFolderName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.readOnly**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#OutlookContactFolderStoreID name="OutlookContactFolderStoreID">OutlookContactFolderStoreID</a>

First included in: Main/OutlookUserSetup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OutlookContactFolderStoreID attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.readOnly**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#OutlookTaskFolderName name="OutlookTaskFolderName">OutlookTaskFolderName</a>

First included in: Main/OutlookUserSetup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OutlookTaskFolderName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.readOnly**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#OutlookTaskOutlookEntryID name="OutlookTaskOutlookEntryID">OutlookTaskOutlookEntryID</a>

First included in: Main/OutlookUserSetup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OutlookTaskOutlookEntryID attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#OutlookTaskOutlookStoreID name="OutlookTaskOutlookStoreID">OutlookTaskOutlookStoreID</a>

First included in: Main/OutlookUserSetup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OutlookTaskOutlookStoreID attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#OutlookUserEntryID name="OutlookUserEntryID">OutlookUserEntryID</a>

First included in: Main/OutlookUserSetup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OutlookUserEntryID attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.readOnly**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#OutlookUserID name="OutlookUserID">OutlookUserID</a>

First included in: Main/OutlookUserSetup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OutlookUserID attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.readOnly**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#smmSynchronizeDaysBack name="smmSynchronizeDaysBack">smmSynchronizeDaysBack</a>

First included in: Main/OutlookUserSetup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the smmSynchronizeDaysBack attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#smmSynchronizeDaysForward name="smmSynchronizeDaysForward">smmSynchronizeDaysForward</a>

First included in: Main/OutlookUserSetup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the smmSynchronizeDaysForward attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#UserId name="UserId">UserId</a>

First included in: Main/OutlookUserSetup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the UserId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.readOnly**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ExchangeServerUrl name="ExchangeServerUrl">ExchangeServerUrl</a>

First included in: Main/OutlookUserSetup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Synchronization settings</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ExchangeServerUrl attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Synchronization settings</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_WorkCalendarTable_FKRelationshipId name="Relationship_WorkCalendarTable_FKRelationshipId">Relationship_WorkCalendarTable_FKRelationshipId</a>

First included in: Main/OutlookUserSetup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_WorkCalendarTable_FKRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../ProductionControl/Group/WorkCalendarTable.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/ProductionControl/Group/WorkCalendarTable.cdm.json/WorkCalendarTable</a></td><td><a href="../../ProductionControl/Group/WorkCalendarTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>
